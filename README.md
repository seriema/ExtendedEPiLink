This is a TinyMCE extended link button for EPiServer 10+. 

It is basically the same button you get when you use standard epilink, but expanded to support linking to a specific place on the page instead of top of it.

Info on how to use it and motivation behind, can be found here:
http://www.mogul.com/en/About-Mogul/Blog/Hooking-to-a-page-dojo-widget-inside-EPiServer-TinyMCE-link/
http://www.mogul.com/en/About-Mogul/Blog/Extending-EPiServer-link-in-TinyMCE-to-support-anchors-on-page/

When using these files, they will work when copied in the same structure, but ofc, you can refactor the code according to your design. Scripts and styles should stay in the same place.

This is the part of packages.config with the EPiServer versions this plugin is tested on, but probably it would work on any version later than 8.
  <package id="EPiServer.CMS" version="10.0.1" targetFramework="net452" />
  <package id="EPiServer.CMS.Core" version="10.0.1" targetFramework="net452" />
  <package id="EPiServer.CMS.UI" version="10.0.2" targetFramework="net452" />
  <package id="EPiServer.CMS.UI.AspNetIdentity" version="10.0.2" targetFramework="net452" />
  <package id="EPiServer.CMS.UI.Core" version="10.0.2" targetFramework="net452" />
  <package id="EPiServer.Framework" version="10.0.1" targetFramework="net452" />
  <package id="EPiServer.Logging.Log4Net" version="2.1.0" targetFramework="net452" />
  <package id="EPiServer.Packaging" version="3.3.0" targetFramework="net452" />
  <package id="EPiServer.Packaging.UI" version="3.3.0" targetFramework="net452" />
  
WebAPI has been installed as well:
  <package id="Microsoft.AspNet.WebApi.Client" version="5.2.3" targetFramework="net452" />
  <package id="Microsoft.AspNet.WebApi.Core" version="5.2.3" targetFramework="net452" />
  <package id="Microsoft.AspNet.WebApi.WebHost" version="5.2.3" targetFramework="net452" />