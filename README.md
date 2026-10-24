Plataforma de Acolhimento, Orientação e Resposta Rápida no Combate à Violência Contra a Mulher

Projeto acadêmico em equipe, orientado pelo prof. Álvaro Machado Júnior (@profalvaromjunior), que reúne backend, front-end, chatbot e documentação para apoiar mulheres em situação de violência doméstica.

Princípios do projeto: toda a ajuda, os guias e a busca de locais públicos de apoio funcionam sem login. O cadastro é opcional e serve apenas para contatos de emergência e diário de evidências. Banco de dados em PostgreSQL + PostGIS para localizar serviços de proteção próximos.

Repositório original: plataforma-acolhimento-vcm

Minha participação:fiquei responsável pelo banco de dados.

Utilizamos o PostgreSQL com PostGIS para calcular distâncias no mapa.

Organizei os dados em quatro tabelas: usuárias, serviços, contatos de confiança e diário de evidências.

Também cuidamos da segurança, protegendo as senhas, criptografando o diário e identificando possíveis alterações nos registros.

Eu e a Dayene trabalhamos juntas na defesa técnica do back-end.
