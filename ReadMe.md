# Mobile Development - Nuts & Bolts Workshop

The Mobile Development Nuts and Bolts Workshop is a hands on workshop that will take you from `dotnet new` to having a fully functional application on Android, iOS, MacCatalyst and Windows with an automated build. 

This workshop will focus on building a mobile app with .NET MAUI. We will be using a number of open source libraries to help accelerate our development process. Some of these projects include:

- [Prism Library](https://github.com/prismlibrary/prism.maui)
- [Shiny Library](https://github.com/shinyorg/shiny)
- [Reactive UI](https://github.com/reactiveui/reactiveui)
- [Mobile.BuildTools](https://github.com/dansiegel/Mobile.BuildTools)
- [Nuke.Maui](https://github.com/avantipoint/nuke.maui)

While the focus of the workshop will be on building a .NET MAUI app, much of what you learn in the workshop is transferrable to a Xamarin.Forms app.

## What's needed?

It is critical that you plan to attend the full workshop. Those who come in late will miss critical pieces of information that they need to have a working app. I will not have time to teach you how to program in C# or about XAML. You should have a working understanding of both prior to attending the workshop but you do NOT need to be an expert.

### Required

- You must have one of the following:
  - Windows Laptop with the latest version of Visual Studio 2022 Preview installed
  - Mac Laptop with the latest version of Visual Studio 2022 for Mac installed
- You must have the MAUI workload installed with your install of Visual Studio 2022
- You must have .NET 6.0 installed
- You must have a GitHub account as we will be creating a public repository & build for your app
  - You do NOT need to have a paid account
- Ability to deploy a Web App to the hosting service of your choice... Or ngrok installed on your laptop 
- You must be ready to learn and have fun!

### Recommended

- If you have a Mac, you should have Xcode installed
- An Apple Developer Account with the ability to create an application id, provisioning profile, certificate and keys
  - If you are unable to do this you can still attend you just will not be able to build your app for iOS or MacCatalyst
- If you are using Windows, it is recommended that you have the Window Terminal installed

While you can complete most of the workshop using an iOS Simulator or Android Emulator, there are certain things that you really will need to deploy to a physical device for testing locally.

- For those with USB-C only laptops, you should have an adapter with a standard USB-A port
- You should have a physical iOS or Android device that you can deploy to for testing.
  - You should have a USB cable to connect your physical device to your laptop
  - Please verify that you can deploy a `File -> New -> .NET MAUI` app to your device from the laptop that you are bringing