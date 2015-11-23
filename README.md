# vianet
A python script to get current status of my vianet plan.

## Dependencies
**python3** and **BeautifulSoup** is what you need, along with in-built **requests** module.

```bash
pip3 install beautifulsoup4
```

To install **pip3**, hit:
```bash
sudo apt-get install python3-pip
```

If `requests` module is missing in your case:
```bash
sudo apt-get install python3-requests
```

## usage
Just run the python script `vianet.py`.  
The script uses your vianet's **username** and **password**. 
So, the script loads them from a JSON located in `data/vianet.json' in current directory as: 

```json
{
    "lg_name"       : "username", 
    "lg_password"   : "password",
    "url"           : "https://customers.vianet.com.np/portal/show_details.pl?id=your_id"
}
```

##### note
Here, for `url` key, the query id **id=your_id** must be your id. You can get your id, from vianet as:

![vianet image](/images/vianet)

The id is in the format **xxxx-xxxxx**. Use the second number as your id.

