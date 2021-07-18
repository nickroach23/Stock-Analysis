# Stock-Analysis
### Overview: VBA Stock Analysis 
- Created for loops and conditional
- Created nested for loops
- Created a VBA macro, showing changes in cells and change in flows for each year.
- Applied codes, solved debugging issues and syntax recollection 
## Purpose 
 The purpose of this project is to edit from the current data that was given to properly refactor it with the VBA Solution code. By doing so it gives the VBA access to loop throughout all the data at once, collecting the the entire dataset. After so, we will determine whether the code was successful at a faster speed. We want to make sure the code runs more efficient this time by taking fewer steps, using less memory or improving the logic of the code to make it easier for users to read and comprehend. 

## Results 
1.) -I created a ticker index set equal to zero before looping over all the rows.   
      '1a) Create a ticker Index
       tickerIndex = 0.
       
      Created three arrays: tickerVolumes, tickerStartingPrice and tickerEndingPrice. The #tickerVolumes array is set to a #Long data type. The #tickerStartingPrices and #tickerEndingPricesarray is set to #single data type. Beside each array I included the number of elements (12). 

