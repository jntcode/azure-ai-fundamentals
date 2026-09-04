# Azure AI Fundamentals

## Projeto de Estudo - Microsoft Learn AI Fundamentals

Este repositorio documenta os conceitos fundamentais de Inteligencia Artificial aprendidos atraves do Microsoft Learn, focando em **Speech Analysis** e **Language/Sentiment Analysis**.

---

## 🎯 Objetivo

Documentar e consolidar o conhecimento sobre servicos de IA do Azure, especificamente:
- **Speech Studio** - Analise de voz e transcricao de audio
- **Language Studio** - Analise de sentimento e procesamento de linguagem natural

---

## 📚 Conteudo

### 1. Speech Studio (Analise de Voz)

O Azure Speech Studio oferece servicos de conversao de audio em texto e reconhecimento de voz.

#### Principais Funcionalidades

| Servico | Descricao | Uso Comum |
|---------|-----------|-----------|
| **Speech-to-Text** | Converte audio em texto | Transcricao de reunioes, legendas automaticas |
| **Text-to-Speech** | Converte texto em voz | Assistentes virtuais, audiolivros |
| **Speaker Recognition** | Identifica quem esta falando | Autenticacao por voz, analise de participantes |
| **Translation** | Traduz audio em tempo real | Comunicacao internacional |

#### Conceitos Chave

- **Transcricao Automatizada**: Conversao automatica de audio para texto
- **Reconhecimento de Fala**: Identificacao de palavras e frases em tempo real
- **Diarizacao de Falante**: Identificacao de diferentes falantes em um audio
- **Processamento de Audio**: Melhoria de qualidade e remocao de ruido

---

### 2. Language Studio (Analise de Linguagem)

O Azure Language Studio fornece ferramentas para analise de texto e extracao de informacoes.

#### Principais Funcionalidades

| Servico | Descricao | Exemplo |
|---------|-----------|---------|
| **Sentiment Analysis** | Analise de sentimento | Avaliar opinioes de clientes |
| **Key Phrase Extraction** | Extracao de frases-chave | Resumir documentos |
| **Named Entity Recognition (NER)** | Reconhecimento de entidades | Extrair nomes, datas, locais |
| **Entity Linking** | Vinculacao de entidades | Conectar mencoes a entidades conhecidas |
| **Language Detection** | Deteccao de idioma | Identificar o idioma do texto |

#### Análise de Sentimento

A analise de sentimento classifica texto em categorias:

- **Positivo** 😊 - Avaliacoes favoraveis, elogios
- **Negativo** 😞 - Criticas, reclamacoes
- **Neutro** 😐 - Informativo, sem carga emocional
- **Misto** 🔄 - Combinacao de sentimentos positivos e negativos

##### Exemplo de Analise

```
Texto: "O produto e otimo, mas o atendimento foi muito lento"

Sentimento: Misto
- Positivo: "otimo" (confianca: 0.95)
- Negativo: "lento" (confianca: 0.87)
```

#### Aplicacoes Reais

1. **Atendimento ao Cliente**
   - Analisar feedback de chatbots
   - Priorizar tickets com sentimento negativo
   - Monitorar satisfacao em tempo real

2. **Redes Sociais**
   - Monitorar opiniao publica
   - Detectar crises de reputacao
   - Analisar engajamento

3. **Pesquisa de Mercado**
   - Processar avaliacoes de produtos
   - Identificar tendencias
   - Comparar com concorrentes

---

## 🔧 Ferramentas Utilizadas

- **Azure Speech Studio** - Para experimentacao de servicos de voz
- **Azure Language Studio** - Para experimentacao de analise de linguagem
- **Microsoft Learn** - Plataforma de aprendizado

---

## 📖 Referencias

- [Microsoft Learn - AI Fundamentals](https://learn.microsoft.com/pt-br/training/paths/get-started-with-artificial-intelligence-on-azure/)
- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.cognitive.microsoft.com/)
- [Documentacao Azure AI](https://learn.microsoft.com/pt-br/azure/ai-services/)

---

## 🤝 Contribuicao

Este e um projeto de estudo pessoal. Sinta-se livre para:
- Fork do repositorio
- Criar issues com sugestoes
- Enviar pull requests com melhorias

---

## 📝 Notas

- Os servicos Azure exigem assinatura para uso em producao
- O Microsoft Learn oferece creditos gratuitos para experimentacao
- Os labaratorios sao interativos e permitem testes em tempo real

---

## 📅 Data de Criacao

Setembro 2026

---

*Projeto criado durante o bootcamp DIO*
