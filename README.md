# SOAPUITest
1. Create a suite as instructed in SOAUP UI learning sessions and add these grrovy scripts as a test case
2. Library Suite Should be first suite to be run in your project, that means above all test suites
3. Disable the Generate HTML code grrovy test step. Enable Delete Report Test setp.
4. Set a Variable @ testsuite level to store the testsuite name.
          - add below grrovy in setup script of every suite
          testSuite.project.setPropertyValue("suite_name",testSuite.name)
5. Call Generate HTML code grrovy test step in every test case.           
