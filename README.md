# APP_Projeto_IS

Projeto foi desenvolvido para a disciplina de Integração de Sistemas do curso de Engenharia de Informática com o objetivo de criar um middleware orientado a serviços para fins de IoT

O objetivo do projeto era criar um middleware que permitisse a criação, leitura, atualização e exclusão de Aplicações e Containers, a criação e exclusão de Subscriptions e a criação e exclusão de Dados. 

Para criar um Container, é necessário selecionar uma Aplicação. Dessa forma, cada Aplicação pode ter entre 0..N Containers. 
O mesmo acontece com a Subscription e Dados, uma Aplicação e Container precisam ser selecionados. Cada Container pode ter entre 0..N, Dados pode ter entre 0..N Subscriptions.

O middleware pode criar quantas aplicações o utilizador pretender e tem uma profundidade máxima de 3 níveis (Containers, Subscription e Dados). 

A URL do serviço web começa com http://<domain:port>/api/somiod.

 
