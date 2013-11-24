Harden CVE 2012-4681
---------------------
CVE 2012-4681 has been a best seller of ours for a long time, but anti-virus vendors have caught up with us on this one.  We need to harden this exploit so that the majority of anti-virus tools can't detect it anymore.  

You don't have to make the exploit undetectable by all anti-virus tools, but the more the better (less than 10 detections on VirusTotal will earn full points).

For some tips on getting started you will want to read up on our company guide to hardening malware.  To save you some time we already put the CVE in an Eclipse Project, just open Eclipse and do File->Import->General->Existing Projects Into Workspace.  

Submission Instructions
---------------------
To submit this anomaly modify CVE 2012-4681 (currently in our product inventory) so that is resistant the anti-virus detection.  Create a new product "hardened_cve_2012_4681" and add it as a new product.  On the product page be sure to upload the .java file of your refactored CVE.  On IScore submit a link to the products view page (example: www.siteN.isucdc.com/products/M where N is your team number and M is the product ID).