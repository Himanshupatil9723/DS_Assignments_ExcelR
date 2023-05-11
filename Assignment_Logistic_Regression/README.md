# Predicting Customer Response to Telemarketing Campaigns for Term Deposit
### 1. Project Background
Nowadays, marketing spending in the banking industry is massive, meaning that it is essential for banks to optimize marketing strategies and improve effectiveness. Understanding customers’ need leads to more effective marketing plans, smarter product designs and greater customer satisfaction.

<b>Main Objective: increase the effectiveness of the bank's telemarketing campaign
This project will enable the bank to develop a more granular understanding of its customer base, predict customers' response to its telemarketing campaign and establish a target customer profile for future marketing plans.

By analyzing customer features, such as demographics and transaction history, the bank will be able to predict customer saving behaviours and identify which type of customers is more likely to make term deposits. The bank can then focus its marketing efforts on those customers. This will not only allow the bank to secure deposits more effectively but also increase customer satisfaction by reducing undesirable advertisements for certain customers.
  
  #### 1.1 About the Dataset <a class="anchor" id="1.1"></a>
##### Attribute Information:

+ age (numeric) 
+ job : type of job (categorical:admin.','bluecollar','entrepreneur','housemaid','management','retired','selfemployed','services','student','technician','unemployed','unknown')
+ marital : marital status (categorical:'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
+ education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
+ default: has credit in default? (categorical: 'no','yes','unknown')
+ balance: average yearly balance, in euros (numeric)
+ housing: has housing loan? (categorical: 'no','yes','unknown')
+ loan: has personal loan? (categorical: 'no','yes','unknown')
+ contact: contact communication type (categorical:'cellular','telephone')
+ day: last contact day of the month (numeric 1 -31)
+ month: last contact month of year (categorical: 'jan', 'feb','mar', …, 'nov', 'dec')
+ duration: last contact duration, in seconds (numeric). 

<b>Important note:</b> this attribute highly affects the output target (e.g., ifduration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known.Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic
predictive model.

+ campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
+ pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
+ previous: number of contacts performed before this campaign and for this client (numeric)
+ poutcome: outcome of the previous marketing campaign(categorical: 'failure','nonexistent','success')
+ target: has the client subscribed a term deposit? (binary:"yes","no")
