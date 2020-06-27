## Subnautica dnSpy mono

Build Release x64, then replace mono-2.0-bdwgc.dll in SubnauticaZero/MonoBleedingEdge/EmbedRuntime/


#### Start Subnautica, then in dnSpy:
* Debug > Start Debugging
* Debug engine: **Unity (Connect)**
* IP Address: *empty*
* Port: *default* 55555




#### Gathered from:
- https://github.com/0xd4d/dnSpy-Unity-mono
- UnitySetup64-2019.2.17f1.exe from https://unity3d.com/get-unity/download/archive
- unity-2019.2-mbe-fix-debugger-hang branch from https://github.com/Unity-Technologies/mono
