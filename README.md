# _Vanessa Stewart_

_28 September 2020_

#### _Basic application for creating, updating, and deleting parcels_

#### By _**Vaness Stewart**_

## Description

_This is a project for Epcidous to practice routing with Ruby using test-driven development. The original instructions include:_

Create a basic CRUD application for creating, updating and deleting Parcels. First, start with the backend logic, which should provide functionality to:

Create an instance of Parcel. A user should be able to specify the dimensions and weight of a Parcel.
Update an instance of Parcel.
Delete a Parcel.
View all Parcels.
Find an instance of Parcel.
When CRUD functionality is complete, add the following additional functionality:

Include a volume() instance method to calculate the volume of a Parcel.
Add a cost_to_ship() instance method. This will return a cost based on a formula you make up (you might consider factors like speed of delivery, distance, dimensions, weight).
Once the backend logic is complete and tested, build a website in Sinatra that lets users calculate shipping costs.
Make sure to commit regularly and create a README file.

For bonus points, consider:

offering gift wrapping services that require the surface area of the parcel to determine cost;
offering discounts based on size or date or some other property;
adding CSS/Bootstrap to enhance the user experience.

## Specifications
| Spec     | Behavior |
| -------- | -------- | 
| 1 | View all parcels | 
| 2 | Create an instance of a parcel (with weight and dimensions) | 
| 3 | Update an instance of a parcel |
| 4 | Delete a parcel |
| 5 | Find all instances of parcels |

## Backend Logic
| CRUD Action | Method | Class or Instance | Description | URL |
| ------------| ------ | ----------------- | ----------- | --- |
| Read | .all() | Class | View all parcels | / |
| Create | .save() | Instance | Create a single instance of a parcel | /
| Update | .update() | Instance | Update an instance of a parcel |
| Delete | .delete() | Instance | Delete an instance of a parcel |
| Read | .find() | Class | Find all instances of parcels |

## Setup/Installation Requirements

- Clone this project using the 'git clone' command in terminal/command line.
- Navigate to the cloned folder and run 'bundle' in your command line.
- Open the cloned repo in a text editor of your choice.
- To run tests: While in the root directory of the project, run 'rspec' in your command line.
- To run the app.rb file in the terminal, run 'ruby app.rb' in the terminal.

## Known Bugs

_There are no known bugs at this time._

## Technologies Used

* Ruby
* Ruby Gems: rspec, pry, sinatra, sinatra-contrib

### License

Copyright (c) 2020 **_Vanessa Stewart_**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
