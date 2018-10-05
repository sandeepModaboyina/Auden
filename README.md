#  Write a simple tests for below WSDL using Groovy test step 
WSDL Address:
http://currencyconverter.kowabunga.net/converter.asmx?WSDL

Current Test Struture with name
"Testing" is a Test suite 
  At testSuite level I defined some values for the test. i.e USD,GBP ,CurrentDate and Rate. 

-TestCase 1- "GetConversionRate_testcase" is a test case in which I Ised tool specific assertions to validate if its a SOAP Response ,has correct Https status Codes and Validate response contains the value

-TestCase2 - "GetConversionAmount_testcase" is another test cases in which I used tool specific assertions to validate if its a SOAP Response ,has correct Https status Codes and Validate response contains the value

-TestCase3 - "Property transfer" function of the tool to get a value from Request1 request and use it in Request 2 as a Request. 

-TestCase4 - Scripts - It contains the scripts for validating the response has a desired value for both Requests[Request1 and Resquest2]
