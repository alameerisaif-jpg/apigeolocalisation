🌍 Shopify Auto-Currency Switch by IP
Automatically switch customer country + currency based on IP address using Shopify’s /localization endpoint, Shopify Markets, and a geolocation API.
This implementation works with any modern Shopify theme and requires no backend modifications.


#
#
#


🚀 Overview
This project adds automatic currency switching to a Shopify store based on the visitor’s location. Because Shopify Liquid cannot access the customer’s IP, the logic is handled using client-side JavaScript plus a hidden /localization form.
When a user visits your store:
Their IP is resolved via a geolocation API.
The detected country is compared to Shopify’s current localization.
If different, the script auto-submits the localization form.
Shopify reloads the store in the correct market + currency.
A localStorage flag prevents repeated switching.

#
#
API RESTORE 
