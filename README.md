# Site Currículo pessoal

Site simples criado apenas para ter algo no meu domínio principal. Criei tudo em apenas um hora e agora que estou me aventurando no mundo dos freelances internacionais, pretendo aprimorar algumas coisinhas por aqui.


## Base para site estáticos
Apesar de ser um site-currículo meu, a estrutura é genérica e pode ser usada da mesma forma para qualquer site estático. Apenas cole seu html e mande um `docker run ...`

## Suba seu site estático usando esse repo como guia
1. `git clone ...`.
2. Apague qualquer arquivo `*.html`, e os assets.
3. Coloque seus arquivos estáticos como quiser (html, imagens, estilos e scripts).
4. Certifique-se de que seu `index.html` está no root directory (assim como o meu está hoje).
5. `docker build -t myimage:tag .`
6. `docker run -d -p 80:80 myimage`
7. Awesome! 

## Precisa de uma mão?
Fale cmg no meu gmail: igorcedrolb