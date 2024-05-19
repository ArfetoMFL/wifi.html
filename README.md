```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Wi-Fi Família MFL</title>
</head>
<body>
    <h1>Parabéns por se conectar na Wi-fi Família MFL</h1>
    <p>Para continuar, por favor faça o pagamento via Pix. Clique no botão abaixo para copiar o código Pix.</p>
    <button onclick="copyPixCode()">Copiar Código Pix</button>
    <script>
        function copyPixCode() {
            navigator.clipboard.writeText('seu-codigo-pix-aqui');
            alert('Código Pix copiado! Realize o pagamento para continuar.');
        }
    </script>
</body>
</html>
```
