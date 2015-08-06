# SimpleWithFabric
you'll see this error even you replace the real key and secret of fabric in the run script 
/parth/to/your//Xcode/to/your/project/Build/Intermediates/projectName.build/Debug-iphoneos/projectName.build/Script-XXXXXXX.sh: line 2: ./Fabric.framework/run: No such file or directory

follow these steps below should help you get ride of this error : 

0. replace key and secret in script
1. build app, see the error
2. Open Fabric App
3. click the down arrow button on top-left corner
4. click + New App on the right side
5. chose the project
6. click install of Crashlytics
7. build project, Fabric should be integrated when the built is finished
8. run app, done~*
