# Directory lists without duplicates

This repo contains modified versions of James Fisher's directory lists version 2.3.

The lists in this repo were changed so that:

- -medium does not include words from -small.
- -big does not include words from -medium or -small.

Also, words from the three lowercase lists have been removed from their non-lowercase counterparts.

## Why?

To save time during web fuzzing. If a short list fails, I don't want to waste time re-using those words in a medium list.

## License

[Creative Commons Attribution-Share Alike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/)
