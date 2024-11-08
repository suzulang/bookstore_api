source "https://rubygems.org"

gem "rails", "~> 8.0.0"
gem "puma", ">= 5.0"
gem "jbuilder"
gem "redis", ">= 4.0.1"
gem "kredis"
gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem "image_processing", "~> 1.2"
gem "rack-cors"

group :development, :test do
  gem "sqlite3", ">= 1.4"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :production do
  gem "pg"
end