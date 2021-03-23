# hello javascript action

## Author: Sergio González Guerra

This action prints "Hello World" or "Hello" + the name of a person to greet to the log

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-js-action-alu0100901214@v1
with:
  who-to-greet: 'Sergio'