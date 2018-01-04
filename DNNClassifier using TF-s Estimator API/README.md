# Classification using TensorFlow #
We have some California Census Data, we'll be trying to use various features of an individual to predict what class of income they belong in (>50k or <=50k).

## Data: ##  

age:	The age of the individual  
work class:	The type of employer the individual has (government, military, private, etc.).  
fnlwgt:	The number of people the census takers believe that observation represents (sample weight). This variable will not be used.  
education:	The highest level of education achieved for that individual.  
education_num:	The highest level of education in numerical form.  
marital_status:	Marital status of the individual.  
occupation:		The occupation of the individual.  
relationship:	Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  
race:		White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  
gender:		Female, Male.  
capital_gain:		Capital gains recorded.  
capital_loss:		Capital Losses recorded.  
hours_per_week:	Hours worked per week.  
native_country:	Country of origin of the individual.  
income:	">50K" or "<=50K", meaning whether the person makes more than $50,000 annually.  

## Conclusion ##
We observe an accuracy of 85% which looks to be good enough. We can perform feature scaling to see further improvements in the performance.
