# CustomeMessage
**This package helps encapsulate features like**
* [x] Clearing and Printing message on the console with different color depending on the method called.

```C#
///<summary>
/// This method takes in one parameter string message and print the message in the console with danger color.
///</summary>
///<param name="message">The message that you want to print on the console.</param>
Message.Error(string message);

The method encapsulates some method from system namespace like Console.Clear() , <br > Console.ForegrandColor = ConsoleColor.Red and Console.ResetColor() <br >
Which helps to clear the console, Change the console color to red before printing <br > the message and after printing the messsage the last Console.ResetColor() <br > method will then change the console color to normal.
```

Note: **The difference between the methods are the color of the message they print.**
 </br > The only method that has another difference is the Message.Alert() method that has no Console.Clear() method.

 ### List of Methods available in the Repo
 * [x] ```C# Message.Error(string message); ```
 * [x] ```C# Message.Success(string message); ```
 * [x] ```C# Message.Warning(string message); ```
 * [x] ```C# Message.Alert(string message); ```