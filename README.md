# lb_3.1

```
<html>
<meta charset="UTF-8">
  <head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
   <title>Sample page</title>
   
<script>

var settings = {
  "async": true,
  "crossDomain": true,

  "url": "https://api.openweathermap.org/data/2.5/weather?zip=32044&units=%20imperial%0A&appid=587aa2f9be7d264edf0a8b52bdc74030",
  "method": "GET"
}

     $.ajax(settings).done(function (response) {
       console.log(response);
   });
 </script>
</head>
<body>
 <h2>Sample page</h2>

</body>
</html>
```
