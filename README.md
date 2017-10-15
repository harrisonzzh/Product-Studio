# Product-Studio (in working)

The project is focusing on how to create a real time transportation recommendation in New York City. 
We want to natual language processing to analyze subway service change notifications and convert it into machine readable data, and make transportation recommendation based on those data. 

### Project Decomposition:
* Real-time MTA notification crawler
* Notification Processing Engine (in working)
* Transporation Recommendation Engine (in working)

### Example of the notification crawler

Get real-time notifications on 9/27/2017: <br />
```
get_clean_data('9/27/2017')
```

Get real-time notifications from 9/27/2017 to 9/29/2017: <br />
```
get_data_over_period('9/27/2017', 3)
```
### Sample Output: <br />
![Alt Text](/Subway_notification/Relatives/sample_output.png)
