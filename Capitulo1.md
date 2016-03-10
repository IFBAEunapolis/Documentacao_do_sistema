Documento de Requisitos de Software
---

Este documento especifica os requisitos do sistema Teacher Timetable, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

###2.1. Visão geral do documento

Além desta seção introdutória, as seções seguintes estão organizadas como descrito abaixo.

Seção 2 – Descrição geral do sistema: apresenta uma visão geral do sistema, 
caracterizando qual é o seu escopo e descrevendo seus usuários.

Seção 3 – Requisitos funcionais (casos de uso): especifica todos os casos de uso do sistema, descrevendo os fluxos de eventos, prioridades, atores, entradas e saídas de cada caso de uso a ser implementado. 

Seção 4 – Requisitos não-funcionais: especifica todos os requisitos não funcionais do sistema, divididos em requisitos de usabilidade, confiabilidade, desempenho, segurança, distribuição, adequação a padrões e requisitos de hardware e software.

Seção 5 – Referências: apresenta referências para outros documentos utilizados para a confecção deste documento.

###2.1.1 Convenções, termos e abreviações

A correta interpretação deste documento exige o conhecimento de algumas convenções e termos específicos, que são descritos a seguir.

####2.1.2. Identificação dos requisitos

Por convenção, a referência a requisitos é feita através do nome da subseção onde eles estão descritos, seguidos do identificador do requisito, de acordo com a especificação a seguir:

     [nome da subseção. identificador do requisito]

Por exemplo, o requisito funcional [Recuperação de dados.RF016] deve estar descrito em uma subseção chamada “Recuperação de dados”, em um bloco identificado pelo número [RF016]. Já o requisito não-funcional [Confiabilidade.NF008] deve estar descrito na seção de requisitos não-funcionais de Confiabilidade, em um bloco identificado por [NF008]. 

Os requisitos devem ser identificados com um identificador único. A numeração inicia com o identificador [RF001] ou [NF001] e prossegue sendo incrementada à medida que forem surgindo novos requisitos.

#### 2.1.3. Prioridades dos requisitos

Para estabelecer a prioridade dos requisitos, nas seções 4 e 5, foram adotadas as denominações “essencial”, “importante” e “desejável”. 

*  **Essencial:** é o requisito sem o qual o sistema não entra em funcionamento. Requisitos essenciais são requisitos imprescindíveis, que têm que ser implementados impreterivelmente.

* **Importante:** é o requisito sem o qual o sistema entra em funcionamento, mas de forma não satisfatória. Requisitos importantes devem ser implementados, mas, se não forem, o sistema poderá ser implantado e usado mesmo assim.

* **Desejável:** é o requisito que não compromete as funcionalidades básicas do sistema, isto é, o sistema pode funcionar de forma satisfatória sem ele. Requisitos desejáveis podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá-los na versão que está sendo especificada. 

####2.2 Descrição geral do sistema




 [RF001] Criar Regra

Descrição do requisito: Este permite que o administrador crie e armazene um novo 

componente no sistema.

Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: Deverá estar logado como administrador.

Saídas e pós-condição: um componente é cadastrado no sistema

 [RF002] Excluir Regra

Descrição do requisito: Este permite que o administrador exclua um componente do cadastro 

de componentes do sistema. 

Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: recebe como entrada o componente que se deseja excluir

Saídas e pós-condição: o usuário consegue excluir o componente que deseja

[RF003] Alterar Regra

Descrição do requisito: Este permite que o administrador altere os dados de um componente.

Documento de Requisitos

Arquivo: documentoRequisitos.doc 

Última Atualização: 18/02/2016 11:46:00 h 

Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: recebe como entrada o componente que se deseja alterar.

Saídas e pós-condição: um componente é alterado no sistema.

3.1 Criar horário

 [RF001] Modalidade do curso

Descrição do requisito: Este permite que o usuário visualize as modalidades de cursos 

disponíveis para seleção, tais como, SUPERIOR< SUBSEQUENTE, INTEGRADO..

Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: não tem.

Saídas e pós-condição: A modalidade do curso é selecionada e a próxima etapa é ativa.

 [RF002] Escolha do curso

Descrição do requisito: Este permite que o usuário visualize todos os cursos disponíveis de 

acordo com a modalidade do curso escolhida e selecione o (s) que for (em) de seu interesse.

Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: A modalidade do curso deve ter sido escolhida (RF002).

Saídas e pós-condição: o usuário visualiza as disciplinas selecionadas.

 [RF003] Escolha do período

Descrição do requisito: Este permite que o usuário escolha o período ao qual deverá lecionar 

de acordo com a modalidade do curso selecionada.


---



---


Prioridade:  Essencial  Importante  Desejável 

Entradas e pré-condições: a modalidade do curso deve estar definida (RF001).

Saídas e pós-condição: O período é selecionado e as disciplinas estarão disponíveis de 

acordo com a tipo do curso escolhido.

 [RF004] Escolha de disciplinas

---



---

