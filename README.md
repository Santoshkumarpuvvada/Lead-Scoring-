# Business Problem:
# Business Problem:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. 

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Goals of the Case Study:
There are quite a few goals for this case study.
1)Assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
2) Understand the factors that lead to lead conversion

# Methodology:
After doing Data Cleaning & EDA, Logistic Regression was used to predict 'Hot' leads. It is a supervised classification problem. Logistic Regression was chosen as the out come of the model will also be probability & hence assigning scores for each lead can be done & lead persual can happen as per scores. This can help in better conversion ratio & also all factors impacting lead conversion can be understood clearly.

# Results & Recommendations:
a) An optimal cutoff of .42 was chosen by plotting the sensitivity, specificity & accuracy curves. All important metrics were close to 80% in test data set, hence model is an acceptable one.
b) The Top three Variables in my model which contributed the most toward the probability of a lead getting converted are
* TotalVisits
* Page Views Per Visit
* Total Time Spent on Website
Based on above factors, sales team can target leads & generate better conversions 
