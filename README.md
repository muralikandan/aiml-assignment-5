# Travel Coupon Acceptance

**Introduction**
  
  This exercise mainly to ingest data from CSV, understand, clean, analyze and build hypothesis


**How to setup**

1. Clone this repository to local or direcly open '.ipynb' in collab notebook
2. Google Collab has all prerequisites, as long as python notebook has required import statetements.
3. If its in local then recommend to have anacondo navigator which comes with run time as well
4. Create a folder 'data' and have data file as CSV
5. Just run individual steps from notebook

Jypiter notebook can load https://github.com/muralikandan/aiml-assignment-5/blob/main/prompt.ipynb

Refer below summary of findings
1. The proportion of the total observations chose to accept the coupon : 56.84%
2. **Bar Coupon Analysis**
   Hypothesis based on various exploration about bar coupon acceptance
   **Hypothesis 1** : - Drivers who go to a bar more than 3 times a month have a significantly higher bar coupon 
                        acceptance rate than those who got to a bar less than 3 times a month.

   **Hypothesis 2** : - Bar visit habbit has positive influence than driver's age in bar coupon acceptance.

   **Hypothesis 3** : - Drivers travel with kids not at all influence to bar coupon accepting. Occupation - Farming Fishing 
                      & Forestry occupation has less influence to bar coupon acceptance rate where as over all rest of 
                      occupation has more influence.

   **Hypothesis 4** : - Bar visit habbit has positive influence than driver's age or marital status in bar coupon 
                      acceptance. Cheap restaurants visit habbit with less than 50K income has reasonable impact to bar 
                      coupon acceptance rate.


3. **Coffee Coupon Analysis**
            Hypothesis based on various exploration about coffee coupon acceptance
   **Hypothesis 1**: Half of coffee coupons accepted by drivers, especially who frequent visitors of coffee house more than 
                     3 times a month have a significantly higher coffee coupon acceptance rate than who visit less than 3 
                    times a month to coffee house.

   **Hypothesis 2**: Habit of frequent visitors to coffee house have much influence than driver's age in coffee coupon 
                    acceptance rate.

   **Hypothesis 3**: Drivers who go to a coffee house more than once a month and have an occupation other than Farming, 
                    Fishing & Foresty have a significantly higher coffee coupon acceptance rate.

   **Hypothesis 4**: Drivers with kids passanger or their marital status doesn have much influence to coffee coupon 
                     acceptance rate.

   **Hypothesis 5**: Drivers go to cheap restuarant and income less than 50K has resonable influence to coffee coupon 
                     acceptance rate.

In conclusion, regular habit influence more than any other factor for most cases.
