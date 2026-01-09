# 💸 App de Organização de Finanças da Pizzaria com Vibe Coding

PRD refinado no Copilot web:

```markdown
# PRD – Aplicativo de Organização de Finanças para Pizzarias

## 1. Contexto
O objetivo é criar um aplicativo de Organização de Finanças para pizzarias, que funcione por meio de conversas em linguagem natural.  
A proposta é simplificar o controle financeiro, eliminando a necessidade de formulários complexos ou planilhas manuais, tornando o processo mais intuitivo e acessível.

## 2. Problema
- Muitos donos de pizzarias (especialmente pequenos negócios) desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual e oferecem pouca personalização.  
- A falta de clareza sobre custos fixos (aluguel, energia, insumos) e custos variáveis (ingredientes, entregas, promoções) dificulta a tomada de decisão.  
- Sem relatórios simples e recomendações práticas, o gestor não consegue visualizar oportunidades de economia ou crescimento.

## 3. Público-Alvo
- Pizzarias de pequeno e médio porte, especialmente aquelas em fase inicial de organização financeira.  
- Donos que buscam uma solução prática, acessível e sem complicações técnicas.  
- Usuários que preferem interações conversacionais em vez de sistemas tradicionais de planilhas.

## 4. Princípios de Design
- Design Universal: a solução deve ser projetada para oferecer uma boa experiência ao maior número possível de pizzarias, independentemente de tamanho, nível de conhecimento tecnológico ou contexto de uso.  
- Acessibilidade: interface clara, linguagem simples e suporte a diferentes perfis de usuários.  
- Escalabilidade: permitir que pizzarias iniciantes usem recursos básicos e que pizzarias maiores possam expandir para relatórios mais avançados.  

## 5. Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural  
   - Exemplo: “Gastei R$ 200 em queijo mussarela hoje.”  
   - O sistema interpreta e registra automaticamente.  

2. Classificação automática das transações  
   - Categorias como: insumos, aluguel, energia, marketing, entregas, funcionários.  

3. Definição e acompanhamento de metas financeiras  
   - Exemplo: meta de reduzir gastos com insumos em 10% no mês.  

4. Agente Financeiro Inteligente  
   - Recomendações automáticas de economia.  
   - Alertas sobre gastos acima da média.  
   - Sugestões de promoções ou ajustes de preço.  

5. Relatórios simples e personalizados  
   - Gráficos de fluxo de caixa.  
   - Comparativo de custos fixos vs variáveis.  
   - Insights semanais/mensais.  

6. Funcionalidades adicionais sugeridas  
   - Integração com meios de pagamento (cartão, Pix, maquininhas).  
   - Controle de estoque básico (ex.: monitorar insumos mais usados).  
   - Exportação de relatórios em PDF para contabilidade.  
   - Alertas de vencimento de contas (água, luz, aluguel).  

## 6. Entregável da IA
- Plano de MVP com:  
  - Principais telas:  
    - Tela de chat (entrada de dados em linguagem natural).  
    - Dashboard financeiro (resumo de gastos, metas e relatórios).  
    - Tela de metas (configuração e acompanhamento).  
    - Tela de relatórios (gráficos simples e insights).  
  - Recursos necessários:  
    - Motor de NLP (Processamento de Linguagem Natural).  
    - Banco de dados para transações e categorias.  
    - Módulo de relatórios e visualização.  
    - Sistema de notificações.  
  - Esboço de validação inicial:  
    - Testar com 3–5 pizzarias reais.  
    - Coletar feedback sobre clareza das conversas e utilidade dos relatórios.  
    - Ajustar categorias e recomendações conforme uso.  

## 7. Fluxo Visual de Telas (User Flow – MVP)
[Início] → [Tela de Chat]  
           → Usuário registra gasto em linguagem natural  
           → Sistema classifica automaticamente  

[Tela de Dashboard]  
           → Resumo financeiro (gastos, receitas, saldo)  
           → Acesso rápido a metas e relatórios  

[Tela de Metas]  
           → Definir objetivos (ex.: reduzir custos, aumentar margem)  
           → Acompanhar progresso  

[Tela de Relatórios]  
           → Gráficos simples (fluxo de caixa, categorias de gasto)  
           → Insights e recomendações do Agente Financeiro  

[Notificações]  
           → Alertas de vencimento de contas  
           → Recomendações de economia  

## 8. Diferenciais
- Experiência conversacional em vez de formulários.  
- Design Universal para atender o maior número de pizzarias com boa experiência.  
- Personalização para pizzarias, com categorias e relatórios adaptados ao setor.  
- Educação financeira embutida, com dicas práticas e linguagem acessível.  
```

Interações com o Lovable:
> Crie um App de Finanças de Pizzaria com base no seguinte PRD: (Product Requirements Document):(PRD)

> Faça uma interface com login e senha para cada usuário ter controle do seu estabelecimento e quero que ela venha zerada para o proprietário da pizzaria começar os registros de ganhos e saídas da loja dele (esse atual já veio com ganhos e gastos aleatórios)

Resultado final do Lovable: https://pizza-cash-chat.lovable.app/

<img width="1318" height="636" alt="image" src="https://github.com/user-attachments/assets/6264558b-3357-4e9e-8db3-f4defd2588b9" />

## Funcionalidades do App de Finanças para Pizzarias

### 1. Dashboard Financeiro
- Exibe o saldo do mês, receitas e despesas de forma clara e visual.
- Permite uma visão rápida da saúde financeira da pizzaria.

### 2. Registro de Transações via Chat
- Os usuários podem registrar gastos e receitas usando linguagem natural.
- Exemplo: “Recebi R$ 300 de vendas hoje” ou “Gastei R$ 150 em farinha”.

### 3. Classificação Automática de Gastos
- O sistema categoriza automaticamente os registros.
- Categorias como: insumos, aluguel, energia, marketing, entregas, funcionários.

### 4. Dicas Financeiras Personalizadas
- Um Agente Financeiro oferece recomendações diárias para melhorar o controle de gastos.
- Exemplo: “Continue registrando seus gastos e receitas para ter uma visão completa do seu negócio!”

### 5. Relatórios Personalizados
- Acesso a relatórios simples com visualização por categoria de gasto.
- Gráficos e insights para facilitar decisões.

### 6. Metas Financeiras
- Definição e acompanhamento de metas como redução de custos ou aumento de margem.
- Ajuda a manter o foco em objetivos mensais.

### 7. Navegação Intuitiva
- Menu com seções: Início, Chat, Metas, Relatórios.
- Interface clara e acessível para diferentes perfis de pizzarias.

### 8. Design Universal
- A solução é projetada para oferecer uma boa experiência ao maior número possível de pizzarias.
- Interface acessível, linguagem simples e suporte a diferentes níveis de familiaridade com tecnologia.

## Reflexão
### O que funcionou bem?  
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 2 duas mensagens.

### O que não funcionou como o esperado?  
Esperava poder interagir mais vezes gratuitamente com o Loveble, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.
### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhes e clareza você dá, melhor é a interação.
