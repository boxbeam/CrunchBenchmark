# CrunchBenchmark
Benchmarks of Crunch against other expression evaluation libraries

# Results

```
Benchmark                                        Mode      Score     Error  Units
CompileBenchmark.crunchCompileComplexExpression  avgt      2.974 ±   0.033  us/op
CompileBenchmark.crunchCompileSimpleExpression   avgt      0.050 ±   0.001  us/op
CompileBenchmark.evalExCompileComplexExpression  avgt     38.450 ±   0.526  us/op
CompileBenchmark.evalExCompileSimpleExpression   avgt      9.156 ±   0.256  us/op
CompileBenchmark.exp4jCompileComplexExpression   avgt      3.464 ±   0.026  us/op
CompileBenchmark.exp4jCompileSimpleExpression    avgt      0.276 ±   0.009  us/op
EvalBenchmark.crunchConstantEval                 avgt      0.823 ±   0.020  ns/op
EvalBenchmark.crunchSimpleEval                   avgt      4.296 ±   0.058  ns/op
EvalBenchmark.evalExConstantEval                 avgt  26156.342 ± 183.188  ns/op
EvalBenchmark.evalExSimpleEval                   avgt   2283.572 ±  19.630  ns/op
EvalBenchmark.exp4jConstantEval                  avgt    540.194 ±   4.434  ns/op
EvalBenchmark.exp4jSimpleEval                    avgt     44.727 ±   0.554  ns/op

```