# Supahands Coding Assessment
* This is a coding asssessment for prospective supahands engineers
* Please create a new file for the solution, **DO NOT** modify the seed.py file
* The seed file **MUST NOT** be modified, it is expected to generate a list of random timestamps to be used in the test

## Submission Instructions
* Create a project on https://replit.com/
* Copy the seed file contents there, and utilize the seed file in replit.com
* You can solve the problem using either python, javascript, or ruby
* Use the **LATEST PRODUCTION** versions of the language
* Notify [careers@supahands.com](mailto:careers@supahands.com) upon completion and include the join link for your replit.com project
* Solutions that do not follow the submission instructions WILL NOT be considered

## Hints
* We **WILL NOT** be processing submissions that do not match the output format as stipulated in Outputs
* You are **ENCOURAGED** to re-attempt the assessment in the event that you do not do well enough in the first attempt


## Problem Statement
* Given a list of time stamps that is generated by the provided seed.py, where the timestamps represent login time
* Length is defined as the number of days of consecutive logins, NOT the number of consecutive logins
* Output a table with time stamps sorted by consecutive logins, sorted by descending length
* For example, if given the following timestamps 
  * ['2021-03-13 15:13:05', '2021-03-13 23:13:05', '2021-03-16 15:13:05', '2021-03-16 23:13:05', '2021-03-17 07:13:05', '2021-03-17 15:13:05', '2021-03-17 23:13:05', '2021-03-18 07:13:05', '2021-03-18 15:13:05']
* Since the longest period of consecutive logins occur from 2021-03-16 to 2021-03-18, the answer would be

| START      | END        | LENGTH |
|------------|------------|--------|
| 2021-03-16 | 2021-03-18 |      3 |
| 2021-03-13 | 2021-03-13 |      1 |


* The problem stems from needing to award badges for consecutive logins

## Expected Solution
* Call the seed file from the your script in order to generate a data pipeline for the processing code
* You are welcome to convert the seed python script to ruby/javascript to be used on replit.com
* Create a separate unit test for your script file to test the various scenarios presented in your script
* DO NOT edit or amend the seed.py file
* Include a separate readme in the form of a README.txt if additional instructions are required to get your solution running
* Your solution should follow best practices such as DRY, KISS, YAGNI, SOLID etc.
* **IMPORTANT** Your solution should consists of a solution file, and a unit test file
* Solutions that do not follow the submission instructions WILL NOT be considered

## Assessment Criteria
* Submitted code will be assessed based on the following criteria
  * Cyclomatic complexity
  * Maintainability index
  * Best practices
  * Elegance of solution
  * Defensibility of code
  * Optimization


## Outputs
Our test script expects a stdout of the following format
| START      | END        | LENGTH |
|------------|------------|--------|
| 2021-03-03 | 2021-03-10 |      8 |
| 2021-02-15 | 2021-03-18 |      4 |
| 2021-02-10 | 2021-03-12 |      3 |
| 2021-01-03 | 2021-01-03 |      1 |