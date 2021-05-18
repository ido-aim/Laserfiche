Prerequisite :

- Enable **Window IIS** on **Server Manager** shown below;
- Enable ASP.NET 3.5,4.6 on web app
- Set SSL (selfsign is OK) on Host Machine
- If AD server is used, finished setting up Domain Controller(AD server) and join domain
- (Optional) Enable TLS 1.2 on Host Machine for Docusign integration

https://trustzone.com/knowledge-base/how-to-enable-tls-1-2-on-windows-server-2008-2016/

To fixed broken site, go to   
C:\\ProgramData\\Laserfiche\\LFDS\\connections.config.

**Manage &gt; Add Roles and Features**

![p0UX9cembbB47lyctW00xQ8cXEvKBOhWO4i60dr3.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/p0UX9cembbB47lyctW00xQ8cXEvKBOhWO4i60dr3.png)![jLyUr8E0WJO3ULSBSJo4tbBacCav8oPnQAaUuASt.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/jLyUr8E0WJO3ULSBSJo4tbBacCav8oPnQAaUuASt.png)## Installation Steps

![IHhVDutEVsq2JWR7u4LUWyFoJcaOucPmAmswCzSc.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/IHhVDutEVsq2JWR7u4LUWyFoJcaOucPmAmswCzSc.png)## Note : This installation does not config SSL; However,

As of LSF version 10.4.3++, SSL must be enable

![9DslBfYujQZHeIyCfpuTqnkVIJ3j3KleUuI6fjPL.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/9DslBfYujQZHeIyCfpuTqnkVIJ3j3KleUuI6fjPL.png)![WaROaiPKAIQaMaHip30xAQZ6MpEgBf4ByAwFRTrO.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/WaROaiPKAIQaMaHip30xAQZ6MpEgBf4ByAwFRTrO.png)![qJKqUxJphWsi0mObAt5VDBise8NvogpKSgsBND0R.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/qJKqUxJphWsi0mObAt5VDBise8NvogpKSgsBND0R.png)## Note : This installation does not config SSL --&gt; Skip installation

No![yJVeeKQnESFfb0aFZgy1PZC8vlZAlPebh0wNClRx.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/yJVeeKQnESFfb0aFZgy1PZC8vlZAlPebh0wNClRx.png)![po5dK7o8lbeAfMlwTtFijps2pSozPtiMrNmePQ12.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/po5dK7o8lbeAfMlwTtFijps2pSozPtiMrNmePQ12.png)![X2UcyD26xeXKGFNYF1xPCZNIxOEXlaBaVOml1OpC.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/X2UcyD26xeXKGFNYF1xPCZNIxOEXlaBaVOml1OpC.png)# Finished

got Icon **Directory Server and Web STS**

![bBuHaZ4xLWVCF920CuFLn4Suf7GBLh4cQqFuBhPU.png](https://tettra-production.s3.us-west-2.amazonaws.com/0d6efb4f154041e899af17bdcd19c1b5/da03ed883cdd7d743a3fdd74ff62975a/d822b155a4112474fdb7aea5ee22465e/09a2db589f601a66b75b3ab00cdfe769/bBuHaZ4xLWVCF920CuFLn4Suf7GBLh4cQqFuBhPU.png)got Icon Directory Server and egot c