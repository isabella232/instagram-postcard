# NOTE: This example was created on an outdated version of the Lob API. Please see the latest [Lob documentation](https://lob.com/docs) for the most up to date implementation.

# Instagram Postcard App in Express.js

## Registration

You will need to register for an Instagram Developer Account and a Lob API Key

* [Lob Registration](https://dashboard.lob.com/#/register)
* [Instagram Registration](https://instagram.com/developer/?hl=en)


## Install Dependancies
```
npm i
```

## Run
```
node index.js
```

Visit `localhost:3000` in your browser


## instagram/config.js
Configuration for Lob API Keys and Instagram Credentials

```
var config = {
  lob_api_key: 'xxxxx',
  instagram_redirect_uri: 'http://localhost:3000/handleauth',
  instagram_client_id: 'xxxxx',
  instagram_client_secret: 'xxxxx',
}
```


