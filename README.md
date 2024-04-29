<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-exclude-stacks/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace All Exclude Stacks Example

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

An example Terraspace project to show how to use the options:

config/app.rb

```ruby
Terraspace.configure do |config|
  config.all.include_stacks = "..."
  config.all.exclude_stacks = "..."
end
```

## Usage

Uncomment out the examples in `config/app.rb` and run:

    terraspace all up

## Video

[![Watch the video](https://uploads-learn.boltops.com/u1neymrblh5zsrify9z4rxdztvvb)](https://learn.boltops.com/courses/terraspace-fundamentals/lessons/terraspace-all-exclude-stacks-for-specific-environments)

Note: Premium video content requires a subscription.
