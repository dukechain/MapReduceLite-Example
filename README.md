###MapReduceLite-Example###
This project includes some running examples for [MapReduceLite](https://github.com/dukechain/MapReduceLite)

Before compile this project, please download the [MapReduceLite](https://github.com/dukechain/MapReduceLite) and go to the root directory of MapReduceLite to execute the following command in the console
```bash
mvn clean package install
```
It would be published in local maven repository. Then, you can execute the following command 
```bash
mvn clean package install
```
in the root directory of MapReduceLite-Example and the *.jar* file would be generated automatically.

Alternatively, you can copy the files in *lib* directory under *mapreducelite-XXX-bin.zip* and use the IDE such as Intellij or Eclipse. However, the genrated *.jar* might be too fat. 