---
layout: bare
title: Extensão Furigana Reader - Guia do usuário
lang: pt
---

# Furigana Reader - Guia do usuário

> Versão: v1.3.0

## Introdução

O Furigana Reader é uma extensão de navegador para quem estuda japonês. Com um analisador morfológico WASM (Lindera) e fallback em JavaScript, ele adiciona furigana (anotações de leitura) aos kanji nas páginas da web com precisão, facilitando o aprendizado da pronúncia.

---

## Principais recursos

- **Anotação por seleção de texto** — Selecione texto japonês na página para exibir furigana e botões de fala automaticamente
- **Modo furigana na página inteira** — Adicione furigana a todos os kanji com um clique
- **Texto em voz** — Clique no botão do alto-falante para ouvir a pronúncia em japonês
- **Leitura da seleção** — Selecione texto japonês, use o botão flutuante ou o clique com o botão direito em «Ler seleção em voz alta»
- **Dicas ao passar o mouse** — Passe o cursor sobre os caracteres anotados para ver furigana e botões de pronúncia
- **Vários estilos de furigana** — Hiragana, katakana e rōmaji
- **Interface multilíngue** — 38 idiomas de interface

---

## Como usar

### Etapa 1: Instalar a extensão

Instale o **Furigana Reader** na [Chrome Web Store](https://chromewebstore.google.com/) ou carregue localmente no modo desenvolvedor.

### Etapa 2: Abrir qualquer página da web

Acesse uma página com conteúdo em japonês.

### Etapa 3: Selecionar texto ou usar o botão flutuante

Selecione o texto japonês que deseja anotar ou clique no botão flutuante no canto inferior direito para ativar o furigana em toda a página.

### Etapa 4: Ver os furigana

Passe o mouse sobre os caracteres para ver as dicas; clique no ícone do alto-falante para ouvir a pronúncia.

### Etapa 5: Ler o texto selecionado

Selecione texto japonês com o mouse, clique no botão flutuante do alto-falante ou clique com o botão direito e escolha «Ler seleção em voz alta».

> **Dica:** Clique no ícone da extensão na barra de ferramentas para abrir as configurações (estilo de furigana, velocidade da fala, etc.).

---

## Guia de configurações

| Configuração | Descrição |
|---------|-------------|
| **Ativar furigana** | Interruptor principal para ligar ou desligar os furigana |
| **Furigana na página inteira** | Quando ativo, exibe furigana para todos os kanji (pode afetar o layout) |
| **Estilo de furigana** | Escolha hiragana, katakana ou rōmaji |
| **Velocidade da fala** | Ajusta a velocidade da leitura |
| **Dicas ao passar o mouse** | Mostra dica de furigana ao passar o mouse |

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

---

## Links relacionados

- [Política de privacidade](../privacy-policy)
- [Suporte e feedback](../support)

---
