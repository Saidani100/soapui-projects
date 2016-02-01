# Sample1

Sample SoapUI Project with artifacts.

**Problem Description:**

_Many times, the same question from different new users of `SoapUI` is noticed asking as below:_

"There is a test case with multiple steps and each step represents different operation either from the same service or from different service. The common problem is that how to retrieve certain value from first step's response and pass that value to input to other test step of same test case". 

**How to use this soapUI project:**

Import this _soapui project_ into your SoapUI software. This will domonstrate the solution addressing the above mentioned problem by using mock service. 

_You would see the following in the project:_
- checkNumberSOAP [this is a service interface]
- TestSuite1 [this is a test suite using the existing service operations]
- checkNumberSOAP MockService [this is a mock service which enables users to test]

1. Start `checkNumberSOAP MockService` using right click.
2. Open the `TestSuite 1`, then `CheckIfNumberIsEvenOrOdd` test case.
3. Just, run the project and you should find it execute successfully.

In to the details:
TODO
