source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.7.3"
gem "liquid-tag-parser", "~> 1.9"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem 'jekyll-archives'
  gem "jekyll-assets", "3.0.11"
  gem 'jekyll-environment-variables'
  gem 'octopress-autoprefixer'
  gem 'jekyll-tidy'
  gem 'jekyll-include-cache'
  gem 'jekyll-redirect-from'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Make sure watch mode works A-OK on Windows too
gem "wdm", "~> 0.1.1" if Gem.win_platform?

group :development, :test do
  gem "html-proofer"
  gem "jekyll-import"
end
