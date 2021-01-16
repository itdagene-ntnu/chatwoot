release: bundle exec rails db:prepare
web: bin/start-stunnel bin/rails server -p $PORT -e $RAILS_ENV
worker: bin/start-stunnel bundle exec sidekiq -C config/sidekiq.yml
