# cli-alerts
A node module which prompt out cli alerts


## Install

```sh
npm install node-cli-alerts

```

<br>


## Usage

```js
const alerts = require('node-cli-alerts');

alert({type: `success`, msg: `Everything finished!`, name: `Done`});
alert({type: `warning`, msg: `You didn't add something!`});
alert({type: `info`, msg: `Elvis is awesome!`});
alert({type: `error`, msg: `Something went wrong!`});

// Provide the type, msg, and name options.


```

<br/>

## API

### alert(options)

#### > options

Type: object <br>
Default: {} (optional)

You can specify the options below.

#### > type

Type: string <br>
Default: error

#### > msg

Type: string <br>
Default: `You forgot to define all options.`

#### > name

Type: string <br>
Default: ``


<br>