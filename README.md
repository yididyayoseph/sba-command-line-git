# sba-command-line-git

# This assessment contains 2 parts. Each part is explained below. You will have 60 minutes to complete the entire assessment (Parts 1 and 2)

## Part One: Git Basics

### Please follow the directions the below. You will be assessed on the completion of each task.

1. Fork a copy of this repository to _your_ GitHub account. 
2. Clone the _forked_ copy to your computer.
3. Add an `index.html` file to the root directory of the repository.
4. Open the repository in VS Code.
5. Add the following code to your `index.html` file

````
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>
  </body>
</html>

````
6. Add the changes to the staging area.
7. Save the the changes to your local repository. Include as your message the full command you used to create the index.html file in task 3.
8. Send the changes to your remote repository.
9. Create a pull request

## Part Two: Command Line

### Please follow the directions the below. You will be assessed on the completion of each task.

### Setup: 
1.  You will need to create a replit.com account to complete this portion. This video provides directions: https://www.youtube.com/watch?v=ZAC0TQEU5gI
2. Start a new "Bash" repl
3. Click on "Shell" to run commands in a way similar to Git Bash or Terminal

### Use the appropriate commands complete the tasks listed below. 

1. Create a folder named `folder1`
2. Navigate to `folder1`
3. Add a file named `file1.txt` to `folder1`
4. Use text commands to add the following text to `file1.txt`: `grapes\napples\noranges\nlimes\nlemons\napples\ngrapes\npears\nberries\nlimes` There should be one item per line in the file. Hint: You will need to use -e along with your command to ensure each item is on separate line (ex. `command -e "text here"`)
5. Alphabetize the contents of `file1.txt` and add the alphabetized content to a new file named `sorted-folder1.txt`
6. Create a folder named `folder2` that is a sibling of `folder1`
7. Navigate to `folder 2`
8. Add a file named `file2.txt` in `folder2`
9. Use text commands to add the following text to `folder2.txt`: `grapes\ngrapes\napples\noranges\nlimes\nlimes\nlemons\nlemons\ngrapes\npears\npears\nberries` Hint: you will need to use -e along with your command to ensure each item is on separate line (ex. `command -e "text here"`)
10. Filter out duplicate adjacent lines from from `folder2.txt` and add the filtered list to a new file named `unique-folder2`
11. Use the "Invite" button in the top right of the replit.com window to generate a sharable link (as showin in [video](https://www.youtube.com/watch?v=ZAC0TQEU5gI) linked here and above)
12. Take a screenshot of the Shell showing the commands you used to complete the assignment
13. Submit your link to the Canvas submission page for this session
14. Submit your screenshot to the Canvas submission page for this session

