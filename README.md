Linux Web TWAIN: Hello World
============

The sample demonstrates how to create a simple HTML5 scanning app with [Dynamic Web TWAIN for Linux][1] on **Ubuntu 14.04**.

![Android barcode scanner](http://www.codepool.biz/wp-content/uploads/2016/08/dwt-linux-helloworld.PNG)

Getting Started
---------------
1. Download and install [dynamic_web_twainx64.deb][2].
2. Download **Resources** [package][3].
3. Install and start **nginx**:

    ```
    sudo apt-get update
    sudo apt-get install nginx
    sudo nginx
    ```

4. Create a folder **linux-dwt-beta** under **/usr/share/nginx/html/**.
5. Copy **Resources** and **helloworld.html** to **/usr/share/nginx/html/linux-dwt-beta**.
6. Open web browser and visit **http://localhost/dwt-linux-beta/helloworld.html** to access scanner.

The Fancy Online Demo
---------------------
https://www.dynamsoft.com/Demo/DWTLinux/online_demo_scan.aspx

Support
-------
For more information about the SDK, please feel free to contact support@dynamsoft.com.

Blog
------
[SANE Scanner Access Using JavaScript on Linux][4]

[1]:http://labs.dynamsoft.com/linux-web-twain.htm
[2]:http://www.dynamsoft.com/Downloads/DownloadLog.aspx?server=1&product=DynamicWebTWAIN11.3.2.deb
[3]:http://www.dynamsoft.com/Downloads/DownloadLog.aspx?server=1&product=DWTLinux-Resources.zip
[4]:http://www.codepool.biz/sane-scanner-access-javascript-linux.html
