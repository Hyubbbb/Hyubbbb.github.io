# frozen_string_literal: true

source "https://rubygems.org"

# Jekyll과 Chirpy 테마 추가
gem "jekyll", "~> 4.2"
gem "jekyll-theme-chirpy", "~> 7.2", ">= 7.2.4"

# 로컬 gemspec을 사용 중이라면 유지 (없다면 삭제 가능)
# gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
