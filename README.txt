Prerequisites:
- download files "PetCircle Task.postman_collection" and "PetCircle.postman_environment" JSON files.
- Postman installed.
- Access to the Postman app to import collections and environments.

Importing the collection and the environment:
1. Open postman.
2. Click the "Import" button found on the left side of the screen beside "New" button.
3. Locate the downloaded files "PetCircle Task.postman_collection" and "PetCircle.postman_environment" JSON files.
4. Drag and drop them on the import window.
5. Click Import button to import the files.
6. Verify that the "PetCircle" environment is now added to the list of environment.
7. Verify that the "PetCircle Task" collection is now added to the list of collections and contains folders "PositiveTests" and "NegativeTests"


Running the test:
Note: Tests are organized into separate folders for positive and negative tests, I recommend executing them separately for better organization.

PositiveTest:
1. Select the "PetCircle" environment from the Environment dropdown in the top-right corner of Postman.
2. Hover on the "PositiveTests" collection folder and click the ellipsis two view more actions.
3. Click "Run folder".
4. Runner tab will open in Postman.
5. All tests are slected by default to run all tests.
6. Test is to be run manually.
7. Set the Iterations value based on your requirement
8. Add at least 1500ms delay between each test.
9. Click button "Run PetCircle Task"

PositiveTest Expectations:
All tests should return "PASS" result.


NegativeTest:
1. Select the "PetCircle" environment from the Environment dropdown in the top-right corner of Postman.
2. Hover on the "NegativeTests" collection folder and click the ellipsis two view more actions.
3. Click "Run folder".
4. Runner tab will open in Postman.
5. All tests are slected by default to run all tests.
6. Test is to be run manually.
7. Set the Iterations value based on your requirement
8. Add at least 1500ms delay between each test.
9. Click button "Run PetCircle Task"

NegativeTest Expectations:
10 out of 19 Tests should return "PASS" and the remaining 9 are expected to return "FAIL".