# tarulhas-java
para as aulas de java script venturus
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script>
        function verificaViagem() {
            var saldo = +prompt("Digite seu saldo:");
            if (saldo >= 5000) {
                alert("parabens sua viagem  chegou!!");

                var paises = ["belgica ", "marrocos", "coreia"];
                var paisescolhido = +prompt("escolha um dos tres paises:" + paises[0] + paises[1] + paises[2]);
                console.log(paisescolhido);
                switch (paisescolhido) {
                    case 0:
                        paisesescolhidos = "belgica"
                        document.write("seu pais é a belgica e seu passeio é bruxelas")
                        break

                    case 1:
                        paises = "marrocos"
                        document.write("seu pais é a marrocos e seu passeio é marrakech ")
                        break

                    case 2:
                        paises = "coreia"
                        document.write("seu pais é a coreia e seu passeio é momorial de guerra")
                        break
                }

            } else {
                
                
                var meses = 0;


                for (var i = 0; saldo < 5000; i++) {
                    saldo += saldo
                    meses ++;
                }
                alert('você não poede viajar agora voce precisa de:' + meses)

            }
        } 
    </script>
</head>

<body>
    <button onclick="verificaViagem()">consultar</button>
</body>

</html>
