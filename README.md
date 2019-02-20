# LithiumBit-pool-list

The goal of this repository is to have a central list of pools for TurtleCoin (http://lithiumbit.com) mining. If you run a pool, please submit a Pull Request against *v2/turtlecoin-pools.json* to get added.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: https://raw.githubusercontent.com/LithiumBit/turtlecoin-pools-json/master/v2/lbit-pools.json

## Contributing

Please add your pool to the list in **alphabetical order**, named using CamelCase.domain style, and **include trailing slashes** for the `url` and `api` values.

**e.g.**
```
    {
        "name" : "LithiumBit.com",
        "url" : "https://pool01.lithiumbit.com/",
        "api" : "https://pool01.lithiumbit/api/",
        "type" : "forknote"
    },
```

### Possible values for 'type'
 - forknote
 - forknote-alt
 - node.js
 - other
