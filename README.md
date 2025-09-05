## SITE

Visit the Site https://geoinf25.github.io/site/

## APPLICATIONS
Some Applications created in the most common programming language. 
### -- Important note: libraries / frameworks and other elements associated with them are the property of their respective owners --
The description follows:
* __APP001__: after having created a WinForm .NET project (in C#) and having prepared the related WebView2, ReoGrid - .NET Spreadsheet components (also through the related NuGet packages), the Application in question uses an HTML page with which to call the functions and Markers of the Leaflet Library (Javascript). The coordinates of the insertion Markers will then be listed in the spreadsheet arranged on the side of the Application. In this context, communication between C# and Javascript is ensured thanks to the _webView21.ExecuteScriptAsync_, _chrome.webview.postMessage_ instructions. The management of the handlers / events is defined starting from the WinForm Load event, through expressions such as _webView21.NavigationCompleted_ _+=_ _(_,_ _args)_ _=>_ _{...}_.
Example images:
![alt text](https://github.com/GeoInf25/Applications/blob/main/App001_GitHub/Images/01Image_App001.png)
![alt text](https://github.com/GeoInf25/Applications/blob/main/App001_GitHub/Images/02Image_App001.png)
