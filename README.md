### App Empresa

# Dashboard

- **Contratos que vencem em 30 dias**
- **Contratos vencidos**
- **Situação de contratos - gráficos**
- **Gráfico de donut - movimentação dos clientes, como estão cadastrados**
  - **Tipos de clientes**
    - Cliente comum
    - Cliente avulso - finaliza ele de forma diferenciada, só operadores específicos podem finalizar chamados de clientes avulsos
    - Cliente bloqueado
    - Fornecedor - vincular o fornecedor no App Chamados

# Menu Lançamentos

- **Clientes**
  - Está cadastrando a empresa que vai abrir chamados
  - Nome fantasia
  - Razão social
  - Email principal
  - Nome do contato principal
  - Telefone
  - Permissões/Configurações
  - Total de solicitantes cadastrados
  - Total de chamados
  - Bloquear para lançamento de chamado
  - **Configurações em massa**
    - **Cliente**
      - Habilitar Cliente para Abertura de Chamados
      - Enviar Emails dos Chamados para os Solicitantes
      - Habilitar Pesquisa de Satisfação para todos Solicitantes desta Empresa
      - Habilitar Abertura de Chamado por Email para todos Solicitantes desta Empresa
      - Habilitar Interação de Chamado por Email para todos Solicitantes desta Empresa
      - Habilitar Abertura de Chamado pelo Portal do Solicitante para todos os Solicitantes desta Empresa
      - Habilitar Interação de Chamado pelo Portal do Solicitante para todos os Solicitantes desta Empresa
      - Habilitar Interação de Chamado para Observadores por Email
      - Habilitar Abertura e Interação de Chamados pelo Chat para todos Solicitantes desta Empresa
      - Avulso
      - Bloquear cliente para atendimento de seus Chamados
      - Motivo do Bloqueio

    - **Visualizar Campos no Portal do Solicitante**
      - Habilitar Tipo de Ocorrência no Portal do Solicitante
      - Habilitar Impacto no Portal do Solicitante
      - Habilitar Urgência no Portal do Solicitante
      - Habilitar Prioridade no Portal do Solicitante
      - Habilitar Categoria no Portal do Solicitante
      - Habilitar Categoria - Tipo
      - Permitir inserir Anexos no Portal do Solicitante e por e-mail
      - Permitir inserir IC's no chamado pelo Portal do Solicitante
      - Grupo de Atendimento

    - **Visualizar Campos Extras no Portal do Solicitante**
      - CPF
      - Campo extra de testes

    - **Catálogos de Serviço**
      - Catálogos de Serviço
      - Permitir o Solicitante Alterar Itens da Categorização na Abertura Chamado
      - Obrigar o uso das Auto-Categorias

    - **Grupo de Empresas**
      - Adiciona/Remove a(s) Empresa(s) selecionada(s) no(s) Grupo(s) de Empresa abaixo.
      - * Caso essa opção de configuração de Grupo de Empresa estiver ativa (Adicionar ou Remover), as outras opções de configurações em massa (acima) não serão executadas.
      - Grupo de Empresa

    - **Tipo de Suporte**
      - Tipo de suporte

    - **Alertas**
      - Horas/Mês
      - Chamados/Mês
      - Mostra Soma de Horas no Chamado
      - Mostra Soma de Horas no Portal do Solicitante
      - **Via Email**
        - Operador
        - Solicitante
        - Quando o tempo do Contrato for Excedido, Envie Alerta de Horas por Email
      - **Por SMS**
        - Operador
        - Solicitante
        - Quando o tempo do Contrato for Excedido, Envie Alerta de Horas por SMS

    - **Pesquisa Avançada**
      - Fornecedor  - Tipo - Matriz
      - Grupo de empresas
      - Empresas
      - Nome fantasia
      - Razão Social
      - Contato
      - CNPJ - CPF
      - Nome
      - Sobrenome
      - Email - Telefone
      - Obs
      - External ID
      - Domínios Permitidos
      - Tipos de suporte
      - Permissão a grupo
      - **Endereço**
        - Cidade - UF

      - **Configurações de Consumo**
        - Horas por mês
        - Chamados por mês

      - **Atividade no Sistema**
        - Clientes com zero chamados
        - Clientes que não abriram chamados no período

## Cadastro de Clientes

### Criar Clientes

#### Cadastro

##### Geral

- Jurídico/Fisíco
- Matriz/Fornecedor
- Grupo de empresa
- Nome fantasia
- Razão Social
- CNPJ
- Contato - contato principal
- Email - email principal
- Telefone - telefone principal
- OBS - toda observação, vai aparecer na tela de chamados. Exemplo: "Melhor horário para contato com os clientes desta empresa é 15h"
- Domínios permitidos - Esse domínio vai possibilitar cadastrar automaticamente do mesmo domínio de email. Exemplo "exemplo.com.br". Quando ela enviar o email para abrir o chamado para você, a desk manager automaticamente vai pegar esse email, converter esse email em um cadastro dentro dessa empresa e abrir um chamado automaticamente para você.
- Idioma - alterar idioma
- Permissão a grupo
- External ID

##### Endereço

- CEP - País
- Endereço - Numero
- Complemento
- Bairro - Cidade - UF

#### Campo Extras

- Pode servir como um formulário, com informações de que plano de assinatura aquele cliente possui
- Pode criar quantos campos extras no app de painel

#### Configurações

- Habilitar Cliente para o Atendimento
- Enviar Emails dos Chamados para os Solicitantes
- Habilitar Pesquisa de Satisfação para todos Solicitantes desta Empresa
- Habilitar Abertura de Chamado por Email para todos Solicitantes desta Empresa
- Habilitar Interação de Chamado por Email para todos Solicitantes desta Empresa
- Habilitar Abertura de Chamado pelo Portal do Solicitante para todos os Solicitantes desta Empresa
- Habilitar Interação de Chamado pelo Portal do Solicitante para todos os Solicitantes desta Empresa
- Habilitar Interação de Chamado para Observadores por Email
- Habilitar Abertura e Interação de Chamados pelo Chat para todos Solicitantes desta Empresa
- Avulso - Nem todos os operadores podem finalizar o chamado de clientes avulsos; todos os solicitantes podem interagir no chamado, só não podem finalizar
- Bloquear cliente para atendimento de seus Chamados - Operadores vão poder interagir em chamados antes do cliente ser bloqueado; o solicitante pode criar chamados mesmo bloqueado, só não vão poder ser atendidos
- Descreva o Motivo de Bloqueio
- Obrigar o uso das Auto-Categorias
  - Habilitar Árvore de Assuntos (Com o recurso ativo será obrigatório o uso de Auto-Categorias no Portal do Solicitante)
    - Habilitar Exibição de Árvore em Blocos
- Gerar Token na Abertura de Chamado - O operador não pode finalizar chamado até que o solicitante passe esse token para o operador (Só o solicitante e os administradores têm acesso a esse token)
- Exibir Cliente no Mapa de Atendimento
- Habilitar o Duplo Fator (SMS) para os Solicitantes desta Empresa
  - Quando esta permissão estiver ativa, todos os Solicitantes desta empresa que tenham seus números de Telefone configurados no Campo: WhatsApp/SMS de seu Cadastro, serão obrigados a inserir um Token que será enviado aos seus respectivos celulares para concluir seu login.
  - Observações Importantes:
    - Se o solicitante não tiver um número cadastrado ele conseguirá logar normalmente.
    - Esta permissão não funcionará caso o Solicitante esteja com o Login Google, Microsoft ou integrado com o LDAP.
  
##### Reabertura de Chamados

- Permitir que Solicitantes Reabram Chamados
  - Bloquear Reabertura via Email
  - Dias para Reabertura do Chamado (Dias Corridos) - Indeterminado
  - Criar chamado filho associado ao chamado finalizado caso ocorra uma tentativa de reabertura via email.
- Tipo de Ocorrência
- Causa
- Observação:
  - Se nenhum valor for especificado em ambos os campos, será possível a reabertura de todos os Chamados, independentemente do seu Tipo de Ocorrência e/ou Causa. Esta configuração é ideal para um cenário onde a flexibilidade é prioritária e todos os chamados, sem exceção, devem ter a possibilidade de serem reabertos para revisão ou atualização.
  - Quando um dos campos estão preenchidos a reabertura fica restrita aos registros preenchidos que correspondam exatamente aos critérios estabelecidos. Ou seja, essa configuração oferece um controle mais refinado, permitindo que apenas Chamados de certos Tipos de Ocorrência e/ou Causas específicas sejam elegíveis para reabertura. Isso pode ser especialmente útil para manter o foco em Chamados que requerem atenção especial ou para evitar a reabertura desnecessária de casos já resolvidos ou irrelevantes.
  - Ambas as Condições se somam caso preenchidas em conjunto.

##### LDAP

- Habilitar LDAP – "O lightweight directory access protocol (LDAP) é um protocolo que ajuda os usuários a localizar dados sobre organizações, pessoas e muito mais. O LDAP tem dois objetivos centrais: armazenar dados no diretório LDAP e autenticar o acesso de usuários a ele."
- Servidor
- Domínio

##### Tipo de Suporte

- Tipo de suporte

##### Envio do Email

Existem 5 regras para esta rotina:

1. Só é possível utilizar o Grupo em um Cliente.
2. É preciso configurar um Redirecionamento de Emails do Email cadastrado neste Grupo de Atendimento para o email do seu prefixo, normalmente: [seuprefixo]@desk.ms.
3. É preciso cadastrar o SMTP no Grupo de Atendimento.
4. Todos emails enviados para este Grupo de Atendimento abrirão chamados no Desk Manager cadastrando os Solicitantes neste Cliente.
5. Todas respostas de Chamados, mesmo que por pessoas de outros Grupos de Atendimento serão disparadas através do SMTP configurado neste Grupo de Atendimento.

- SMTP por Grupo

#### Alertas

- Hora/Mês - Chamados/Mês
- Mostra Soma de Horas no Chamado

#### Portal do Solicitante

##### Default

- Marcar Todos
- Habilitar Tipo de Ocorrência no Portal do Solicitante
- Habilitar Impacto no Portal do Solicitante
- Habilitar Urgência no Portal do Solicitante
- Habilitar Prioridade no Portal do Solicitante
- Habilitar Categoria no Portal do Solicitante
- Habilitar Categoria - Tipo
- Permitir inserir Anexos no Portal do Solicitante e por e-mail
- Permitir inserir IC's no chamado pelo Portal do Solicitante
- Grupo de Atendimento

##### Campos Extras

- Marcar Todos
- CPF
- Campos extra de Testes

#### Aprovação

- Pedir aprovação para os chamados - somente para determinados assuntos no chamado
- Qualquer gerente
- Qualquer Administrador
- Por solicitante
- Habilitar quantidade mínima de aprovadores
  - Quantidade
- Justificar o motivo da aprovação
- Notificar os operadores (em caso de aprovação/reprovação)
  - operadores
- Categorização de status em caso de aprovação
  - Status
- Categorização de status em caso de reprovação
  - Finalizar o chamado em caso de reprovação
  - Forma de atendimento
  - Causa
  - Operador

#### Catálogos de Serviços

- Auto-Categoria - Permitir que o solicitante altere itens da categorização na abertura do chamado
- Obrigar o uso das auto-categorias
- Campo (Restrição) - Usar regra de catálogo para o campo categoria no portal do solicitante
- Catálogos de serviço - catálogo

#### IPs Liberados

- Nome - IP

#### Layout

- Mudar o layout no site do solicitante
- Ativar logo
- CSS

#### Formulário

#### Cadastro Externo de Usuários

```
<form name="deskmanager_cadastrar" action="https://jornaduca.desk.ms/ext/portal/cadastrar/?Portal" method="post"> <input type="hidden" name="desk_prefixo" value="jornaduca"> <input type="hidden" name="desk_caminho_cadastro" value > <input type="hidden" name="desk_caminho_validacao" value> Nome <input type="text" name="desk_nome" maxlength="100"> Sobrenome <input type="text" name="desk_sobrenome" maxlength="100"> Telefone <input type="text" name="desk_telefone" maxlength="100"> Email <input type="email" name="desk_email" > <input type="hidden" name="desk_departamento" value > <input type="hidden" name="desk_local" value > <input type="hidden" name="desk_codigo_cliente" value > <input type="submit" value="OK"> </form>
```

## Solicitante

### Criar Solicitantes

#### Cadastro

- Cliente
- Email
- Senha - Confirmar senha
- Nome - Sobrenome
- Departamento
- Local
- Telefone - Ramal
- WhatsApp/SMS - Telegram

##### Avançado

- Prioridade
- Centro de custo
- Centro de custo adicional
- Aniversário Dia - Mês
- Observação
- Login AD
- authorTag Discord

##### Campos Extras

- (Nenhum campo extra especificado)

#### Permissões

- Habilitar Acesso ao Sistema
  - Gerente de Departamento desta Empresa
    - Com esta permissão o Solicitante será Gerente do Departamento selecionado na aba Cadastro deste formulário. Ele pode visualizar todos os chamados dos Solicitantes que pertencem ao seu Departamento e também pode ser incluído como Aprovador para chamados que necessitem da Aprovação de Solicitantes Gerentes.
  - Administrador desta Empresa
    - Assim como o Gerente, o Administrador poderá visualizar todos os chamados dos Solicitantes de sua Empresa. Sendo assim uma Permissão Superior ao Gerente. Ele também será incluído como Aprovador para chamados que necessitem da Aprovação de Solicitantes Administradores.
  - Solicitante VIP
    - Os Solicitantes VIP são aquelas pessoas que você deseja sinalizar, tanto indicando um SLA específico para ele como uma identificação visual na Lista de Chamados e dentro de seu Chamado. Sendo assim, podendo distingui-los de outros Solicitantes.
  - Aprovador Superior
    - O solicitante com a permissão de "Aprovador Superior" possui autoridade para sobrepor decisões e acelerar o fluxo de aprovação, garantindo maior agilidade e eficiência na tomada de decisões. Recomenda-se atribuir esta permissão apenas a solicitantes com posição hierárquica mais elevada ou com comprovada experiência e autonomia dentro da organização.
  - Aprovação Inter-Empresa
    - O solicitante com a permissão de "Aprovação Inter-Empresa" permite que um solicitante de uma empresa possa aprovar chamados de outra empresa. Quando esta permissão está ativada, um solicitante de qualquer empresa, mesmo que não pertença à empresa que abriu o chamado, pode ser selecionado para aprovar o andamento do chamado. Isto permite uma maior flexibilidade e cooperação entre empresas diferentes, mas deve ser usada com cuidado para evitar confusões, erros de aprovação ou falhas de segurança.
  - Aprovador de Grupo de Empresas
    - A permissão "Aprovador do Grupo de Empresas" permite que um Solicitante Aprovador possa revisar e aprovar chamados de outras empresas que fazem parte do mesmo grupo de empresas ao qual ele está vinculado. Por favor, note que esta permissão não concede acesso a aprovar chamados de empresas que não pertencem ao grupo de empresas do solicitante.
  - Ocultar este Solicitante da Lista de Abertura para Operadores
    - Como a própria Permissão diz ela bloqueia Operadores para que eles não possam selecionar um determinado Solicitante na abertura de um chamado. Isso para garantir a segurança de operações focadas em ESM onde um diretor ou superior hierárquico pode estar disponível.
  - Permitir criação de novos Solicitantes no Portal de Solicitantes
    - Com esta permissão marcada um Solicitante (Não importa a Hierarquia) pode criar um novo Solicitante através do Portal do Cliente. Note que ele só poderá criar Solicitantes para o seu departamento (caso seja um solicitante comum ou gerente) e para qualquer departamento se for um Administrador.
  - Permitir adicionar Observadores no Portal do Solicitante
  - Visualizar SLAs Contratuais no Portal do Solicitante
    - Com esta permissão ativa o Solicitante pode visualizar os SLAs de contratos de sua Empresa dentro do Portal do Solicitante. Esta exibição será realizada no Grid de Solicitantes.
  - Visualizar SLAs Internos no Portal do Solicitante
    - Com esta permissão ativa o Solicitante pode visualizar os SLAs de Internos de sua Empresa dentro do Portal do Solicitante. Esta exibição será realizada no Grid de Solicitantes.
  - Unificar Visualização de Portal do Solicitante para Multi-Empresa
    - Ao unificar a visualização de um Solicitante Multi-Empresa, ele deixa de poder escolher a empresa que deseja se logar no Portal do Solicitante e passa a escolher o solicitante que deseja abrir o chamado, dentre todas as empresas que ele está cadastrado.
    - Caso os Solicitantes marcados como Unificados tenham configurações de acessos diferentes entre seus cadastros (Ex.: 1 solicitante é Administrador e outro é Gerentes ou solicitante comum) implicará no não carregamento dos seus Chamados no Portal do Solicitante. Portanto, verifique sempre as permissões para que os Solicitantes tenham acessos iguais mesmo cadastrados em mais de uma empresa.
   
    - ## Configurações Gerais (Minhas Anotações sobre o comentário acima)

### Alerta

- Enviar Boas Vindas para Este Solicitante
- Receber Emails de Abertura e Interação dos meus Chamados
- Receber apenas Emails de Abertura e Finalização de Chamados para este Solicitante
- Receber Pesquisa de Satisfação por Email e pelos Canais de Conversa para este Solicitante
- Obrigar resposta da Pesquisa de Satisfação para abertura de novos Chamados
- Receber Emails de Notificações para este Solicitante
- Receber SMS de Abertura e Interação de Chamados para este Solicitante

### Login

- Forçar a Mudança de Senha para este Solicitante
- Permitir que este Solicitante atualize seus dados pessoais no Portal do Solicitante
- Ativar o acesso via Conta Google para este Solicitante
- Ativar o acesso via Conta Microsoft para este Solicitante
- Bloquear o Login Local com a conta do Desk Manager para este Solicitante

## Endereço

- CEP
- Endereço - Numero
- Complemento
- Bairro - Cidade - UF

# Contratos

- Na tela de contrato tem: Nome - Labels - Cliente - Data de Início - Data final - Custo - Anexos

## Criar Contratos

- Nome
- Modelo de contratos
- Cliente
- Catálogos de serviço

### Avançado

- Forma de recebimento
- Unidade
- Classificação
- Fornecedor
- Matrícula
- Total de Horas
- Centro de Custo
- Centros de custo adicionais
- Link externo
- Data de emissão
- Labels de contratos
- Campos extras{}

### Detalhes do contrato

- Início - Fim

#### Alerta

- Enviar alertas em dias
- Template(Chamado)
- Enviar após o vencimento - sim/nao
- Custo
- Termos especiais
- Descrição

#### Permissão ao operador

- Adicionar operador

#### Solicitantes Responsáveis

- Adicionar solicitante

#### Grupo de empresa

- Grupo de empresas

#### Anexos
- Adicionar Anexos

#### Custo de Serviços

- Bloquear abertura de chamado com a vigência expirada

# Menu Cadastro

## Grupo de Empresas

- Nome
- Empresas (Bom para a visualização de relatórios e especificação de dados)

## Departamentos

- Nome

## Grupo de Aprovadores

- Nome
- Complemento
- Solicitantes

## Locais

- Nome

## Cadastro Rápido de Solicitantes

- Departamento
- Local
- Forçar mudança de senha
- Enviar boas vindas
- Receber pesquisa de satisfação por email e conversas
- Administrador
- Gerente
- Logar com Google/Microsoft account
- Enviar alerta por email

## Criar modelo de contratos

- Nome
- Custo
- Enviar alerta em
- Termos especiais
- Descrição

## Criar tipo de suporte

- Nome
- Observações

## Criar labels de contratos

- Nome

## Criar campos extras

- Nome
- Label opcional
- Label explicação (opcional)
- Lista
- Tipo
- Permissão a grupo
- Avançado (Não exibir este campo extra na pesquisa avançada de chamados/gmuds)

# Configurações

## Relatório de contratos

- Nome
- Tipo - Contratos são relatórios que foram criados, Históricos são relatórios que foram renovados
- Operadores
- Grupos
- Dashboard adicional - exibir no dashboard sim/nao - ícone

### Colunas

- Colunas(O que, como, pra quem)

  - Dados

### Filtros

- Adicionar filtros para mostrar as respectivas informações

### Ordem

- Ordem de dados

### Envio Programado

- Programar o envio do relatório por: Hora, Dias do mês, Mês, Dias da semana, Ano

### Detalhes do email

- Mensagem
- Enviar email para - operador, solicitantes
