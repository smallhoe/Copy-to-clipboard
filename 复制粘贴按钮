<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>点击复制文本</title>
<style>
.container-group {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 20px;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center; /* 文本和按钮居中对齐 */
  width: calc(50% - 20px); /* 让每个 container 占据 .container-group 的 1/2，减去一些间距 */
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin-bottom: 10px;
  width: calc(100% / 5); 
}

.textbox {
  width: 60%; /* 调整输入框的宽度 */
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin-bottom: 10px;
}

.button {
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.button:hover {
  background-color: #0056b3;
}

.button-container {
  width: 100%; /* 让按钮容器占据整个宽度 */
  text-align: center; /* 让按钮和文本居中对齐 */
}
</style>
</head>
<body>

<div class="container-group">
  <div class="container">
    <div class="button-container">
      <input type="text" class="textbox" id="text1" value="czj">
      <button class="button" onclick="copyText('text1')">账号</button>
    </div>
    <div class="button-container">
      <input type="text" class="textbox" id="text2" value="123456">
      <button class="button" onclick="copyText('text2')">密码</button>
    </div>
  </div>

  <div class="container">
    <div class="button-container">
      <input type="text" class="textbox" id="text3" value="czj">
      <button class="button" onclick="copyText('text3')">账号</button>
    </div>
    <div class="button-container">
      <input type="text" class="textbox" id="text4" value="123456">
      <button class="button" onclick="copyText('text4')">密码</button>
    </div>
  </div>

  <div class="container">
    <div class="button-container">
      <input type="text" class="textbox" id="text5" value="czj">
      <button class="button" onclick="copyText('text5')">账号</button>
    </div>
    <div class="button-container">
      <input type="text" class="textbox" id="text6" value="123456">
      <button class="button" onclick="copyText('text6')">密码</button>
    </div>
  </div>
  <div class="container">
    <div class="button-container">
      <input type="text" class="textbox" id="text5" value="czj">
      <button class="button" onclick="copyText('text5')">账号</button>
    </div>
    <div class="button-container">
      <input type="text" class="textbox" id="text6" value="123456">
      <button class="button" onclick="copyText('text6')">密码</button>
    </div>
  </div>
  
</div>

<script>
function copyText(elementId) {
  var copyText = document.getElementById(elementId);
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */
  document.execCommand("copy");
  // alert("已复制文本: " + copyText.value);
}
</script>

</body>
</html>
