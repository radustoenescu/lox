Core Java 9 for the Impatient
=============================

- strings are UTF-16 encoded
- `/** */` is a documentation comment
- `Shift + Tab` in jshell starts a smarter auto completion
- + v generates variable creation
- + i generates an import for a given class short name

# Primitive values

- all NaN values are different, use `Double.isNan( value )`

# Variables

- `final` variables can be initialized later, as long as they're initialized exactly once before use

# Misc

- division by zero is checked for integers and yields an exception
- `strictfp` makes floating-point ops portable by not using dedicated hardware that might affect the
precision of the computation

# Generic advice

- declare variables as late as possible, close to the place you want to use them

