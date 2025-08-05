PReDict toobox 
Contant: Itay Katzir, itaykatzir@gmail.com
---------------------------------------------------------------------------
Provides predicted response to multi-drug cocktails using the effective dose model.
See more details about the model in :
"Prediction of multidimensional drug dose responses based on measurements
of drug pairs" published in PNAS (2016)
---------------------------------------------------------------------------
Input : File with the doses of the cocktail and the measured response.
The input file should be in csv, text (tab delimited) or xls format
The data structure is:
Drug1 ,Drug2,Drug3, ... Response
0,   ,0    ,0     , ... 1
1,   ,0    ,0     , ... 0.5
0.5, ,3    ,5     , ... 0.1 
... ...    ...      ... 
The code can give predictions for any number of drugs.
---------------------------------------------------------------------------
Output : 
1. Output File (ExpName-predictions) in the same format. The predicted response is in the last column.
2. Figures (in fig,pdf,png,emf format) compares the predicted and measured response. 
   The figures are located in the folder "ExpName" that the code creates
---------------------------------------------------------------------------    
Two examples are provided:
Three drugs example - Cm-Ofl-Sal
Four drugs example - Linc-Cm-Ofl-Tmp

Run main.m

    
 

