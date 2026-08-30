# 🍔⚡ BURGER & OTAKUS

Mangá full-color de Ação • Sobrenatural • Shonen • Comédia • Mistério.

## 📖 Episódios

| Episódio | Título | Páginas | Status |
|---|---|---|---|
| 1 | O Despertar do Caçador | 14 | ✅ Completo (raiz do repo, `Pagina 1–14.png`) |
| 2 | A Caçadora da Lua Negra | 20 | ✅ Completo (`episodio-2/Pagina 1–20.png`) |
| 3 | O Primeiro Portador | — | ⏳ Aguardando roteiro/envio |

## 🗂️ Estrutura

```
├── Pagina 1–14.png          # Episódio 1 (mangá original)
├── analise/
│   └── episodio-1.md        # Análise canônica completa: história, personagens, regras do mundo, style bible
├── modelos/                 # Model sheets para IAs de vídeo (frente/perfil/costas/expressões/paleta)
│   ├── raildo-base.png      # Raildo (civil) — protagonista
│   ├── raildo-desperto.png  # Raildo (forma desperta: Núcleo, sigilo, aura de chamas)
│   ├── luna.png             # Luna — mistério/guia
│   ├── cacador-misterioso.png # O homem do Burger Supremo
│   ├── criaturas.png        # Criaturas de sombra (comum + chefe + escala + dissolução)
│   └── cenarios-e-sistema.png # Cenários-cardeais, janela do Sistema, ranking dos caçadores
├── prompts/
│   └── prompt-kit-video-ia.md # Kit de prompts (Veo/Kling/Runway/Hailuo/Pika/Luma) + negative prompt + checklist
└── episodio-2/
    └── COMO-ENVIAR.md       # Fluxo de trabalho do Episódio 2
```

## 🔄 Fluxo de trabalho (Episódio 2+)

1. Usuário envia as páginas do próximo episódio/capítulo.
2. Análise página a página com continuidade canônica (ver `analise/episodio-1.md`).
3. Todo personagem novo ganha **model sheet** em `modelos/` no mesmo padrão.
4. Blocos de prompt novos são adicionados a `prompts/prompt-kit-video-ia.md`.
5. Opcional: geração de páginas novas no estilo oficial a partir de roteiro.
