FROM ruby:2.6.0
WORKDIR /app/
RUN apt-get update
RUN apt-get install -y nodejs

RUN git clone https://github.com/docker-hy/rails-example-project.git .
RUN bundle install
RUN rails db:migrate

ENTRYPOINT rails s