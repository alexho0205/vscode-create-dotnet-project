# vscode-create-dotnet-project
create dotnet project on vscode.

練習使用VSCODE建立 dotnet 專案.

## Steps

1. open vscode -> file -> open folder -> ( create folder my-new-web-app ) 
2. open terminal -> dotnet new mvc -> dotnet run
3. use vscoode 'Run and Debug' to run project
    1.  command + P -> input ```>.Net Generate Asset for Build and Debug ```
    2.  vscode will auto generate file ```launch.json```
    3.  click 'Run and Debug' run project.
4. enable auto compile
    1. edit ```launch.json``` change preLaunchTask to   ```"preLaunchTask": "watch",```
    2. try to edit page or controller , will trigger auto compile.
