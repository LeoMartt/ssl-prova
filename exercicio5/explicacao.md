Neste exercício foi gerado um certificado digital no arquivo aluno.crt.

O comando openssl x509 foi usado para criar um certificado autoassinado a partir do arquivo CSR (aluno.csr) e da chave privada (aluno.key). A opção -days 365 define que o certificado será válido por 365 dias.

Esse certificado é chamado de autoassinado porque foi assinado pela própria chave privada do usuário, sem uma autoridade certificadora externa. Ele é útil para testes e ambientes de estudo.
