# Casa Alto da Colina

Modelo 3D interativo da casa do Lote 04 (Jacuí-MG), montado a partir da planta baixa do projeto.

- Modos: casa completa, sem teto e planta (paredes cortadas a 1,20 m)
- Câmeras: isométrica, de cima e fachada
- Móveis, portas internas e pisos com acabamento (dá para ocultar os móveis no menu)
- Toque num cômodo para ver medidas, área, pé-direito e as cotas das paredes
- Lote de 10 × 36 m com muros e portões na frente e nas laterais; no fundo, alambrado com portão de pedestre para a área verde (dá para ocultar no menu)
- Adicionais em estudo, cada um com liga/desliga em Camadas e visíveis pela câmera Fundos:
  - Pergolado de madeira com vidro na faixa lateral, da cozinha até o fim da casa, passando pela porta-balcão da suíte (deck, espreguiçadeiras, cadeira suspensa, jardim vertical, canteiro e samambaias); dali segue um corredor coberto até o espaço gourmet
  - Espaço gourmet no canto esquerdo do fundo, com estrutura própria a 1 m do alambrado e aberto para a área verde (churrasqueira, bancada, mesa para 8), com banheiro social no canto da frente
  - Canil no canto direito do fundo, com casinha de 2 baias (3 cães grandes e 1 pequeno), solário cercado e portão no alambrado para a área verde
- Sol e vento (em Camadas, grupo Lote real): sol real do lote por data e hora, com sombras, e rosa dos ventos do local que gira junto com a câmera
  - Orientação tirada de dois pontos do lote: a frente olha para 26,7° (nor-nordeste), o lado dos quartos para 296,7° (oés-noroeste)
  - Vento: reanálise ERA5 de 2016 a 2025; o mais frequente vem do leste e do nordeste, os temporais do oeste e do noroeste
- Controles responsivos: barra inferior no celular, painéis laterais em telas grandes (Visualização e Sol e vento à esquerda, Camadas à direita)
  - Os cards contraem e expandem pela seta do cabeçalho, e o navegador lembra como ficaram; no celular contraem as Camadas e o Sol e vento, a barra de baixo fica sempre aberta
- Manete para mover a câmera (toque) ou W A S D / setas; arraste para girar, pinça ou roda para zoom

Página única em HTML com [three.js](https://threejs.org) carregado por CDN. Para rodar localmente, abra `index.html` no navegador.
