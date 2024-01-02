docker-compose run backend sh -c "rails db:create && rails db:migrate RAILS_ENV=development"

docker-compose run backend rails db:migrate RAILS_ENV=development