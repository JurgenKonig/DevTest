# DevTest

## Start Time of File: 3:41 PM
## Stop Time of File: 5:49 PM
## Thoughts:
  - For some reason, despite having code to remove "Grade" from the csv file read, it still came up in the actual code.
  - Overall_Class.txt does not return the highest grade nor the average for all students despite each individual Class
    .txt file successfully calculating the grades (this is why I made sure to have those output
    as well, since abnormalities can come up).
  - Redundancy of variable declaration certainly not needed but wanted to ensure I could reference those values in
    overall_calc function. Definitely a better way to do it (and that works, since I presume that is the root of my pro-
    blem with the program outputting 0 in that specific .txt file.
  - Attempted to do individual class files but unsure if I could implement it in the 1-3 hour window, which I wanted to
    adhere to.
  - If I had more time, I would certainly add/do:
      + Exception handling
      + Checking for illegal values (grade of A instead of a number)
      + Streamlining of code to be more efficient and less redundant
      + Way to detect weird characters (see issue referenced in read_csv_C()
      + More in-depth comments, for sure
      + Not have all of the code in one massive file, segment it into different files and import those into other files
        as needed
      + Figure out how to "output in a prominent way" (more expression? more characters?)
