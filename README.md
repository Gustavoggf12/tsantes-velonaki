# Página grega — 101 Σχέδια για Τσάντες με Βελονάκι

Arquivo único: `index.html` (sem dependências além do Google Fonts). Sobe em qualquer host estático.

## Antes de publicar
1. `index.html` → bloco `CHECKOUT` no fim do `<script>`: colar os 2 links Hotmart (ofertas Βασικό 10 € e Πλήρες 15 €).
2. Colar o Meta Pixel no comentário `<!-- META PIXEL -->` do `<head>`. O botão de cada pacote já dispara `InitiateCheckout`.
3. Colocar as imagens em `images/` com estes nomes (enquanto faltarem, a página mostra um placeholder listrado com o nome do arquivo):
   - `mockup-principal-el.webp` — mockup principal (capa em grego + celular + páginas), ~1254×940
   - `modelo-1.webp` … `modelo-6.webp` — 6 fotos quadradas 640px da vitrine (grid no desktop, carrossel no mobile; slots vazios ficam ocultos)
   - `doro-1.webp`, `doro-2.webp`, `doro-3.webp` — capas dos 3 bônus, 3:4
   - `avatar-1.webp`, `avatar-2.webp`, `avatar-3.webp` — fotos dos depoimentos (se faltarem, mostra a inicial)
4. Criar as 4 páginas legais em grego: `nomika.html`, `aporrito.html`, `oroi.html`, `ypanachorisi.html`.
5. Validar: "95% προτιμά…" (herdado da italiana, sem fonte) · FAQ "όλα στα ελληνικά — Ναι" só com os PDFs e bônus traduzidos · tratamento de ΦΠΑ no checkout Hotmart para GR/CY.

## Design
Paleta e ritmo da LP italiana (hero chocolate, seções creme/areia alternadas, CTA verde pill) + tipografia da LP grega atual (Playfair Display para títulos, Lato para corpo). Mobile-first, gutter 16 px, CTA fixo no rodapé mobile (aparece depois do hero, some sobre os pacotes), FAQ em accordion, carrossel por scroll-snap no mobile.
