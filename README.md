# CalculatorProj-DotNetFramework

Collection of desktop and console calculator applications developed in C# with .NET Framework and .NET Core.

## Description

CalculatorProj-DotNetFramework contains practical implementations of arithmetic calculator applications. The repository includes a graphical Windows Forms desktop application for performing mathematical operations via an interactive UI, as well as a console-based companion implementation demonstrating basic input handling and arithmetic logic.

## Technologies

- **Language:** C#
- **Frameworks:**
  - .NET Framework 4.7.2 (Windows Forms)
  - .NET Core / Modern .NET (Console Application)
- **IDE:** Visual Studio

## Project Structure

```text
CalculatorProj-DotNetFramework/
├── CalculadoraMedia/
│   ├── CalculadoraMedia.sln
│   └── CalculadoraMedia/
│       ├── Form1.cs               # Windows Forms UI and event handlers
│       ├── Form1.Designer.cs      # Auto-generated UI layout code
│       ├── Operacoes.cs          # Arithmetic calculation methods
│       ├── Program.cs             # Application entry point
│       └── CalculadoraMedia.csproj
└── CalculatorBasicConsole/
    ├── Calculadora.sln
    ├── Operacoes.cs              # Core arithmetic logic
    ├── Program.cs                 # Console interaction loop
    └── Calculadora.csproj
```

## Features

- **Windows Forms Application (`CalculadoraMedia`):**
  - Interactive graphical user interface with text input controls and operation buttons.
  - Basic arithmetic operations: Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`), and Modulo/Percentage (`%`).
  - Output display directly bound to form text controls.
- **Console Calculator (`CalculatorBasicConsole`):**
  - Terminal-based calculator executing arithmetic functions via standard input and output streams.

## Setup & Execution

### Prerequisites
- Windows OS (required for Windows Forms runtime)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with the **.NET desktop development** workload installed

### Running the Windows Forms Application
1. Clone the repository:
```bash
git clone https://github.com/EuKaueCMP/CalculatorProj-DotNetFramework.git
```

2. Open the solution file in Visual Studio:
```text
CalculadoraMedia/CalculadoraMedia.sln
```

3. Build and run the project by pressing `F5` or clicking **Start**.

### Running the Console Application
1. Open a terminal and navigate to the console project directory:
```bash
cd CalculatorProj-DotNetFramework/CalculatorBasicConsole
```

2. Run the application:
```bash
dotnet run
```

## Developer

**Kauê Sérgio Campos**  
GitHub: [@EuKaueCMP](https://github.com/EuKaueCMP)
