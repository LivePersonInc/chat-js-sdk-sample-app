LivePerson JS Chat SDK - Demo App
=================================

Prerequisites for un-monitored flow
===================================
- Create LiveEngage site
- Create an engagement of type "API" that will appear on the page implementing the SDK
- Configure your new engagement to use an Engagement Window of type "API"
- Ensure that your account has an agent, with the appropriate skill if you configured your engagement with a skill

Prerequisites for monitored flow
================================
- Create LiveEngage site
- Create any engagement that will appear on the page implementing the SDK
- Configure your new engagement to use an Engagement Window with context:`window` and methodName: `externalJsMethodName`
- Ensure that your account has an agent, with the appropriate skill if you configured your engagement with a skill

Getting Started for un-monitored flow
=====================================
1. Login to your site with the user mentioned in prerequisites
2. Run "index.html"
3. Add query params to the index.html?site={siteId}
4. Click the chat button to start chat

Getting Started for monitored flow
==================================
1. Login to your site
2. Run "index.html"
3. Add query params to the index.html?site={siteId}&lptag=true
    - If your chat button is an embedded button, add query param &divid={button div id} 
4. Click the chat button to start chat
