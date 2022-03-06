# pitch_app
#### By Venus Mwende
## Table of Content
+ [Description](#description)
+ [Installation Requirement](#Installation)
+ [Behaviour Driven Development](#Behaviour-Driven-Development)
+ [Technology Used](#technology-used)
+ [Licence](#licence)
+ [Authors Info](#authors-info)

****
## Description
This is an application that allows users to submit their pitches. The other users will vote on them and leave comments to give their feedback on them.


## Live link

## Installation
### Requirements
* python3.8
* pip 

### Installation process
* Open terminal
* run `git clone https://github.com/Venus-Kavunza/pitch_app.git`

### Dependancy Installation process
```
$ pip install -r requirements.txt

```

### Running the Application
To view the website run the command
```
$ chmod a+x start.sh
$ ./start.sh

```
To run the tests run the command
```
$ python3.8 manage.py test

```
## Behaviour Driven Development
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
|  Form validation    | User submits empty or invalid data on form | An error is message is displayed    |
|  Sign up   | User enters a input for all fields and submits    | User is redirected to log in page|
|  Log in   | User enters valid details  | User is logged in and redirected to main page|
|  New pitch   | User enters submits a new pitch  | Pitch is added to list |
|  Comment   | User clicks on comment link | All comments are displayed and user can submit a new comment|
|  Profile   | User clicks on account link | Account details and posts made by the user are displayed |
|  Log out   | User logs out |Redirected to main page and a message shown |

## Technology Used
Python
Html
css

## Licence
MIT License

Copyright (c) 2022 Venus Mwende

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Authors Info
Email - [Venus Mwende](venusmwende@gmail.com)