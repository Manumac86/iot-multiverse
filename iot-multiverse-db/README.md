# iot-multiverse-db

## Usage

```js
const setupDatabase = require('iot-multiverse-db');

setupDatabase(config).then(db => {
    const { Agent, Metric } = db;
}).catch(err => console.error(err));
```