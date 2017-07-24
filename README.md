# GetTheForecast
GTF: Get The Forecast - A weather application written in Swift

# GTF: Get The Forecast

GTF is a mobile application written in Swift that displays local weather data to users. As an added feature
users can also see information on the next four major moon cycles. All data is provided by the Aeris RESTful API
and is implemented using their software development kit. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

* You will need to sign up for a free developer account with Aeris, in order to obtain an API key and secret code
https://www.aerisweather.com/signup/developer/
* You will need a version of Xcode 8 or higher


### Installing

A step by step series of examples that tell you have to get a development env running

Download the git repo to your local machine by either clicking 'Download' or using the following command in terminal

```
git clone https://github.com/ahspadafora/GetTheForecast.git
```

go to the project directory in terminal and open the Xcode workspace 

Go to https://www.aerisweather.com/signup/developer/ and sign up for a free developers account

Enter your api credentials in the Credentials.swift file inside the Xcode project
```
class Credentials {
    
    var shared = Credentials()
    
    var apiKey = "enter your api key here"
    var apiSecret = "Enter your api secret code here"
}
```

Run the Xcode Workspace

## Built With

* [Aeris iOS SDK](https://www.aerisweather.com/support/docs/toolkits/aeris-ios-sdk/) - The sdk used
* [CocoaPods](https://cocoapods.org/) - Dependency Management


## Authors

* **Amber Spadafora** - 


