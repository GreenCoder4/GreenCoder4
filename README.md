name: Recent posts
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.posts.svg
  token: NOT_NEEDED
  base: ""
  plugin_posts: yes
  plugin_posts_source: dev.to
name: Recent posts with descriptions and cover images
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.posts.full.svg
  token: NOT_NEEDED
  base: ""
  plugin_posts: yes
  plugin_posts_source: dev.to
  plugin_posts_limit: 2
  plugin_posts_descriptions: yes
  plugin_posts_covers: yes
