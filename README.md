# tscss

`tscss` is a CLI tool that generates TypeScript definitions for [Modular CSS](https://github.com/tivac/modular-css)
files.

## Usage Example

```sh
$ tscss --watch --path src/**/*.css
```

## CLI Options

```
  Usage: tscss [opts]
  Available options:
    --path or -p <path>   Minimatch pattern for css files. Defaults to "src/**/*.css".
    --watch or -w         Enable watch mode.
    --version or -v       Print tscss version.
```