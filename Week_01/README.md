# Week 1 - Development Setup

## macOS

### Install Homebrew

[Homebrew](https://brew.sh/) is the missing package manager for macOS, we are going to use it to install everythinf in the setup.

1. Open the terminal
  1.1. In Finder (`CMD + Spacebar`), type Terminal
2. Paste this code `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Install Visual Studio Code on macOS

[Visual Studio Code](https://code.visualstudio.com/)  is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

1. Open the terminal
2. Install with this command: `brew cask install visual-studio-code`
3. Open with `code`

### C# Development (.NET Core SDK) on macOS

[.NET Core](https://dotnet.microsoft.com) is a cross-platform version of .NET for building websites, services, and console apps. We are going to use it for our C# Development.

1. Open the terminal
2. Install with this command: `brew cask install dotnet-sdk`
3. Go to your development folder, for example Documents
4. Run `dotnet new console -o MyNewApp`, this will create a basic console application called `MyNewApp`
5. Go to the application directory with `cd MyNewApp`
6. Open Visual Studio Code in this directory with `code .`
7. Open Terminal in Visual Studio Code
8. Execute with `dotnet run` on the terminal, you should see a greating message

### Install NodeJS for JavaScript Development on macOS

[Node.js](https://nodejs.org/en/) is a JavaScript runtime built on Chrome's V8 JavaScript engine.

1. Open the terminal
2. Install with this command: `brew install node`
3. Go to your development folder, for example Documents
4. Create and go to a Folder with `mkdir JSApp && cd JSApp`
5. Open Visual Studio Code in this directory with `code .`
6. Open Terminal in Visual Studio Code
7. Create File with `code app.js`
8. Type `console.log('Hello from JS')` and save the file
9. Execute with `node app.js` on the terminal, you should see a greating message

## Windows

### Install Chocolatey

[Chocolatey](https://chocolatey.org/) is the package manager for Windows.

1. Search in the Start Button for ***cmd***
2. Rigth Click with the mouse and open as Administrator
3. Accept Dialog Box
4. Paste this code `@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`

### Install Visual Studio Code on Windows

[Visual Studio Code](https://code.visualstudio.com/)  is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

1. Open the ***cmd*** as administrator
2. Install with this command: `choco install vscode`
3. Open with Code

### C# Development (.NET Core SDK) on Windows

[.NET Core](https://dotnet.microsoft.com) is a cross-platform version of .NET for building websites, services, and console apps. We are going to use it for our C# Development.

1. Open the ***cmd***
2. Install with this command: `choco install dotnetcore-sdk`
3. Go to your development folder, for example Documents
4. Run `dotnet new console -o MyNewApp`, this will create a basic console application called `MyNewApp`
5. Go to the application directory with `cd MyNewApp`
6. Open Visual Studio Code in this directory with `code .`
7. Open Terminal in Visual Studio Code
8. Execute with `dotnet run` on the terminal, you should see a greating message

### Install NodeJS for JavaScript Development on Windows

[Node.js](https://nodejs.org/en/) is a JavaScript runtime built on Chrome's V8 JavaScript engine.

1. Open the ***cmd***
2. Install with this command: `choco install nodejs.install`
3. Go to your development folder, for example My Documents
4. Create Folder with `mkdir JSApp`
5. Open Forlder in Visual Studio Code in this directory with `code JSApp`
6. Open Terminal in Visual Studio Code
7. Create File with `code app.js`
8. Type `console.log('Hello from JS')` and save the file
9. Execute with `node app.js` on the terminal, you should see a greating message