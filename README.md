Hacker news é um site criado pela startup **incubator**, onde histórias enviadas por usuários (também conhecidas como posts), obtém votos e comentários, similar ao reddit. Hacker News é popular em circulos de tecnologias e startups, a posts que estão no topo das listas podem chegar a milhares de visitantes como resultado.

O dataset pode ser encontrado [aqui](https://www.kaggle.com/hacker-news/hacker-news-posts), mas perceba que foi reduzido de 300.000 linhas para aproximadamente 20.000 removendo todos os envios que não tiveram nenhum comentário, e depois foram pegos alguns posts aleatoriamente.

Essas são as descrições das colunas:

- id: Identificador unico do Hacker News para o post
- title: O titulo do post
- url: A URL do post, se o post tiver uma
- num_points: O número de pontos ganhos, calculado pelo total de "upvotes" menos o total de "downvotes"
- num_comments: A quantidade de comentários que foi feito no post
- author: O username da pessoa que enviou o post
- created_at: Data e hora que o post foi enviado

Estamos especificamente interessados em posts do tipo **Ask HN** ou **Show HN**.
Usuários enviam **Ask HN** posts para fazer uma pergunta especifica.
Por outro lado, usuários enviam **Show HN** posts para mostrar à comunidade um projeto, produto ou compartilhar algo interessante.

Vamos comparar esses dois tipos para determinar:
- Quais deles recebem mais comentários em média?
- Posts criados em um certo horario recebem em média mais comentários?