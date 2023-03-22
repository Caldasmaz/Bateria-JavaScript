# Bateria-JavaScript
Criamos uma bateria, ou seja, quando você pressiona determinadas teclas do teclado, o som da bateria será tocado, e você pode até criar uma melodia e tocá-la. A mesma ideia pode ser usada para desenvolver um jogo que emita um som toda vez que um personagem faça uma interação. 
</html>
<!DOCTYPE html
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bateria</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <h1>Bateria</h1>
    <h3>Utilize o teclado para "tocar"</h3>


    <div class="keys">
        <div data-key="keyq" class="key">Q</div>
        <div data-key="keyw" class="key">W</div>
        <div data-key="keye" class="key">E</div>


        <div data-key="keya" class="key">A</div>
        <div data-key="keys" class="key">S</div>
        <div data-key="keyd" class="key">D</div>


        <div data-key="keyz" class="key">Z</div>
        <div data-key="keyx" class="key">X</div>
        <div data-key="keyc" class="key">C</div>
    </div>
    <div class="composer">
        <input type="text" id="input" placeholder="Faça uma composição..." />
        <button>Tocar</button>
    </div>


    <footer>Javascript</footer>


    <audio id="s_keyq" src="sounds/keyq.wav"></audio>
    <audio id="s_keyw" src="sounds/keyw.wav"></audio>
    <audio id="s_keye" src="sounds/keye.wav"></audio>
    <audio id="s_keya" src="sounds/keya.wav"></audio>
    <audio id="s_keys" src="sounds/keys.wav"></audio>
    <audio id="s_keyd" src="sounds/keyd.wav"></audio>
    <audio id="s_keyz" src="sounds/keyz.wav"></audio>
    <audio id="s_keyx" src="sounds/keyx.wav"></audio>
    <audio id="s_keyc" src="sounds/keyc.wav"></audio>
    
    <script src="script.js"></script>
</body>
</html>
