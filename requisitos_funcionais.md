#1.3. Requisitos Funcionais

###1.3.1. Dos cursos

| **CODIGO**     | RF001   |
| :------:      | :---------- |
|  **NOME**     | Cadastrar  Curso|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** | <p style="text-align:justify"> É importante para todo sistema manter os cursos da instituição no sistema pois ele representa a primeira entidade/camada a ser cadastrada.</p> |

| **CODIGO**     | RF002  |
| :------:      | :---------- |
|  **NOME**     | Consultar de Curso|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** | <p style="text-align:justify"> Fazer a consulta de cursos será um processo importante na associação do mesmo com alguma outra entidade.</p> |

| **CODIGO**     | RF003  |
| :------:      | :---------- |
|  **NOME**     | Apagar Curso|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** |  <p style="text-align:justify">Essa funcionalidade se faz necessária no caso da instituição optar por retirar uma oferta de curso.</p> |

###1.3.2. Dos Locais Físicos

| **CODIGO**     | RF004   |
| :------:      | :---------- |
|  **NOME**     | Cadastrar Local Físico|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** | <p style="text-align:justify"> É necessário manter os dados dos locais físicos pois para que as aulas sejam dadas é necessário que a sala comporte os alunos matriculados na disciplina.</p> |

| **CODIGO**     | RF005  |
| :------:      | :---------- |
|  **NOME**     | Consultar Locais Físicos|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** |  <p style="text-align:justify">Haverão momentos em que será preciso saber quais locais estão disponíveis para dar aula.</p> |

| **CODIGO**     | RF006  |
| :------:      | :---------- |
|  **NOME**     | Apagar Locais Físicos|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** |  <p style="text-align:justify">A instituição pode passar por reformas e por isso alguns locais físicos podem deixar de existir.</p> |

###1.3.2. Dos Períodos

| **CODIGO**     | RF004   |
| :------:      | :---------- |
|  **NOME**     | Cadastrar Período|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** | <p style="text-align:justify"> É necessário manter os dados dos locais físicos pois para que as aulas sejam dadas é necessário que a sala comporte os alunos matriculados na disciplina.</p> |

| **CODIGO**     | RF005  |
| :------:      | :---------- |
|  **NOME**     | Consultar Período|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** |  <p style="text-align:justify">Haverão momentos em que será preciso saber quais locais estão disponíveis para dar aula.</p>|

| **CODIGO**     | RF006  |
| :------:      | :---------- |
|  **NOME**     | Apagar Período|
|  **NIVEL**     |Essencial|
|  **DESCRIÇÃO** |  <p style="text-align:justify">A instituição pode passar por reformas e por isso alguns locais físicos podem deixar de existir.</p> |





> 



























**NOME:** [RF001] Cadastrar Usuário

**DESCRIÇÃO:** Realizar o cadastro de usuário no sistema inserindo os dados de (nome, matrícula, Setror de lotação, Login e Senha)e armazenando os dados no banco de dados.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema

**SAIDA:** Mensagem confirmando o cadastro

---

**NOME:** [RF002] Alterar Usuário

**DESCRIÇÃO:** Realiza a alteração dos do cadastro de usuário no sistema, podendo ser manipulados (nome, matrícula, Setror de lotação, Login e Senha.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca de usuário pelo nome

**SAIDA:** Mensagem confirmando a alteração dados.

---

**NOME:** [RF003] Excluir Usuário

**DESCRIÇÃO:** Apaga os dados do  usuário cadastrado no sistema.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca de usuário pelo nome

**SAIDA:** Mensagem confirmando a exlusão do  usuário.


###2.2. Dos do Departamento

**NOME:** [RF004] Cadastrar Departamento

**DESCRIÇÃO:** Realizar o cadastro do departamento inserindo os dados (nome, sigla, email, telefone e ramal  e chefe) e armazenando informações no banco de dados.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema

**SAIDA:** Mensagem confirmando o cadastro

---

**NOME:** [RF005] Alterar Departamento

**DESCRIÇÃO:** Realiza a alteração dos dados do departamento no sistema, podendo ser manipulados os dados (nome, sigla, email, telefone e ramal  e chefe).

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca do  departamento pelo nome

**SAIDA:** Mensagem confirmando a alteração dados.

---

**NOME:** [RF006] Excluir Departamento

**DESCRIÇÃO:** Apaga os dados do  usuário cadastrado no sistema.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca de usuário pelo nome

**SAIDA:** Mensagem confirmando a exlusão do  usuário.

###2.3. Dos do Item

**NOME:** [RF007] Cadastrar Item

**DESCRIÇÃO:** Realizar o cadastro do Item  inserindo os dados (nome, descrição, unidade, categoria, tipo) e armazenando informações no banco de dados.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema

**SAIDA:** Mensagem confirmando o cadastro

---

**NOME:** [RF008] Alterar Item

**DESCRIÇÃO:** Realiza a alteração dos dados do item no sistema, podendo ser manipulados os dados (nome, descrição, unidade, categoria, tipo).

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca do  item pelo nome

**SAIDA:** Mensagem confirmando a alteração dados.

---

**NOME:** [RF009] Excluir Item

**DESCRIÇÃO:** Apaga os dados do  usuário cadastrado no sistema.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca de usuário pelo nome

**SAIDA:** Mensagem confirmando a exlusão do  usuário.

###2.3. Da Requisição 

**NOME:** [RF010] Nova Requisição 

**DESCRIÇÃO:** Realizar o cadastro de uma requisição inserindo os dados (tipo, data, resumo da contra, categoria, tipo) e armazenando informações no banco de dados.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema

**SAIDA:** Mensagem confirmando o cadastro

---

**NOME:** [RF011] Alterar Item

**DESCRIÇÃO:** Realiza a alteração dos dados do item no sistema, podendo ser manipulados os dados (nome, descrição, unidade, categoria, tipo).

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca do  item pelo nome

**SAIDA:** Mensagem confirmando a alteração dados.

---

**NOME:** [RF012] Excluir Item

**DESCRIÇÃO:** Apaga os dados do  usuário cadastrado no sistema.

**PRIORIDADE:** Essencial

**ENTRADA:** Autenticação do usuário no sistema e busca de usuário pelo nome

**SAIDA:** Mensagem confirmando a exlusão do  usuário.

