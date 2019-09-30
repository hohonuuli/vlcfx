# vlcfx

Demostration player using JavaFX 13+ (with native buffer support) and VLCJ. From discussions at <https://github.com/caprica/vlcj/issues/883#>. Requires that VLC is installed.

## Usage

Requires at least Java 12 to compile and run. To package up like a platform native app, you will also need to download a [JDK with jpackage](https://jdk.java.net/jpackage/).

### Run

```
gradle run
```

### Package

```
export JPACKAGE_HOME=/Path/to/jdk14-with-jpackage
gradle jpackage
```
