# Driving Test Cancellations
A simple Python bot which will search, reserve and book driving tests for you using the DVSA website.

## Features
- Reserves earlier tests for you automatically
- Can bypass DVSA firewalls using chrome extensions
- You can easily implament your own notification system
- Seach for multiple bookings
- Waits in the queue for you when the site is busy
- FREE!

## Cloud Connection (Coming Soon)
We are hoping to allow you to connect your bot to our cloud serivces at https://copadrivingtest.co.uk/ soon so that you can easily manage cancellations via SMS through our website. Check back soon for an update!

## About
Due to current high demand for driving tests I have built a simple python script which will quickly check the driving test booking page for any available tests. It is also free to use and fairly simple, just put your current test in to the script file and it will do the rest for you. You can also configure your own notification system such as using gmail.

## Requirements
- Latest version of captcha buster https://github.com/dessant/buster/releases/latest (Please download the chrome .zip file, call it buster-chrome.zip and save it in the same directory as the python script as python cannot access the downloads from the chrome store)
- Google Chrome (https://www.google.com/intl/en_uk/chrome/) or Chromium
- PIP packages:
  - selenium
  - undetected-chromedriver
  - configparser

## Limitations
- You cannot book tests unless you are at the computer. However, this will be fixed soon with our cloud connection.
- It gets stuck waiting for a user input on weather to book a test.
- You can only use your booking refrence and not your theory test pass number
