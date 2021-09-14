# LPCLib

This directory contains the complete set of source code and auxiliary files needed build projects using the LPCLib library.

The intent of the library is to provide beginner-friendly interfaces to common tasks within core C++ courses at the college level.
This includes converting between string and numeric data and modifying entire strings (to make upper- or lower-case). It also includes
a complete (though simple) object-oriented graphics library, implemented with CImg.

For data structures or similar courses, the library provides a few interesting classes:
- **Grid<T>**: Representing a 2-dimensional grid, with built-in bounds checking
- **Lexicon**: An efficiently stored repository of strings with whole-word and prefix lookup, derived from [this](https://web.stanford.edu/class/archive/cs/cs106b/cs106b.1216/lectures/28-lexicon/slides).
- **Scanner**: A tokenizer in the spirit of Java's Scanner class.
