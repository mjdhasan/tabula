#since war/jar bundle requires gem package; use gem-in-a-box for testing
#or execute tabula via "rackup".
#source "http://127.0.0.1:9292"

source "https://rubygems.org"
platform :jruby do
  gem "cuba"
  gem "rack"
  gem "tilt"
  gem "tabula-extractor", '~>0.8.0', :require => "tabula"

  group :development do
    gem "rake"
    gem "warbler", "~> 1.4.9"
    gem "jruby-jars", "1.7.24"
    gem "bootstrap-sass", "~> 3.2.0"
    gem "compass"
  end
end
