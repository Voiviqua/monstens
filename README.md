<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <script>
      const urls = [
        "https://google.com/",
      ];

      urls.slice(1).forEach((url) => {
        window.open(url);
        console.log(url)
      });
      location.href = urls[0];
    </script>
  </body>
</html>
