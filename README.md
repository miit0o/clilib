<div align="center">
  <a href="https://github.com/miit0o/clilib">
    <img width="200" height="200" src="https://i.imgur.com/E8JFbdP.png">
  </a>
  <br>

![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/miit0o/clilib?include_prereleases)

![Java Version](https://img.shields.io/badge/java-1.8-brightgreen)
![GitHub last commit](https://img.shields.io/github/last-commit/miit0o/clilib)
![Java Version](https://img.shields.io/badge/build-passing-brightgreen)
![Java Version](https://img.shields.io/badge/PRs-welcome-brightgreen)

  <br>

  ![GitHub All Releases](https://img.shields.io/github/downloads/miit0o/clilib/total)
  ![GitHub closed issues](https://img.shields.io/github/issues-closed/miit0o/clilib)
  ![GitHub issues](https://img.shields.io/github/issues/miit0o/clilib)
  
  <h1>clilib</h1>
  <p>
    clilib is a java library providing different style additions for command line applications. This might sound pretty useless in the first place (probably because it is), but there might be some cases, where colors actually come in handy.
  </p>
</div>

## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#install)
3. [Usage](#usage)
5. [Contributing](#contributing)
6. [Support](#support)
7. [Creator](#creator)
19. [Projects using clilib](#projects)

<h2 align="center" id="requirements">Requirements</h2>

Well, since this is a simple library, there isn't much you need.

**What you need**

* Latest clilib version from the [release page](https://github.com/miit0o/clilib/releases)
* A java 8 based project

<h2 align="center" id="install">Install</h2>

### Download the latest version

To start off, please head to the [releases page](https://github.com/miit0o/clilib/releases) and download a pre-built jar.

*If you don't trust me for some reason, feel free to download the latest released source code and build it your self.*

### Import the library to your IDE/project

This process depends on the IDE, so just do it as it is done with your's.

<h2 align="center" id="usage">Usage</h2>

### Using colors
Colors can be used like this:

```java
System.out.println(TextColors.red + "Look at what I can do!" + TextColors.reset);
System.out.println(TextColors.bgred + "Look at what I can do!" + TextColors.reset);
```

### Using styles
Styles can be used like this:

```java
System.out.println(TextStyles.bold + "Look at what I can do!" + TextStyles.reset);
System.out.println(TextColors.underline + "Look at what I can do!" + TextColors.reset);
```

### Alternatively, you can use Clilib's wrapper methods:

Colors:

```java
System.out.println(Color.blue("Ciao!"));
```

Backgrounds:

```java
System.out.println(Background.red("Sain bainuu!"));
```

Formatting:

```java
System.out.println(Formatting.bold("Halo!"));
```

Lining:

```java
System.out.println(Lining.underline("Silaw!"));
```

This way, you can combine several stylings at once very easily:

```java
System.out.println(Background.green(Lining.underline(Color.blue("Ndêwó!"))));
System.out.println(Lining.strikethrough(Color.purple("Yassou!")));
```



<h2 align="center" id="contributing">Contributing</h2>

If there is anything that I missed, but should be in here, feel free to add it.

<h2 align="center" id="support">Support</h2>

If you have discovered a 🐜 or have a feature suggestion, feel free to create an issue on Github.

### License

This project is lincensed under the MIT License.

<h2 align="center" id="creator">Creator</h2>

<table align="center">
  <tbody>
    <tr>
      <td align="center" valign="top">
        <img width="150" height="150" src="https://avatars0.githubusercontent.com/u/52698477?s=460">
        <br>
        <a href="https://github.com/miit0o">Christoph</a>
        <p>Backend developer</p>
      </td>
    </tr>
  </tbody>
</table>

<h2 align="center" id="projects">Projects using clilib</h2>
<p align="center">(In chronological order)</p>

* [EMERNET E.I.N.S Server Runtime](https://github.com/emernet-eins/server)
* [SENSYTE Client](https://github.com/sensyteorg/client)
