#Working as a data scientist working for an electric car-sharing service company.To determine expansion while answering common questions such as: #most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018 #What is the most popular hour for returning cars? #What station is the most popular? To achieve this we load our dataset directly from the web to save on space and we do this by writing the following code df=pd.read_csv('http://bit.ly/Autolibdataset') this will show the excel file in our working space. We therefore clean our data by dropping columns and finding duplicates.
