source "https://rubygems.org"

# The `github-pages` gem mirrors the exact Jekyll + plugin versions GitHub Pages runs server-side.
# Local `bundle exec jekyll serve` then renders identically to what GitHub will publish, so
# preview surprises don't sneak through. Pinning to whatever `github-pages` ships keeps us off
# Bundler's "pick a version" loop.
gem "github-pages", group: :jekyll_plugins

# Tzinfo on Apple Silicon needs the platform-pinned tzinfo-data gem; otherwise Jekyll falls
# back to system zoneinfo and emits a deprecation warning.
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby, :arm64_darwin, :x86_64_darwin]
