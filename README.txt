Projeto Piauí
=============

Site de 5 páginas sobre a natureza, a arte rupestre e a cultura do Piauí.
Feito apenas com HTML e CSS (sem JavaScript, frameworks ou bibliotecas).

COMO ABRIR
----------
Dê dois cliques em index.html. O site funciona offline, exceto o mapa
interativo da página Localização (OpenStreetMap), que precisa de internet.

ESTRUTURA DE PASTAS
-------------------
projeto-piaui/
├── index.html           Início (banner com a paisagem, boas-vindas e atalhos)
├── curiosidades.html    Curiosidades
├── localizacao.html     Localização, dados, clima e como chegar
├── fauna.html           Fauna
├── galeria.html         Galeria de imagens
├── css/
│   └── style.css        Estilo único de todas as páginas
├── imagens/
│   ├── cidades/         Fotos de cidades (Teresina, Parnaíba)
│   ├── cultura/         Fotos de cultura e arquitetura
│   ├── fauna/           Fotos de animais
│   ├── flora/           Fotos de plantas
│   ├── mapas/           Mapas
│   └── paisagens/       Fotos de paisagens
└── README.txt

PALETA DE CORES (arquivo "Paleta de cores para o site do Piauí")
----------------------------------------------------------------
--cor-primaria  #A8442A  Terracota Rupestre  (cabeçalho, títulos)
--cor-sec-1     #0E6E8C  Azul Delta          (faixas de título, links)
--cor-sec-2     #2F6B3A  Verde Carnaúba      (etiquetas, destaque numérico)
--cor-destaque  #F28C1B  Laranja Caju        (botões, página atual; texto sempre grafite)
--cor-fundo     #F7EFE2  Areia do Sertão     (fundo das páginas)
--cor-texto     #2B2420  Grafite Quente      (textos e rodapé)
Branco (#FFFFFF) é usado nos cartões e no texto sobre terracota, azul e verde.
Cores derivadas (bordas e texto suave) são misturas dessas cores feitas com color-mix().

IMAGENS E CRÉDITOS
------------------
- paisagens/paisagem-por-do-sol.jpg: foto enviada pelo autor do projeto.
- cultura/igreja-azul.jpg (banner de Curiosidades), fauna/teiu.jpg (banner
  de Fauna) e mapas/mapa-da-regiao.jpg (banner de Localização): fotos
  enviadas pelo autor do projeto.
- Toda página tem um banner com foto no topo, com o menu por cima da foto.
  A Galeria usa um mosaico com as 4 fotos principais.
- flora/mandacaru.jpg e flora/vegetacao-de-cerrado.jpg: recortes da mesma foto.
- Paisagens:
    paisagens/por-do-sol-na-caatinga.jpg - Foto de Arison Silvino (Pexels) - https://www.pexels.com/photo/serene-desert-sunset-with-distant-cacti-35450808/
    paisagens/ceu-do-sertao.jpg - Foto de Arison Silvino (Pexels) - https://www.pexels.com/photo/scenic-desert-landscape-with-cacti-at-sunset-35450789/
    paisagens/serra-da-capivara.jpg - Foto de Lindos Horizontes (Pexels) - https://www.pexels.com/photo/stunning-view-of-serra-da-capivara-national-park-30282591/
    paisagens/mirante-do-gritador.jpg - Foto de Gustavo Cordeiro (Pexels), Pedro II (PI) - https://www.pexels.com/photo/rochas-no-piai-mirante-do-gritador-27334228/
    paisagens/pedra-furada.jpg - "Pedra Furada - Serra da Capivara I", de Artur Warchavchik (Wikimedia Commons, CC BY-SA 3.0) - https://commons.wikimedia.org/wiki/File:Pedra_Furada_-_Serra_da_Capivara_I.jpg
- paisagens/delta-do-parnaiba.jpg ainda é um ESPAÇO RESERVADO (não está
  sendo usado no site). Para trocar uma foto, salve a nova na mesma pasta,
  com o mesmo nome de arquivo (.jpg), e ajuste o texto "alt" no HTML.
- Fotos do Pexels (licença gratuita do Pexels):
    cidades/porto-de-parnaiba.jpg - Foto de Fuka jaz - https://www.pexels.com/photo/colorful-wooden-boats-on-body-of-water-13926153/
    flora/caju.jpg - Foto de Nanda Mends - https://www.pexels.com/photo/fresh-cashew-fruits-on-a-natural-mat-30878153/
    flora/cacto-da-caatinga.jpg - Foto de Leonardo Dourado - https://www.pexels.com/photo/cacto-caatinga-baiana-13011045/
    cidades/teresina.jpg - Foto de Fernanda Quaresma - https://www.pexels.com/photo/low-angle-photography-of-high-rise-buildings-15202514/
    fauna/onca-pintada.jpg - Foto de adrian vieriu - https://www.pexels.com/photo/close-up-photo-of-a-jaguar-11630694/
    fauna/guara.jpg - Foto de Jerson Martins - https://www.pexels.com/photo/scarlet-ibis-bird-perched-in-tropical-environment-34195094/
    fauna/peixe-boi-marinho.jpg - Foto de Koji Kamei (Belize) - https://www.pexels.com/photo/manatee-under-water-4766707/
- Fotos do Wikimedia Commons:
    flora/carnaubas.jpg - "Carnaúbas na caatinga", de Rapper Ouriço (domínio público) - https://commons.wikimedia.org/wiki/File:Carna%C3%BAbas_na_caatinga.jpg
    paisagens/sete-cidades.jpg - "Parque Nacional de Sete Cidades - Piauí", de deltafrut (CC BY 2.0) - https://commons.wikimedia.org/wiki/File:Parque_Nacional_de_Sete_Cidades_-_Piau%C3%AD.jpg
    fauna/tatu-bola.jpg - de Reuber Brandão (CC BY 4.0) - https://commons.wikimedia.org/wiki/File:Tolypeutes_tricinctus_466118804.jpg
    fauna/moco.jpg - de Thomaz de Carvalho Callado (CC BY 4.0) - https://commons.wikimedia.org/wiki/File:Kerodon_rupestris_349236236.jpg
    fauna/veado-catingueiro.jpg - de Miguelrangeljr (CC BY-SA 4.0) - https://commons.wikimedia.org/wiki/File:Brocket_deer_Mazama_gouazoubira_Santa_fe_do_Sul_1.jpg
- Se usar outras fotos do Pexels (pexels.com), anote aqui o nome do fotógrafo e o
  link de cada foto. Exemplo:
    fauna/onca-pintada.jpg - Foto de NOME DO FOTÓGRAFO - https://www.pexels.com/photo/...
