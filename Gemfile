# frozen_string_literal: true
# ↑ 这一行是 Ruby 的标准写法，意思是文件中的字符串默认使用 UTF-8 编码，保持原样即可。

# 指定 gem 包（Ruby 的代码库）的官方下载来源
source "https://rubygems.org"

# 将所有 Jekyll 相关的插件都放在这个组里，这是推荐的做法，方便管理。
group :jekyll_plugins do
  # 指定 Jekyll 核心库。我们不再使用 "github-pages" 这个大礼包，
  # 而是直接指定 Jekyll 的版本，这样更灵活，可以避免与其他插件的依赖冲突。
  # "~> 4.3" 表示使用 4.3 或更高但小于 5.0 的版本。
  gem "jekyll", "~> 4.3"

  # 添加 jekyll-feed 插件，用于生成 RSS 订阅源，对 SEO 友好。
  # "github-pages" 包里默认包含了它，所以我们最好也手动加上。
  gem "jekyll-feed"
  
  # 这就是我们需要的核心插件，用来加载您存放在 GitHub 上的自定义主题。
  gem "jekyll-remote-theme"
end
