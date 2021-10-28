# ZX0-Java

**ZX0-Java** is a multi-thread implementation of the
[ZX0](https://github.com/einar-saukas/ZX0) data compressor in
[Java](https://www.java.com/).


## Requirements

To run this compressor, you must have installed [Java](https://www.java.com/) 8
or later.


## Usage

To compress a file such as "Cobra.scr", use the command-line compressor as
follows:

```
java -jar zx0.jar Cobra.scr
```

Java 8 memory allocation is limited to (at most) 1Gb by default. You can use
parameter "-Xmx" to increase maximum memory allocation, for instance:

```
java -Xmx2G -jar zx0.jar Cobra.scr
```

This compressor uses 4 threads by default. You can use parameter "-p" to
specify a different number of threads, for instance:

```
java -jar zx0.jar -p2 Cobra.scr
```

All other parameters work exactly like the original version. Check the official
[ZX0](https://github.com/einar-saukas/ZX0) page for further details.


## License

The Java implementation of [ZX0](https://github.com/einar-saukas/ZX0) was
authored by **Einar Saukas** and it's available under the "BSD-3" license.


## Links

* [ZX0](https://github.com/einar-saukas/ZX0) - The original version of **ZX0**,
by the same author.

* [ZX0-Kotlin](https://github.com/einar-saukas/ZX0-Kotlin) - A similar
multi-thread data compressor for [ZX0](https://github.com/einar-saukas/ZX0)
in [Kotlin](https://kotlinlang.org/), by the same author.

* [ZX5-Kotlin](https://github.com/einar-saukas/ZX5-Kotlin) - A similar
multi-thread data compressor for [ZX5](https://github.com/einar-saukas/ZX5)
in [Kotlin](https://kotlinlang.org/), by the same author.
