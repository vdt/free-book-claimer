# free-book-claimer
Selenium project allowing to automatically claim current free e-book at [PacktPub.com](https://www.packtpub.com/) using provided credentials.

## :notebook: How to use

### Download a web driver
In order to use this app you need to download one of the Selenium WebDrivers appropriate for the browser that you have installed on your PC.

Currently supported browsers are:
* Firefox ([Mozilla GeckoDriver](https://github.com/mozilla/geckodriver/releases))
* Chrome ([Google Chrome Driver](https://sites.google.com/a/chromium.org/chromedriver))
* Opera ([Opera](http://choice.opera.com/developer/tools/operadriver))
* Edge ([Microsoft Edge Driver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/))
* Internet Explorer - latest drivers can be downloaded from [http://www.seleniumhq.org/download](http://www.seleniumhq.org/download)

**Important**: The brower must have support for jQuery in order to let app run properly.

### Add path to web driver to a proper environment variable
For example, if you want to use Firefox, add environment variable with key `webdriver.gecko.driver` and value containing `path\to\your\gecko\driver.exe`. Alternatively, you can provide this variable during **free-book-claimer** execution as java VM variable `-Dwebdriver.gecko.driver=path\to\your\gecko\driver.exe`.

### Provide email and password as command-line arguments
Once you imported project, in your run configuration provide `email` and `password` (**in that order!**) as command-line arguments. They will be used to log in using your account at [Pubpackt.com](https://www.pubpackt.com/).

### See it in action
Run the app and claim your free book with no effort!
