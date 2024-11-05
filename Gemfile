source "https://rubygems.org"

# Jekyll 버전 지정
gem "jekyll", "~> 4.3.2"

# 테마를 사용하는 경우 여기에 추가
# gem "garth-jekyll-theme"

# 플러그인 목록
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows와 JRuby는 이 의존성이 필요합니다
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 성능 향상을 위한 옵션 (Windows에서는 기본적으로 false)
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]