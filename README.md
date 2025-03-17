# dynamic-H1-replacement
Yes, this code dynamically replaces the h1 heading on the page based on the keyword passed in the URL. For example, if the URL contains the parameter ?utm_term=delivery, the h1 heading will change to "delivery". 
Google Sheets - https://docs.google.com/spreadsheets/d/1ZeJ_G0ilwsE55997lBeBQQgUS-rxt3ZNSm-cFQCSIps/edit?gid=0#gid=0 .
Create in GTM variable - {{ Url - ps_term }}, Type - Query, Key - ps_term .
Create trigger - PW - URL - ps_term not undefined .
