# tv-maze

## Usage

```javascript
var tvmaze = require('tv-maze')

var client = tvmaze.createClient()

client.shows(function (err, shows) {
  // do something shows
})

client.search('lost', function (err, shows){
  // do something shows
})
```
