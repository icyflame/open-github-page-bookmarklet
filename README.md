## Open GitHub Page : Bookmarklet

Drag and drop this link into your bookmarks bar :-

[Open GH Page](javascript: var https = document.URL;var matches = https.split('https://github.com/');if (matches.length <= 1) {	document.location = "https://github.com";} else {	matches = matches[1];	var username = matches.split('/')[0];	var repo = matches.split('/')[1];	var newURL = "https://" + username + ".github.io/" + repo;	document.location = newURL;})

