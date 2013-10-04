Welcome to Barclaycard SmartPay

This file covers some basic changes you may wish to make to this default skin template, for more details on skins please refer to the Integration guide.



----Customising the Default Skin----



///---Displaying Merchant Logo---\\\

If you wish to display your own logo on the payment pages please see the following. 

In the file "screen.css" find the following lines.

#logoheader2 {
	width: 900px;
	height: 101px;
	border-top: 1px solid #eee;
	margin-top: 5px;
	padding-top: 5px;
	background: url(../img/merchantlogo.gif) no-repeat;
	display: none;
}

Change the line "display: none;" to "display: block;" and then do the following and upload your updated skin as per the integration guide.

In the 'img' folder replace merchantlogo.gif with your merchant logo.
 
If you are using the one page payment screen then edit the following line in the screen.css under .popupMsgOPP top:190px; Add to this the height of your merchant logo to keep the "What is CV2 window" inline.
 



///---Displaying the Internet Authentication logos---\\\
 
By default the Internet Authentication logos for Verified by Visa and MasterCard SecureCode are displayed on the default skin payment page, if you wish to hide these as you are not using the service then please do the following

In the file "screen.css" find the following lines.

.IAlogo {
	width:180px;
	height: 99px;
	background:  url(../img/IAlogos.gif) no-repeat;
	display: block;
	margin-top  0px;
	float: right;
}
 
Change the line "display: block;" to "display: none;" and upload the updated skin file as per the integration manual, this will hide the internet authentication images on the payment page.
