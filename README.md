# Hello world javascript action

Esta action imprime "Hello World" or "Hello" + o nome da pessoa a ser saudada no log.

## Inputs

### `who-to-greet`

**Required** O nome da pessoa a ser saudada. Default `"World"`.

## Outputs

### `time`

A hora da saudação.

## Exemplo de uso

```yaml
uses: actions/hello-world-javascript-action@e76147da8e5c81eaf017dede5645551d4b94427b
with:
  who-to-greet: 'Mona the Octocat'
```
