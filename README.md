# api-playgroung-task-solution
- API Testing implemented using Postman Tool.
## API Task Solution Details:
- You Will find to postman collections one of them is the imported one form the documentaion called <obj>API Playground</obj>
 and the other one is the i made for categories requests <ob>TestCategoryAPI</ob> 
-I have created a monitor for each of the two collections:
1) For the <obj>API Playground</obj>, i have created a monitor with the same name which runs every Monday on weekly bases.
2) For the <obj>TestCategoryAPI</obj>, i have created a monitor named <od>Categories Testsuite</od> which also runs every Monday on a daily bases.
### For the TestCategoryAPI Collection
- It contains three GET requests, one POST request, One PATCH request and one DELETE request which cover all the functionalities of <od>Categories</od> endpoint.
- For each request in the Tests tab you will find a test written in javascript that asserts the returned status code number is the right code according to the documentation.
- Some of the requests contain tests with the status code assertion test.
- You can run the Testsuite form the Monitor to check all of the request and testcases at once by going to the monitor tab
 and select <od>Categories Testsuite</od> then click the run button.
### For the API Playground Collection:
- I have added status assertion tests inside the categories requets that checks the status code returned from the request according to the request type.
### Notes 
- Some of the requests on API playground returns status code:500 which is a server side error due to a parameter <obj>map</od> the does not exist, please not that this is not an error with the request.
<aside> There are some uncovered testcases due to that the task was sent during working days so i did as much as possible</aside>
### Testcases
- Assert the returned status code incase of right valid request or bad request according to the api documantation.
- Assert Header values returned.
- If the api requires authentication then test sending the right values and the wrong values in the request and validate the response.
- Validate the responce body syntax using some regex.
- Validate the response type.
- Basic positive tests (happy paths).
- Extended positive testing with optional parameters. 
- Negative testing with valid input.
- Negative testing with invalid input. 


 

