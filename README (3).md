
# 💸 Ferramenta de Controle de Investimentos com o Excel

## 📘 Introdução
Esta ferramenta foi desenvolvida para ajudar investidores — especialmente iniciantes — a organizar e acompanhar seus aportes mensais, rendimentos e dividendos com o uso de Excel. Com ela, é possível simular diferentes cenários de longo prazo, visualizar o patrimônio acumulado ao longo dos anos e entender o impacto de diferentes taxas de rendimento, tempo de investimento e tipos de fundos imobiliários. 

## 🧭 Passo a Passo

## 1. ❓ Perguntas de Negócio
Antes de começar a desenvolver a planilha, definimos as principais perguntas que a ferramenta deveria responder:

    Quanto investi por mês?

    Por quantos anos?

    Qual é a taxa de rendimento mensal?

    Qual é o patrimônio acumulado ao longo do tempo?

    Quais são os dividendos mensais estimados?

Essas perguntas servem como norteadoras para estruturar a planilha e utilizar fórmulas financeiras adequadas.

## 2. 📊 Estrutura da Base de Dados
A base de dados é uma tabela simples contendo:

- Data de cada aporte

- Valor investido

- Rendimento mensal

- Valor acumulado

- Dividendos estimados

Essa estrutura serve como alicerce para os cálculos e simulações futuras.

## 3. 🧮 Simulador de Patrimônio
A principal fórmula utilizada é o Valor Futuro (VF), que calcula o montante acumulado ao longo do tempo com base em aportes mensais e rendimentos.

📌 Fórmula:

    =VF(Taxa de rendimento; Número de períodos; Valor investido mensal * -1)

Exemplo real:
Se você investir R$ 750 por mês, durante 5 anos, com rendimento de 1,08% ao mês:

    =VF(1,08%; 5*12; -750)

A multiplicação por -1 é necessária para que o Excel retorne o valor positivo no final.

## 4. 🔮 Cenários de Investimento
Simulamos cenários com diferentes prazos:

- 2 anos

- 5 anos

- 10 anos

- 20 anos

- 30 anos

Cada cenário mostra como o patrimônio evolui com o tempo usando a fórmula VF.

    💡 Dica: Colunas auxiliares (com os anos convertidos em meses) podem ser deixadas em branco ou ocultas, facilitando o uso das fórmulas sem poluir visualmente a planilha.

## 5. 🌐 Variáveis Globais
Variáveis globais são valores fixos utilizados em diversas fórmulas, como:

- Valor investido por mês

- Taxa de rendimento

- Número de meses

Ao definir essas variáveis em células separadas, é possível alterar os parâmetros sem precisar editar as fórmulas uma por uma.

## 6. 🏷️ Nomeando Intervalos
Nomear células (por exemplo: InvestimentoMensal, TaxaMensal) ajuda a tornar as fórmulas mais legíveis e reduz erros. Por exemplo:

    =VF(TaxaMensal; Anos*12; InvestimentoMensal*-1)

Isso facilita a manutenção da planilha e a compreensão por terceiros.

## 7. 🏢 Tipos de Fundos Imobiliários (FIIs)
A ferramenta inclui a categorização de diferentes tipos de FIIs, permitindo análises mais específicas:

- FII de tijolo (imóveis físicos)

- FII de papel (recebíveis imobiliários)

- FII híbrido (mistura dos anteriores)

- FII de desenvolvimento

- FII de fundos (FOFs)

- FII de agências bancárias

- FII de hospitalidade

- FII logístico/industrial

## 8. 🧠 Tipos de Investidores
Cada investidor possui um perfil que influencia na escolha dos ativos:

- Conservador: busca segurança, prefere renda fixa e fundos com menor risco.

- Moderado: aceita algum risco em troca de retornos maiores, diversifica entre renda fixa e variável.

- Agressivo: foca em alta rentabilidade e assume riscos mais elevados com ações, criptomoedas, fundos mais voláteis.

## ✅ Conclusão
Com esta ferramenta desenvolvida em Excel, qualquer pessoa pode simular, entender e planejar melhor seus investimentos, independentemente do perfil de investidor. A clareza das fórmulas, o uso de variáveis globais e a categorização de tipos de fundos ajudam a tomar decisões mais conscientes e estratégicas.

Este projeto foi desenvolvido como parte de uma trilha de aprendizagem prática na DIO (Digital Innovation One), uma plataforma de educação tecnológica que conecta estudantes e profissionais com experiências reais do mercado. Ao aplicar os conhecimentos adquiridos na DIO, foi possível transformar teoria em uma solução útil e aplicável à vida financeira de qualquer investidor.

## Imagens da Ferramenta 

![image](https://github.com/user-attachments/assets/77be6c0d-d03a-477f-b626-360901f62aa7)
![image](https://github.com/user-attachments/assets/b30ac954-3986-4e26-b17b-4c675ca16e22)
![image](https://github.com/user-attachments/assets/d12cd22a-398a-49ae-98a5-d0a307baf794)
