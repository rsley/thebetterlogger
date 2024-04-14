# TheBetterLogger
My personal logger, published to NPM.
--

*A little bit of a messy codebase; but in my defense, this was a 1 hour mini-project*

## Initialization
```js
const Logger = require("thebetterlogger")

const logger = new Logger("debug", "America/Chicago", "logs")
logger.deleteToday()
logger.log("info", "test", "This is a test log")
logger.log("error", "test", "This is a test error")
logger.log("debug", "test", "This is a test debug")
```
- You may replace `debug` with `info` to ignore DEBUG logs
- You may replace `America/Chicago` to Any Timezone
- You may replace `logs` with a full folder path, like `/home/you/mylogs`

### Log Levels
- debug
- info

### Log Types
- Info
- Success
- Error
- Debug

### Platforms
- Console
- Files