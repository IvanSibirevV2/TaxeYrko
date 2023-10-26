<!DOCTYPE>	
# TaxeYrko
<head>dffwfwew
<title># TaxeYrko</title>
</head>

<body>
  <p><q>Привет</q> <b>мир</b>!!!</p>
<form name="search">
    <input type="text" name="key"></input>
    <input type="submit" name="send" value="Отправить" />
</form>
<script type="text/javascript">
function sendForm(e){
     
    // получаем значение поля key
    var keyBox = document.search.key;
    var val = keyBox.value;
    if(val.length>5){
        alert("Недопустимая длина строки");
        e.preventDefault();
    }   
    else
        alert("Отправка разрешена");
}
 
var sendButton = document.search.send;
sendButton.addEventListener("click", sendForm);
</script>
