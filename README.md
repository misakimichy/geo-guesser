# Geo Guesser

#### _Async and API call - Geo Guesser application_

## Description
It's a mock application of [Geo Guesser](https://geoguessr.com/).

When you open an application, you will be on the street view somewhere in Seattle (currently only in Seattle).
The you need to guess where you are from the street view then pin your guess on Google map.
Once you click the guess button on the bottom of the page, you'll see how close/far your guess is from the actual street.



## Application should have:

- A user can move around the street view.

- A user can pin his/her guess on the Google map.

- Once the guess button is clicked, the user can see how close/far the his/her guess is from the actual street on the map and in meters.

- Depends on the distance between two points, the user earns points.

- Once the modal is closed, the page reloads, and the user will be dropped off on a random street.


## Authorization
This application requires an API key. The application works without the API key but the street view color is inversion.

- Create your Google map API key at [Google Developer Console](console.developers.google.com).

- If you save this repo remotely, please save your API key separately and do not commit your API key.



## Setup/Installation Requirements

1. Clone this repo:
```
$git clone https://github.com/misakimichy/geo-guesser.git
```

2. Install dependencies: 
```
$npm install
```

3. Get an API key.

4. Insert your API key in `index.html`. No string needed:
```
<script src='https://maps.googleapis.com/maps/api/js?key=your-api-key'></script>
```

5. Open the web site with this command:
```
$npm run start
```

## Known Bugs
* No known bugs at this time.

## Support and contact details
Please contact me for any questions or feedbacks:
 misaki.koonce@gmail.com

## Technologies Used
_Git, GitHub, HTML, CSS, Bootstrap, jQuery, JavaScript, Webpack, Jasmine and Karma


## License
Copyright © 2019 under the MIT License