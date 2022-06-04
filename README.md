# docker_simple_memo_laravel
【Laravel＿memo】</br>
・起動時
docker-compose -f .docker_memo_laravel/docker-compose.yml up -d

・終了時
docker-compose -f .docker_memo_laravel/docker-compose.yml down

・コンテナに入る
docker-compose  -f .docker_memo_laravel/docker-compose.yml exec php /bin/bash
