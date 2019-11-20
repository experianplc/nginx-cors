# nginx-cors
A nginx configuration that makes CORS easy

# How to use.
1. [Download](http://nginx.org/en/download.html) a copy of nginx.
2. [Edit](https://github.com/experianplc/nginx-cors/blob/master/nginx.conf) our configuration file, replacing `YOUR-LINK-GOES-HERE`
   with the full path (and optionally port) of the service you're proxying, e.g. https://app1.company.com:232
3. Replace the built in configuration file (in Windows this is /nginx/conf/nginx.conf) with the edited file from **(2)**.
4. Start nginx. 
5. By default, per the configuration nginx listens at port 8080. So requests that go to localhost:8080 will be proxied to `YOUR-LINK-GOES-HERE`. 
