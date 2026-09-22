# Indicador de Inventário

Versão web do programa, protegida por senha.

O `index.html` traz o aplicativo cifrado com AES-GCM, chave derivada da senha
por PBKDF2-SHA256. Sem a senha não há o que ler no arquivo. Aberto, o programa
roda inteiramente no navegador de quem acessa: nenhum dado de inventário é
enviado a lugar nenhum, e o histórico fica no próprio aparelho.

Gerado por `scripts/publicar-web.mjs`, no repositório do projeto.
