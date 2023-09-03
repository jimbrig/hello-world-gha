# Hello World GitHub (Docker) Action

[![.github/workflows/main.yml](https://github.com/jimbrig/hello-world-gha/actions/workflows/main.yml/badge.svg)](https://github.com/jimbrig/hello-world-gha/actions/workflows/main.yml)

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example Usage

```yaml
uses: jimbrig/hello-world-gha@v1
with:
  who-to-greet: 'John Doe'
```
