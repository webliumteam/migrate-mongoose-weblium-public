# CHANGELOG

### 4.0.3

 * Update dependencies: `"yargs": "^4.8.1" => "yargs": "^15.3.1"`

### 4.0.2

 * Add init script support: check and run file `init/init-connection.js` at migrations dir to establish mongo connection or other init functionality 

### 4.0.1

 * Fix deprecation warning - add `{ useUnifiedTopology: true }` to module's internal mongo connection 