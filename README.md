1) I would put the automated tests within a Github action that runs whenever code is pushed, as it is the best for code development. It's easiest to review pull requests that have the tests automatically run on them, rather than manually running tests locally, and running them after development is finished. 
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no) 
   no, I would not use an end to end test to check if a function is returning the correct output.



"test": "jest --maxWorkers=1"


