# Frontend Mentor - Testimonials grid section
Olá a todos, este é mais um desafio feito pelo frontend mentor e estou muito feliz de compartilha-lo com o mundo!

## Ideias, Planejamento e Execução
Inicialmente, encontrei muitos dilemas entre com uso de grid e flexbox, sem fugir da simplicidade e objetividade com clareza. tentei usar somente grid, entretanto percebi que estava usando valores muito especificos para cada requisiçâo de design do desafio, então decidi por integrar flexbox e grid + media queries ao design do projeto para maior versatilidade e efetividade do mesmo sem perder as estlilzações basicas com leves alteraçôes na responsividade.

### O que eu aprendi
A volatilidade do uso de ferramentas com funçôes semelhantes, flexbox, grid e media queries 

Pontos de destaque das classes CSS:

```css
@media (max-width: 600px) {
  .container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    max-width: 250px;
    }
}

.container {
  display: grid;
  grid-gap: 20px 20px;
  padding-top: 200px;
  justify-content: center;
  grid-template-columns: repeat(4, minmax(100px, 220px));
  grid-template-rows: repeat(2, minmax(200px, 220px));
}

```
### Desenvolvimentos futuros

prosseguirei com os desafios do fontend mentor

### sites com recursos Úteis

- [site W3schools](https://www.w3schools.com/css/css_rwd_intro.asp)
## Autor

- Frontend Mentor - [@MAIAN-HUNTER](https://www.frontendmentor.io/profile/MAIAN-HUNTER)
- Linkedin - [Maian-Lucas](https://www.linkedin.com/in/maian-lucas-1a796026a/)

## Conhecimentos

92% de meu conhecimento foi adquirido pelo curso de programação Dev Quest, oa outros 8% foram de documentações de sites da internet como o proprio Frontend Mentor, W3schools e de videos da plataforma youtube.