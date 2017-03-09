LivePerson JS Chat SDK - Demo App
=================================

Prerequisites for un-monitored flow
===================================
- Create LiveEngage site
- Configure to your site external engagement window
- Configure to your site external engagement referring to your external window
- Ensure you have a user to login for the demo

Prerequisites for monitored flow
================================
- Create LiveEngage site
- Configure to your site external engagement window with context:`window` and methodName: `externalJsMethodName`
- Configure to your site web engagement referring to your external window
- Ensure you have a user to login for the demo

Getting Started for un-monitored flow
=====================================
1. Login to your site
2. Run "index.html"
3. Add query params to the index.html?site={siteId}&lptag=false
4. Click the chat button to start chat

Getting Started for monitored flow
==================================
1. Login to your site
2. Run "index.html"
3. Add query params to the index.html?site={siteId}&lptag=true
4. Click the chat button to start chat
