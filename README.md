# Background Knowledge in Schema Matching: Strategy vs. Data | Supplemental Material
This is supplementary material for article "Background Knowledge in Schema Matching: Strategy vs. Data" to be published in the proceedings of the International Semantic Web Conference 2021 (ISWC 2021).

## Contents of this Repository
```
raw_results_data/
   |
   --- performance/
   |      |
   |       --- <...>
   |
   --- significance/
          |
           --- <...>
significance_matrix
   |
   --- all_testcase_matrix.png
```

The directories in `raw_results_data` have been generated with [MELT](https://github.com/dwslab/melt/). If you have any questions on how to interpret the `performance` result files, have a look at the [user guide for the default evaluation](https://dwslab.github.io/melt/matcher-evaluation/evaluators#evaluatorcsv). The `performance` directory also contains *all* alignments used in this paper. 

If you have any questions on how to interpret the `significance` result files, have a look at the [user guide for the significance evaluation](https://dwslab.github.io/melt/matcher-evaluation/evaluators#evaluatormcnemarsignificance).

A high resolution version of Figure 2 is provided in directory `significance_matrix`.

## Code Contributions
The implementation has been directly commited to the MELT framework and is documented there:
- [MELT Background Knowledge Component](https://dwslab.github.io/melt/matcher-development/with-background-knowledge)
- [Significance Evaluation](https://dwslab.github.io/melt/matcher-evaluation/evaluators#evaluatormcnemarsignificance)