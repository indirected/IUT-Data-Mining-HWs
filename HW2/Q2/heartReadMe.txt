This database contains 13 attributes (which have been extracted from
a larger set of 75)       
  


Attribute Information:
------------------------
      -- 1. age       
      -- 2. sex       
      -- 3. chest pain type  (4 values)       
      -- 4. resting blood pressure  
      -- 5. serum cholestoral in mg/dl      
      -- 6. fasting blood sugar > 120 mg/dl       
      -- 7. resting electrocardiographic results  (values 0,1,2) 
      -- 8. maximum heart rate achieved  
      -- 9. exercise induced angina    
      -- 10. oldpeak = ST depression induced by exercise relative to rest   
      -- 11. the slope of the peak exercise ST segment     
      -- 12. number of major vessels (0-3) colored by flourosopy        
      -- 13.  thal: normal; fixed defect; reversable defect     


Variable to be predicted
------------------------
Absence (0) or presence (1) of heart disease

Cost Matrix

	 abse  pres
absence	  0	1
presence  5	0

where the rows represent the true values and the columns the predicted.

No missing values.

270 observations

