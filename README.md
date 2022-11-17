# bikesharing
Tableau
This project is designed to analyze New York bike sharing program Citi Bike in order to start similar company in Des Moines, Iowa.
## Results


[NYC Citi Bike Tableau Link](https://public.tableau.com/app/profile/dianabasi.robinson5416/viz/NYC_CitiBike_Challenge_16682154917810/Story1?publish=yes)

The tripduration column's data type is changed from integer to datetime to get the time in hours and minutes and also,  the gender column is change from integer to string using replacement method in Pandas.
![image](https://user-images.githubusercontent.com/109990578/202355278-99b9304e-018d-46ec-8b34-4b0e3f779241.png)

### Trip duration for all the users. Bikes are mostly used at least 30 minutes.
![image](https://user-images.githubusercontent.com/109990578/202355569-b6533936-187e-4a8b-a18f-dc79b90f5f35.png)

### Trip duration by gender. Males use Citi Bike about 2.5 times more than females.
![image](https://user-images.githubusercontent.com/109990578/202355687-0af982a5-c060-4a01-ac6e-cc5891b031c5.png)

### Trips by weekday for each hour. On weekdays most of the trips are in the morning and evening hours but during the day on weekends for Citi Bike. .
![image](https://user-images.githubusercontent.com/109990578/202355919-c814a8a0-6763-4b18-9d63-d233956f39fe.png)

### Trips by gender (weekday per hour). Males are more active users than females. Wednesdays afternoon is less popular time for biking among all three genders.
![image](https://user-images.githubusercontent.com/109990578/202356120-75e4d6be-526b-43b0-963f-7ceb38d44faf.png)

### User trips by gender by weekday.
![image](https://user-images.githubusercontent.com/109990578/202356215-a2e57b54-4a60-4cc8-ac9a-e5636dc2c93f.png)

### Bike maintenance analysis. About one third of the bikes are highly used. The least busy hours are from 1am to 5am.
![image](https://user-images.githubusercontent.com/109990578/202358255-4e696580-d999-477b-b72e-4f63088f866d.png)

## Summary
The following conclusions are drawn from the visualization:

- Bikes are mostly used for up to 30 minutes
- Males use Citi Bike about 2.5 times more than females
- On weekdays most of the trips come to morning and evening hours while on weekends Citi Bike is more popular during the day
- Users who don't share their gender mostly ride on weekends. Wednesdays afternoon is less popular time for biking among all three genders
- About one third of the bikes are highly used. The least busy hours are from 1am to 5am which is the most convenient time for maintenance.
