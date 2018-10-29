Feedback:

- Ran the program in the server and is working well. The first 4 user stories are implemented and you cannot sign up if the username or email is already taken which is good
- 8 tests, all passing and 100% coverage
- 20 offences in rubocop
- A comment has been left in the user model
- Nice use of private methods
- Good use of web helpers
- Could have some tests in the peep spec, however you do have 100% coverage, might be something to clear up with a coach how coverage works?
- Good that most of the logic is done in the model
- Could have extracted the database connection to its own model. It is good though that you extracted the database connection into a private method
- Could include a rakefile, maybe ask a coach
- Good spec helper
- Clean database before each test which is good
- Could have included expect current path to be '/' in feature tests. I got this from the code review rubric I did not know this was necessary
- Could introduce flash sinatra to run error message
- Try to in-cooperate restful routes
- Good form set up with placeholders
- To reduce the amount of divs could name them something else e.g. <peep>
- Great diagram included
- Good database set up instructions