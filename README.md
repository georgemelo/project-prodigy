# project-prodigy
Project developed using fundamentals of responsive web design. HTML5 and with CSS3 features. Honoring the band The Prodigy with this project.

#Web Design Responsivo

Projeto P foi desenvolvido de forma responsiva utilizando HTML5 e CSS3 (OOCSS).

Arquivo index.html e styles.css foram validados pela W3C e os ícones para redes sociais gerados por fontawesome.

##Biblioteca, recursos e tecnologias utilizados:

- Meta tag para visualização em qualquer dispositivo e compatibilidade no IE=Edge.
- JQuery: Fontawesome JS (https://kit.fontawesome.com/0226750bc1.js).
- Media Queries.
- Google Fonts (https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap).
- CSS Sprites Optimization.

```css
.spotify {
    background: url("../img/retailers.png");
    background-repeat: no-repeat;
    background-position: -189px top;
    width: 133px
}
```
<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="CSS válido!" />
    </a>
</p>

As imagens do background variam conforme a resolução da tela:
```css
@media (max-width: 550px) {
    body {
        background-color: #dee5ec
    }
    .fundoTopo {
        display: block
    }
    section {
        padding: 10px
    }
}
@media (min-width: 551px) {
    body {
        background: url("../img/the-prodigy956x936.png") top center no-repeat
    }
    .logo {
        width: 433px;
        height: 177px
    }
}
@media (min-width: 900px) {
    body {
        background: url("../img/theProdiyHD.jpg") top center no-repeat
    }
    .logo {
        width: 350px;
        height: 177px
    }
}
@media (min-width: 1931px) {
    body {
        background: url("../img/1962039.jpg") top center no-repeat
    }
    .logo {
        width: 500px;
        height: 177px
    }
}
```
#####Markdown editor: pandao.github.io/

#####Provedor de imagem: imgur.com

![1366px](https://i.imgur.com/eeM4HB2.png "1366px")![1366px footer](https://i.imgur.com/VwY0jbq.png "1366px footer")![898px](https://i.imgur.com/3ypoVUL.png "898px")![549px](https://i.imgur.com/AlEwAgf.png "549px")![1936px](https://i.imgur.com/haXUAkz.png "1936px")
