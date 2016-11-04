### ionic-start
1. Apache Cordova 转换原生应用

		npm install -g cordova
2. 安装ionic 便于命令行创建、启动项目

		npm install -g ionic
3. 创建项目骨架（参考官网[目录结构](http://ionicframework.com/docs/guide/installation.html)）

		ionic start todo blank

		$ cd todo && ls
		
		├── bower.json     // bower dependencies
		├── config.xml     // cordova configuration
		├── gulpfile.js    // gulp tasks
		├── hooks          // custom cordova hooks to execute on specific commands
		├── ionic.project  // ionic configuration
		├── package.json   // node dependencies
		├── platforms      // iOS/Android specific builds will reside here
		├── plugins        // where your cordova/ionic plugins will be installed
		├── scss           // scss code, which will output to www/css/
		└── www            // application - JS code and libs, CSS, images, etc.

4. 配置平台

		$ ionic platform add ios
		$ ionic platform add android
5. 测试

		$ ionic build ios
		$ ionic emulate ios
6. 你好 