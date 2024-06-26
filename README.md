# Strapi plugin address-fields

This is a Strapi plugin that allows you to select address fields (country, prefecture, city, etc.)

## Installation

To install this package, run the following command in an existing strapi project:

```sh
npm install strapi-plugin-address-fields
```

## Usage

To enable the plugin, you'll need to include the following code in your Strapi project, in the `/config/plugins.js` file:

```javascript
module.exports = () => ({
  'address-fields': {
    enabled: true,
  },
  // ... your other plugin configurations
});
```

## Additional Information

At this time (2022-08-02), the plugin only supports [Vietnam](https://simplemaps.com/data/vn-cities) and [Japan](https://simplemaps.com/data/ja-cities)

The address options are based on [SimpleMaps](https://simplemaps.com).
