# html_css

## Getting Started

### 2021-03-29

#### 總記錄

1. VS Code 擴展庫：Prettier，和 Live Server

## Web Development Fundamentals

### 2021-03-29

#### 總記錄

1. 要重點復習 Git
2. 瀏覽器會將 HTML 轉換成 DOM，再呈現出來
3. 可以在 https://validator.w3.org/ 來鑑定 html 文件的完整性
4. http://jigsaw.w3.org/css-validator/ 鑑定 css 完整性

#### 分點

1. html & css demo file

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <title>webpage</title>
       <style>
         img {
           width: 100px;
           border-radius: 50px;
           float: left;
           margin-right: 10px;
         }
   
         .username {
           font-weight: bold;
         }
       </style>
     </head>
     <body>
       <img src="images/123.png" alt="img"/>
       <p class="username">@mosh</p>
       <p>HTML</p>
     </body>
   </html>
   
   ```

## HTML Basics

### 2021-03-29

#### 總

1. UTF-8 可以包含所有字符

#### 分

1. 自動因應設備更改寬度的 `meta data`

   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```

2. 常用 `meta`

   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <meta name="keywords" content="HTML, CSS">
   <meta name="description" content="search first display content.">
   ```

   