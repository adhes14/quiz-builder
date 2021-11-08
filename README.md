# Description
Quiz Builder is a console application that allows you to create and fill quizzes.
 
## Current features
 * Create quiz
   * Supports the next kind of questions:
     * Text
     * Date
     * Pick one option (similar to a radio input element in HTML)
   * Each question type has its own associated validations, for example:
     * The question type *TEXT* supports the validations *REQUIRED* and *MIN_LENGTH*
   * Given a created quiz, it is possible to fill the values for its questions   

## Pending features to implement
### Question types
Add support for a new question type called *NUMERIC*, and associate the next validations *REQUIRED* and *MIN* to it. 
Remember that you need to convert the values to int
### Validations
We want to support other kind of validations for question's answer, some of them are:
   * Text validations
     * Max length
     * Only uppercase text
     
Once the new question type *NUMERIC* is implemented, we want to add the validation for a *MAX* values.

### Enhance the _Show Quiz_ menu action
We want to enhance this action because currently the question information is not usefully, please enhance that logic to show the question title and answer.  

### Persistence
Currently all the information is stored on memory, that means quizzes are lost after finishing the application. 
Sometime ago, a member of the dev team did a research about persisting information in a JSON file, you can check and run the JsonPersistence.java file which was the result of the research.
   * Given the JsonPersistence.java file, try to reuse that code to implement the quiz persistence in a JSON file and also load a quiz given a JSON file.
   Don't forget to include the respective action menu for this.

### Menu
We don't like how the action menu (Menu.java) is implemented, it has too much IFs; there should be a better way to implement it, try to provide a better alternative that helps in the maintainability .

### Unit testing
There are some unit tests that will help you during the refactoring, it will be great if you can include more scenarios. Additionally, there are some features that are failing, please fix them and add the related tests.


# Submit your task
You have 3 hours for this assignment, the way to submit your work is:
 * If you have a github account, you can clone this project and refactor the application in your clone. You must push your changes before the time limit.
 After that, send an email to felipe.canaviri@fundacion-jala.org with the url of your repository.
 * If you are not familiar with git repositories, you can download the project from the next url:
 https://github.com/jala-dev/quiz-builder/archive/refs/heads/master.zip
 To submit your changes, you can zip your project folder and send it to felipe.canaviri@fundacion-jala.org before the time limit.  
 **NOTE:** Please make sure only include project files. 
 
# NOTE
To run the application you must have installed OpenJDK-8 (or higher) and Maven

Make sure that you are running the App.java file.
