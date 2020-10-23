# Sitecore-Base
Sitecore Base Project

Publish Instructions
1-Back up a copy of your sitecore instance folder
2-Backup a copy of web.config File in this project
3-Copy web.config sitecore content and then paste it to web.config in this project
4-Go to the back-up file for web.config of this project and copy The System.Web.Mvc dependencyAssembly oldVersionValue
5-Paste that value in the current  web.config System.Web.Mvc -> dependencyAssembly -> oldVersionValue
6-Do the same for asemblies such as Newtonsoft.Json
7-In Visual Studio publish the solution as a Folder Target, the root path will be the same where the sitecore web.config (Step 1) is located  

Folowed this tutorial: https://www.youtube.com/watch?v=JWCGILTZzLs
