//Pokémon API Test Collection

//Description

This collection contains API requests for the Pokémon API, designed to get information on specific Pokémon. The main goal is to verify whether their `base_experience` value above 150.

// Setup Instructions

1. Download Postman on your system.
2. Open Postman and import the provided collection JSON file(Pokémon API Test.postman_collection.json).
3. Import the CSV file(Pokemon_List.csv), which has the names of the Pokémon to test, into Postman as a data file for running the collection.


// Environment Setup

1. Import the "Pokemon API Testing.postman_environment.json" file into Postman.
2. Select "Pokemon API Testing" from the environment dropdown in the top right corner.
3. Ensure your variables match the ones required for the requests in the collection.

//Running the Tests

1. go to the Collection Runner within Postman.
2.drag and drop the collection you want to run to the run order window.
3.select and attach the CSV file as the data source for the test runs.
4.Hit the "Run" button to execute the tests across the collection with the data provided in the CSV.

//Assumptions

1. The API endpoints are case-sensitive; therefore, Pokémon names are used in lowercase in the CSV file.
2. A successful response from the API is indicated by a 200 status code along with a valid JSON response body.

//Test Results Summary

1.The API successfully responded with a 200 status code for the details of all 10 Pokémon.
2.Of these, only 3 Pokémon possessed a `base_experience` above the set threshold of 150, indicating that not all Pokémon in the test set meet this particular requirement.

//Contributions

You are welcome to use this repository to add collections or modify the tests as per further requirements. Feedback and contributions to improve the existing tests are highly appreciated.


