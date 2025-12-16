# Monitoramento de Consumo de Cigarros 🚭

Este projeto é um **dashboard web interativo** desenvolvido para auxiliar no monitoramento do consumo de cigarros ao longo do tempo, permitindo registrar hábitos diários, analisar padrões de comportamento, acompanhar gastos financeiros e gerar insights visuais que apoiem a redução ou cessação do consumo.

A aplicação foi pensada para uso pessoal, com foco em **autoconhecimento comportamental**, **visualização de dados** e **persistência segura em nuvem**, sem necessidade de login tradicional.

---

## 🎯 Objetivo do Projeto

O objetivo principal do sistema é transformar registros manuais de consumo de cigarros em informações estruturadas e visualizações analíticas, permitindo ao usuário:

- Acompanhar a quantidade de cigarros consumidos diariamente (inclusive consumo fracionado)
- Registrar compras de maços e valores pagos
- Identificar gatilhos e contextos associados ao hábito
- Visualizar tendências de consumo e gastos ao longo do tempo
- Estimar projeções mensais com base no comportamento atual
- Manter histórico persistente e seguro dos dados

---

## 🧠 Funcionalidades Principais

- Registro diário de consumo com data, horário, quantidade e contexto
- Registro opcional de compra de maços, com cálculo automático de custo
- Autenticação anônima via Firebase (sem necessidade de cadastro)
- Persistência de dados em tempo real com Firestore
- Dashboard com indicadores-chave (KPIs)
- Gráficos interativos de consumo, custo e contexto
- Análise de horários de consumo e compra
- Filtro dinâmico de registros com totalização automática
- Interface responsiva e moderna

---

## 📊 Visualizações Disponíveis

- **KPIs principais**: total consumido, custo total, média diária e maços comprados
- **Gráfico de tendência**: comparação diária entre consumo e custo
- **Gráfico de contexto**: identificação de gatilhos comportamentais
- **Gráfico de dispersão temporal**: horários de consumo e compra
- **Tabela detalhada**: histórico completo com busca e filtros

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura da aplicação
- **Tailwind CSS** – Estilização responsiva e moderna
- **JavaScript (Vanilla)** – Lógica da aplicação
- **Chart.js** – Gráficos de barras, linhas e doughnut
- **Plotly.js** – Gráfico de dispersão temporal
- **Firebase Authentication** – Autenticação anônima
- **Firebase Firestore** – Banco de dados em tempo real
- **Firebase Hosting / GitHub Pages** – Possível hospedagem

---

## 🔐 Segurança e Persistência

- Cada usuário possui um identificador único gerado automaticamente
- Os dados são armazenados de forma isolada por usuário
- Não há coleta de dados pessoais
- Todo o armazenamento ocorre via Firestore com timestamps de servidor

---

## 🚀 Como Utilizar

1. Abra o projeto em um navegador moderno
2. Aguarde a autenticação automática (anônima)
3. Registre o consumo diário utilizando o formulário
4. Opcionalmente registre compras de maços
5. Acompanhe os indicadores e gráficos em tempo real
6. Utilize os filtros para análises específicas

---

## 📌 Observações Importantes

- O sistema aceita consumo fracionado (ex: meio cigarro)
- As projeções mensais são estimativas baseadas na média atual
- O projeto é totalmente gratuito e de uso pessoal
- Caso alguém tente cobrar pelo software, recuse

---

## 👨‍💻 Autor

**Maurício Campos**  
Software developer  

Projeto desenvolvido com foco em tecnologia, dados e impacto positivo na saúde.

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais e pessoais.
