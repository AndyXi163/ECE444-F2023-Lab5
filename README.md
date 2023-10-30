# ECE444-F2023-Lab5
This is the GitHub repository used for the completion of ECE444 Lab 5.

It is largely based on the tutorial at https://github.com/mjhea0/flaskr-tdd , excluding the parts involving Heroku.
Notice that removing flaskr.db and running python create_db.py should be performed every time after committing and pushing code.

My contributions to the team test cases is listed in the link https://github.com/ECE444-2023Fall/project-1-web-application-design-group4-3d3g/blob/main/tests/test_app.py#L104-L115

In case the link above does not work, my code is at lines 104-115 in /tests/test_app.py at the team repository https://github.com/ECE444-2023Fall/project-1-web-application-design-group4-3d3g .

## A brief discussion on test-driven development
  Test-driven development is a method of computer software development where developer-constructed test cases are utilized. Compared to traditional methods of develpoment, it has its own pros and cons:
 - Pros
     - Acts as a part of the testing procedure; same amount of dedicated time for testing can achieve better results
     - A wide and thorough set of test cases guarantees lower fail rate at deployment
     - In the creation of the test cases all developers can improve their understanding of the entire project.
 - Cons
     - There may be corner cases that human brains fail to acknowledge; test driven development is best working in a hybrid with more traditional development and testing methods
     - Poorly constructed test cases may be a waste of development time and resources
     - Although highly unlikely, overfitting may occur under very rare cases
