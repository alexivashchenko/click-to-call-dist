# click-to-call-dist

## Description

Simple Vanilla JavaScript repository to make phone links callable by "VoiceMpower Click to Call" software.


## Usage

1. Add to the target links class `click-to-call` (`href` attribute should be started from `tel:` or `callto:`).
2. Add to the links page config JavaScript object `CTC_Config`.
3. Add to the links page JavaScript file `click-to-call-dist.js` (right after `CTC_Config` object).


## Config

The `CTC_Config` object variables:

| Variable | Possible values | Default value | Description |
| ------ | ------- | ------- | ------ |
| `SSL` | `true` / `false` | `true` | Define if the WebSocket connection should be created with SSL |
| `Host` | `IP` / `URL` | `192.168.11.52` | Your "VoiceMpower Click to Call" software IP address or Host |
| `Port` | `INT` | `4445` | Your "VoiceMpower Click to Call" host port |
| `Extension` | `STRING` | `601` | Your Extension (may be unique for each operator) |
| `Password` | `STRING` | `601` | Your Password (may be unique for each operator) |
| `debug` | `true` / `false` | `false` | Show / Hide additional debug messages |




## Example

[example.html](example.html)

