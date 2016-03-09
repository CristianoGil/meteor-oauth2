## Meteor OAuth2

This is the root repository of several meteor packages that give your application the ability to act as an OAuth2 server or login to a OAuth2 Meteor application.

Checkout the packages for the package source. The examples will be very helpful in understanding what you can do with these packages.


=========================================
#### OAuth Flow  


````bash
1         Start App                     # Meteor.startup()
1.1       Launch Browser                #
1.1.1.    Request Login                 #
1.1.1.1   Create Login Page             #
1.1.1.2   Return to Login Page          #
2         Enter Login Details           #
2.1       Submit Login Details          #
2.1.1     Authenticate User             #
2.1.2     Redirect to Application       #
3         Intercept Redirect            #
4         Extract Auth Code             #
5         Get Access Token              #
5.1       Return Access/Refresh Token   #
6         Save Refresh Token            #
7         Get Data                      #
7.1       Check Access Token            #
7.2       Return Data                   #
8         Rest of Business Logic        #
````


=========================================
#### Licensing  

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
