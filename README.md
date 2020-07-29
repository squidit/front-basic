# Front-end - Avalição Squid

## Proposta
Criar uma página HTML utilizando de ponto de partida esse repositório. Depois, utilizando Javascript AJAX para a Url (https://vision.squidit.com.br/v1/feed/test) liste o feed do Instagram da @squidapp. Utilizar de CSS para personalizar o layout como o da imagem do resultado abaixo, considerar o hover para todas as imagens (ver primeira imagem do resultado). Além do hover, cada imagem deve ter um click para o Link da imagem no instagram, abrindo em uma nova aba ao clicar.
Responsividade e experiência de usuário (como loaders, tratamento de erros, animações, efeitos, etc) serão levados em consideração na avaliação.
No final, subir o código em um repositório público no seu próprio GitHub e mandar o link para o avaliador.

## Parâmetros do Endpoint de feed
O endpoint https://vision.squidit.com.br/v1/feed/test trará o feed de postagem do @squiditapp. Os parâmetros aceitos na query string são:

- `count` - `Number` - Define o número de postagens que vem na lista (default: 33)
- `nextUrl` - `String` - Ao trazer a primeira página, na resposta tem um parâmetro `pagination > next_url`, se passado na query string, a requisição traz a próxima página e assim por diante (deve usar `encodeURIComponent`)

## Resultado Final

![Resultado](assets/result.jpeg "Resultado")
