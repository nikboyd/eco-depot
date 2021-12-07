### Site Build Instructions

0. Make sure you have Java and Git LFS installed.
1. Clone this repository from GitHub.
2. Run the following command in the repo base folder: 

```shell
java -jar syntopica.jar
```

This runs the [Syntopica][syntopica-tool] tool in the base folder. <br/>
**Syntopica** reads the files in **briefs** and **forms** to generate the model site in **topics** and **images**.

### Code Build Instructions

The code sketch included in this repository uses [Hoot Smalltalk][hoot-smalltalk] for its examples.
Once you have the requisite tools configured in your environment, 
you can run the following command:

```
mvn -U -B clean install
```

This will download the [Hoot compiler plugin][hoot-plugin] and bundled libraries.
Then, it will generate Java code from the Hoot code, build the depot models, and run the associated tests.

Back to [Overview](README.md/#overview)

[syntopica-tool]: https://github.com/nikboyd/syntopica/#syntopica
[hoot-smalltalk]: https://github.com/nikboyd/hoot-smalltalk#hoot-smalltalk
[hoot-plugin]: https://github.com/nikboyd/hoot-smalltalk#hoot-compiler-plugin
[get-credentials]: https://github.com/nikboyd/hoot-smalltalk#project-planning
