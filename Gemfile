source "https://rubygems.org"

# Die Basis-Gems für deine Seite
gem "minima", "~> 2.5"
gem "github-pages", "~> 220", group: :jekyll_plugins

# Plugins für SEO-Power und Sichtbarkeit
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"     # Erzeugt automatisch die sitemap.xml für Google
  gem "jekyll-seo-tag"     # Fügt Meta-Tags für besseres Ranking hinzu
  gem "jekyll-paginate"    # Ermöglicht die Seitenaufteilung (wichtig für deinen Blog)
end

# Plattform-spezifische Einstellungen (Windows/JRuby)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-Booster für Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Kompatibilitäts-Fix für JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
