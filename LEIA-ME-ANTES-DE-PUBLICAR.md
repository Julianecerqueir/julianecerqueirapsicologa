# Site profissional — Juliane Cerqueira

Pacote estático em HTML5, CSS e JavaScript, preparado para GitHub Pages e Netlify.

## Estrutura
- `index.html` — página inicial
- `sobre.html` — apresentação profissional
- `psicoterapia.html` — serviço e informações do atendimento
- `conteudos.html` — biblioteca de temas
- `contato.html` — canais e agendamento
- `politica-de-privacidade.html` — minuta inicial de privacidade
- `categorias/` — páginas de temas
- `artigos/` — quatro artigos iniciais
- `assets/` — fotografia WebP e ícones
- `styles.css`, `script.js`
- `robots.txt`, `sitemap.xml`, `llms.txt`
- `identidade-profissional.json`

## Antes de publicar — obrigatório
1. Comprar o domínio e substituir `https://SEU-DOMINIO.com.br` pelo domínio real em todos os arquivos HTML (canonical, Open Graph e JSON-LD), `sitemap.xml`, `robots.txt` e `llms.txt`.
2. Confirmar se deseja publicar os valores das sessões. Eles não foram expostos nesta versão; revisar a comunicação de preços com as orientações do CFP/CRP antes de acrescentar.
3. Revisar a política de privacidade para a hospedagem, Calendly, WhatsApp, Google Fonts e eventuais ferramentas futuras. A política atual é uma minuta informativa, não parecer jurídico.
4. Configurar o Calendly para informar corretamente pagamento, horários, duração, público e regras de cancelamento. O site direciona ao link informado, mas não configura a conta Calendly.
5. Conferir o texto e os dados profissionais antes da publicação.
6. Validar a política de cancelamento e não comparecimento e a adequação dos textos publicitários às normas do CFP/CRP.
7. Configurar Search Console e Bing Webmaster Tools após o domínio estar ativo. Enviar o sitemap e verificar a propriedade.
8. Habilitar HTTPS na plataforma de hospedagem.

## Hospedagem
### Netlify
- Arraste a pasta do site ou conecte o repositório Git.
- Configure o domínio em Domain management.
- Ative HTTPS/SSL no painel.
### GitHub Pages
- Envie o conteúdo da pasta para um repositório.
- Ative Pages em Settings > Pages.
- Configure o domínio personalizado e HTTPS quando o domínio estiver comprado.

## Integrações e limites desta versão
- Calendly abre em nova aba pelo link fornecido.
- WhatsApp aparece como botão discreto com o texto “WhatsApp”.
- Não há formulário público, analytics, pixel, newsletter ou cookies de marketing instalados.
- Os links para Substack, LinkedIn, Quora e demais redes abrem os perfis fornecidos; não foram inventados títulos de artigos externos.
- Os vídeos do YouTube podem ser incorporados em cada artigo quando houver uma URL específica e contextualizada. Não foram inventados IDs de vídeo.
- O favicon.svg contém a imagem raster enviada incorporada em um contêiner SVG; também foram incluídos favicon.ico e PNG. Para um símbolo vetorial verdadeiro, será necessário vetorizar a arte original.

## Domínio provisório
Atualmente os arquivos usam `https://SEU-DOMINIO.com.br`. Não publique sem substituir esse marcador.
