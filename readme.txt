c:\Tools>phonegap

Usage: node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js [options] [commands]

Description:

  PhoneGap command-line tool.

Commands:

  create <path>        create a phonegap project
  serve                serve a phonegap project
  build <platform>     build the project for a specific platform
  install <platform>   install the project on for a specific platform
  run <platform>       build and install the project for a specific platform
  local [command]      development on local system
  remote [command]     development in cloud with phonegap/build
  platform [command]   update a platform version
  plugin [command]     add, remove, and list plugins
  help [command]       output usage information
  version              output version number

Options:

  -d, --verbose        allow verbose output
  -v, --version        output version number
  -h, --help           output usage information

Platforms:

  keyword            | local environment   | remote environment
  -------------------|---------------------|-------------------
  android            | Yes                 | Yes
  ios                | Yes                 | Yes
  wp8                | Yes                 | Yes
  Blackberry 10      | Yes                 | No

Examples:

  $ node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js help create
  $ node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js help remote build
  $ node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js create path/to/my-app
  $ node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js remote build android


c:\Tools>cd c:\projects

c:\Projects>cd Apps




node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js [options] [commands]





c:\Tools>cd c:\projects

c:\Projects>cd Apps

c:\Projects\Apps>node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js --verbose create TestApp
[phonegap] Creating a new cordova project with name "HelloWorld" and id "com.phonegap.helloworld" at location "c:\Projects\Apps\Test
App"
[phonegap] Using custom www assets from https://github.com/phonegap/phonegap-app-hello-world/archive/3.4.0.tar.gz
[phonegap] missing library com.phonegap.helloworld/www/3.4.0
[phonegap] downloading https://github.com/phonegap/phonegap-app-hello-world/archive/3.4.0.tar.gz...
[phonegap] Downloading com.phonegap.helloworld library for www...
[phonegap] Download complete
[phonegap] create called with the options c:\Projects\Apps\TestApp com.phonegap.helloworld HelloWorld
[phonegap] created project at c:\Projects\Apps\TestApp

c:\Projects\Apps>
c:\Projects\Apps\TestApp>phonegap serve

[run the Andriod app on the device and connect - using a web browser will not work]








this does not work - needs the Android SDK
http://stackoverflow.com/questions/18423479/phonegap-version-3-phonegap-js-not-found
node C:\Users\Rick\AppData\Roaming\npm\node_modules\phonegap\bin\phonegap.js --verbose build android c:\Projects\Apps\TestApp


