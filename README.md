<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>]
<script>
    function main() {
    var usuario;
    var senha;
    var recorrente;
    
    recorrente = true;
    while (recorrente == true) {
        usuario = window.prompt('Enter a value for usuario');
        senha = window.prompt('Enter a value for senha');
        if (usuario == "caua") {
            if (senha == "1234") {
                window.alert("lugin efetuado com sucesso");
            } else {
                window.alert("senha incorreta");
            }
        } else {
            window.alert("usuario ou senha invalida");
        }
    }
}

</script>
</body>
    <botton onclick="faca()"></botton>
    <botton onclick="enquanto()">login enquanto</botton>
</body>
</html>
