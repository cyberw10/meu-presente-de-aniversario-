<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário!</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            margin: 50px;
            background-color: #f58585;
        }
        h1 {
            color: #FF69B4;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        p {
            color: #f0e9e9;
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        #gift-img {
            width: 150px;
            animation: float 4s ease-in-out infinite alternate;
        }
        @keyframes float {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-10px);
            }
        }
        .gift-options {
            margin-top: 30px;
        }
        .gift-options button {
            background-color: #FF69B4;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .gift-options button:hover {
            background-color: #D81B60;
        }
        .coruja-img {
            width: 80px;
            vertical-align: middle;
        }
    </style>
</head>
<body>
    <h1>Feliz Aniversário, Meu Amor!</h1>
    <p>Te amo muito! <img class="coruja-img" src="https://cdn.discordapp.com/attachments/1181311175292629162/1238557289808400404/coruinha-removebg-preview.png?ex=663fb7dd&is=663e665d&hm=ef086086a73a5f8f01d4b9b268f3fdba0906db11a0ad716d877bf7f878a18860&" alt="Coruja fofa"></p>
    <img id="gift-img" src="https://cdn.discordapp.com/attachments/1181311175292629162/1238557289808400404/coruinha-removebg-preview.png?ex=663fb7dd&is=663e665d&hm=ef086086a73a5f8f01d4b9b268f3fdba0906db11a0ad716d877bf7f878a18860&" alt="Presente">
    <p>Meu <span style="color: #FF69B4;">presente</span> para você é que você tem direito a escolher:</p>
    <div class="gift-options">
        <button onclick="chooseGift('presente')">Qualquer coisa no valor de até R$40,00</button>
        <button onclick="chooseGift('pix')">Um PIX meu</button>
    </div>
   

    <script>
        function chooseGift(choice) {
            if (choice === 'presente') {
                // Aqui você pode adicionar o redirecionamento para uma página de escolha de presente
                alert("Você escolheu um presente no valor de até R$40,00. Vamos às compras, ou comer algo juntos!");
            } else if (choice === 'pix') {
                // Aqui você pode adicionar o redirecionamento para uma página de instruções para o PIX
                alert("Você escolheu um PIX meu. entao me passe sua chave pix que eu te mando!");
            }
        }
    </script>
</body>
</html>
