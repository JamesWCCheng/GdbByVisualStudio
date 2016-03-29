# GdbByVisualStudio
Use remote gdb and debug on visual studio. A template setting.

#### 使用 Visual Studio GDB 擴充套件在 Visual Studio 上遠端偵錯 Linux 上的 C/C++ 程式
http://blogs.msdn.com/b/ericsk/archive/2016/02/16/remote-gdb-debugging-c-and-cpp-program-via-vs-gdb-extension.aspx

#### Announcing the VS GDB Debugger extension
https://blogs.msdn.microsoft.com/vcblog/2015/11/18/announcing-the-vs-gdb-debugger-extension/

#### Visual Studio GDB Debugger 
https://visualstudiogallery.msdn.microsoft.com/35dbae07-8c1a-4f9d-94b7-bac16cad9c01


c:\tools\pscp.exe -i $(PrivateKey) ".\main.cpp" $(RemoteUserName)@$(RemoteHostName):$(RemoteWorkingDirectory)/main.cpp

$(SecureShellExecutable) $(RemoteUserName)@$(RemoteHostName) -i $(PrivateKey) "cd $(RemoteWorkingDirectory);gcc -g main.cpp -o $(RemoteExecutable)"

