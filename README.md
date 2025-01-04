<h1>
  <img src="https://github.com/user-attachments/assets/7e5b8e34-81cd-4695-a861-a40cad9187bc9" width="35" />
  Projeto Laravel
</h1>

Este é um projeto desenvolvido com Laravel, utilizando as melhores práticas e conceitos aprendidos no curso Hora de Codar com o instrutor Matheus Battisti.

## Sobre o Projeto
O objetivo deste projeto é fornecer uma aplicação de gerenciamento de dados com autenticação de usuários, interação com o banco de dados e funcionalidades essenciais de CRUD (Create, Read, Update, Delete). Utilizando Laravel como framework, o projeto conta com recursos como autenticação, relações entre modelos, salvamento de imagens e JSON, além de funcionalidades de busca e validações.

## 🚀 Tecnologias Utilizadas
<li>Laravel: Framework PHP robusto e eficiente.
<li>MySQL: Banco de dados utilizado para armazenar informações.
<li>Blade: Motor de templates do Laravel.
<li>Migrations: Estruturas de banco de dados que facilitam a criação e manipulação das tabelas.
<li>Controllers: Lógica de negócio e gerenciamento de dados.
<li>Models: Manipulação e relacionamento dos dados.
<li>Autenticação de Usuários: Criação e gerenciamento de usuários com autenticação segura.
<li>Flash Messages: Mensagens temporárias que são exibidas ao usuário, como mensagens de sucesso ou erro.
<li>Upload de Imagens: Salvamento e manipulação de imagens no banco de dados.
<li>Relações de Modelos: Implementação de relações one-to-many e many-to-many.
<li>Busca e Filtros: Ferramentas de pesquisa avançada para encontrar registros no banco. <br>
    
## Funcionalidades Principais

<li>Autenticação de Usuários: Sistema de login e registro de usuários com autenticação segura.
<li>CRUD de Dados: Criar, Ler, Atualizar e Deletar registros no banco de dados.
<li>Relacionamentos: Relações one-to-many e many-to-many entre os modelos.
<li>Salvamento de Arquivos: Upload de imagens e armazenamento no banco de dados.
<li>Busca e Filtros: Permite realizar consultas filtradas de dados.
<li>Flash Messages: Notificações de sucesso e erro exibidas ao usuário.
<li>Validadores de Formulários: Validação de entradas para garantir dados corretos.

## 📸 Telas 
### Inicial
![image](https://github.com/user-attachments/assets/c5c66ed4-f9c8-4b8f-9a57-67b6d1a1b4be)
![image](https://github.com/user-attachments/assets/e988e30f-7a18-4663-b740-5bd3b077d7b8)
![image](https://github.com/user-attachments/assets/419beb1c-b83d-4206-b710-e00e04800197)

### Criar Evento
![image](https://github.com/user-attachments/assets/89f4010a-d263-4681-a1a4-3aec3143409e)

### Meus Eventos
![image](https://github.com/user-attachments/assets/c8ce975d-5ba0-41c3-9ac2-8e40e9a7f2f8)

### Ver o evento
![image](https://github.com/user-attachments/assets/210f5a9b-89e3-4c0b-99da-215e434bcd92)

## Como Rodar o Projeto
1. Instale as dependências:
`composer install`

2. Configure o ambiente:
Configure o .env com as configurações do seu banco de dados.

3. Gere a chave de aplicação:
`php artisan key:generate`

4. Rode as migrations para criar as tabelas no banco de dados:
 `php artisan migrate`

5. Inicialize o servidor local:
`php artisan serve`

6. Acesse o projeto em seu navegador em http://localhost:8000

