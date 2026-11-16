# Portfólio Pessoal – Larissa Petrovichi

Me chamo Larissa Petrovichi e esse é o meu projeto de portfólio.

## Descrição do projeto
Este projeto consiste no desenvolvimento de um portfólio pessoal com o objetivo de apresentar minha trajetória acadêmica, conhecimentos técnicos, habilidades e interesses profissionais na área de tecnologia.

O site foi desenvolvido para reunir minhas informações de forma organizada, permitindo que visitantes conheçam meu perfil, minha formação e meus projetos.

## Tecnologias utilizadas
- **HTML:** estruturação do conteúdo do site.
- **CSS:** estilização e personalização dos elementos.
- **Bootstrap :** criação do layout responsivo e utilização de componentes visuais.
- **JavaScript:** implementação de interações e animações.


## Link do site publicado
A ser adicionado após a publicação do projeto.

## Funcionamento do projeto
O portfólio possui uma navegação dividida em seções:

- **Perfil Profissional:** apresenta uma breve descrição sobre mim e meus interesses na área de tecnologia.
- **Idiomas:** apresenta os idiomas que conheço e meus respectivos níveis de domínio.
- **Formação Acadêmica:** apresenta minha formação e os cursos que estou realizando.
- **Projetos:** seção destinada à apresentação de projetos e trabalhos desenvolvidos.
- **Contato:** disponibiliza informações para entrar em contato comigo.

O site também possui um carrossel de imagens e utiliza componentes do Bootstrap para organizar os elementos da página. Sua estrutura permite a navegação entre as diferentes seções e se adapta a diferentes tamanhos de tela.


## Recurso novo adicionado
Foi implementada uma animação de entrada nos cards da seção Formação Acadêmica.

Quando o visitante rola a página e os cards entram na área visível da tela, eles aparecem gradualmente com um movimento de baixo para cima.

Esse recurso foi adicionado para tornar a navegação mais dinâmica e proporcionar uma experiência visual mais agradável.

Além disso, foram adicionadas novas seções, elas sendo sobre a minha formação e meu nível de proficiência em alguns idiomas.

## Como o recurso foi implementado
A animação foi desenvolvida utilizando CSS e JavaScript.

No CSS, foi criada a classe `.animar`, responsável por definir a transparência inicial dos elementos e seu deslocamento vertical. Também foi criada a classe `.visivel`, que altera essas propriedades para fazer os cards aparecerem suavemente.

No JavaScript, foi utilizado o recurso `IntersectionObserver`, que identifica quando os elementos entram na área visível da página. Quando isso acontece, o código adiciona a classe `.visivel` ao elemento, ativando a animação.

Dessa forma, os cards aparecem automaticamente durante a rolagem da página, sem necessidade de interação adicional do usuário.