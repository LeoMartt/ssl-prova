# Atividade Prática - SSL e Certificados Digitais

## Nome
Leonardo Martins

## Ambiente
WSL com Ubuntu

## IP
localhost (127.0.0.1)

## Dificuldades
Durante a realização da atividade, tive algumas dificuldades práticas no ambiente. No início, encontrei problemas de permissão ao tentar usar comandos como `apt update`, porque ainda estava entendendo a diferença entre o usuário real do sistema e apenas a personalização visual do prompt com `PS1`.

Também tive dificuldades com a autenticação no GitHub, principalmente na parte de `git push`, porque precisei entender o uso do token de acesso pessoal no lugar da senha da conta. Além disso, em alguns momentos foi necessário sincronizar o repositório local com o remoto antes de conseguir enviar os commits.

Outra dificuldade foi no exercício com `scp`, porque eu não tinha outra máquina disponível para testar a cópia do certificado. Então precisei configurar e usar o `localhost` no próprio WSL, incluindo a instalação e o uso do serviço SSH.

Mesmo com esses obstáculos, consegui resolver cada etapa aos poucos e entender melhor tanto a parte de certificados digitais quanto o uso prático do ambiente Linux no WSL.

## Conclusão
Essa atividade foi importante para eu entender, na prática, como funciona o processo de criação e uso de certificados digitais com OpenSSL. Ao longo dos exercícios, consegui enxergar melhor a função da chave privada, do CSR e do certificado, além de perceber como a comunicação segura depende dessas etapas.

Também foi uma experiência valiosa para desenvolver mais familiaridade com o terminal, com o GitHub e com a configuração do ambiente no WSL. Mesmo quando apareceram erros, fui resolvendo passo a passo, o que tornou o aprendizado mais natural e mais sólido.

No fim, a atividade reforçou bastante meu interesse em aprender coisas novas na prática, principalmente quando envolve segurança, organização e entendimento real de como as ferramentas funcionam.
