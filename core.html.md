# core


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

------------------------------------------------------------------------

<a
href="https://github.com/frankausberlin/nbdevhelloworld/blob/main/nbdevhelloworld/core.py#L9"
target="_blank" style="float:right; font-size:smaller">source</a>

### say_hello

>      say_hello (to)

*Say hello to somebody*

------------------------------------------------------------------------

<a
href="https://github.com/frankausberlin/nbdevhelloworld/blob/main/nbdevhelloworld/core.py#L14"
target="_blank" style="float:right; font-size:smaller">source</a>

### foo

>      foo ()

``` python
say_hello("Isaac")
```

    'Hello Isaac!'

``` python
assert say_hello("Hamel") == "Hello Hamel!"
```

``` python
from fastcore.test import *
```

``` python
test_eq(say_hello("Hamel"), "Hello Hamel!")
```

``` python
from IPython.display import display,SVG
```

``` python
display(SVG('<svg height="100" xmlns="http://www.w3.org/2000/svg"><circle cx="50" cy="50" r="40"/></svg>'))
```

![](00_core_files/figure-commonmark/cell-9-output-1.svg)