# Monte Carlo Simulation Python and calculate complexity metrics of the code
- by Heider Jeffer
## In This project we answer the following question
- what is the longest random walk you can take so that on average you will end up 4 blocks or fewer from home?
- The Longest-Random-Walk?
##  We used multimetric to calculate the following metrics for this project:
* Comment to Code percentage
* Cyclomatic complexity according to McCabe
* Difficulty according to Halstead
* Effort according to Halstead
* Fan-Out
* Lines of code
* Maintainability index
* Metric according to pylint
* Metric according to TIOBE
* Number of delivered bugs according to Halstead
* Time required to program according to Halstead
* Volume according to Halstead

## Example 
We use multimetric to extract the following information from Monte-Carlo-Longest-Random-Walk.py file

Output:

```
      "comment_ratio": 34.92063492063492,
      "cyclomatic_complexity": 5,
      "fanout_external": 1,
      "fanout_internal": 0,
      "halstead_bugprop": 0.26407821806216875,
      "halstead_difficulty": 17.41071428571429,
      "halstead_effort": 13793.371211282923,
      "halstead_timerequired": 766.2984006268291,
      "halstead_volume": 792.2346541865063,
      "lang": [
        "Python"
      ],
      "loc": 1,
      "operands_sum": 65,
      "operands_uniq": 28,
      "operators_sum": 81,
      "operators_uniq": 15
    }
```

## multimetric extract the following information from our codes:

| item                  | description                                    | range    | recommendation |
| --------------------- | ---------------------------------------------- | -------- | -------------- |
| comment_ratio         | Comment to Code percentage                     | 0..100   | > 30.0         |
| cyclomatic_complexity | Cyclomatic complexity according to McCabe      | 0..(inf) | < 10           |
| fanout_external       | Number imports from out of tree modules        | 0..(inf) |                |
| fanout_internal       | Number imports from same source tree modules   | 0..(inf) |                |
| halstead_bugprop      | Number of delivered bugs according to Halstead | 0..(inf) | < 0.05         |
| halstead_difficulty   | Difficulty according to Halstead               | 0..(inf) |                |
| halstead_effort       | Effort according to Halstead                   | 0..(inf) |                |
| halstead_timerequired | Time required to program according to Halstead | 0..(inf) |                |
| halstead_volume       | Volume according to Halstead                   | 0..(inf) |                |
| lang                  | list of identified programming languages       | list     |                |
| loc                   | Lines of code                                  | 1..(inf) |                |
| maintainability_index | Maintainability index                          | 0..100   | > 80.0         |
| operands_sum          | Number of used operands                        | 1..(inf) |                |
| operands_uniq         | Number of unique used operands                 | 1..(inf) |                |
| operators_sum         | Number of used operators                       | 1..(inf) |                |
| operators_uniq        | Number of unique used operators                | 1..(inf) |                |
| pylint                | General quality score according to pylint      | 0..100   | > 80.0         |
| tiobe_compiler        | Compiler warnings score according to TIOBE     | 0..100   | > 90.0         |
| tiobe_complexity      | Complexity according to TIOBE                  | 0..100   | > 80.0         |
| tiobe_coverage        | Coverage according to TIOBE                    | 0..100   | > 80.0         |
| tiobe_duplication     | Code duplications score according to TIOBE     | 0..100   | > 80.0         |
| tiobe_fanout          | Fan-Out score according to TIOBE               | 0..100   | > 80.0         |
| tiobe_functional      | Functional defect score according to TIOBE     | 0..100   | > 90.0         |
| tiobe_security        | Security score according to TIOBE              | 0..100   | > 90.0         |
| tiobe_standard        | Language standard score according to TIOBE     | 0..100   | > 80.0         |
| tiobe                 | General quality score according to TIOBE       | 0..100   | > 80.0         |

