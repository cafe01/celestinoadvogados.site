# celestinoadvogados.site

O site do escritório. Três coisas num domínio só, de propósito: **autoridade de busca não atravessa subdomínio**, então institucional, artigos e a landing de aviação compõem no mesmo `celestinoadvogados.com.br`.

```
/            institucional
/artigos/    os textos — o motor orgânico
/voo/        a landing do produto de aviação (chrome próprio, sem menu)
```

Construído pelo **Jekyll**, que é o gerador que o GitHub Pages roda sozinho: não há nada para instalar nem para compilar na máquina. Escrever um artigo é criar um arquivo markdown e dar push.

## Escrever um artigo

Um arquivo em `_posts/`, nomeado `AAAA-MM-DD-endereco-do-artigo.md`:

```markdown
---
title: "Meu voo atrasou mais de quatro horas. E agora?"
resumo: "O que a companhia deve oferecer durante a espera e o que se pode pedir depois."
area: "Direito do Passageiro Aéreo"
autor: "Mariela Celestino — OAB/ES 14.594"
date: 2026-08-02
---

O texto, em markdown.
```

`area` faz duas coisas além de rotular: agrupa na listagem e, quando vale `Direito do Passageiro Aéreo`, acrescenta ao pé do artigo a chamada para `/voo/`.

## A régua da OAB

Todo texto publicado responde ao **Provimento 205/2021**. Obrigatório: nome e inscrição do advogado responsável. Vedado: honorários, gratuidade, promessa de resultado, valores, casos concretos, a palavra "especialista" e descrição de estrutura física. O rodapé já carrega o aviso de conteúdo informativo; o corpo do artigo é responsabilidade de quem assina.

## O que ainda espera as sócias

O `index.html` está com o esqueleto pronto e o texto entre `[colchetes]` — a história do escritório, a área da Milena, a terceira área e o endereço. Nada disso vai ao ar antes da palavra delas.
