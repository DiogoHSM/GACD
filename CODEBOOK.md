CODEBOOK
========

Information about the process, variables and code on the Getting and Cleanning Data Course Project (Coursera.org)
For more information: [README](https://github.com/DiogoHSM/GACD/blob/master/README.md)

# Process
* 1. Set a default workind directory.
* 2. Read the data in accordance with the project description (UCI HAR Dataset directory).
* 3. Adjust feature names to use in R.
* 4. Merge datasets of test and trainning
* 5. Prepare the dataset the way we will use in the project. Only the columns of the result will be available.
* 6. Write the result in tidy.txt

# Variables (by step)

* 2.  `trainnig, testing` - variables that receive all the raw data used in the project
* 3.  `features` - "Support" data used to give names to the features columns used in the project.
* 4.  `allData` - Used to merge all the data of the step 2.
      `colsWeWant` - Used to separete just the columns used in the project.
* 5.  `tidy` - Used for the result data of the project.
