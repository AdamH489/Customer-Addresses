# Customer-Addresses
I cleaned a dataset of a company's customers 

The purpose of this project was to display my Python skills with regards to data cleaning. I found a dataset at https://github.com/AlexTheAnalyst/PandasYouTubeSeries/blob/main/Customer%20Call%20List.xlsx which was a relatively small dataset yet it needed to be cleaned. The uncleaned dataset can be seen below:

![image](https://github.com/AdamH489/Customer-Addresses/assets/122322345/c922c006-f204-4ad8-9262-35c68732be95)

This is a company's customer data and they have asked me to clean the data so that they can use the cleaned data to reach out to their customers. As a result, I must decide what is relevant infomration to the company with regards to reaching out to their customers and I must discard any data which isn't needed.

Firstly, I drop all the duplicate values, of which there was only one duplicate which was 'Anakin Skywalker'. Then, I standardised the different types of format in the 'Phone Number' column as XXX-XXX-XXXX. In addition, I dropped any rows with 'NaN' in the 'Phone Number' column. After that, I split the address column into different columns so that one column would show their street address and the other would show their state. I then standardised the values in the 'Paying Customer' column from 'Yes' to 'Y' and 'No' to 'N'; I did the same in the 'Do_Not_Contact' column. I then dropped the values which had missing values in the 'Phone_Number' column as they could not be contacted. I also dropped the customers who responded 'Y' to 'Do_Not_Contact' as they did not want to be contaced as well as dropping the 'Not_Useful_Column'. Having performed all the steps, I then exported the clean data to a new excel file and the output of this can be seen in the photo below: 


![image](https://github.com/AdamH489/Customer-Addresses/assets/122322345/a1db9115-f7d8-4dfb-bdd6-079f54527738)
