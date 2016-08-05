Address Book for Angular 2
==========================
#How to develop the project on your local machine 

##Prerequisites

- node v4.x.x higher and npm 2.14.7
- to develop independently, without having to put source files in df instance, make sure cors is enabled and necessary permissions are given to services in your df instance

##Run project
```bash
git clone --depth 1 https://github.com/dreamfactorysoftware/angular2-sdk.git
cd angular2-sdk/angular2-sdk
# paste your dsp_instance_url and app_key in app/config/config.ts
# install the project's dependencies
npm install
# watches your files and uses livereload by default
npm start
