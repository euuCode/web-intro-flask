# 🚀 Meu Primeiro App Flask

Este projeto é uma introdução prática ao microframework **Flask** com Python. Ele foi desenvolvido como parte de uma atividade para entender o funcionamento de rotas, templates HTML com Jinja2, retorno de dados em JSON, tratamento de formulários (GET/POST) e tratamento de erros.

---

## ⚙️ Tecnologias Utilizadas

- Python 3.x
- Flask
- Jinja2 (engine de template do Flask)

---

## 📌 Funcionalidades e Rotas

| Rota              | Descrição                                                                 |
|-------------------|--------------------------------------------------------------------------|
| `/api`               | Retorna uma mensagem em formato JSON                                     |
| `/hello/`         | Retorna um HTML padrão com saudação genérica                             |
| `/hello/<nome>`   | Retorna um HTML personalizado com o nome passado pela URL                |
| `/show/<int:id>`  | Retorna uma mensagem com o número passado como parâmetro                 |
| `/login` (GET)    | Exibe um formulário HTML                                                 |
| `/login` (POST)   | Processa os dados enviados e exibe uma mensagem de confirmação           |
|  `/qualquercoisa`        | Exibe um HTML personalizado em caso de rota inexistente                 |

---
## 🧠 Aprendizados
Como criar rotas com e sem parâmetros

Como retornar JSON e HTML dinâmico

Como usar Jinja2 para renderizar templates com variáveis

Como lidar com formulários usando métodos GET e POST

Como personalizar páginas de erro (ex: 404)

## 👨‍💻 Autor
Feito com 💻 e curiosidade por [Márcio Ferreira].
Desenvolvido como parte da atividade “Primeiro Contato com o Flask”.

