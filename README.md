# Linux Web TWAIN: Hello World


The sample demonstrates how to create a simple HTML5 document scanning app with [Dynamic Web TWAIN v17.2](https://www.dynamsoft.com/web-twain/downloads/) on **Ubuntu 14.04**.

![Linux web document scanning](http://www.codepool.biz/wp-content/uploads/2016/08/dwt-linux-helloworld.PNG)

## Web TWAIN SDK Activation
Apply for a [valid license key](https://www.dynamsoft.com/customer/license/trialLicense?product=dwt) and update the following JavaScript code:

```javascript
Dynamsoft.DWT.ProductKey = 'LICENSE KEY';
```

## Usage
1. Install and start **nginx**:

    ```
    sudo apt-get update
    sudo apt-get install nginx
    sudo nginx
    ```

2. Create a folder **linux-dwt** under **/usr/share/nginx/html/**.
3. Copy **Resources** and **helloworld.html** to **/usr/share/nginx/html/linux-dwt**.
4. Visit `http://localhost/dwt-linux/helloworld.html` in your web browser to test the web document scanning app on Ubuntu.

## Web TWAIN Online Demo for Windows, Linux (both x64 and arm64), and macOS
https://demo.dynamsoft.com/web-twain/

## Support
For more information about the SDK, please feel free to contact support@dynamsoft.com.

## Blog
[SANE Scanner Access Using JavaScript on Linux](http://www.codepool.biz/sane-scanner-access-javascript-linux.html)
