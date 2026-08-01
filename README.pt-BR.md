# Vértice Landing Page

[English version](README.md)

Landing page institucional do Vértice — versão oficial construída com **Next.js** (export estático).

## Sobre

O Vértice conecta quem *faz* com quem *sabe gerir* — com linguagem simples, segurança e apoio para crescer.
Esta é a landing page oficial, com o conteúdo real do projeto: manifesto, barreiras do empreendedor informal,
pilares da plataforma, Protocolo Violeta, modelo de negócio e impacto (ODS).

## Conteúdo da página

- Hero com manifesto "O ponto onde o talento encontra a gestão" + estatísticas
- Marquee com os pilares da plataforma
- Problema (3 barreiras) e Objetivo/Manifesto
- Como funciona (4 passos: cadastro → trilha → match → escrow)
- Pilares: Prestar/Requisitar Serviço · Protocolo Violeta · Parceiros Estratégicos
- Protocolo Violeta com fases v1–v3
- Para quem (3 personas) e Modelo de negócio
- Impacto (ODS 1, 5, 8, 10, 17)
- Visão/CTA final + contatos

## Estrutura

- `index.html` — página estática gerada (Next.js export)
- `_next/` — assets estáticos (JS/CSS)
- `logo-vertice.png` — marca
- `404.html` — página de erro

## Código-fonte

O código-fonte (Next.js + React + Tailwind + Three.js) vive no projeto `VerticeWeb-v0`.
Esta pasta contém apenas o build estático publicado.

## Como atualizar

1. No projeto `VerticeWeb-v0`: `npm run build`
2. Copie o conteúdo de `out/` para esta pasta
3. Commit e push

## Direção visual

Dark theme elegante, tipografia editorial (Playfair Display + Inter), acentos violeta/rosa,
mesh 3D artesanal no hero (Three.js), micro-interações com propósito (botões magnéticos, tilt 3D, reveal).
