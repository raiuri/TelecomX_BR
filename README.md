# 📊 Análise de Cancelamento de Clientes da TelecomX_BR

Este projeto foi desenvolvido como parte do programa ONE (Oracle Next Education) G8 BR Data Science, uma iniciativa conjunta entre Alura e Oracle. O foco é investigar o comportamento dos clientes de uma operadora de telecomunicações para entender quais fatores estão ligados ao cancelamento dos serviços (churn). Por meio de técnicas de análise estatística e visualização de dados, buscamos identificar padrões e sugerir estratégias para reduzir a evasão.

---

## 🔍 Objetivo da Análise

O propósito principal é explorar quais características dos clientes influenciam o cancelamento dos contratos, respondendo perguntas como:

- Qual o perfil dos clientes que mais abandonam o serviço?
- Que variáveis apresentam maior relação com o churn?
- Quais medidas podem ser adotadas para evitar futuras perdas?

---

## 🧮 Ferramentas e Tecnologias

- Python 3.12.7
- Ambiente Jupyter Notebook
- Principais bibliotecas utilizadas:
  - `pandas` e `numpy` para manipulação e análise de dados
  - `matplotlib`, `seaborn` e `plotly` para criação de gráficos e visualizações

---

## 📁 Organização do Projeto  
📦 TelecomX_BR
┣ 📊 app.ipynb
┣ 📈 histograma.png
┣ 📑 README.md


- `app.ipynb`: notebook com o código completo da análise.
- `histograma.png`: gráfico ilustrando a distribuição das variáveis numéricas em relação ao churn.
- `README.md`: documentação explicativa do projeto.

---

## 🧼 Preparação e Limpeza dos Dados

- Ajuste de tipos de dados, convertendo colunas categóricas e numéricas.
- Tratamento de valores ausentes, com remoção ou substituição conforme necessário.
- Criação de variáveis adicionais, como `Contas_Diarias`, para enriquecer a análise.
- Garantia da consistência e qualidade dos dados.

---

## 📊 Exploração dos Dados

Foram aplicadas técnicas visuais como gráficos de barras, setores, histogramas e boxplots para investigar:

- Diferenças entre clientes que permaneceram e os que cancelaram
- Influência de fatores como:
  - Tipo de contrato
  - Forma de pagamento
  - Serviços adicionais (streaming, segurança, suporte técnico)
  - Faixa etária e gênero

**Exemplo:** ![Histograma](histograma.png)

---

## 📌 Principais Descobertas

- Clientes com contratos mensais apresentam maior índice de cancelamento (~43%).
- Serviços de segurança online e suporte técnico estão associados a maior fidelização.
- O método de pagamento via cheque eletrônico mostra a maior taxa de churn (~45%).
- Clientes mais velhos, com conexão via fibra óptica e mensalidades elevadas também tendem a cancelar mais.
- Clientes com tempo de contrato inferior a 6 meses ou baixo uso diário estão em maior risco de evasão.

---

## ✅ Sugestões para Redução do Churn

1. Incentivar contratos com prazos mais longos, oferecendo descontos e vantagens.
2. Disponibilizar suporte técnico gratuito para novos clientes por períodos iniciais.
3. Estabelecer acompanhamento próximo durante os primeiros 6 meses para facilitar a adaptação.
4. Promover métodos de pagamento automáticos para aumentar o engajamento.
5. Monitorar padrões de uso para identificar e agir rapidamente sobre clientes com baixo engajamento.

---

## 📌 Considerações Finais

Este estudo proporciona uma compreensão detalhada dos fatores que levam ao churn, servindo como base para ações estratégicas. Futuramente, é possível ampliar o trabalho com modelos preditivos para antecipar cancelamentos e otimizar as intervenções.

---

## 👤 Sobre o Autor

📧 Email: raiuresantos@ymail.com  
📎 GitHub: [github.com/raiuri](https://github.com/raiuri)

---

## 📝 Licença

Este projeto está distribuído sob a [Licença MIT](LICENSE).

