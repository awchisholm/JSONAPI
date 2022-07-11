# JSONAPI
This is the World's simplest Flask application. It allows you to set up an API that can be accessed remotely to illustrate how APIs work.

The Flask package needs to be installed - use the requirements.txt file and a virtual environment to install it.

Run the Python file JSONAPI.py and you will see http://127.0.0.1:5000/ being logged as the address to visit.

Use a browser to go to http://127.0.0.1:5000/ and you should see 

```{"name": "alice", "email": "alice@outlook.com"}```

This is JSON.

You will find that if you try to access the site from another PC, your firewall will block the attempt.

More advanced things to do include
1. change the JSON
2. run in the cloud and use Wireshark to capture the exchange
3. run in the cloud to open the firewall and observe access from other PCs
