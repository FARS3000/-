<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download Video</title>
</head>
<body>
    <h1>Download Video</h1>
    <form action="/download" method="POST">
        <label for="url">Video URL:</label>
        <input type="text" id="url" name="url" required>
        <button type="submit">Download</button>
    </form>
</body>
</html>
