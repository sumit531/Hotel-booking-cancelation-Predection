# Hotel-booking-cancelation-Predection
Hotel booking cancelation Predection Logistic Regression
Import libraries, Removing the null values which have greater than 45%
After that EDA analysis take place some insight are got
1. In this analysis the low cancelation rate in the Resort Hotel.
2. In olnile TA maximum cancelation Happend
3. In Distribution channel have max cancelation.
4.  Max cancelation no Deposite.
5.  Max arival cancelation in month of August.
After that chcking high corelated corelation by heat map and drope as well
Get dummy variables for the analysing of categorical columns and Droping the existance one default coumns.
assigning the X,Y column to train and test split
scaling the variables and apply logistic regression model and anf apply RFE selection for the 20 columns.
Import stac model to cheking p value, ensuring p value not more greater that 0.05
After that cheking the VIF which is not more than value 5
Than the result got of the metrix
sensitivity: 1.0
specificity: 1.0
false +ve rate: 0.0
+ve predictive value: 1.0
-ve predictive value: 1.0


