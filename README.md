<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>

<link rel="shortcut icon" href="ICON.png">

<h1>Введите название EXE файла:</h1>
<input type="text" id="filename">
<button onclick="openFile()">Открыть</button>

<script>
    function openFile() {
        const filename = document.getElementById("filename").value;
        window.location.href = filename + ".html"; // Перенаправление на файл
    }
</script>
</body>
</html>
