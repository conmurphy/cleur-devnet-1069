# Cisco Live Barcelona 2020 - DEVNET-1069 

This is a sample weather application which provides detailed information about the weather in a particular location 

* Website: developer.cisco.com 
* Mailing List: [Google Groups]()
* Chat: 
   * [Webex Teams]()
   * #devnet-1069 on freenode.org 


![alt tag](https://github.com/conmurphy/cleur-devnet-1069/blob/master/weather-app.png)



## Table of Contents

* [Cisco Live Barcelona 2020 - DEVNET-1069](#cisco-live-barcelona-2020---devnet---1069)
   * [Table of Contents](#table-of-contents)
      * [Features](#features)
      * [Quick Start](#quick-start)
         * [Prerequisites](#prerequisites)
         * [Installation](#installation)
         * [Usage](#usage)
      * [Documentation](documentation)
      * [Guidelines and Limitations](#guidelines-and-limitations)
      * [Release Notes](release-notes)
      * [Contributing and Support](#contributing-and-support)
	   * [License](#license)

### Features

* Simple to use and install
* Weather reports for cities of your choosing
* 5 Day forecast available

## Quick Start

### Prerequisites

Tested on the following:

* Centos 7.7
* Ubuntu 18.04

### Installation

1. Clone the application repository to your local machine

   `git clone https://github.com/conmurphy/cleur-devnet-1069`

2. Modify the permissions of the weather application so that it is executable

   `chmod +x weather`

3. Move the weather application to your local bin folder 

   `mv weather /usr/local/bin`

### Usage



```

$ weather help

This is the help menu for the weather app. The following commands are available:

   <city>               View weather for a city
   <city> tomorrow      View tomorrows weather for a city
   <city> week          View the weekly weather report for a city
   
   set                  Set configuration
   show                 Show configuration
   delete               Delete configuration

   remindme             Set reminders for weather reports
   
   help                 View help information


$ weather barcelona

It will be mostly cloudy today with a high of 17°C and a low of 11°C.


$ weather barcelona tomorrow 

It will be be raining tomorrow with a high of 14°C and a low of 9°C.


$ weather barcelona week

| Day       |   High °C |   Low °C |
|-----------|-----------|----------|
| Monday    |        17 |        8 |
| Tuesday   |        17 |        6 |
| Wednesday |        16 |        6 |
| Thursday  |        15 |        6 |
| Friday    |        14 |        5 |


```

### Documentation

Full documentation with all commands is available at https://readthedocs.org/

### Guidelines and Limitations

* Only tested with Centos 7.7 and Ubuntu 18.04
* Does not currently accept countries so will not work where there are multiple cities of the same name in different countries

### Release Notes

Please see the [releases page]() for release notes on the incremental functionality and bug fixes incorporated into the published releases.


### Contributing and Support

If you experience any issues using this application, please report them using the issues page. 

For any contributions you would like to make please see the [contributing page](https://github.com/conmurphy/cleur-devnet-1069/blob/master/contributing.md) for further details.

### License

This project is licensed to you under the terms of the [Cisco Sample Code License](https://github.com/conmurphy/cleur-devnet-1069/blob/master/LICENSE).
