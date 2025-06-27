# jogo-da-velha

# 🎮 Jogo da Velha Web - Projeto de Extensão

Este é um projeto web completo de um **Jogo da Velha (Tic-Tac-Toe)**, desenvolvido com foco em front-end, back-end e integração com banco de dados.  
O sistema conta com cadastro, login, histórico de partidas, replay e modo contra IA.

## ✅ Funcionalidades
- 🎮 Jogabilidade direto no navegador  
- 🤖 Modo contra Robô (IA simples)  
- 🕹️ Histórico de partidas com resultados detalhados  
- 🔁 Replay das partidas (visualização lance a lance)  
- 🔐 Login e cadastro com **criptografia de senha**  
- 💾 Integração com banco de dados para salvar partidas e usuários  

## 💻 Tecnologias Utilizadas
- **PHP** – Back-end principal  
- **HTML, CSS, JavaScript** – Interface e lógica do usuário  
- **SQL Server (SSMS)** – Banco de dados com tabelas normalizadas  
- **XAMPP (Apache + PHP)** – Ambiente de desenvolvimento local  

## 🛡️ Segurança
- Senhas armazenadas com **criptografia (bcrypt)**  
- Boas práticas de segurança em login e validação  
- Proteção contra acesso não autorizado  

## 📂 Estrutura do Projeto
/index.php → Tela principal do jogo da velha
/login.php → Página de login de usuário
/cadastro.php → Página de cadastro
/logout.php → Realiza logout e finaliza a sessão
/replay.php → Exibe replay das partidas jogadas
/historico.php → Histórico de partidas do usuário
/db.php → Conexão com o banco de dados (SQL Server)

## 📌 Objetivo do Projeto
Este projeto tem como objetivo aplicar os conhecimentos adquiridos nas disciplinas de:  
- Desenvolvimento - Web  
- Banco de Dados - SQL 
- Infraestrutura - Windows  
- Segurança - Web 

Trata-se de um sistema completo com front-end, back-end, persistência de dados e segurança, simulando um cenário real de aplicação web funcional e integrada.

## 📦 Como executar localmente
> 1. Instale o **XAMPP**  
> 2. Coloque os arquivos do projeto em `htdocs/jogo-da-velha`  
> 3. Ative o **Apache** no painel do XAMPP  
> 4. Certifique-se de que o SQL Server está ativo e o banco `jogodavelha` foi importado  
> 5. Acesse `http://localhost/jogo-da-velha/cadastro.php` no navegador  

## 📸 Imagens do Projeto
> 1. Tela de cadastro
![image](https://github.com/user-attachments/assets/ac8969d9-b006-4e8e-95fa-d547df3575cd)
> 2. Tela de login
![image](https://github.com/user-attachments/assets/f5ce1b4f-ce00-4769-b67b-8f414d7bc6e4)
> 3. Tela inicial (index.php)
![image](https://github.com/user-attachments/assets/b140cd19-075a-46e1-b6fd-645c0c1d35b6)
> 4. Histórico de partidas
![image](https://github.com/user-attachments/assets/8d7b1e42-78f3-4c05-bdb5-bac8e1c300b2)
> 5. Tela de replay
![image](https://github.com/user-attachments/assets/6cae6c60-7f83-4170-a518-a798cfe8145b)
> 6. Banco de dados (SSMS; #### 🔐 Tabela de usuários com senhas criptografadas via bcrypt)
![image](https://github.com/user-attachments/assets/59140ef8-7d45-41e8-8dae-4b85297fe0ab)

## 🙋‍♂️ Desenvolvido por
- **Gustavo dos Santos Paes** – Banco de Dados - Infraestrutura - Segurança - Desenvolvimento (Front-end e Lógica)
