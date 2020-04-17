source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.0.0"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "jekyll-theme-prologue"
gem "jekyll-feed", "~> 0.12"
gem "jekyll-seo-tag", "~> 2.6"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

#############

# Gem::Specification.new do |spec|
#   spec.name          = "jekyll-theme-prologue"
#   spec.version       = "0.3.2"
#   spec.authors       = ["HTML5 UP", "Chris Bobbe"]
#   spec.email         = ["csbobbe@gmail.com"]
#
#   spec.summary       = %q{A Jekyll version of the Prologue theme by HTML5 UP.}
#   spec.description   = "A Jekyll version of the Prologue theme by HTML5 UP. Demo: https://chrisbobbe.github.io/jekyll-theme-prologue/"
#   spec.homepage      = "https://github.com/chrisbobbe/jekyll-theme-prologue"
#   #spec.license       = "CC-BY-3.0"
#
#   spec.files         = `git ls-files -z`.split("\x0").select { |f| f.match(%r{^(assets|_layouts|_includes|_sass|_config.yml|404.html|LICENSE|README)}i) }
#
#   #spec.add_development_dependency "jekyll", "~> 3.3"
#   #spec.add_development_dependency "bundler", "~> 2.1.4"
# end
