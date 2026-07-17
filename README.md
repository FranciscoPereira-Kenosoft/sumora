# Sumora

**Seu coach de calorias com IA** — registre o que comeu por voz ou texto, acompanhe macros, treinos, água e hábitos. Feito pra comida brasileira. 🇧🇷

> Protótipo funcional v2.1 (PWA). Dados ficam no aparelho (localStorage). App de bem-estar — não substitui orientação de nutricionista ou médico.

## Rodar

É um app estático (um arquivo). Qualquer servidor estático funciona:

```bash
npx serve .
```

## Deploy na Vercel (1 clique)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/FranciscoPereira-Kenosoft/sumora)

Ou: [vercel.com/new](https://vercel.com/new) → Import Git Repository → `sumora` → Deploy (zero config).

## GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → Branch `main` / `/ (root)` → Save. O app fica em `https://franciscopereira-kenosoft.github.io/sumora/`.

## Instalar no celular

Abra a URL no Chrome (Android) ou Safari (iPhone) → menu → **Adicionar à tela inicial**. Funciona offline.

## Stack

HTML + CSS + JS vanilla, sem build. Base nutricional local (~TACO). Voz via Web Speech API. PWA com service worker.

---

© Sumora. Todos os direitos reservados.
