# Correction spacing: eqnarray(*), aligned, alignedat, and gathered.

## Descriptions

We will fix some expression environments spacing.
It is a correction in the horizontal spacing of the alignment.

## Version

1.0

## Usage

### Preamble

```
\usepackage{amsmath}% optional: if you use aligned, alignedat or gathered env.
\usepackage{correctmathalign}
```

### Options

 * latexorg: original behavior of LaTeX/amsmath package
 * fleqn: corresponds to class file and/or amsmath package's fleqn option

## File with Original Definitions

 * eqnarray: latex.ltx
 * \start@aligned and gathered: amsmath.sty

## Author

Yuwsuke Kieda

## License

BSD 2-Clause License
