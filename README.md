# CodErator

Query metadata, violently encapsulate metadata information, violently generate source code—if it can generate, it's a good tool! You'll end up modifying it to fit your needs anyway!

## Environment & Dependencies

* Project created in Visual Studio 2017

* .NET Framework 4.5.2

* WinForms

* The "painfully hard to use" [Razor Engine 3.9.3](https://github.com/Antaris/RazorEngine)

* MySQL Connector.Net 6.9

## Usage Goals

### JavaEE

* SSM framework code generation

* Freely select which layers to generate

### CSharp

* Generate Entities

## Supported Features

* Connect to a specified schema (currently does not support connecting without specifying a schema)

* Retrieve table field information

* Multi-select tables from a list to choose which ones to generate

* Specify output location

## Development Roadmap

* The initial version of the project is a product of the XP model, and may require re-analysis of the code framework and logic design as issues are encountered during development.

* The initial version has strict support for templates; users are not encouraged to modify template files. However, this may sound like nonsense, but it's not: I actually encourage you to modify the template files according to your own needs or coding style, as long as you follow the existing file naming conventions and Razor Engine syntax.

* In the future, I plan to make major improvements to template support, so that developers can define their own templates. This only requires developers to follow Razor Engine syntax; code can be generated regardless of the template file name.

* The above roadmap may be delayed due to procrastination, but as an open-source project, you are welcome to make modifications if you wish. Feel free to fork; I'm not asking for a star.

## Existing Issues

* Template files are fixed, including file names (prefixes and suffixes) and number of files

* Only supports three-layer generation (Entity, Dao, Service)

* C# currently only supports Entity; the other two layers are not yet supported because I haven't worked with ASP.Net MVC

* Some deeply hidden bugs
