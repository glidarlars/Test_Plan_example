# 4.6 Item Pass/Fail Criteria

A test case always has a reported status. Until its execution is finished, it is reported with the status **PENDING**. After execution, it receives either a **PASS** or **FAIL** status.

A test case execution is considered **finished** when all results are reported into the appropriate system (such as Pythia) and any issues found have been highlighted to the correct stakeholders.

## 4.6.1 PASS

A test case is considered **PASS** when all conditions below are met:

* The related (or part of the) requirement is fully met.
* The test instruction could be followed, and the expected results noted therein were achieved.

> [!NOTE]
> A test case can pass even if minor bugs/issues are found during execution. However, any issue found during a test execution must be reported to the appropriate stakeholder. If the test executor is unsure if the issue is within the tested function, the test case must be reported as **FAIL** for review.

## 4.6.2 FAIL

A test case is considered **FAIL** under all conditions where it is not considered PASS or PENDING.

Any anomalies/bugs reported must always contain the following:

* The condition under which the error occurred.
* A detailed description of how to reproduce the issue (if possible).
* Any relevant log files from the **UUT** (Unit Under Test) and/or the test execution environment to assist in debugging.

---
[« Back to Table of Contents](../README.md)
