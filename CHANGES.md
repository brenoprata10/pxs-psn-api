# Change Log


## **[1.1.0] - 2019-08-13**

###Added<br>
* Add node-fetch as dep to reintroduce sending image messages.
* use experimental fs.promises nodejs feature;
###Changed
* PSN object now use constructor. Accepts<br> 
```{lang: <psn response language>, region: <server region>, refresh_token:<refresh_token>, access_token:<access_token>}``` as optional params.

* sendMessage method accept local file path as arg instead of file buffer.

* example has been updated according to these changes.