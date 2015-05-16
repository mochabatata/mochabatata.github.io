title: Hexo_clean
date: 2014-07-18 00:36:56
tags: [hexo,debug,solved]
category: Hexo Blog
---


###Question: 
When I deploy the website I created，it shows errors in layout. However, it shows what I expect correctly in local server. 


###Answer:
Please use command '$ hexo clean' before '$ hexo g'.
'hexo clean' can clean cache files which affect the new layout.


