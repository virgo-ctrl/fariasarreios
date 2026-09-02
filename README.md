# Farias Arreios & Cia — Site & Landing Pages Oficiais

Site oficial e landing pages de alta conversão da **Farias Arreios & Cia**, fabricante tradicional de artigos de selaria, arreios de vaquejada, moda country e personalização a laser localizada no polo seleiro de **Cachoeirinha-PE** ("Capital do Couro e Aço").

## 📁 Estrutura do Projeto

- `index.html`: Página principal (Hub geral com vitrine de produtos, vídeo da fábrica, regras de atacado e bifurcação de canais).
- `obrigado.html`: Página de agradecimento pós-conversão (com hooks para Meta Pixel, Google Ads e instruções de despacho).
- `sitemap.xml`: Mapa do site estruturado para SEO nos mecanismos de busca.
- `robots.txt`: Regras de rastreamento com permissão explícita para motores de IA (GPTBot, ClaudeBot, Perplexity, etc.).
- `llms.txt`: Resumo factual estruturado em Markdown para motores generativos (AEO/GEO).
- `assets/`: Vídeos e imagens reais da oficina de Cachoeirinha-PE.

### 📑 Páginas por Categoria (Cluster Topics)
- `/selaria-e-arreios/`: Selas profissionais de vaquejada (correr boi), selas mangalarga, cabeçadas e peitorais.
- `/protecao-animal-e-vaqueiro/`: Crochê/cloche Superflex para patas, protetor de rabo, capacetes e perneiras.
- `/chapeu-agro-e-botas/`: Chapéu Agro de bambu que não amassa, chapéus Panamá e caixas de botas para atacado.
- `/personalizacao-laser-e-bordados/`: Canivetes gravados, facas campeiras, copos térmicos e bonés de comitivas.
- `/atacado-lojistas/`: Portal B2B dedicado para selarias e lojas agropecuárias com regras comerciais.

## 🚀 Como Executar Localmente

Para rodar localmente com Python:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Acesse em: `http://localhost:8080`

## ⚙️ Tecnologias Utilizadas
- HTML5 Semântico
- Tailwind CSS via CDN
- Lucide Icons
- Schema.org (JSON-LD para SEO & AEO)
- Roteamento inteligente de mensagens para WhatsApp (Eliane - Varejo / Jooyce - Atacado)
