# vlcfx

Demostration player using JavaFX 13+ (with native buffer support) and VLCJ. From discussions at <https://github.com/caprica/vlcj/issues/883#>. Requires tha VLC is installed.

## Usage

Requires at leas Java 12 to comple and build. You will also need to download a [JDK with jpackage](https://jdk.java.net/jpackage/).

### run

```
gradle run
```

### Package

```
export JPACKAGE_HOME=/Path/to/jdk14-with-jpackage
gradle jpackage
```