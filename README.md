# Stream-Real-Time-Stock-Data
Firstly, I created an Event HUbs NameSpace: stockfeeddatademo927.
![1664316594935](https://user-images.githubusercontent.com/114533700/192646608-a19d9c2f-45d2-43e7-b135-7332220c030d.png)
Then, I created an Event Hub Instance inside the Event HUbs NameSpace.
![ecceaa1932799ed984b0761b14b926d](https://user-images.githubusercontent.com/114533700/192647214-acc4f23b-58bf-4618-9a0b-85a6563eaca2.jpg)
The next step is creating a SAS policy so the Python program can reference it and get it permission to access and adjust the data into Azure.
![1664317150121](https://user-images.githubusercontent.com/114533700/192647738-884a93a2-ece5-4879-9da1-ed09bbff3b76.jpg)
Then I created a Stream Analytics Job and defined the inputs.
![image](https://user-images.githubusercontent.com/114533700/192647982-a3a44702-ad60-4fcd-b609-ba87cc52010f.png)
![image](https://user-images.githubusercontent.com/114533700/192648070-72deab75-0278-47e5-82df-e4df8c62cbb4.png)
The next step is creating the Python coding to work with stock data, data manipulation, defined SAS connection string/Event Hub name and looping the event.
The coding file: datafeedstock.py has been uploaded
After these steps, the stock data can be monitored in Azure Stream Analytics.
![image](https://user-images.githubusercontent.com/114533700/192649029-548ae260-b921-475a-85ed-81a6d0657ca3.png)
The last step is defining the output
![image](https://user-images.githubusercontent.com/114533700/192649271-5c8f3ddb-814e-4551-aeae-a7f44dc9670f.png)
