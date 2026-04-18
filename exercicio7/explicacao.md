O comando python3 -m http.server inicia um servidor HTTP simples, sem suporte nativo a HTTPS.

Ao acessar https://localhost:8443, o navegador tenta estabelecer uma conexão segura usando SSL/TLS. Porém, como o servidor iniciado não possui configuração de certificado digital nem suporte a TLS, a conexão segura falha e o navegador exibe um erro.

Portanto, o erro ocorre porque foi usado https:// para acessar um servidor que está funcionando apenas com HTTP.
