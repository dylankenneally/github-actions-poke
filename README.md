# Poking GitHub Actions

Repo used for learning more about GitHub Actions. Probably not useful to anyone else.

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: dylankenneally/github-actions-poke
with:
  who-to-greet: 'Mona the Octocat'
```
