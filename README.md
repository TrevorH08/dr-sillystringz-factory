# _Dr Sillystring'z Factory_

#### By _**Trevor Hunter**_

#### _An application where Dr Sillystring can manage their engineers and machines according to licensees._

## Technologies Used

* _C#_
* _.NET 5_
* _Entity_
* _MySQL_
* _ASP.NET Core MVC
* _HTML_
* _JavaScript_
* _CSS_

## Description

_This application lets the user manage their machines, their engineers, and assign the machines to engineers based on their licenses._

_On this application, the user can create new Engineers and Machines seperately, then decide to assign one to the other using a Many-to-Many relationship. This allows Engineers and Machines to exist independently from each other, but still be able to connect the two._

_All CRUD Methods exist for both Engineers and Machines, as well as the added ability to remove the join entry between the two once they have been joined._

## Setup/Installation Requirements

* _Clone project from repo: https://github.com/TrevorH08/dr-sillystringz-factory ._
* _Make sure you have Entity Framework Core installed at a Global level. To Ensure, paste the following into your terminal 
** _$ dotnet tool install --global dotnet-ef --version 5.0.1_
* _Create a file in the main project folder /Factory called appsettings.json_
* _Enter this code into the file: 
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=factory;uid=[ENTER YOUR USERNAME];pwd=[ENTER YOUR PASSWORD];"
  }
}_
* _From there run the following commands in the terminal:_
* _$ dotnet restore_
* _$ dotnet build_
* _$ dotnet ef migrations add Initial_
* _$ dotnet ef database update_
* _$ dotnet run_

## Known Bugs

* _No Known Bugs_

## License

MIT

If you have any questions or issues, head over to this projects GitHub Repository, and navigate to the "Issues" tab to leave feedback! If you have any suggestions or would like to contribute to this project, reach out and let me know!

Copyright (c) 10/23/22 Trevor Hunter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
