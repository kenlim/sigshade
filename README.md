# SigShade
SigShade is a simple hack to hide the "Please consider the environment..." suffixes that are tacked to every Guardian email message. 

These suffixes make reading threads of emails harder, and cost us an extra scroll per email. This hack will not remove the signatures (as that is done at the email server level) but at least we don't have to see it. 

## Instructions for use
1. Install [Stylish for Firefox] (https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome) or [Stylish for Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe)
1. Create a new style named "SigShade"
1. Set the "Applies to" field to "URLs starting with", and set the value to "https://mail.google.com".
1. Set the "Code" field to:
	.gs pre {width: 250px;
	white-space: nowrap;
	overflow: hidden !important;
	text-overflow: ellipsis}
1. Click the "Save" button.


