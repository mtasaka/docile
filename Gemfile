require File.expand_path("on_what", File.dirname(__FILE__))
source "https://rubygems.org"

# Travis-only dependencies go here
if on_travis? && !on_less_than_2_3?
  group :test do
    gem "codecov", ">= 0.0.9", :require => false
  end
end

# Specify gem's dependencies in docile.gemspec
gemspec
