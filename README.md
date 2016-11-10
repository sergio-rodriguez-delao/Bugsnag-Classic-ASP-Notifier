# BugSnag-Classic-ASP-Notifier
BugSnag.com - Classic ASP Notifier

A simple VBScript / Classic ASP wrapper for the www.bugsnag.com web API. 

How to use: 
1. Fill our the strBugSnagAccessToken in bugsnag.asp
1. On your custom 500 error page, include bugsnag.asp and call `BugSnagASPError()`

To log items in BugSnag manually use `BugSnagError(strMessage, strExtraPayload)` / `BugSnagWarning(strMessage, strExtraPayload)` / `BugSnagInfo(strMessage, strExtraPayload)` accordingly.
