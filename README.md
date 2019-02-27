# Introduce
Spring-boot works with jacoco to do a small demo of the test coverage report
# Start
```powershell
mvn clean install
```
Then, look at ``target/site/jacoco/index.html``, you can get a test coverage report
# Scene
 - Jenkins cooperated with Gitlab in continuous integration and sent the test coverage report to the specified mailbox.
