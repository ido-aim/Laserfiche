If havn't config SSL, must set SSL cookies in `web.config` to False

web.config is located at C:\\Program Files\\Laserfiche\\Web Access\\Web Files\\web.config

![Ege35PxHncyOw6RCmZlvNtjXH28CNyAr9nj6xWmR.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/Ege35PxHncyOw6RCmZlvNtjXH28CNyAr9nj6xWmR.png)Under section &lt;system.web&gt;

edit &lt;httpCookies requireSSL="true" /&gt; to &lt;httpCookies requireSSL=**"false"** /&gt;

![pFrDoj02aENtzzGszhj4wtUcdn4R0SVEeCTNTpfN.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/pFrDoj02aENtzzGszhj4wtUcdn4R0SVEeCTNTpfN.png)then save web.config

# Configuration

access web client config on http://localhost/laserfiche/Configuration/Configuration.aspx

![9ZPD7i2s45MBRtRicQsM9v7qIMwcxhx2p7LUxPMW.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/9ZPD7i2s45MBRtRicQsM9v7qIMwcxhx2p7LUxPMW.png)1. Add Repository

1.1 Server Name (ชื่อเซิร์ฟเวอร์) : Name of the Server i.e. WIN-FUK6K9SO7RM

1.2 Repository Name (ชื่อที่เก็บ) : Name of Repositry created i.e. DittoAdminRepo

1.3 Connection : SelectPrompt for Laserfiche Credentials

![cmr3q9qoekhZaiWnqVfIeLROMjQftQfp5mutBSVg.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/cmr3q9qoekhZaiWnqVfIeLROMjQftQfp5mutBSVg.png)# Additional

Set SMTP server mail as needed

![QW4l2nZeBwnzeLJQ1bT3VBZhgZavpaVee5wIbTBB.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/QW4l2nZeBwnzeLJQ1bT3VBZhgZavpaVee5wIbTBB.png)# Finished

try login at http://localhost/laserfiche/Browse.aspx

![YL2PTDsMUynhDjwMYyNnWhPbJZn3xh2gGWDOuDP4.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/YL2PTDsMUynhDjwMYyNnWhPbJZn3xh2gGWDOuDP4.png)![WjeWFdLsdYKH9mstxEYdtFrdZe13N01ICOAtfHCf.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/WjeWFdLsdYKH9mstxEYdtFrdZe13N01ICOAtfHCf.png)#   


# Note

Additional setup for Chrome ver 75 ++

Since Chrome has strict SSL cookies.

follow this KB to config

https://support.laserfiche.com/kb/1014195/you-may-not-be-able-to-sign-in-to-the-laserfiche-web-client-through-chrome-version-84-when-using-an-insecure-connection-http


Additional setup for Chrome ver 80 ++

https://support.laserfiche.com/kb/1014094/additional-configuration-for-chrome-80
