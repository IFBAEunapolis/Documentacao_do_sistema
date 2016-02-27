2.2. Detalhamento dos casos de uso
===

## **Caso de Uso: [ UC-01 ] - Efetuar Login**

### Descrição: Este caso de uso especifica a ação de autenticação que um usuário
executa no sistema, com objetivo de se conectar na aplicação. Apenas usuários
cadastrados podem se autenticar no sistema. O usuário fornece seus dados básicos
de autenticação e, após a validação no sistema, o usuário torna-se apto a realizar
operações da área restrita do sistema. Os usuários se dividem em: a) cliente
(usuário habilitado a comprar pacotes de viagem pelo sistema), b) operador
(usuário que opera o sistema, habilitado a manter os cadastros do portal e
consultar os pacotes adquiridos pelos clientes), c) administrador (usuário
habilitado a realizar as configurações de segurança e ações de administração do
sistema).

### Atores: 

Cliente, Operador, Administrador

### Pré-condições:
1. O ator deve estar cadastrado no sistema.

###Pós-condições:
1. O ator fica habilitado a realizar ações na área restrita do sistema.

### Requisitos funcionais:

1. RF28. O portal deve prover uma interface para clientes, operadores
e administradores se autenticarem no sistema

### Requisitos não funcionais:

1. RNF01- O portal deve registrar em um log as operações realizadas no sistema para permitir auditoria

2. RNF06. Impedir acesso ao sistema a usuários bloqueados

3. RNF12. As senhas de usuários devem ser armazenadas
de forma criptografada.

### Fluxo Básico:

1. O ator decide se autenticar no sistema.
2. O sistema solicita as informações obrigatórias para a autenticação(
        1. E-mail
        2. Senha
3. O ator informa os dados de autenticação.
4. O sistema valida os dados de autenticação.
5. O sistema registra em histórico (log) a autenticação realizada pelo ator. Os seguintes dados são armazenados:
        1. Usuário
        2. Grupo de Usuário
        3. Data
6. O sistema habilita as ações relacionadas ao grupo de suário ao qual pertence o ator.
7. O sistema informa que a autenticação foi realizada com sucesso.
O caso de uso se encerra.

###Fluxo Alternativo:

1. No passo 4 do Fluxo Básico, caso haja algum erro na autenticação
relacionado aos dados informados:
2. O sistema informa o erro ao ator.
3. O fluxo retorna ao passo 2 do fluxo básico.
Fluxo Alternativo B:
1. No passo 4 do Fluxo Básico, caso o sistema identifique que ator está
bloqueado:
2. O sistema informa o erro ao ator.
3. O fluxo retorna ao passo 2 do fluxo básico.
Fluxo Alternativo C:
1. No passo 1 do Fluxo Alternativo A, caso aconteça o erro de autentica-
ção após um número configurável de tentativas:
2. O sistema bloqueia o ator.
3. O sistema registra em histórico (log) o bloqueio do ator.
4. O sistema informa o erro ao ator.
5. O fluxo retorna ao passo 2 do fluxo básico.
