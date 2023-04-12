Arquivo criado com o intuito de aplicar um pouco do conhecimento adquirido sobre o git

Anotações importantes desse bootcamp
1 - A partir de 2021 o Git tornou obrigatório o uso de chaves SSD
para gerar a achave basta digitar

ssh-keygen -t ed25519 -c "digiteseuemail@email.com"

após gerar, inicie o agent do git

eval $(ssh -agent -s)

esse comando vai deixar o git escultando a chave publica do git gerada anteriormente

ssh-add "id da chave privada"
adiciona a chave privada no git local para ficar comparando as informações e validando a verecidade delas

pronto, com esses passos ja temos as chaves ssh configuradas.
