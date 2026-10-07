# Using this public copy

Clone this repository instead of the original team URL in the unchanged README:

```sh
git clone https://github.com/ryiugn/Medi-Drone.git
cd Medi-Drone
cp .env.example .env
```

Follow the original README for Docker setup. Supply your own API credentials in the ignored `.env` file. External API calls can incur charges.

The browser map in `ui/index.html` contains `YOUR_GOOGLE_MAPS_API_KEY`. Replace it locally with your own browser Maps JavaScript API key to enable the map; the server-side `.env` setting does not configure that static script. Restrict the browser key to the required APIs and your local HTTP referrer. Do not commit your configured copy.

The original configuration includes a team-hosted hospital API and the README includes original deployment links. Their continued availability is not guaranteed. This snapshot has not been verified as a complete running deployment.
