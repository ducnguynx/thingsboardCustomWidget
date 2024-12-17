#### Update via MQTT  
```
mosquitto_pub -d -h "demo.thingsboard.io" -t "v1/devices/me/attributes" -u "<token>" -f "<yourjsonfile>.json" 
```
replace "\<token\>" with your token & "\<yourjsonfile\>.json" with your JSON file
### Add the widget to your dashboard  
![Alt text](images/Widget.png)  
### Modify the input attribute value  
![Alt text](images/values.png)  
### Modify the HTML code inside the Widget
![Alt text](images/HTMLcode.png) 


