# Bruhat-intervals
The program we used consists of the first part, where we find some basic objects of the Weyl group W in question, and repeating
"building blocks" that calculate data about length n subintervals in the Bruhat graph in question based on the same data for n-1 length intervals. 
These building blocks are almost idetical, so we only present the first part (program for finding non-isomorphic intervals of length 3, file "prep+length_3"),
which also includes the first "building block", and a separate building block for calculating subintervals of length 4 and data for them (file "length_4")

These programs, apart from the first part, are not self-contained and are supposed to be run consecquentially.
To make more "building blocks" one should simply change the length of subinterval in "length_4". However, it proves beneficial to switch to straightforward isomorphism check 
for intervals with greater number of n-1-length subintervals.
By defolt the program is for group A5, which you can change in the first line of "prep+length_3".
