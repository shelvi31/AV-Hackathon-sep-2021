# AV-Hackathon-sep-2021
Rank 78 Solution, MSLE*1000 = 224

**Problem Statement: **

Supplement Sales Prediction

Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs. 

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities. 

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc.

Your task is to predict the store sales for each store in the test set for the next two months.

**Data Dictionary:**
#### Train Data
- ID: Unique Identifier for a row

- Store_id: Unique id for each Store

- Store_Type: Type of the Store

- Location_Type: Type of the location where Store is located

- Region_Code: Code of the Region where Store is located

- Date: Information about the Date

- Holiday: If there is holiday on the given Date, 1 : Yes, 0 : No

- Discount: If discount is offered by store on the given Date, Yes/ No

- Orders: Number of Orders received by the Store on the given Day

- Sales: Total Sale for the Store on the given Day


#### Test Data
- ID: Unique Identifier for a row

- Store_id: Unique id for each Store

- Store_Type: Type of the Store

- Location_Type: Type of the location where Store is located

- Region_Code: Code of the Region where Store is located

- Date: Information about the Date

- Holiday: If there is holiday on the given Date, 1 : Yes, 0 : No

- Discount: If discount is offered by store on the given Date, Yes/ No

**Final Outcome:**

After exhaustive attempts of 3 days and giving my best, I received the best MSLE*1000 Error of 225 (rank 78!). I tried multiple approaches, used the data-centric approach by making changes to data multiple times (as many ways as my brain could think of) apart from changing models. 

I tried multiple models (approx 10), also implemented an algorithm I never used before ARIMA (in this hectic pressures!), much to my disappointment the model didn’t perform that well as compared to ordinary ones.

I also tried to group the data for same-store and make prediction store-wise instead of generic, which also didn’t result in good results test results though performed exceptionally on my train dataset(overfitting because of fewer train data when clubbed).

My best results were in the most simple approach, (Simplicity at its best!) all the good models gave me almost equal results, with all features except Date, the params when kept at default performed best in my case(Still don’t know how, but open to wonders)!

As this hackathon nears the closure, my mind is still restless with what can be the approach (eagerly waiting for top coder code file!!)

Still, I feel satisfied as I gave my 100% at every hour of this weekend challenge and learned a lot!

Peace :)
