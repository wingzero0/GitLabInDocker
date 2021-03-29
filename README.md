copy docker-compose.yml.example to docker-compose.yml

update "yourdomain" in docker-compose.yml

copy config/gitlab.rb.example to config/gitlab.rb

update "smtp and omniauth config" in config/gitlab.rb

run "docker-compose up -d"