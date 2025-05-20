<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parabéns Turma SENAI</title>
    <style>
        body {
            background: #075e54;
            color: white;
            font-family: Arial;
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        h1 { color: #25D366; }
        .members {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .member {
            background: #128C7E;
            margin: 10px;
            padding: 15px;
            border-radius: 20px;
            animation: slideUp 0.5s forwards;
            opacity: 0;
        }
        @keyframes slideUp {
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>🎉 Parabéns Turma 88436 SENAI 🎉</h1>
    <p>Os melhores desenvolvedores do Brasil:</p>
    
    <div class="members">
        <div class="member" style="animation-delay: 0.2s">Davi Cruz</div>
        <div class="member" style="animation-delay: 0.4s">Douglas Barreto</div>
        <div class="member" style="animation-delay: 0.6s">Hugo Batista</div>
        <div class="member" style="animation-delay: 0.8s">Iasmin Angel</div>
        <div class="member" style="animation-delay: 1.0s">Murilo Batista</div>
        <div class="member" style="animation-delay: 1.2s">Rodrigo D'Anunciação</div>
    </div>
</body>
</html>
