IBM VDP UrbanCode Deploy Plugin
This project is a plugin for IBM's UrbanCode Deploy solution. The plugin allows process steps to be created that leverage the instant mount capabilities for Microsoft SQL Server and Oracle that the IBM VDP data management platform provides.

Prequisites
Latest release of this plugin
IBM UrbanCode Deploy 6.2.7 or higher
IBM VDP virtual appliance version 8.1.2 or higher
IBM VDP Global Manager version 8.1.2 or higher
Installing
Login to the UrbanCode console
Navigate to Settings -> Automation Plugins
Click the 'Load Plugin' button
When prompted, click the 'Choose File' button
Select the downloaded zip file and then click 'Submit'
Using
Login to the UrbanCode console
Navigate to Components and create a new or select an existing component
On the component details page select the 'Processes' tab
Create a new or select an existing process
In the Process designer navigate to the IBM VDP entry in the sidebar menu
Drag and drop a step from the Provision Database category onto the layout
Click the edit icon for the step and enter the required information
Limitations
Transaction log roll forward not supported
SQL Server instance level mount not supported
Individual SQL Server database mount from instance level capture not supported
License
Copyright 2018 Anthony Golia

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
