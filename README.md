# gempa-id-info

#### Basic Code:

```js

let gempa_bmkg = require('gempa-id-info') // Includes 2 functions: latestGempa() & listof5plusgempa()


gempa_bmkg.latestGempa().then(data => {
    console.log(data) // Returns {Terjadi: ..., Coordinates: ..., Magnitude: ...,} ...
})

gempa_bmkg.listof5plusgempa().then(data => {
    console.log(data) // Returns [{Terjadi: ..., Coordinates: ..., Magnitude: ...,},{Terjadi: ..., Coordinates: ..., Magnitude: ...,},{Terjadi: ..., Coordinates: ..., Magnitude: ...,} ...]
})

```

##### NPM Package Name: [gempa-id-info](https://www.npmjs.com/package/gempa-id-info)
##### Latest Version: 1.0.22
##### Current Beta Version: 1.0.5-beta
