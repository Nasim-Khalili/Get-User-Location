# Get-User-Location

The Geolocation API of JavaScript is used to get the geographical position or location of a user.  Using this API, you will get the current latitude and longitude coordinates of the user if they allow it. In this small project (Get User Location in JavaScript), on the webpage, there is a button labeled as “Detect your location”.

When you clicked on this button, there will open a location prompt with allow and block options. If you block the request then the button text will change into “You denied the request”. If you allow the request then there will show “detecting your location”. After few seconds, there is shown your current location including city, postal code, and country.

# this website for api: https://opencagedata.com/

<hr/>
You can easily copy-paste or download the code files from there. But before you go to copy-paste codes, let’s understand the main JavaScirpt codes behind creating this project. In JavaScript codes, on the button click, first, I got the current latitude and longitude coordinates of the user device using the geolocation API.

Then using fetch API, I sent a get request to the opencagedata server with passing those coordinates and got all the location details of it means I used opencagedata API to get all location details of those coordinates. Remember, you should never store your API key in the JavaScript file because it’s a client-side language. So users can easily get your key and misuse it.

After extracting the file, open the JavaScript file and pass your API key in the fetch URL. You can get this key from the official OpenCageData site for free. You can also use any other site API for this project. If you do so then you have to modify the JavaScript codes accordingly

