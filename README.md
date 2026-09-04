# Azure AI Fundamentals

## Projeto de Estudo - Microsoft Learn AI Fundamentals

Este repositório documenta os conceitos fundamentais de Inteligência Artificial aprendidos através do Microsoft Learn, focando em **Speech Analysis** e **Language/Sentiment Analysis**.

---

## 🎯 Objetivo

Documentar e consolidar o conhecimento sobre serviços de IA do Azure, especificamente:
- **Speech Studio** - Análise de voz e transcrição de áudio
- **Language Studio** - Análise de sentimento e processamento de linguagem natural

---

## 📚 Conteúdo

### 1. Speech Studio (Análise de Voz)

O Azure Speech Studio oferece serviços de conversão de áudio em texto e reconhecimento de voz.

#### Principais Funcionalidades

| Serviço | Descrição | Uso Comum |
|---------|-----------|-----------|
| **Speech-to-Text** | Converte áudio em texto | Transcrição de reuniões, legendas automáticas |
| **Text-to-Speech** | Converte texto em voz | Assistentes virtuais, audiolivros |
| **Speaker Recognition** | Identifica quem está falando | Autenticação por voz, análise de participantes |
| **Translation** | Traduz áudio em tempo real | Comunicação internacional |

#### Conceitos Chave

- **Transcrição Automatizada**: Conversão automática de áudio para texto
- **Reconhecimento de Fala**: Identificação de palavras e frases em tempo real
- **Diarização de Falante**: Identificação de diferentes falantes em um áudio
- **Processamento de Áudio**: Melhoria de qualidade e remoção de ruído

---

### 2. Language Studio (Análise de Linguagem)

O Azure Language Studio fornece ferramentas para análise de texto e extração de informações.

#### Principais Funcionalidades

| Serviço | Descrição | Exemplo |
|---------|-----------|---------|
| **Sentiment Analysis** | Análise de sentimento | Avaliar opiniões de clientes |
| **Key Phrase Extraction** | Extração de frases-chave | Resumir documentos |
| **Named Entity Recognition (NER)** | Reconhecimento de entidades | Extrair nomes, datas, locais |
| **Entity Linking** | Vinculação de entidades | Conectar menções a entidades conhecidas |
| **Language Detection** | Detecção de idioma | Identificar o idioma do texto |

#### Análise de Sentimento

A análise de sentimento classifica texto em categorias:

- **Positivo** 😊 - Avaliações favoráveis, elogios
- **Negativo** 😞 - Críticas, reclamações
- **Neutro** 😐 - Informativo, sem carga emocional
- **Misto** 🔄 - Combinação de sentimentos positivos e negativos

##### Exemplo de Análise

```
Texto: "O produto é ótimo, mas o atendimento foi muito lento"

Sentimento: Misto
- Positivo: "ótimo" (confiança: 0.95)
- Negativo: "lento" (confiança: 0.87)
```

#### Aplicações Reais

1. **Atendimento ao Cliente**
   - Analisar feedback de chatbots
   - Priorizar tickets com sentimento negativo
   - Monitorar satisfação em tempo real

2. **Redes Sociais**
   - Monitorar opinião pública
   - Detectar crises de reputação
   - Analisar engajamento

3. **Pesquisa de Mercado**
   - Processar avaliações de produtos
   - Identificar tendências
   - Comparar com concorrentes

---

## 🔧 Ferramentas Utilizadas

- **Azure Speech Studio** - Para experimentação de serviços de voz
- **Azure Language Studio** - Para experimentação de análise de linguagem
- **Microsoft Learn** - Plataforma de aprendizado

---

## 📖 Referências

- [Microsoft Learn - AI Fundamentals](https://learn.microsoft.com/pt-br/training/paths/get-started-with-artificial-intelligence-on-azure/)
- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.cognitive.microsoft.com/)
- [Documentação Azure AI](https://learn.microsoft.com/pt-br/azure/ai-services/)

---

## 🤝 Contribuição

Este é um projeto de estudo pessoal. Sinta-se livre para:
- Fork do repositório
- Criar issues com sugestões
- Enviar pull requests com melhorias

---

## 📝 Notas

- Os serviços Azure exigem assinatura para uso em produção
- O Microsoft Learn oferece créditos gratuitos para experimentação
- Os laboratórios são interativos e permitem testes em tempo real

---

## 📅 Data de Criação

Setembro 2026

---

*Projeto criado durante o bootcamp DIO*
