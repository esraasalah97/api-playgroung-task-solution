# api-playgroung-task-solution

- The API Testing implemented using Postman Tool, the solution is the collection TestCategoryAPI.
- You will find two folders one of them contains the solution which is named <obj>TestCategoryAPI</obj>, and you will find also results file of a run inside it. 
The other folder contains the imported <obj>API Playground</obj> postman collection which is named <od>API Playground Collection Enhanced</od> but with some enhancements in the requests related to the category end point. 

## To Run the Collection TestCategoryAPI 

- click on the three dots right next to the collection name then choose the option Run Collection.

## API Task Solution Details:
- You Will find two postman collections one of them is the imported one from the documentaion called <obj>API Playground</obj>
 and the other one is the one i made for categories requests  named <obj>TestCategoryAPI</obj></br>
 
### Collections Monitors:

- For the <obj>API Playground</obj>, i have created a monitor with the same name which runs every Monday on weekly bases.
- For the <obj>TestCategoryAPI</obj>, i have created a monitor named <od>Categories Testsuite</od> which also runs every Monday on a daily bases.</br>

### For the TestCategoryAPI Collection

- It contains four GET requests, one POST request, One PATCH request and one DELETE request which cover all the functionalities of <od>Categories</od> endpoint.
- For each request in the Tests tab you will find tests written in javascript which do the following:
1) asserts the returned status code number is the right code according to the documentation.
2) asserts the Headers' content-type.
3) asserts the response time.
4) some of them will contain assertions on attributes or attributes values that the response body must contain them.</br>
- You can run the Testsuite form the Monitor to check all of the request and testcases at once by going to the monitor tab
 and select <od>Categories Testsuite</od> then click the run button.</br>
 
### For the API Playground Collection:

- I have added status assertion tests inside the categories requets that checks the status code returned from the request according to the request type.</br>

### Notes 

- Some of the requests on API playground returns status code:500 which is a server side error due to a parameter <obj>map</od> the does not exist, please not that this is not an error with the request.
- There are some uncovered testcases due to that the task was sent during working days so i did as much as possible.</br>

### Testcases

- Assert the returned status code incase of right valid request or bad request according to the api documantation.
- Assert Header values returned.
- If the api requires authentication then test sending the right values and the wrong values in the request and validate the response.
- Validate the responce body syntax using some regex.
- Validate the response type.
- Check if specfic parameters exist in the responce body.
- Basic positive tests (happy paths).
- Extended positive testing with optional parameters. 
- Negative testing with valid input.
- Negative testing with invalid input. 


 

