docker run -it --name ubuntu ubuntu sh -c 'apt-get update; apt-get install -y curl; echo "Input website:"; read website; echo "Searhing.."; sleep 1; curl http://$website;'

Input website:
helsinki.fi
Searhing..
<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx/1.20.1</center>
</body>
</html>