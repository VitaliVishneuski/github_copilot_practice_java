# Task: Set Up Java Project and Implement & Test Methods using GitHub Copilot

## Objective

The goal of this task is to familiarize you with the features of GitHub Copilot by setting up a Java project, implementing a set of methods in a Java class skeleton, and validating them through unit tests using JUnit.

## Additional Notes:
- Use GitHub Copilot for assistance at each step.
- Review and understand the generated code.
- Run your tests frequently to validate each implementation step.
- Ensure that all tests pass before completion.

### Note for Participants
This task is helpful for participants with any programming language background since you are not expected to write any code but just utilize GitHub Copilot to go through its features. This exercise is designed to help you explore and get comfortable with what GitHub Copilot can do, regardless of your prior coding experience.

## Instructions

### Step 1: Clone the Repository
1. Clone the repository:
   **Terminal Command**:
    ```bash
    git clone https://github.com/VitaliVishneuski/github_copilot_practice_java.git
    cd github_copilot_practice_java
    ```

### Step 2: Initialize the Java Project
1. **Initialize a Java project**:
    - Ask GitHub Copilot how to initialize a new Java project.

### Step 3: Install Necessary Packages
1. **Install JUnit for testing**:
    - Use GitHub Copilot to understand what packages must be installed and install them.

### Step 4: Create .gitignore File
1. **Create a `.gitignore` file**:
    - Use GitHub Copilot to create a `.gitignore` file with the necessary Java ignoring options.

### Step 5: Implement Methods in the AdvancedOperations Class
1. Open `src/AdvancedOperations.java` and implement the methods using GitHub Copilot assistance (both CodeWhisperer and Copilot assistant features).

### Step 6: Add Documentation and Comments
1. **Add Javadoc comments**:
    - Use GitHub Copilot to add Javadoc comments for the following methods:
        - `findMax`
        - `reverseString`
        - `formatDate`

2. **Add inline comments**:
    - Use GitHub Copilot to add inline comments for the following methods:
        - `factorial`
        - `fibonacci`
        - `isPalindrome`

### Step 7: Implement Unit Tests
1. Open `test/test.java` and ensure that the unit tests for the following methods are implemented using GitHub Copilot:
    - `fibonacci`
    - `isPalindrome`
    - `mergeAndSort`

### Step 8: Run Your Tests
1. Run your tests to validate the implementation:
    - Ask via GitHub Copilot chat how to run the tests and run them.

### Step 9: Refactor a Method
1. **Review a new method with bad practices**:
    - Review the `calculateStatistics` method in `src/AdvancedOperations.java` that calculates statistics for a set of numbers but utilizes bad practices and violates DRY, KISS, SOLID, and other principles.

2. **Refactor the method**:
    - Use GitHub Copilot's refactor feature to refactor the `calculateStatistics` method to follow DRY, KISS, SOLID, and other principles.

### Step 10: Run Your Tests Again
1. Run your tests to validate the implementation and ensure the `calculateStatistics` method works as expected after refactoring.

### Step 11: Commit Your Changes
1. Create a commit message with the help of GitHub Copilot:
    - Use GitHub Copilot to generate an appropriate commit message for your changes.

    **Terminal Commands**:
    ```bash
    git add .
    git commit -m "[Commit message generated by GitHub Copilot]"
    ```

### Step 12: Generate Merge Request Summary
1. Generate a merge request summary using `git diff` and GitHub Copilot chat:
    - Use `git diff` to see the changes you made.
    - Use GitHub Copilot chat to help generate a summary of these changes.

    **Terminal Command**:
    ```bash
    git diff
    ```

2. Use the generated summary when creating a merge request on the platform.

### Step 13: Create a Merge Request
1. Create a merge request on the platform using the summary generated in the previous step.