---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

title: 摄影
subtitle: 精选野生动物摄影
weight: 90

content:
  # Page type to display.
  page_type: photos

  # Default filter index (0 = the first `filter_button` below).
  filter_default: 0

  # Filter toolbar.
  filter_button:
  - name: 全部
    tag: '*'
  - name: 鸟类
    tag: Birds
  - name: 其他
    tag: Others

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
