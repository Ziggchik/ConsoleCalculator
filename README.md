How to work with
How install project:
Before getting started, you need to download the project. With this command:

git clone https://github.com/Holiks-Serbuchev/CalculatorWEB.git
cd CalculatorWEB
dotnet build
dotnet run
How to use:
When a new user first logs into the site. He sees the calculator interface itself:

The calculator interface consists:

From multiple input fields;
And also from several buttons.
alt text

The calculator has several functions:

Addition;
Subtraction;
Multiplication;
Division;
Equal;
Purification.
To start using the calculator, you just need to start entering the required number and also use the functions that were described above.

An example of using the calculator:

hippo

Architecture
The project was developed using ASP.NET MVC technology. Using languages such as C# and JavaScript.

The element has been selected to simplify markup. Which made it possible to quickly create a grid for the controls.
This project used JavaScript to update data in real time. All JavaScript code is stored in js/site.js file.
The AddValuesTB function allows you to enter numbers into the input field.
The SelectChar function allows you to select (+, -, /, *).
The ClearClick function allows you to clear input fields.
The PointClick function allows you to add a sign for decimal fractions.
Also, in this project, C# was used to calculate examples.
C# code has been applied to HomeController. And in the Clicked event, examples are calculated.
