### csgo-stats
About the module: csgo-stats is a very simple to 
use module to communicate with csgo's API by filling 2 very simple to understand parameters that will let you get data

### example
```js
const csgoStats = require('csgo-stats');
  csgoStats.load({
      key: 'steamAPIkey',
      id: 'steamCommunityID'
    }).then(r => {
       console.log(r.body.playerstats.stats)
    }).catch(e => console(e))```

# License
