#### Learning Resource:

* Learn about how to write Reports
 	
  * First Collect the Screenshot of all the process
	  
  * Make notes and attach the screen shot from it 
	 
  * Software which i used for report writting is [KEEP NOTE](http://keepnote.org/) and [Cherry Tree](https://www.giuspen.net/cherrytree/) 

* Learn about the FILE PATH TRAVERSAL 
   
    * [Solving PORT SWIGGER LABS FILE PATH TRAVERSAL  ](https://portswigger.net/web-security/file-path-traversal)
        
    * FILE PATH TRAVERSAL -
      Directory traversal (also known as file path traversal) is a web security vulnerability that allows an attacker to read arbitrary files on the server that is running an application. This might include application code and data, credentials for back-end systems, and sensitive operating system files. In some cases, an attacker might be able to write to arbitrary files on the server, allowing them to modify application data or behavior, and ultimately take full control of the server.  
    
    * FILE PATH TRAVERSAL LABS 
      * File path traversal, simple case
       * File path traversal, traversal sequences blocked with absolute path bypass
       * File path traversal, traversal sequences stripped non-recursively
       * File path traversal, traversal sequences stripped with superfluous URL-decode
       * File path traversal, validation of start of path

  * How to prevent a directory traversal attack

The most effective way to prevent file path traversal vulnerabilities is to avoid passing user-supplied input to filesystem APIs altogether. Many application functions that do this can be rewritten to deliver the same behavior in a safer way.


