Contributors: Diana Kostina; Ray Wang

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed 
Manually run them locally before pushing code
Run them all after all development is completed

Answer: We fit automated tests within a Github action that runs whenever code is 
pushed. This ensures that any problematic code is caught before it merges into the main branch, keeping the repository clean and preventing bugs from affecting other team members.


2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No. Testing if a specific function returns the correct output is the job of a unit test. End to end tests are used to verify the entire system flow from the user's perspective.







