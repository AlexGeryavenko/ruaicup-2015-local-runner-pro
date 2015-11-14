# Plugin for Russian AI Cup 2015 
Using this plugin will allow you to test your strategy with couple additional features.

Release notes:

v1.0
- Numbered and higlight all waypoints;
- Addition higlight next waypoints;
- Display speed;
- Apply solytion for map01 tile[3;4], duplication waypoints index.

Setup:

1. Download [local-runner](http://russianaicup.ru/p/localrunner "local-runner").
2. Unzip and go to folder "/local-runner" open file "local-runner.properties", find the line:
 ```
 plugins-directory=
 ```
3. Add path to the plugin (use right slashes), for example:
 ```
 plugins-directory=D:/local-runner-beta/plugins
 ```
4. Downloading a file "LocalTestRendererListener.java" and save/replace it in the folder "/local-runner/plugins".
5. In the same folder, run batch file "compile.bat" to compile, if appears couple of new files, ex.: "LocalTestRendererListener.class" - compilation successful - if not, correct batch file by specifying correct path to Java. 
6. Next as usual: in "/local-runner" run "local-runner.bat" and after u strategy.
