superSimpleBrowserVersionDetector
=================================

Detects if the user's browser is up to date


Call oldBrowser_checkMyBrowser() to see if the user's browser is up to date.
You can set the limit of how many versions back you want to support by changing the olderVersionLimit and safariVersionLimit variables.

Here's an example:
  var oldBrowser_hideOldBrowserMsg;
	oldBrowser_hideOldBrowserMsg = function() {
   //Have some functionality to hide a message div
		alert("You're browser is OK");
	}//oldBrowser_hideOldBrowserMsg
		
	//If the user's browser version is up to date:
	if(oldBrowser_checkMyBrowser()){
		//Hide the old browser message
		oldBrowser_hideOldBrowserMsg();
	}
	else{
		alert("You're browser... it's... sooo ooold");
	}
