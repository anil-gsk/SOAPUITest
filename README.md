# SOAPUITest
Create a suite as instructed in SOAUP UI learning sessions and add these grrovy scripts as a test case
Library Suite Should be first suite to be run in your project, that means above all test suites
Disable the Generate HTML code grrovy test step. Enable Delete Report Test setp.
Set a Variable @ testsuite level to store the testsuite name.
          - add below grrovy in setup script of every suite
          testSuite.project.setPropertyValue("suite_name",testSuite.name)
Call Generate HTML code grrovy test step in every test case.           
