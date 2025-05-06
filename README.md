# COMP-1012-Lab-4

Download Here: [   COMP 1012: Lab 4  ](   https://codingherolab.com/product/comp-1012-lab-4/    )

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Exercise 1: Standard deviation
Open the file lab4.csv. This file has 3 numbers per-line, separated by commas.

Calculate the mean and standard deviation of each column of the file, using the formula:

σ=√∑Ni=1(xi−¯¯¯x)2N−1σ=∑i=1N(xi−x¯)2N−1

Where σσ is standard deviation, ¯¯¯xx¯ is the mean of the dataset, NN is the number of elements in the dataset, and xixi is an element of the dataset at spot ii.

You will need to:

open the file.
Initialize 3 list accumulators.
Iterate over the lines of the file in a for loop and accumulate the values in the columns.
Compute the average (either do this inside the loop with a running sum or use the sum function on your lists).
Once you have the mean ¯¯¯xx¯, calculate the standard deviation using a second for loop.

Your output should look like:

The mean of column 1 is 50.30, and the standard deviation is 28.81
The mean of column 2 is 499.79, and the standard deviation is 290.16
The mean of column 3 is 5011.12, and the standard deviation is 2874.15
Nested 🐤 lists
As an extra exercise, consider how to write this using nested lists. You may need to use the range function if you choose to solve this problem.

Exercise 2: Standard deviations from the mean
Add to your program from the previous part to ask for numerical input from the user. Find how many standard deviations from the mean the input is.

The formula for deviations from the mean is:

deviationsFromMean=|¯¯¯x−x|σdeviationsFromMean=|x¯−x|σ

Where σσ is the standard deviation, ¯¯¯xx¯ is the mean of the dataset, and xx is the data the user provided.

Give me a number : > 50
This number is 0000.0104 standard deviations from the mean for column 1.
This number is 0001.5501 standard deviations from the mean for column 2.
This number is 0001.7261 standard deviations from the mean for column 3.
Nested 🐤 lists
If you did the extra exercise for above, add to this part an option for the user to choose which column the standard deviation is calculated for.

Optional exercises
Basic if usage
Change your above code. Use an if statement to remove negative numbers, creating a standard deviation with only positive numbers (which we will define as greater than or equal to 0).

Evens only
Change your if statement to only accept even numbers and positive. The data are decimal numbers, so we will define ‘even’ as “The 1s place is even”.

Saving your work
Save the files to the H: (Home) drive on your lab computer if you can; otherwise use the desktop or a USB drive. The desktop on a lab computer is stored on the computer itself, not on your network drive, so you should copy your files to a more permanent location before you leave. A good approach is to carry a thumb drive and plug it into the lab computer, using it to store your programs. Remember to take it with you!

Or, students have access to cloud storage (OneDrive), accessible through your @myumanitoba account. Log in at http://365.myumanitoba.ca. Once logged in, click on the App Launcher at the top left hand side and select OneDrive. To save a file, simply drag it to the OneDrive screen.
