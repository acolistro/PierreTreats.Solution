# _Pierre's Treats Tracker_

#### _ASP.NET MVC Independent Project for Epicodus_, _Mar. 27 2020_

#### By _**Alyssa Colistro**_


## Description

_A website where a Pierre (user) can add and edit and track both the treats he sells and the flavors that are assigned to those treats._

## Specifications:

| Specification | Example Input | Example Output |
| ------------- |:-------------:| -------------------:|
|User can can choose to add a new treat| "Donut"| "Donut" is added to the treats database|
|User can view all treats|Selects "view all" or returns to home index|All treats in the treat table of the database are printed to the page|
|User can view all flavors of each treat|Clicks "Donut"|All flavors assigned to "Donut" are displayed.|
|User can edit added treats|"Donut" --> "Maple Bar"|"Donut" is updated to "Maple Bar" in the treat table|
|User can delete treats|User selects "Delete" from options on "Maple Bar" Details page|"Maple Bar" is removed from the treats table.|
|User can add a new flavor and specify which treat it belongs to, as well as it's description.|"Sweet", "Maple Bar"|"Sweet" is added to the flavors table, with the id of the specified treat in a treat column.|
|User can view all flavors|Selects "view all"or navigates to the home index|User can see all flavors listed in the flavors table.|
|User can edit flavors|"Sweet" --> "Cinnamon"|"Sweet" is updated to "Cinnamon" in the flavors table.|
|User can delete flavors|User selects "Delete"|The row with "Cinnamon" is removed from the flavors table.|
|User can enter a query to search existing treats |User enters "Croissant"| Search results return a link to the treat Croissant, which then can take the user to all Croissant's flavors |


## Setup/Installation Requirements

### Install .NET Core

#### on macOS:
* _[Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer) to download a .NET Core SDK from Microsoft Corp._
* _Open the file (this will launch an installer which will walk you through installation steps. Use the default settings the installer suggests.)_

#### on Windows:
* _[Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.203-windows-x64-installer) to download the 64-bit .NET Core SDK from Microsoft Corp._
* _Open the .exe file and follow the steps provided by the installer for your OS._

#### Install dotnet script
_Enter the command ``dotnet tool install -g dotnet-script`` in Terminal (macOS) or PowerShell (Windows)._

### Clone this repository

_Enter the following commands in Terminal (macOS) or PowerShell (Windows):_
* ``cd desktop``
* ``git clone https://github.com/acolistro/PierreTreats.Solution``
* ``cd PierreTreats.Solution``

_Confirm that you have navigated to the PierreTreats.Solution directory (e.g., by entering the command_ ``pwd`` _in Terminal)._

_Run this application by entering the following command in Terminal (macOS) or PowerShell (Windows):_
* ``cd Bakery``
* ``dotnet restore``
* ``dotnet build``
* ``dotnet run`` or ``dotnet watch run``


_To view/edit the source code of this application, open the contents of this directory in a text editor or IDE of your choice (e.g., to open all contents of the directory in Visual Studio Code on macOS, enter the command_ ``code .`` _in Terminal)._

### Create Project Database
* Navigate to your terminal and cd into the Bakery folder and enter the following:
```dotnet ef migrations add Initial```
```dotnet ef database update```
* This will create your databases and start your migrations.

Your project is now ready.

## Known Bugs

_No known bugs at this time._

## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/acolistro/PierreTreats/issues) here on GitHub._

## Technologies Used
* _Git_
* _C#_
* _.NET Core 2.2_
* _ASP.NET Core MVC_
* _dotnet script_
* _MySQL_
* _EF Core_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Alyssa Colistro_**