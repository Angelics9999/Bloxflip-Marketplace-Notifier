This code is a Python script that monitors the prices of limited items on the Bloxflip marketplace and sends a notification if an item is selling below a certain percentage of its value.

To run this code, you need to install the required packages: cloudscraper, requests, discord_webhook, and win10toast.

You also need to create a configuration file named "config.json" in the same directory as the script, with the following fields:

"auth": your Bloxflip authentication token for the API to check Marketplace

"percentage": only put from 0.5 to 1 because 0.5 is a 50% deal and 1 is basically item that has the same price as its value 

"webhook_enabled": whether to enable Discord webhook notifications (True or False)

"webhook": the URL of the Discord webhook to send notifications to

"webhook_ping": the message to send as a mention in the Discord webhook notification

"windows_notification": whether to enable Windows toast notifications (True or False)

"refresh_rate": the time in seconds to wait before refreshing the marketplace data


To stop the script, you can press Ctrl+C in the command line.

