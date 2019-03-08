<h2>Build a .NET Standard library with C# and the .NET Core SDK in Visual Studio 2017</h2>
In this topic, you'll create a simple utility library that contains a single string-handling method.
You'll implement it as an extension method so that you can call it as if it were a member of the String class.
<br><br>
<a href="https://docs.microsoft.com/en-gb/dotnet/core/tutorials/library-with-visual-studio">Tutorial Here</a>
<br><br>

<h2>Test a .NET Standard library with .NET Core in Visual Studio 2017</h2>
In Build a .NET Standard library with C# and .NET Core in Visual Studio 2017 or
Build a .NET Standard library with Visual Basic and .NET Core in Visual Studio 2017,
you created a simple class library that adds an extension method to the String class.
Now, you'll create a unit test to make sure that it works as expected.
You'll add your unit test project to the solution you created in the previous article.
<br><br>
<a href = "https://docs.microsoft.com/en-gb/dotnet/core/tutorials/testing-library-with-visual-studio?tabs=csharp">Tutorial Here</a>
<br><br>

<h2>Consume a .NET Standard library in Visual Studio 2017</h2>
Once you've created a .NET Standard class library by following the steps in 
Building a C# class library with .NET Core in Visual Studio 2017 or 
Building a Visual Basic class library with .NET Core in Visual Studio 2017, 
tested it in Testing a class library with .NET Core in Visual Studio 2017,
and built a Release version of the library, the next step is to make it available to callers.
<br>
You can do this in two ways:
<br><br>
<ul>
<li>If the library will be used by a single solution (for example, if it's a component in a single large application), 
you can include it as a project in your solution.</li>
<li>If the library will be generally accessible, you can distribute it as a NuGet package.</li>
</ul>
<br>
<a href = "https://docs.microsoft.com/en-gb/dotnet/core/tutorials/consuming-library-with-visual-studio?tabs=csharp">Tutorial Here</a>

