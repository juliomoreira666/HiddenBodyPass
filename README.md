# HiddenBodyPass
Ocultar o Body do site com Password

$(document).ready(function() {
    $(document.body).hide();
    var password = prompt("Site em construção, digite a senha fornecida!");
    if (password == "senha_que_deseja")
    {
        $(document.body).show();
    }
    else
    {
        $(document.body).hide();
        alert("Senha incorreta!");
    }
});
