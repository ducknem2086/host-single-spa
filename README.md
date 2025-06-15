
### HOST SINGLE SPA FOR VUE MICROFRONTEND
-   this is example host application for vue mfe
### note : 
-   if you using this meta config, it has error - or not:
    ```ts
    <meta http-equiv="Content-Security-Policy"
    content="default-src 'self' https: localhost:*; script-src 'unsafe-inline' 'unsafe-eval' https: localhost:*; connect-src https: localhost:* ws://localhost:*; style-src 'unsafe-inline' https:; object-src 'none';"> 
    
    it has error :
    
    Refused to connect to 'ws://localhost:8080/ws'
    because it violates the following Content Security Policy directive:
     "connect-src https: localhost:* ws://localhost:*".
    --> if you get this error, you can remove it from index.ejs file
---
  
        