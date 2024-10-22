# CalculatorServiceProject

This project contains a simple calculator service that performs basic arithmetic operations. It consists of:
- A **Console Application** that takes two numbers and an operator from the user and performs calculations.
- A **Web Application** that consumes the Calculator Web Service and provides a web interface for calculations.

## Project Structure

1. **Calculator Console App**:  
   This is a simple command-line application where users can input two numbers and select an operation (+, -, *, /) to get the result.

2. **Calculator Web App**:  
   This web app is built using **ASP.NET Web Forms**. It provides a web interface with text boxes for input, buttons for operations, and labels to display the results.

## Features
- **Addition**, **Subtraction**, **Multiplication**, **Division** operations supported.
- **Web Service Integration**: The web app communicates with the external [Calculator Web Service](http://www.dneonline.com/calculator.asmx?WSDL).

## How to Run

### Console Application
1. Navigate to the **ConsoleApp** directory.
2. Build the project using Visual Studio or `dotnet build` command.
3. Run the application by pressing `F5` in Visual Studio or running the executable in the `bin/Debug/` directory.
4. Input two numbers and an operator when prompted.

### Web Application
1. Open the **WebApp** project in Visual Studio.
2. Right-click the project in Solution Explorer and choose **Set as Startup Project**.
3. Press `F5` to start the application.
4. The web application will open in the browser, where you can input two numbers, click the operation buttons, and view the result.

## Web Service Configuration
- The web application consumes a public web service hosted at `http://www.dneonline.com/calculator.asmx?WSDL`.
- Ensure that you have a working internet connection to access the service.

## Technologies Used
- **ASP.NET Web Forms** (for the web app)
- **C# Console Application**
- **Calculator Web Service**

## Contributing
Feel free to fork this project and contribute via pull requests.


