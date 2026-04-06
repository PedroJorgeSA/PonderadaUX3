# Teste de Funil — Cadastro de Novo Local

**Plataforma:** SuzFogo — Sistema de Gestão de Incêndios Florestais  
**Data:** Abril de 2026  
**Módulo avaliado:** Cadastro de Locais (UPs, Fazendas e Núcleos)

---

## 1. Tela(s) Analisada(s)

### Tela 1 — Página Inicial (Dashboard)

![Página Inicial do SuzFogo](./teste_funil_home.png)

A tela inicial apresenta um painel de controle com contadores de ocorrências (em andamento e finalizadas), um histórico de ocorrências e quatro botões de ação rápida na lateral direita: **Criar nova Ocorrência**, **Editar Recursos**, **Cadastrar Locais** e **Ocorrências Arquivadas**.

### Tela 2 — Cadastro de Locais

![Formulário de Cadastro de Locais](./teste_funil_cadastro.png)

Aba aberta após clicar em "Cadastrar Locais". Apresenta um formulário manual com os campos **UP**, **Fazenda**, **Núcleo**, **UF**, **Longitude (X)** e **Latitude (Y)**, além de um botão verde "+ Adicionar". Abaixo do formulário, uma tabela lista os locais já cadastrados, com suporte a busca e remoção individual. Há ainda o botão "Importar CSV" no canto superior direito para importação em lote.

---

## 2. Tipo de Teste

**Tipo:** Tarefa

Será testada a capacidade do usuário de **identificar o caminho correto** na interface e **completar o formulário de cadastro de um novo local** (UP/Fazenda/Núcleo) de forma autônoma, sem nenhuma instrução prévia sobre como utilizar a plataforma.

---

## 3. Conjunto de Perguntas (Lógica de Funil)

As perguntas seguem a progressão do funil: abertura ampla → foco no contexto → tarefa específica → execução → reflexão.

### Pergunta 1 — Abertura (Contexto geral)
> *"Ao olhar para esta tela pela primeira vez, o que você entende que este sistema faz? O que você acha que pode fazer aqui?"*

*Objetivo:* Verificar se o propósito geral da plataforma é compreendido a partir dos elementos visuais disponíveis (contadores, histórico, botões de ação).

---

### Pergunta 2 — Orientação (Identificar o ponto de entrada)
> *"Imagine que você precisasse registrar uma nova propriedade rural (uma UP dentro de uma fazenda) no sistema. Por onde você começaria?"*

*Objetivo:* Avaliar se o botão "Cadastrar Locais" na página inicial é percebido como o ponto de entrada correto para essa tarefa sem ajuda.

---

### Pergunta 3 — Exploração (Navegação na tela de formulário)
> *"Você chegou à tela de Cadastro de Locais. Observando os campos disponíveis, o que cada um representa? Você sente falta de alguma informação para preenchê-los?"*

*Objetivo:* Verificar se os rótulos dos campos (UP, Fazenda, Núcleo, UF, Longitude/Latitude) são autoexplicativos para o perfil de usuário-alvo (operadores ou gestores de campo).

---

### Pergunta 4 — Execução (Realizar a tarefa)
> *"Tente cadastrar um local fictício com os dados a seguir: UP = 'T99', Fazenda = 'Fazenda Teste', Núcleo = 'CS1', UF = 'MS', Longitude = -53.5482, Latitude = -20.3474. Fique à vontade para falar em voz alta o que está fazendo."*

*Objetivo:* Observar se o usuário consegue preencher todos os campos obrigatórios e acionar o botão "+ Adicionar" com sucesso, e identificar pontos de fricção durante a execução (campos confusos, ordem não intuitiva, erros de validação inesperados).

---

### Pergunta 5 — Reflexão (Avaliação pós-tarefa)
> *"Você conseguiu cadastrar o local. O que foi mais fácil? Teve alguma parte do processo que te gerou dúvida ou que você mudaria?"*

*Objetivo:* Capturar percepções subjetivas sobre usabilidade, legibilidade dos campos e satisfação com o fluxo de cadastro.

---

## 4. Objetivo do Teste

Descobrir se um usuário com conhecimento do domínio florestal (mas sem treinamento prévio no sistema) consegue **localizar a funcionalidade de cadastro de locais e concluir o registro de uma nova UP de forma independente**, identificando possíveis barreiras de navegação ou compreensão nos campos do formulário.

---

## 5. Ação ou Entendimento Esperado

O usuário deve ser capaz de:
1. **Identificar o botão "Cadastrar Locais"** na página inicial sem orientação;
2. **Preencher corretamente todos os campos obrigatórios** do formulário (UP, Fazenda, Núcleo, UF, Longitude e Latitude) e clicar em "+ Adicionar", verificando que o novo registro aparece na tabela de locais cadastrados abaixo do formulário.
