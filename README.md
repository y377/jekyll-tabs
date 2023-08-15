# Jekyll Bootstrap Tabs Plugin

A Jekyll plugin that converts specific Markdown syntax into Bootstrap tab components, enhancing your static site's interactivity without diving into frontend complexities.

## Features

- Converts Markdown syntax into Bootstrap tab structures.
- Handles empty or minimal content gracefully by setting uniform tab heights.
- Simple integration with Jekyll static sites.

### pic-1
![image](https://github.com/y377/jekyll-tabs/assets/58632405/0bfa1c17-b74b-43be-84b0-6a17c486d99b)

### pic-2
![image](https://github.com/y377/jekyll-tabs/assets/58632405/91c9a3ea-80f1-4158-9bf3-e8411f8f911a)

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
