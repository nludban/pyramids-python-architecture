# From the Pyramids to Python
## Architecture To Cope With Big Projects

An original presentation for the
[Central Ohio Python User's Group](http://cohpy.org/).

> We learned to break too many lines of code into functions,
> and then reorganize as methods on classes, but how can we
> remember it all as the project grows to hundreds or thousands
> of classes? From ancient pyramids to modern skyscrapers,
> see some patterns (and anti-patterns) that can be applied to
> our Python projects to make them orders of magnitude easier
> (or harder) to build and maintain.

The "slides" are a single HTML page, for best viewing resize
the browser window and embiggen the contents so just one of
the blue page headers is shown (a few slides are longer and
require a little scrolling).

View [online](https://htmlpreview.github.io/?https://github.com/nludban/pyramids-python-architecture/blob/master/presentation.html).

Note the [attrs](https://www.attrs.org/en/stable/)
and [lxml](https://lxml.de/) recommendations from 2018 are
stil good options, but today I would also consider
native [data classes](https://docs.python.org/3.7/whatsnew/3.7.html#dataclasses)
and [Pydantic](https://pydantic.dev/).
