# pysyllable

based on npm package [syllable](https://www.npmjs.com/package/syllable)
([src](https://github.com/words/syllable))

## installation

```{bash}
python3 -m pip install pysyllable
```

## Use

```{python}
from pysyllable import syllable
syllable(value)
```

## API

```count=syllable(value)```
* value -- word(s) to check
* count -- combined number of syllables

## Stats

CMUDict accuracy is 92.2% (see [tests](../blob/main/tests))
