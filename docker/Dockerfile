FROM ruby:2.4.2-jessie

# Clone repo
WORKDIR /sources
RUN git clone https://github.com/sendgrid/smtpapi-ruby.git

# Run bundle
WORKDIR /sources/smtpapi-ruby
RUN bundle
