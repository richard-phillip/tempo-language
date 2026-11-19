# Tempo

Syntax highlighting for the Tempo programming language.

```tempo
* Read a column and fold it.
use tempo/fold.

fn main -> Result
{
  hdu.read-column from binary-file at 'Xgal' into x-gal, reals!
  fold.min x-gal into x-min.
  Ok.
}
```

Install Rust Python Functional Dark for the matching colors.
