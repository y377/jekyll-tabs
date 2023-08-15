# Jekyll Bootstrap Tabs Plugin

A Jekyll plugin that converts specific Markdown syntax into Bootstrap tab components, enhancing your static site's interactivity without diving into frontend complexities.

## Features

- Converts Markdown syntax into Bootstrap tab structures.
- Handles empty or minimal content gracefully by setting uniform tab heights.
- Simple integration with Jekyll static sites.

## Installation

1. Add the `bootstraptabs.rb` file to your `_plugins` directory within your Jekyll project.
2. Ensure that your project's theme includes Bootstrap, as this plugin generates Bootstrap-specific HTML.

## Usage

Write your Markdown with the following structure to generate Bootstrap tabs:

```markdown
====Tab Title 1====

Content for tab 1.

====Tab Title 2====

Content for tab 2.

====tabend====
