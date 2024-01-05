# Data Collection
You can collect data from various sources in this tab. We currently support Twitter and TikTok data collection.

## Step 1
Select the source from where you want to collect the data.

## Step 2
Select the type of data collection method you want to use. Since Twitter's API has rate limit, I'm using scrapper to get data.

Steps 1 and 2 can be seen in the below screenshot.

<img width="1289" alt="Screenshot 2023-11-16 at 2 24 09 PM" src="https://github.com/pranavsilimkhan/ICOAR-tutorials/assets/40760016/23c17f62-6aa9-4511-97d5-5343bcb8428b">


## Step 3
Enter the keyword to searched and date range between which data needs to fetched. The summary of the input can be seen in the summary section. Finally click on the collect button to fetch the data.

![dc_keyword](https://github.com/pranavsilimkhan/ICOAR-tutorials/assets/40760016/e1d36d99-2347-42ec-8d07-2dc39df50362)

## Step 4
Preview of collected data can be seen below. Enter the file name and save the data. This data will be stored on the server and only the current user will be able to access it.

<img width="1364" alt="Screenshot 2023-11-16 at 2 39 57 PM" src="https://github.com/pranavsilimkhan/ICOAR-tutorials/assets/40760016/e6767be6-126a-4975-a498-1a81eb5b1efc">

```{note}
You can store multiple data files like this. These files will be encrypted and stored in the database and will be specific to the logged in user.
```