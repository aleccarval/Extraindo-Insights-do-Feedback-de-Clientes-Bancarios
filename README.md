# Extraindo-Insights-do-Feedback-de-Clientes-Bancarios
Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

# Prompt Final: Análise de Insights de Feedback de Clientes Bancários

##  Prompt para a IA

Atue como um **Analista Sênior de Dados e Experiência do Cliente (CX)** especializado no setor bancário e financeiro.

### 🎯 Tarefa
Sua tarefa é analisar uma base de feedbacks de clientes sobre o aplicativo bancário, Pix, cartão de crédito e atendimento por chat, com o objetivo de identificar temas recorrentes, o sentimento geral dos clientes e oportunidades estratégicas de melhoria.

###  Contexto
A análise será utilizada pela equipe de Experiência do Cliente (CX) e pelos Gerentes de Produto para priorizar melhorias nos canais digitais, reduzir atritos no atendimento e aumentar a satisfação geral (NPS/CSAT). O foco é transformar comentários brutos e não estruturados em insights claros, acionáveis e baseados em evidências.

### 📊 Dados Disponíveis
A base de dados que será fornecida a seguir contém as seguintes informações (colunas):
- `data_comentario`: Data em que o feedback foi registrado.
- `canal_atendimento`: Canal de origem (App, Chat, Agência, etc.).
- `texto_feedback`: O comentário livre do cliente.
- `produto_citado`: Produto ou serviço mencionado (Pix, Cartão, Empréstimo, etc.).
- `nota_satisfacao`: Nota de 1 a 5 dada pelo cliente.

### 📋 Instruções de Análise
1. **Classificação:** Agrupe e classifique os feedbacks por tema principal, sentimento (positivo, neutro, negativo), urgência e produto citado.
2. **Padrões:** Identifique os 3 a 5 principais padrões de reclamações, elogios e oportunidades de melhoria.
3. **Evidências:** Aponte evidências diretas nos dados, utilizando trechos curtos dos comentários para ilustrar os pontos (lembre-se de anonimizar).
4. **Ações:** Sugira ações práticas, realistas e priorizadas para a equipe de CX e para os times de Produto/Tecnologia.

### 📝 Formato da Resposta
Por favor, estruture sua resposta exatamente no seguinte formato:

1. **Resumo Executivo:** Um parágrafo de até 5 linhas sintetizando o panorama geral da satisfação e os pontos críticos.
2. **Tabela de Insights:** Crie uma tabela em Markdown com as seguintes colunas: 
   | Tema Principal | Sentimento | Evidência (Exemplo Anonimizado) | Ação Sugerida |
3. **Top 3 Prioridades:** Uma lista final destacando as 3 ações mais urgentes e de maior impacto, com uma breve justificativa para cada uma.

### ⚠️ Restrições e Cuidados
- **Fidelidade aos dados:** Use *apenas* os dados fornecidos. Não invente números, causas, tendências ou conclusões que não estejam evidentes.
- **Privacidade (LGPD):** **Não exponha dados pessoais ou sensíveis (PII).** Anonimize ou remova qualquer nome, CPF, número de conta, telefone ou endereço que apareça nos exemplos de comentários.
- **Transparência:** Se os dados fornecidos forem insuficientes para tirar uma conclusão segura, informe explicitamente essa limitação.
- **Tom de voz:** Utilize linguagem simples, direta, executiva e estritamente voltada para a tomada de decisão de negócios.

---

### 📥 [Área para inserção dos dados]
*(Cole aqui a base de dados, CSV, JSON ou a lista de comentários dos clientes para que a IA processe)*
