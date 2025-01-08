# [__NAME__](https://doi.org/XXXXX)

## Abstract
Paper abstract or summary of the article submitted.

## Authors
Authors involved in this work and their respective contributions:
- Person1.
- Person2.

## Datasets

Instances are categorized in different datasets inside the 'instances' folder. All instances are from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) or reference to paper where they are from, etc.

### Instance format

(Explain instance format so other users may easily use them even if not using your code.)


## Compiling

You can easily compile and build an executable artifact of this project using...:
```text
mvn clean package
```

## Executing

There is a executable JAR inside the code folder.

Example 1: execute default experiment with the default set of instances
```text
java -jar target/ACO.jar 
```

Example: execute the default experiment using a different set of instances, located inside the `newinstances` folder.
```
java -jar target/ACO.jar --path=newinstances
```

## Requirements and dependencies

List of requirements:
- Java 11 or higher
- Maven 3.6 or higher

## Cite

Consider citing our paper if used in your own work:
(Fill with the references to your own published work)

### DOI
https://doi.org/XXXXXXX

### Bibtex
```bibtex
@article{
...
}
```

## Powered by MORK (Metaheuristic Optimization framewoRK)
| ![Mork logo](https://user-images.githubusercontent.com/55482385/233611563-4f5c91f2-af36-4437-a4b5-572b6655487a.svg) | Mork is a Java framework for easily solving hard optimization problems. You can [create a project](https://generator.mork-optimization.com/) and try the framework in under one minute. See the [documentation](https://docs.mork-optimization.com/en/latest/) or the [source code](https://github.com/mork-optimization/mork). |
|--|--|
