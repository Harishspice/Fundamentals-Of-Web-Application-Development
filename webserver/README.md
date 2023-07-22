# Developing a Simple Webserver

# AIM:

To develop a simple webserver to serve html programming pages.

## DESIGN STEPS:

### Step 1:

HTML content creation is done

### Step 2:

Design of webserver workflow

### Step 3:

Implementation using Python code

### Step 4:

Serving the HTML pages.

### Step 5:

Testing the webserver

## PROGRAM:
```
Developed by: Harish R
Register no: 212222110012
```

```
from http.server import HTTPServer,BaseHTTPRequestHandler

content ="""

<!doctype html>
<html>
<head>
<title> My Web Server</title>
</head>
<body>
<h1>Top Five Web Application Development Frameworks</h1>
<h2>1.Django</h2>
<h2>2. MEAN Stack</h2>
<h2>3. React </h2>
<h2>4. angular</h2>
<h2>5. ASP.NET</h2>
</body>
</html>

"""
class MyServer(BaseHTTPRequestHandler):
    def do_GET(self):
        print("Get request received...")
        self.send_response(200) 
        self.send_header("content-type", "text/html")       
        self.end_headers()
        self.wfile.write(content.encode())

print("This is my webserver") 
server_address =('',80)
httpd = HTTPServer(server_address,MyServer)
httpd.serve_forever()
```
## OUTPUT:
### SERVER OUTPUT:
![229006400-3a39fcc0-da4a-4b6b-8c48-2c00d1550673](https://user-images.githubusercontent.com/117935868/229007422-b67dd831-a307-4364-9189-6bc9332d5ec6.png)

### CLIENT OUTPUT:
![Untitled](https://user-images.githubusercontent.com/117935868/229008068-cb4eddac-e6ac-4d41-a3db-1a48dbd304ad.jpg)

## RESULT:
The program is executed succesfully
