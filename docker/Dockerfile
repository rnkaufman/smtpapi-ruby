FROM ruby:2.4.2-jessie

WORKDIR /sources
RUN git clone https://github.com/sendgrid/smtpapi-ruby.git

WORKDIR /sources/smtpapi-ruby
RUN bundle
