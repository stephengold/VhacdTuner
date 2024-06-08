<img height="150" src="https://i.imgur.com/YEPFEcx.png" alt="Minie Project logo">

[VhacdTuner][project] is a GUI application
to tune [the V-HACD algorithm][vhacd] for a particular mesh.

Complete source code (in Java) is provided under
[a 3-clause BSD license][license].

VhacdTuner was designed for a desktop environment with:

 + a wheel mouse and
 + a display at least 640 pixels wide and 700 pixels tall.


<a name="toc"></a>

## Contents of this document

+ [How to build and run VhacdTuner from source](#build)
+ [Using VhacdTuner](#use)
+ [Conventions](#conventions)
+ [External links](#links)
+ [History](#history)
+ [Acknowledgments](#acks)


<a name="build"></a>

## How to build and run VhacdTuner from source

1. Install a 64-bit [Java Development Kit (JDK)][adoptium],
   if you don't already have one.
2. Point the `JAVA_HOME` environment variable to your JDK installation:
   (In other words, set it to the path of a directory/folder
   containing a "bin" that contains a Java executable.
   That path might look something like
   "C:\Program Files\Eclipse Adoptium\jdk-17.0.3.7-hotspot"
   or "/usr/lib/jvm/java-17-openjdk-amd64/" or
   "/Library/Java/JavaVirtualMachines/zulu-17.jdk/Contents/Home" .)
  + using Bash or Zsh: `export JAVA_HOME="` *path to installation* `"`
  + using [Fish]: `set -g JAVA_HOME "` *path to installation* `"`
  + using Windows Command Prompt: `set JAVA_HOME="` *path to installation* `"`
  + using PowerShell: `$env:JAVA_HOME = '` *path to installation* `'`
3. Download and extract the More Advanced Vehicles source code from GitHub:
  + using [Git]:
    + `git clone https://github.com/stephengold/VhacdTuner.git`
    + `cd VhacdTuner`
4. Run the [Gradle] wrapper:
  + using Bash or Fish or PowerShell or Zsh: `./gradlew run`
  + using Windows Command Prompt: `.\gradlew run`

You can restore the project to a pristine state:
+ using Bash or Fish or PowerShell or Zsh: `./gradlew clean`
+ using Windows Command Prompt: `.\gradlew clean`

[Jump to the table of contents](#toc)


<a name="use"></a>

## Using VhacdTuner

(Documentation not yet written.)

[Jump to the table of contents](#toc)


<a name="conventions"></a>

## Conventions

The source code and pre-built executables are compatible with JDK 8.

[Jump to the table of contents](#toc)


<a name="links"></a>

## External links

+ [V-HACD v4 slideshow](https://docs.google.com/presentation/d/1OZ4mtZYrGEC8qffqb8F7Le2xzufiqvaPpRbLHKKgTIM)

YouTube videos about Minie:

  + August 2022 walkthru of the VhacdTuner application
    [watch](https://www.youtube.com/watch?v=iEWJtPujmM8) (7:45)
    [source code](https://github.com/stephengold/Minie/blob/e1b7781fd06d8060ab96928379509a732fd9398f/VhacdTuner/src/main/java/jme3utilities/minie/tuner/VhacdTuner.java)

[Jump to the table of contents](#toc)


<a name="history"></a>

## History

From August 2022 to June 2024, VhacdTuner was a subproject of
[the Minie Project][minie].

Since June 2024, VhacdTuner has been a separate project, hosted at
[GitHub][project].

[Jump to the table of contents](#toc)


<a name="acks"></a>

## Acknowledgments

Like most projects, the VhacdTuner Project builds on the work of many who
have gone before.  I therefore acknowledge the following
artists and software developers:

+ Khaled Mamou for creating and licensing the [V-HACD Library][vhacd]
  for decomposing meshes into convex hulls
+ Riccardo Balbo (aka "riccardo") for creating and licensing
  the [V-HACD Java Bindings Project][vhacdBindings]
+ plus the creators of (and contributors to) the following software:
    + the [Checkstyle] tool
    + the [Firefox] web browser
    + the [Git] revision-control system and GitK commit viewer
    + the [GitKraken] client
    + the [Gradle] build tool
    + the [IntelliJ IDEA][idea] and [NetBeans] integrated development environments
    + the [Java] compiler, standard doclet, and runtime environment
    + [jMonkeyEngine][jme] and the jME3 Software Development Kit
    + the [Linux Mint][mint] operating system
    + LWJGL, the Lightweight Java Game Library
    + the [Markdown] document-conversion tool
    + the [Meld] visual merge tool
    + Microsoft Windows
    + the [Nifty] graphical user-interface library
    + [Open Broadcaster Software Studio][obs]

I am grateful to [GitHub], [Sonatype],
[MacStadium], [YouTube], and [Imgur]
for providing free hosting for this project
and many other open-source projects.

I'm also grateful to my dear Holly, for keeping me sane.

If I've misattributed anything or left anyone out, please let me know, so I can
correct the situation: sgold@sonic.net

[Jump to the table of contents](#toc)


[adoptium]: https://adoptium.net/releases.html "Adoptium Project"
[checkstyle]: https://checkstyle.org "Checkstyle"
[firefox]: https://www.mozilla.org/en-US/firefox "Firefox"
[fish]: https://fishshell.com/ "Fish command-line shell"
[git]: https://git-scm.com "Git"
[github]: https://github.com "GitHub"
[gitkraken]: https://www.gitkraken.com "GitKraken client"
[gradle]: https://gradle.org "Gradle Project"
[idea]: https://www.jetbrains.com/idea/ "IntelliJ IDEA"
[imgur]: https://imgur.com/ "Imgur"
[java]: https://en.wikipedia.org/wiki/Java_(programming_language) "Java programming language"
[jme]: https://jmonkeyengine.org "jMonkeyEngine Project"
[license]: https://github.com/stephengold/VhacdTuner/blob/master/LICENSE "VhacdTuner license"
[macstadium]: https://www.macstadium.com/ "MacStadium"
[markdown]: https://daringfireball.net/projects/markdown "Markdown Project"
[meld]: https://meldmerge.org "Meld merge tool"
[minie]: https://stephengold.github.io/Minie/minie/overview.html "Minie Project"
[mint]: https://linuxmint.com "Linux Mint Project"
[netbeans]: https://netbeans.org "NetBeans Project"
[nifty]: https://nifty-gui.github.io/nifty-gui "Nifty GUI Project"
[obs]: https://obsproject.com "Open Broadcaster Software Project"
[project]: https://github.com/stephengold/VhacdTuner "VhacdTuner Project"
[sonatype]: https://www.sonatype.com "Sonatype"
[utilities]: https://github.com/stephengold/jme3-utilities "Jme3-utilities Project"
[vhacd]: https://github.com/kmammou/v-hacd "V-HACD Library"
[vhacdBindings]: https://github.com/riccardobl/v-hacd-java-bindings "Riccardo's V-hacd-java-bindings Project"
[youtube]: https://www.youtube.com/ "YouTube"
