# Program Analysis

Program analysis aims for securing or improving the performance of a program; or understanding its meaning. It can be done on both source code and binary code (static analysis) or during runtime (dynamic analysis).

With respect to security, program analysis is to be done manually (auditing) or through static analysis tools to discover potential flaws in programs.

## Concepts

CVE, CWE

static vs. dynamic analysis

formal verification / validation

auding: bottom-up, top-down

tools for automated analysis

[Awesome Static Analysis Tools for Java](https://github.com/mre/awesome-static-analysis#java)

[Awesome Java Security Resources](https://github.com/guardrailsio/awesome-java-security)

## Tasks

### CWE

Go to the [Common Weakness Enumeration website](https://cwe.mitre.org). Search for Java. Identify 3 weaknesses that you've encountered during this training. Identify 2 more that you've not encountered. Develop a program in Java with that weakeness.

### Code Auditing

Look for bugs / defects in as many Java files as you can in the [securibench-micro database](https://github.com/too4words/securibench-micro/tree/master/src/securibench/micro).

### Spot Bugs

Install [SpotBugs](https://spotbugs.github.io/#extensions). See the [documentation](https://spotbugs.readthedocs.io/en/stable/introduction.html). Find flaws in the above programs. Try to install the [find-sec-bugs plugin](http://h3xstream.github.io/find-sec-bugs/).

Aim at discovering bugs from the [find-sec-bugs-demos database](https://github.com/find-sec-bugs/find-sec-bugs-demos).

### Juliet Test Suite for Java

Download the [Juliet Test Suite for Java](https://samate.nist.gov/SRD/testsuite.php). It's a 74 MB file. Unzip it, take a look at the first-level folders, these are classes of bugs. Select 5 classes that you want. For each class, select a Java source code file in the folder, see the bug / weakness, audit it and understand why the bug / weakness manifests. Then see if SpotBugs discovers it.
