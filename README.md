# APP de Finanças Pessoais

💸 App de Finanças Pessoais 
Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o chatgpt. A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural.

## Visão Geral
Criar um aplicativo de organização de finanças pessoais.
O objetivo é tornar o controle financeiro mais intuitivo, acessível e livre de burocracias como planilhas ou formulários complexos.

## Problema a Resolver
Muitas pessoas abandonam o controle financeiro por acharem os aplicativos atuais complicados, exigindo entradas manuais e oferecendo pouca personalização.

## Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações — especialmente iniciantes que não têm familiaridade com apps financeiros tradicionais.

## Funcionalidades-Chave
1. Registro de gastos via chat: O usuário descreve seus gastos em linguagem natural, como “gastei R$ 30 no mercado”.
2. Classificação automática de transações: O app identifica e categoriza os gastos com base no texto.
3. Definição e acompanhamento de metas financeiras: O usuário pode criar metas como “economizar R$ 500 até o fim do mês”.
4. Dicas personalizadas do Agente Financeiro: Um assistente virtual que sugere formas de economizar com base nos hábitos do usuário.
5. Relatórios simples e personalizados: Visualizações claras dos gastos, metas e progresso, adaptadas ao estilo do usuário.

## Princípio de Design Universal
A solução será construída com base em Design Universal, garantindo que o aplicativo ofereça uma experiência acessível, intuitiva e inclusiva para o maior número possível de pessoas — independentemente de idade, nível de alfabetização digital, limitações físicas ou cognitivas.  
Isso inclui:
- Interface clara e legível
- Navegação simples e sem sobrecarga de informações
- Compatibilidade com leitores de tela e comandos por voz
- Feedbacks visuais e auditivos para facilitar o uso

## Entregável da IA
Gerar um plano de MVP contendo:
Features v1:

Resumo geral (saldo, receitas, despesas, investimentos)
Adicionar receitas (salário, hora extra, renda extra)
Adicionar gastos (com categorias incluindo lazer)
Sugestões de investimentos
Gráfico de distribuição
Vou criar um site de finanças pessoais bonito e funcional. Como é uma primeira versão, vou fazer um dashboard elegante com tudo numa página, usando localStorage para persistir os dados.

Conceito visual: Theme financeiro moderno em azul marinho, mais qualificado para tecnologia
  
💬 Interações com o Lovable
Gere um site de finanças pessoais contendo lazeres, contendo gastos, contendo possiveis investimentos e espaço para inserir quantia de cada gasto e de cada ganho, como salario, hora extra e renda extra

🎯 Resultado Final
Acesse o protótipo funcional no Lovable:https://lovable.dev/projects/da689474-4ab8-4170-b97d-f19a224d1734


<img width="912" height="571" alt="image" src="https://github.com/user-attachments/assets/7760ac9f-1a4b-43e3-9440-10d19ecc530d" />

🔍 Funcionalidades do App de Organização Financeira
Componente: Registro e Visualização de Gastos
🎯 Objetivo

Permitir que o usuário:

Registre movimentações financeiras (ganhos, gastos e investimentos)
Visualize para onde o dinheiro está indo através de um gráfico
🧾 Área de Inserção de Dados (formulário)

Responsável por capturar novas movimentações.

🔹 Tipo de movimentação
Ganho → entrada de dinheiro
Gasto → saída de dinheiro
Investimento → valor aplicado

👉 Define como o valor impacta o saldo.

🔹 Categoria
Classifica a movimentação (ex: Moradia, Alimentação, Outros)
Usada para alimentar o gráfico de distribuição

👉 Sem categoria bem definida, o gráfico perde valor.

🔹 Descrição (opcional)
Campo livre para detalhar o registro
Exemplo: “Cinema”, “Conta de luz”

🔹 Quantia (R$)
Valor da movimentação
Deve ser numérico e positivo
🔹 Botão “Adicionar”
-Salva o registro
-Atualiza:
-Saldo
-Histórico
-Gráfico

📊 Visualização: Distribuição de Gastos

Gráfico (tipo donut/pizza) que mostra:

Quanto cada categoria representa no total de gastos
Exemplo:
Moradia → maior fatia
Outros gastos → menor fatia

⚠️ Regra importante
O gráfico considera apenas gastos, não ganhos
Se não houver gastos → gráfico vazio ou zerado

🔄 Fluxo de funcionamento
-Usuário preenche o formulário
-Clica em Adicionar
Sistema:
-Registra a movimentação
-Atualiza o saldo
-Atualiza o histórico
-Recalcula os gastos por categoria
-Atualiza o gráfico

🧠 Reflexão
Funciona Bem?
Resposta: Sim, de uma forma simples que permita que o usuário possa inserir e visualizar em grafico e em quantidade, se está gastando mais do que possue e onde está gastando.

Gostaria de evoluir para alguma outra plataforma?
Sim, para uma corretora com graficos e appis

O que aprendi sobre conversar com IAs?
Aprendi que auxiliam com mais enfase se é utilizado um prompt estruturado.
