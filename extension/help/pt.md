---
layout: bare
title: Extensão Furigana Reader - Guia do usuário
lang: pt
---

# Furigana Reader - Guia do usuário

> Versão: v1.4.1

## Introdução

O Furigana Reader é uma extensão de navegador para quem estuda japonês. Com um analisador morfológico WASM (Lindera + IPAdic) e fallback em JavaScript, ele adiciona furigana (anotações de leitura) aos kanji em páginas da web e em PDFs com precisão. Também inclui um dicionário japonês integrado, texto em voz e tradução — para você aprender a pronúncia do japonês com mais facilidade.

---

## Principais recursos

- **Modo furigana na página inteira** — Adicione furigana a todos os kanji com um clique
- **Dicionário ao passar o mouse** — Passe o cursor sobre os caracteres anotados para ver definições do JMdict (mais de 180 mil entradas), leituras, selos de nível JLPT (N5–N1) e botões de pronúncia; escolha entre modo Dicionário, modo Leitura ou Desligado
- **Leitor PDF** — Leitor PDF integrado com furigana, dicionário, fala e tradução; suporta arrastar e soltar, carregamento por URL e detecção automática de PDF com redirecionamento inteligente
- **Três estilos de leitura** — Hiragana, katakana e rōmaji
- **Separação de okurigana** — Separa com precisão o okurigana (送り仮名) do radical em kanji
- **Suporte a jukujikun** — Leituras corretas em compostos de vários kanji com leituras especiais (熟字訓)
- **Texto em voz** — Clique no botão do alto-falante para ouvir a pronúncia em japonês
- **Fala da seleção com karaokê** — Selecione qualquer texto japonês; uma barra compacta aparece com falar e traduzir; a fala acompanha destaque palavra a palavra ou caractere a caractere em tempo real (efeito karaokê) sincronizado ao áudio
- **Tradução da seleção** — Selecione texto, clique em traduzir na barra para obter tradução instantânea via Bing ou Google Translate, em um balão embutido
- **Atalhos de teclado** — Acesso rápido aos recursos principais com atalhos personalizáveis
- **Interface multilíngue** — 38 idiomas de interface

---

## Como usar

### Etapa 1: Instalar a extensão

Instale o **Furigana Reader** na [Chrome Web Store](https://chromewebstore.google.com/) ou carregue localmente no modo desenvolvedor.

### Etapa 2: Abrir qualquer página da web

Acesse uma página com conteúdo em japonês.

### Etapa 3: Ativar o furigana

Clique no ícone da extensão na barra de ferramentas. Ative «Ativar furigana» e depois «Furigana na página inteira» para anotar todos os kanji. Você também pode usar o botão flutuante no canto inferior direito.

### Etapa 4: Ver os furigana

Passe o mouse sobre os caracteres para ver dicas com leituras e definições do dicionário. Clique no ícone do alto-falante para ouvir a pronúncia.

### Etapa 5: Falar e traduzir o texto selecionado

Selecione texto japonês com o mouse. Perto da seleção aparece uma barra compacta com dois botões:
- **🔊 Falar** — Lê o texto em voz alta com destaque estilo karaokê
- **🌐 Traduzir** — Mostra um balão de tradução embutido abaixo da barra

Você também pode clicar com o botão direito e escolher «Furigana Reader > Ler seleção em voz alta» ou «Furigana Reader > Traduzir seleção».

> **Dica:** Clique no ícone da extensão para abrir as configurações e ajustar estilo de furigana, modo ao passar o mouse, velocidade da fala, motor de tradução e mais.

---

## Dicionário ao passar o mouse

A extensão inclui um dicionário japonês integrado com base no JMdict (mais de 180 mil entradas). Nas configurações você pode escolher entre vários modos ao passar o mouse:

| Modo | Comportamento |
|------|---------------|
| **Dicionário** | Ao passar o mouse: leitura + definição + nível JLPT + botão de pronúncia |
| **Leitura** | Ao passar o mouse: leitura + botão de pronúncia (sem definições) |
| **Desligado** | Sem efeito ao passar o mouse |

No modo **Dicionário**, a dica mostra:
- A palavra e sua leitura (furigana)
- Um botão de pronúncia (clique para ouvir)
- Definições em japonês do JMdict
- Selo de nível JLPT (N5–N1) quando houver

> **Dica:** Os dados do dicionário são carregados sob demanda quando o modo Dicionário está ativo e descarregados ao mudar para outros modos para economizar memória.

---

## Leitor PDF

O Furigana Reader inclui um leitor PDF integrado para ler documentos PDF com furigana, dicionário, fala e tradução — os mesmos recursos das páginas web, agora também em PDF.

### Abrir um PDF

**Método 1: No pop-up**  
Clique no ícone da extensão e depois em «Abrir leitor PDF». Arraste e solte um arquivo PDF ou clique em «Escolher arquivo» para abrir um PDF local. Você também pode colar uma URL de PDF.

**Método 2: Menu de contexto**  
Clique com o botão direito em um link `.pdf` e escolha «Abrir PDF com Furigana Reader».

**Método 3: Detecção automática**  
Com «Detecção inteligente de PDF» ativada nas configurações, a extensão redireciona automaticamente URLs `.pdf` para o leitor integrado. Se um PDF for detectado mas não redirecionado (por exemplo, no visualizador do Chrome), você verá notificações e convites para abrir no Furigana Reader.

### Recursos do leitor PDF

- **Furigana** — Todo o furigana funciona no texto do PDF, incluindo modo de página inteira e dicas ao passar o mouse
- **Cinco modos de furigana** — Hiragana, katakana, rōmaji, só ao passar o mouse e desligado
- **Dicionário por clique** — Clique em uma palavra para ver a definição no JMdict (no PDF usa-se clique em vez de passar o mouse para leitura com menos distração)
- **Barra de seleção** — Selecione texto para falar, traduzir ou copiar
- **Barra lateral** — Sumário e miniaturas de página
- **Busca** — Busca de texto completo no PDF
- **Temas** — Escuro, claro e sépia
- **Zoom** — Vários níveis de zoom, incluindo furigana adaptável ao zoom
- **Atalhos de teclado** — Setas para navegar, +/- para zoom, Ctrl/Cmd+F para buscar

---

## Fala da seleção e karaokê

A fala da seleção permite selecionar qualquer texto japonês e ouvi-lo com um clique — ideal para praticar pronúncia de frases e leitura.

**Método 1: Barra de seleção**  
Selecione texto japonês com o mouse. Aparece uma barra compacta com 🔊 falar e 🌐 traduzir. Clique em falar para reproduzir. Enquanto lê, cada palavra ou caractere é destacado em tempo real (efeito karaokê).

**Método 2: Menu de contexto**  
Depois de selecionar texto japonês, clique com o botão direito e «Furigana Reader > Ler seleção em voz alta».

**Método 3: Atalho de teclado**  
Selecione texto e pressione `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) para falar.

> **Dica:** O destaque karaokê funciona melhor quando o navegador suporta eventos de limite de palavra no TTS. Caso contrário, a extensão usa um fallback baseado em tempo.

---

## Tradução

Selecione qualquer texto na página e use a tradução para obter resultados na hora.

**Método 1: Barra de seleção**  
Selecione texto e clique em 🌐 traduzir na barra. Abaixo aparece um balão com o resultado e um botão copiar.

**Método 2: Menu de contexto**  
Selecione texto, clique com o botão direito e «Furigana Reader > Traduzir seleção».

**Método 3: Atalho de teclado**  
Selecione texto e pressione `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) para traduzir.

**Motores de tradução:**
- **Bing Translate** (padrão) — Microsoft Translator
- **Google Translate** — Google

Ambos suportam **108 idiomas de destino**.

Você pode trocar o motor e o idioma de destino nas configurações da extensão. O idioma de destino é detectado automaticamente a partir do idioma do navegador.

> **Dica:** Clique fora da barra ou do balão para fechá-los.

---

## Atalhos de teclado

| Atalho | Atalho no Mac | Ação |
|--------|---------------|------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Ligar ou desligar anotações furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Falar o texto selecionado |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduzir o texto selecionado |

> **Dica:** Personalize esses atalhos no Chrome em `chrome://extensions/shortcuts`.

---

## Guia de configurações

| Configuração | Descrição |
|--------------|-----------|
| **Ativar furigana** | Interruptor principal para ligar ou desligar o furigana |
| **Furigana na página inteira** | Quando ativo, exibe furigana para todos os kanji (pode afetar o layout) |
| **Modo ao passar o mouse** | Comportamento ao passar o mouse: Dicionário (leitura + definições + JLPT + áudio), Leitura (leitura + áudio) ou Desligado |
| **Estilo de furigana** | Hiragana, katakana ou rōmaji |
| **Velocidade da fala** | Velocidade da leitura em voz alta |
| **Motor de tradução** | Bing Translate ou Google Translate |
| **Idioma de destino** | Idioma para o qual traduzir (detectado automaticamente pelo idioma do navegador) |
| **Detecção inteligente de PDF** | Quando ativo, redireciona automaticamente URLs PDF para o leitor integrado e mostra avisos quando PDFs são detectados |

---

## Perguntas frequentes

**P: Por que não funciona em algumas páginas?**  
R: Por segurança, extensões não rodam em páginas especiais (`chrome://`), nas configurações do navegador nem na Chrome Web Store.

**P: E se os furigana estiverem imprecisos?**  
R: Palavras raras ou leituras especiais (jukujikun) podem ter erros. Continuamos melhorando; exemplos concretos ajudam.

**P: Sem som na síntese de voz?**  
R: Verifique o volume do sistema e se há pacotes de voz em japonês instalados. O suporte varia entre navegadores e sistemas operacionais.

**P: O modo de página inteira altera o layout?**  
R: Furigana precisam de espaço extra. Se atrapalhar a leitura, desative o modo de página inteira e use as dicas ao passar o mouse.

**P: A tradução não funciona?**  
R: A tradução exige conexão com a internet. Se o Bing Translate falhar, tente o Google Translate nas configurações. Algumas redes podem bloquear os serviços de tradução.

**P: Como abro um PDF com o Furigana Reader?**  
R: Você pode abrir PDF de várias formas: «Abrir leitor PDF» no pop-up, clique com o botão direito em um link PDF e «Abrir PDF com Furigana Reader», ou ative «Detecção inteligente de PDF» para redirecionar automaticamente URLs PDF ao leitor integrado.

**P: A detecção inteligente de PDF está ativa, mas alguns PDF não redirecionam**  
R: O redirecionamento automático vale para URLs que terminam em `.pdf`. Para PDF servidos sem extensão `.pdf` ou abertos no visualizador do Chrome, você verá notificação ou selo para abrir no Furigana Reader.

**P: Posso usar o dicionário offline?**  
R: Sim. O dicionário JMdict (mais de 180 mil entradas) vem incluído na extensão. Todas as consultas são locais, sem rede.

---

## Links relacionados

- [Política de privacidade](../privacy-policy)
- [Suporte e feedback](../support)

---
