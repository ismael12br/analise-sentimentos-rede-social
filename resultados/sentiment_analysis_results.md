# Análise de Sentimentos com Azure Language Studio

Este projeto foi desenvolvido como parte do desafio do bootcamp **"Cloud com Inteligência Artificial"** da DIO em parceria com a XP. O objetivo é aplicar técnicas de **análise de sentimentos** em comentários reais de redes sociais, utilizando os recursos do **Azure AI Language Studio**.

## 📌 Objetivo

Classificar o sentimento de textos extraídos de redes sociais como **positivo**, **neutro** ou **negativo**, por meio da ferramenta de análise de sentimentos do Azure.

## ⚙️ Metodologia

1. Seleção de **4 comentários** extraídos de redes sociais.
2. Inserção dos comentários manualmente no Azure Language Studio.
3. Coleta dos resultados: sentimento principal e níveis de confiança.
4. Registro e organização dos dados em uma tabela resumo.

## 📊 Resumo da Análise

| Nº | Sentimento Principal | Confiança Positiva | Confiança Neutra | Confiança Negativa |
|----|----------------------|--------------------|------------------|--------------------|
| 1  | Positivo             | 98%                | 2%               | 0%                 |
| 2  | Positivo             | 95%                | 4%               | 1%                 |
| 3  | Neutro               | 1%                 | 99%              | 0%                 |
| 4  | Negativo             | 0%                 | 6%               | 94%                |

## 🧠 Observações

- O modelo do Azure demonstrou alta assertividade na classificação de sentimentos extremos (positivo e negativo), com níveis de confiança superiores a 90%.
- O comentário classificado como **neutro** apresentou quase total ausência de polaridade, com 99% de confiança na neutralidade.
- Mesmo com uma amostra pequena, o modelo mostrou-se eficiente e pode ser escalado facilmente para análises maiores.

## 📁 Próximos Passos

- Expandir a análise para um volume maior de comentários.
- Automatizar a coleta de dados com integração via API.
- Criar um script Python para envio em lote e análise automatizada.
- Desenvolver dashboards interativos para visualização dos resultados.

## 👨‍💻 Desenvolvedor

**Ismael Lopes** – Farmacêutico clínico em transição para a área de Inteligência Artificial.  
Este repositório integra o projeto educacional do bootcamp **Cloud com IA - DIO/XP**.

---

