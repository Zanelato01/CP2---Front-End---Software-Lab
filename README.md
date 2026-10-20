Vinharia Agnello
Grupo: Software Lab

Sobre o projeto

O projeto Vinharia Agnello foi desenvolvido com o objetivo de criar um site para uma vinharia, apresentando informações sobre o estabelecimento e seus produtos de forma organizada e agradável.
Neste segundo Check-Point, nosso foco é melhorar a aparência do site, deixando as páginas mais bonitas, modernas e interativas. Para isso, utilizamos recursos de CSS que adicionam animações, efeitos ao passar o mouse e transições suaves, melhorando a experiência de quem visita o site.

Integrantes e suas responsabilidades
João Pedro: Página inicial 
Murillo: Página institucional
Heitor: Página de produtos 
Breno: Página de contato

Estrutura do projeto
O site é dividido em páginas, cada uma com uma finalidade específica:
Página inicial (index.html): é a entrada do site, apresentando a Vinharia Agnello e facilitando a navegação pelas outras páginas.
Página institucional (pagina1.html): apresenta informações sobre a vinharia, sua história e sua proposta.
Página de produtos (pagina2.html): reúne a apresentação dos vinhos e outras informações relacionadas aos produtos.
Página de contato (pagina3.html): disponibiliza informações e formas de contato com a vinharia.
Além das páginas HTML, o projeto possui uma pasta para imagens e arquivos CSS responsáveis pela aparência e pelos efeitos visuais do site.

Efeitos Visuais
Neste Check-Point, trabalhamos com recursos de CSS para deixar o site mais interessante e intuitivo de utilizar.
Pseudo-classes
Utilizamos pseudo-classes para modificar a aparência dos elementos de acordo com a interação do usuário.
:hover: muda a aparência de links e botões quando o mouse passa sobre eles.
:focus-visible: destaca os elementos selecionados pela navegação com o teclado, facilitando a acessibilidade.
:nth-child(): permite aplicar estilos diferentes a determinados elementos, como cartões alternados.
Pseudo-elementos
Os pseudo-elementos foram utilizados para adicionar detalhes visuais sem precisar criar novos elementos no HTML.
::before: permite adicionar detalhes decorativos antes do conteúdo de um elemento.
::after: pode ser usado para criar linhas decorativas e outros efeitos nos títulos.
::first-letter: permite destacar a primeira letra de um parágrafo.
Animações
Utilizamos animações com @keyframes para deixar a apresentação do conteúdo mais dinâmica. Entre os efeitos possíveis estão a entrada suave dos elementos na página e o destaque visual de determinadas áreas do site.
Transições e transformações
As transições tornam as mudanças visuais mais suaves durante a interação com os elementos. Já as transformações permitem modificar sua posição, tamanho ou rotação.
Alguns exemplos são o aumento das imagens ao passar o mouse, a elevação dos botões e a mudança de aparência dos links.
Organização dos arquivos CSS
Para manter o código organizado, os efeitos visuais ficam no arquivo efeitos.css, separado dos estilos principais, que ficam em style.css.
O arquivo efeitos.css é importado pelo CSS principal, facilitando a manutenção e a organização dos estilos do projeto.

Organização das pastas
vinharia-agnello/
├── index.html
├── README.md
└── src/
    ├── assets/
    │   └── imgs/
    ├── css/
    │   ├── style.css
    │   └── efeitos.css
    ├── js/
    └── pages/
        ├── pagina1.html
        ├── pagina2.html
        └── pagina3.html
        
index.html: página inicial do site.
assets/imgs/: pasta com as imagens utilizadas.
css/style.css: arquivo com os estilos principais.
css/efeitos.css: arquivo com os efeitos visuais.
js/: pasta destinada aos arquivos JavaScript.
pages/: pasta que reúne as demais páginas HTML.
 Links do projeto
Repositório no GitHub: 
Site publicado no GitHub Pages: 
Software Lab | Vinharia Agnello — Check-Point 02
 # CP2---Front-End---Software-Lab
