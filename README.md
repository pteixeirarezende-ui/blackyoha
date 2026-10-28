# Black Yoha · Landing Page & Design System Oficial

Landing Page mobile-first de captação de leads para a **Black Yoha (Black Friday Antecipada)** com direcionamento ao Grupo VIP Oficial no WhatsApp, além do catálogo completo de Design System da marca.

## 📁 Estrutura de Arquivos

```text
├── index.html            # Landing Page de conversão (3 dobras, tracking, webhook e WhatsApp)
├── design-system.html    # Catálogo interativo de tokens, componentes e simulador mobile
├── css/
│   └── yoha-ds.css       # Folha de estilos e tokens do Design System oficial Yoha
├── assets/               # Imagens otimizadas dos produtos em WebP (4:5)
└── .gitignore
```

## 🚀 Tecnologias & Otimizações

- **Design System Vanilla**: HTML5, CSS3 moderno (tokens semânticos, `clamp()`, grid, flexbox) e JavaScript puro (sem dependências pesadas).
- **Tipografia**: Fontes oficiais `Rebond Grotesque` e `Poppins`.
- **Paleta Oficial**: Carbono (`#0E0C0A`), Champagne (`#E7D3B0`), Vanilla Cream (`#EFE4CE` / `#F3F1E8`) e Bronze Fosco (`#9E8356`).
- **Performance**: Carregamento total ultraleve (~110 KB), com imagens em formato WebP responsivas e lazy-loading.
- **Rastreamento & Automação**:
  - Meta Pixel configurado (`PageView`, `Lead` com Advanced Matching + EventID, e `JoinGroupClick`).
  - Coleta dinâmica de UTMs (`utm_source`, `utm_campaign`, etc.) e IDs (`fbclid`, `campaign_id`, etc.).
  - Integração por Webhook para automações (n8n, CRM, planilhas).

