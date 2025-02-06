# Chatwoot
Para rodar o chatwoot siga as seguintes etapas:

docker compose run --rm rails bundle exec rails db:chatwoot_prepare

docker compose up -d --build
