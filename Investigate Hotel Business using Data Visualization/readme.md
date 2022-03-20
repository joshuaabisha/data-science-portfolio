# Mini Project - Investigate Hotel Business using Data Visualization
* Looking for insights related to hotel business performance
* These insights can be found by data exploration, such as analyzing how customers behave in booking hotel tickets or looking for factors that influence the cancellation of hotel ticket reservations
* Visualizing insights and story telling the data
* This dataset is obtained from [Hotel booking demand | Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand)

## Data Preprocessing
* **Missing Value** : There are 4 columns with missing values. Children, company, and agent columns can be filled with 0 while the city column can be filled with "Unknown" <br>![image](https://user-images.githubusercontent.com/99066590/159164356-5f1870c0-27e0-4cbd-9e58-bd2e888b994f.png)<br>
* **Handle Odd Value** : The Undefined value in Meal column can be replaced with No Meal which can have the same meaning <br>![image](https://user-images.githubusercontent.com/99066590/159164443-b6f7bfc3-06f0-42fe-ab2f-5ac4d70433f1.png)<br>
* **Replace Unnecessary Value** : There are a number of guests that have 0 value. So this data needs to be dropped.<br>![image](https://user-images.githubusercontent.com/99066590/159166336-0c75019b-7079-449f-a190-0202309f6e6d.png)<br>

## Monthly Hotel Booking Analysis Based on Hotel Type
* Both types of hotels have an increase in the number of bookings in each holiday season. However, in the City Hotel type, there was a significant decline after the holiday season (May-July) in August and September <br>![image](https://user-images.githubusercontent.com/99066590/159166956-a73789d2-7085-4770-b047-a9a95a194d28.png)<br>

## Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates
* The longer the total nights booked, the higher the percentage of booking being canceled, also City Hotel type has more steeper trend compared to Resort Hotel <br>![image](https://user-images.githubusercontent.com/99066590/159166963-a41dc9c3-932c-4814-805e-8d3cd6339556.png)<br>


# Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate
The higher the lead time (around 270-390 days, around 1 year), the higher the cancellation rate (above 60%). Meanwhile, the lowest cancellation rate is within 1 month of lead time <br>![image](https://user-images.githubusercontent.com/99066590/159166971-d45c09ff-276d-4a38-a8a7-c25ab91cbf2c.png)<br>

