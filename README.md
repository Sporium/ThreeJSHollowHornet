# ThreeJSHollowHornet
Hornet form Hollow Knight model in browser using ThreeJS
You must run it from local server

Node.js http-server
Node.js has a simple HTTP server package. To install:

<pre>npm install http-server -g </pre>
To run (from your local directory):

<pre>http-server . -p 8000</pre>
Python server
If you have Python installed, it should be enough to run this from a command line (from your working directory):

//Python 2.x
<pre>python -m SimpleHTTPServer</pre>

//Python 3.x
python -m http.server
This will serve files from the current directory at localhost under port 8000, i.e in the address bar type:

http://localhost:8000/
Ruby server
If you have Ruby installed, you can get the same result running this instead:
<pre>
ruby -r webrick -e "s = WEBrick::HTTPServer.new(:Port => 8000, :DocumentRoot => Dir.pwd); trap('INT') { s.shutdown }; s.start"</pre>
PHP server
PHP also has a built-in web server, starting with php 5.4.0:
<pre>
php -S localhost:8000</pre>
