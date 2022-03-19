# junit5-mockito-examples
A test project for https://stackoverflow.com/questions/71531001/why-is-surefire-not-executing-my-junit5-tests


```
[INFO] --- maven-surefire-plugin:3.0.0-M5:test (default-test) @ why-is-surefire-not-executing-my-junit5-tests ---
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running pkg.BDSHelperTest
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.396 s - in pkg.BDSHelperTest
[INFO] 
[INFO] Results:
[INFO] 
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.417 s
[INFO] Finished at: 2022-03-19T21:15:10+01:00
[INFO] ------------------------------------------------------------------------
```

The XML test report:

```
<testcase name="test" classname="pkg.BDSHelperTest" time="0.454"/>
```