Projeto Integrador III – UNIVESP
Grupo 012
Sistema Web para Gestão Empresarial
📌 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina Projeto Integrador III da UNIVESP.

O objetivo foi desenvolver uma aplicação web utilizando framework, banco de dados, linguagem de script, integração com nuvem e práticas modernas de desenvolvimento de software, dada esta emenda, o grupo resolveu continuar e aprimorar o projeto integrador II

O sistema foi projetado para resolver problemas reais de gestão empresarial por meio da digitalização de processos, permitindo maior organização, controle de dados e geração de informações estratégicas.

🎯 Objetivos Atendidos

O projeto contempla os seguintes requisitos da disciplina:

✅ Resolução de problemas reais

✅ Levantamento e análise de requisitos

✅ Desenvolvimento web com framework

✅ Banco de dados integrado

✅ HTML e CSS

✅ Linguagem de script (JavaScript)

✅ Controle de versão com Git e GitHub

✅ Deploy em nuvem

✅ API (uso e/ou fornecimento)

✅ Acessibilidade

✅ Integração Contínua

✅ Testes

✅ Análise de dados

🧠 Problema Identificado

Muitas empresas ainda realizam controle de informações manualmente ou em planilhas isoladas, o que gera:

Perda de dados

Falta de padronização

Dificuldade na geração de relatórios

Baixa rastreabilidade das informações

O projeto propõe uma solução digital centralizada e acessível via navegador.

🛠️ Tecnologias Utilizadas
Front-end

HTML5

CSS3

JavaScript

Back-end

Framework web Django

Banco de Dados PostgreSQL

Versionamento

Git

GitHub

Nuvem Google Cloud

Integração Contínua

GitHub Actions

🧩 Funcionalidades Principais

Cadastro de usuários

Cadastro e gerenciamento de registros

Edição e exclusão de dados

Autenticação (se implementada)

Geração de relatórios

Dashboard com análise de dados

API para integração externa

🔌 API

O sistema disponibiliza (ou consome) uma API para:

Consulta de dados

Cadastro de registros

Integração com outros sistemas

Exemplo de endpoint:

GET /api/registros
POST /api/registros
☁️ Deploy em Nuvem

A aplicação durante o processo de desenvolvimento e avaliação do projeto estava hospedada em ambiente de nuvem, garantindo:

Alta disponibilidade

Acesso remoto

Escalabilidade

♿ Acessibilidade

Foram aplicadas boas práticas de acessibilidade:

Uso correto de tags semânticas HTML

Contraste adequado de cores

Responsividade

Compatibilidade com leitores de tela

🧪 Testes

Foram implementados:

Testes unitários

Testes de integração

Validações no front-end

A automação é executada via integração contínua.

📊 Análise de Dados

O sistema permite:

Visualização de dados consolidados

Geração de métricas

Apoio à tomada de decisão

🔄 Controle de Versão

O projeto utiliza:

Versionamento com Git

Repositório no GitHub

Controle de branches

Histórico de commits documentado


# Projeto integrador 3 Univesp Grupo 12

# Preparando o ambiente

Comece iniciando o ambiente virtual

```
$ python -m venv projeto
```

Isso ira criar o ambiente virtual do projeto, sendo este nomeado como "projeto" nesse caso

AVISO, no caso do gitignore não funcionar, rodar o comando no root chamando o venv de "projeto" deve, em casos normais, passar por cima do venv incorreto, e permitir rodar o projeto

### Ative o ambiente virtual

No diretório raiz do projeto, execute o comando, de acordo com sua necessidade:

Linux:

```
$ source venv/bin/activate
```

Windows:

```
$ venv\Scripts\activate
```

Windows PowerShell:

```
$ venv\Scripts\Activate.ps1
```

Instale os pacotes necessários, sendo os seguintes:

-Django
-Django-admin-interface
-psycopg2
-psycopg2-binary

Usando os comandos

pip install Django
pip install Django-admin-interface
pip install psycopg2
pip install psycopg2-binary


