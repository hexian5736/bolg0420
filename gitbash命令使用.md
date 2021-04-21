
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>小贺的博客</title>
  <script src="https://lib.baomitu.com/marked/2.0.3/marked.js"></script>
    <link rel="stylesheet" href="./typo.css"></link>
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <!-- metavp 按tab键 -->
  <style>
    body{
      padding:16px;
    }
  </style>
</head>
<body>
  <div id="content">
    
# 1.强制推送（慎用，除非你认为其他冲突等可以丢弃 或者不是很重要）

`git push -- force`

# 2.创建文件等小命令

`
touch a // 创建一个a文件
echo 1234 >> a // 把1234这个内容放入a文件
cat a // 打开a文件 读取出a文件中的内容
mkdir test // 创建test文件夹
rm 文件名 // 删除文件
pwd // 打印当前工作路径
`

# 3.安装git的时候 都会安装git bash和git GUI 我们完全也可以使用git GUI来提交版本 与sourcetree等功能相同

`gitk // 用git命令快速打开git GUI`
    

  </div>
  
  <script>
    var content = document.getElementById('content')
    var markdown = content.innerHTML
    var html = marked(markdown)
    content.innerHTML =html
  </script>
</body>
</html>
