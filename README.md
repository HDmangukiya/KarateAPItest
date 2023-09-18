# KarateAPItest
"KarateAPItest" is a test automation framework that simplifies API testing using a readable and expressive DSL. It provides a powerful and easy-to-use toolset for writing and executing API tests, making it a valuable asset for testing and validating APIs.

# Running Tests
- Clone the repository from your fork to this directory
- Open the project using any text editor or Java IDE
- Run the tests with the script below

> $ mvn clean test

# Test Report
- Test report automatically generated on target folder after finished the test execution
- See test report from target/karate-reports/karate-summary.html for the Karate default report
- Also, See the test result that used cucumber report from target/cucumber-html-reports/overview-features.html on your browser

# Performance Tests
- Run the user simulation with the script below
> $ mvn clean test-compile gatling:test
- See test report in the target/gatling/usersimulation/, then open index.html file

![Screenshot](https://github.com/HDmangukiya/KarateAPItest/raw/main/KarateAPItest_target_gatling_req_post.html.png)

![Screenshot](https://github.com/HDmangukiya/KarateAPItest/raw/main/KarateAPItest_target_gatling_usersimulation.html.png)
