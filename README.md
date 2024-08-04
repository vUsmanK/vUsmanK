![Header](./header.png)

Hi 👋 My name is Muhammad Usman
===============================

I’m a Student currently pursuing my bachelor's degree in Computer Science. I’m passionate about developing products that make people's lives easier and miserable.

* 🌍  I'm based in Pakistan
* 🖥️  See my portfolio at [https://vusmank.github.io/](http://usmank.github.io/)
* ✉️  You can contact me at [robinhoodfrost360@gmail.com](mailto:robinhoodfrost360@gmail.com)

name: Organization introduction
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.introduction.svg
  token: ${{ secrets.METRICS_TOKEN }}
  user: github
  base: header
  plugin_introduction: yes

name: Repository introduction
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.introduction.repository.svg
  token: ${{ secrets.METRICS_TOKEN }}
  template: repository
  repo: metrics
  base: header
  plugin_introduction: yes

