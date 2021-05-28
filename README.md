# TND News Hugo Module

## Requirements

Requirements:
- Go 1.14
- Hugo 0.61.0


## Installation

If not already, [init](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module) your project as Hugo Module:

```
$: hugo mod init {repo_url}
```

Configure your project's module to import this module:

```yaml
# config.yaml
module:
  imports:
  - path: github.com/theNewDynamic/hugo-module-tnd-news
```

### Settings

Settings are added to the project's parameter under the `tnd_news` map as shown below. (Entered are defaults)

```yaml
# config.yaml
params:
  tnd_news:
    date_formats:
      datetime: January 2, 2006 at 3:04 pm
      date: 'January 2, 2006'
      time: '3:04 pm'
```

#### date_formats

Date formats are used to format dates throughout the view files.

## theNewDynamic

This project is maintained and loved by [thenewDynamic](https://www.thenewdynamic.com).
