# Unity glTF

## Build instructions

I used VS 2017 to build the GLTFSerialization solution, and then used this command to build the unity package:

``` bash
/c/Program\ Files/Unity/Hub/Editor/2018.1.8f1/Editor/Unity.exe -projectPath ${PWD}/UnityGLTF -quit -batchmode -nographics -exportPackage "Assets/UnityGLTF" ${PWD}/current-package/UnityGLTF.unitypackage -logfile -
```
