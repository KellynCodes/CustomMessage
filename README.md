# CustomeMessage
**This package helps encapsulate features like**
* [x] Clearing and Printing message on the console with different color depending on the method called.

## Live Demo: [Demo Link](https://KellynCodes.github.io/CustomMessage)

- Language: C#
- Frameworks: .NET Standard 2.0
- IDE: Visual Studio

  - To install our package using the .NET CLI, run: `dotnet add package CustomMessage --version 1.0.0`
  - Installation using Visual Studio
    - Right-click on project dependencies
    - Select manage Nuget packages
    - Search `CustomMessage`
    - Click install

### Usage
```C#
///<summary>
/// This method takes in one parameter string message and print the message in the console with danger color.
///</summary>
///<param name="message">The message that you want to print on the console.</param>
Message.Error(string message){}

The method encapsulates some method from System namespace like Console.Clear(),
Console.ForegrandColor = ConsoleColor.Red and Console.ResetColor()
Which helps to clear the console, Change the console color to red before printing
the message and after printing the messsage the last Console.ResetColor()
method will then change the console color to normal.
```

Note: **The difference between the methods are the color of the message they print.**
 </br > The only method that has another difference is the Message.Alert() method that has no Console.Clear() method.

 ### List of Methods available in the Repo
 ```C# Message.Error(string message){}
   Message.Success(string message){}
   Message.Warning(string message){}
   Message.Alert(string message){}
  ```
  ## Authors

👤 **KellynCodes**

- GitHub Profile: [@KellynCodes](https://github.com/KellynCodes)
- Twitter: [@KellynCode](https://twitter.com/Kellyncode)
- LinkedIn: [KellynCodes](https://linkedin.com/in/kellynCodes)
