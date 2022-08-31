### Projeto CRUD Frases

* Criar frases
* Ler frases
* Ler uma frase especifica
* Atualizar frases
* Deletar uma frase

# Orientações para utilizar a API
Para instalar as dependencias
`npm install`

## Criar o banco de dados
CREATE TABLE `phrase` (
    `author` varchar(100) NOT NULL,
    `id` int(11) NOT NULL,
    `txt` text NOT NULL
) ENGINE=InnDB DEFAULT CHARSET=utf8mb4;