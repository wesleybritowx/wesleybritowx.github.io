# wesleybritowx.github.io

Currículo e portfólio de **Wesley Brito** — Analista de Dados (People Analytics).

🔗 **https://wesleybritowx.github.io**

## Estrutura

| Arquivo | Descrição |
| --- | --- |
| `index.html` | Currículo/portfólio — página única, HTML + CSS, sem dependências externas |
| `credito.html` | Case de risco de crédito: previsão de inadimplência com LightGBM |
| `relatorio.html` | Case de automação: relatório de R&S no GitHub Actions com análise da API do Claude |
| `img/` | Foto de perfil |
| `img/credito/` | Gráficos do case de crédito, exportados do notebook |

## Recursos

- **Tema claro/escuro** — segue a preferência do sistema, com alternância manual salva no `localStorage`
- **Download em PDF** — o botão "Baixar PDF" abre a impressão do navegador com layout A4 dedicado (`@media print`)
- **Responsivo** — layout adaptado para desktop e mobile
- **Zero dependências** — ícones em SVG inline, sem CDN, sem build; basta abrir o `index.html`

## Desenvolvimento

Não há etapa de build. Edite o `index.html` e abra no navegador.

Para servir localmente:

```bash
python -m http.server 8000
# http://localhost:8000
```
