---
type: PostLayout
title: "Blade Ball Plontium.lua | 3.7.2 \U0001F5C2️"
colors: colors-a
date: '2024-11-11'
author: content/data/team/doris-soto.json
excerpt: The best frequently updated script for blade ball.
featuredImage:
  type: ImageBlock
  url: /images/featured-Image6.jpg
  altText: Post thumbnail image
bottomSections: []
---
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blade Ball Script</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: #1e1e1e;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
            max-width: 600px;
            width: 100%;
            text-align: center;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .code-container {
            background-color: #333333;
            padding: 15px;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-family: monospace;
            font-size: 14px;
            color: #00ff88;
        }
        .code {
            overflow-x: auto;
        }
        button {
            background-color: #00ff88;
            color: #121212;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        button:hover {
            background-color: #00cc70;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Blade Ball Script</h1>
        <div class="code-container">
            <span class="code">loadstring(game:HttpGet("https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua", true))()</span>
            <button onclick="copyToClipboard()">Copy</button>
        </div>
    </div>
<script>
    function copyToClipboard() {
        const code = document.querySelector('.code').innerText;
        navigator.clipboard.writeText(code)
            .then(() => alert("Скопировано в буфер обмена!"))
            .catch(err => console.error('Ошибка при копировании: ', err));
    }
</script>
</body>
</html>
```

