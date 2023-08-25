# NAME

    ansiexpand - convert tabs to spaces in text containing ANSI color codes

# SYNOPSIS

    ansiexpand [-t] [FILE]...

# DESCRIPTION

![UI](https://github.com/nkh/ansiexpand/blob/main/media/ansiexpand.png)

Convert tabs in each FILE to spaces, writing to standard output.

Compared to *expand (1)* it:
- handles ANSI color codes
- handles Unicode characters
- fast enough

# OPTIONS

```bash
-t, --tabs=N
      have tabs N characters apart, not 8
```

# SEE ALSO 

[ansiexpand](https://github.com/tecolicom/App-ansiexpand)


[expand](https://www.gnu.org/software/coreutils/manual/html_node/expand-invocation)

# AUTHORS

    Khemir Nadim ibn Hamouda
    https://github.com/nkh
    CPAN ID: NKH

# LICENCE

© Nadim Khemir 2023, Artistic licence 2.0
