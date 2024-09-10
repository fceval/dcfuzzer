This is the main project for our new paper of Robust Directed Fuzzing by Reusing and
Combining Existing Fuzzers.

In this paper, directed collaborative fuzzing is proposed to improve the robustness of directed fuzzing. First, an extensible framework is designed to coordinate efficiently the two stages of general exploration and directed exploitation. Second, a general method of multi-target oriented redundant basic block termination (rbbt for short) is presented to enrich the diversity of directed fuzzing from existing fuzzers in a large batch.

Source code is publicized in this project.

Due the space limitation, big data files would be stored at Google drive instead with the same directory structures.

![](https://github.com/fceval/dcfuzzer-main/blob/a2b191ddbc4351cf803a934610efe929650abd98/directory.png)

aaadcfuzzer: compiling scripts.

docker: buld scripts for all Docker images of fuzzers and our proposals.

drivers: code for driver container.

framework: Coordinator components for central analysis.

misczxy: customized misc tools.

runners: experimental scripts

The appendix documents are listed here.

[GitHub - fceval/dcfuzzer-appendix: Online appendix for the paper of DCFUZZER](https://github.com/fceval/dcfuzzer-appendix)

The detail of new real bugs found by DCFUZZER is shown here.

[GitHub - fceval/dcfuzzer-realbugs: detailed information of new real bugs found by dcfuzzer](https://github.com/fceval/dcfuzzer-realbugs)

We have made much effort to test almost all of the benchmark programs from FuzzBench, Magma, Binutils, Unibench and AFLGO. It is still an open issue to make effective and fair benchmark datasets for diverse fuzzing scenarios.
![](https://github.com/fceval/dcfuzzer-main/blob/d2efc4271117b20491e47f71c7e6002f7da53afc/programstested.png)
