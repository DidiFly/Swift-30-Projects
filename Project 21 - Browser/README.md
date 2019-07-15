Browser
==========

Browser is an app mocks the safari web browser on iOS side -- it is implemented by WKWebView via using its KVO and Error Handling features with the help of WKNavigationDelegate, UIAlertViewController, UIProgressBar, and UIToolBar.

For all details, please reference [A Look at at the WebKit Framework](https://www.appcoda.com/tag/wkwebview/)

## Be careful
After opening the project, it is recommended to add WebKit. framework under Linked Frameworks and Libaries in General. Otherwise, under the current Xcode version 10.2.1 (10E1001) and swift5, the running project will have this problem:
Terminating app due to uncaught exception'NSInvalid Unarchived Operational Exception', reason:'Can not instantiate class named WKWebView because no class named WKWebView was found; the class needs to be defined in source code or linked in a library (ensure the class is part of the correct target) ''

## Screenshots
![Browser](./Browser.gif)
