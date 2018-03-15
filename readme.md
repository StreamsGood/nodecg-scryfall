# nodecg-scryfall

[![Greenkeeper badge](https://badges.greenkeeper.io/StreamsGood/nodecg-scryfall.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/StreamsGood/nodecg-scryfall.svg?branch=master)](https://travis-ci.org/StreamsGood/nodecg-scryfall)

```sh
# All dependencies are managed by bower.
bower install
```

Two nodecg dashboard panels to search [scryfall](https://scryfall.com)'s Magic The Gathering card database.

### Search for Results with Scryfall's Autocomplete
![search-autocomplete.jpg](.github/images/search-autocomplete.jpg)

### Hover over Results to preview them
![search-results.jpg](.github/images/search-results.jpg)

### Click on a Result to change the output
![search-output.jpg](.github/images/search-output.jpg)


Access the image in your graphics by hooking into the Replicant.

```js
replicant-name="selected"
replicant-bundle="nodecg-scryfall"

// Example: Javascript
const selected = nodecg.Replicant('selected', 'nodecg-scryfall');

// Example: nodecg-replicant WebComponent
<nodecg-replicant replicant-name="selected" replicant-bundle="nodecg-scryfall" value="{{selected}}"></nodecg-replicant>
```
