# HandsOn3

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=laVieApi&uri=https%3A%2F%2Fraw.githubusercontent.com%2FNeryVictor%2FtestFiles%2Fmain%2FinsomniaButton)

<p align="center">
<a href= "#-Project">Project</a> .
<a href= "#-Client">Client</a> .
<a href= "#-Authors">Authors</a> .
<a href= "#-Technology and Dependency used">Technology and Dependency used</a> .
</p>

🖥️ Project
===============
 Projeto do bootcamp de desenvolvimento web Gama XP #43 para desenvolver habilidades backend com NodeJs e SQL.
 
✨ Client
===============
Um grupo de psicólogos criau a
clínica La Vie - Saúde Mental que oferece
diversos tipos de terapia.

Para ajudar nos atendimentos, eles precisam de uma API que permita criar registros de
psicólogos, pacientes e prontuários. Em uma conversa com os Front-end e os PO foram
decididos alguns grupos de endpoints a serem gerados.

![lavie](https://user-images.githubusercontent.com/106200173/181382023-b3424979-d826-43fc-a45e-2df175a1b66f.png) 

🏗️ Authors
=================
- [x] Victor Nery
- [x] Giordano Cassini 
- [x] João Marcelo Dantas  
- [x] Lucas Gomes Noronha Canuto

📝 Features Created
=====================
* Buscar psicologos, pacientes e atendimentos (individual e total)
* Cadastrar psicologos, pacientes e atendimentos
* Editar psicologos e pacientes
* Excluir psicologo e pacientes

🚀 Technology and Dependency used
=================
Este projeto foi desenvolvido com as seguintes tecnologias:

<table>
<tr>
<td>NodeJS</td>
<td>Express</td>
<td>Express-validator</td>
<td>Sequelize</td>
<td>MySQL</td>
<td>MySQL2</td>
</tr>

<tr>
<td>18.5.0</td>
<td>4.18.1</td>
<td>6.14.2</td>
<td>6.21.3</td>
<td>2.18.1</td>
<td>2.3.3</td>
</tr>
</table>

Para clonar e executar este aplicativo, você precisará do [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/), Express, Express-validator,[MySQL](https://www.mysql.com/) e Mysql2 + npm instalado em seu computador.
É recomendado ter um editor para trabalhar com codigo como [VSCode](https://code.visualstudio.com/).

#### Referencia de linha de comando:

## Install API

```bash
# Clone this repository
$ git clone https://github.com/giordanocassini/handsOn3.git

# Install dependencies
$ npm install

# Start server
$ npm run dev

# running on port 3500
```
## Banco de Dados

A equipe também ficou responsável por criar o banco de dados;
Gerando DER e script SQL que gera o banco.


## Funcionalidades Opcionais

Dashboard
Deverá ser criados um grupo de endpoints a partir da rota /dashboard para cada tipo de
informação presente nesta lista:
- Número de pacientes
- Número de atendimentos
- Número de psicólogos
- Média de atendimentos por psicólogos
Ficando por exemplo: /dashboard/numero-paciente. Os dados a serem retornando
podem ser apenas os números dos resultados em si!
## API Reference
