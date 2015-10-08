###How to Choose A Cran Mirror When the GUI Doesn't Work###

Say you want to install a new package in R, but you get this error:
        
        > library(vcd)
        Error in library(vcd) : there is no package called 'vcd'
        
        > install.packages("vcd")
        --- Please select a CRAN mirror for use in this session ---
        
        Error: Line starting '<!DOCTYPE HTML PUBLI ...' is malformed!

Also, the GUI for selecting a mirror on XQuartz 11 didn't work for me either.

1. Restart R

2. Type in your console:
    chooseCRANmirror(81)

3. You'll get a list of mirrors. I wanted an HTTP mirror so I entered 21 in my console.


4. Now enter which HTTP mirror you prefer. I entered 83 for USA-California. 

5. Voila! Now download that package! 
