# User Manual
## Installation:
1) Follow the link https://github.com/Ziggchik/ConsoleCalculator
2) Press green button "Code"

      ![image](https://user-images.githubusercontent.com/70440445/131725484-09fbbd99-bbb1-417d-8a02-b4b6c0e6e8e1.png)

3) In the drop-down list that opens, select how you want to install the project

      ![image](https://user-images.githubusercontent.com/70440445/131725753-8f39cd5f-c8f0-4043-9797-fd262e47fa1d.png)
### Download Zip:
1) Press button "Download Zip"
2) The "download" folder will contain the downloaded archive, unzip it to any place on your computer
3) Press button combination "Win+R" and write "cmd". In open console write: dotnet path\to\MyApp.dll
4) Press "Enter" to launch application.
### Open with Visual Stido:
1) Download Visual Studio. link for download: https://visualstudio.microsoft.com/ru/downloads
2) Press button "Open with Visual Stido"
3) In Visual Stidio click to button "Clone repository"
4) Solution will donwload from repository and you can save project (Ctrl+Shift+S) in any place on you computer
### Download with command:
1) Press button combination "Win+R" and write "cmd"
2) Write this commands:
* git clonehttps://github.com/Ziggchik/ConsoleCalculator.git
* cd ConsoleCalculator
* dotnet build
* dotnet run
3) After that application will start
## How to use:
Short gif which help user with working in application

![Анимация](https://user-images.githubusercontent.com/70440445/131733385-4306fdae-ece7-47f5-9cef-ac462b65dd5c.gif)

## Architecture:
1) The project create with .NET Core 2.1 and uses the C# language.
2) All functions release in class Program.cs
3) Program.cs have main function Main(string[] args) which performs the operation of the calculator like: Addition,Subtraction,Multiplication,Division,Equal,Purification
