# WIC xaringan template

Xaringan theme for html presentations using WIC colors

![wic](https://raw.githubusercontent.com/olayabucaro/WICslides/master/libs/figures/Screenshot_WICtemplate.png)

## Example

Example presentation [here](https://olayabucaro.github.io/WICslides)

## Usage

Install the R package xaringan from CRAN or the latest version using {remotes}.

```r
remotes::install_github('yihui/xaringan')
```

From version 0.25 the wic template is avalible in the xaringan package.
Add this to the start of the presentation file to use it without needing to clone this repo.
```
output:
  xaringan::moon_reader:
    css: [wic, wic-fonts]
```

Clone this repo and edit the index.Rmd file.
Additional configurations can be done in the wic.css file.

Note that the Markdown used to create slides with this package is different and more limited that Pandoc's Markdown.

## Documentation

Xaringan documentation [here](https://github.com/yihui/xaringan/wiki)

Remark.js documentation [here](https://github.com/gnab/remark/wiki)

## Issues

Please report any errors encountered by opening a issue in this repo or by email.

Feel also free to request additional features or make a pull request if you have something to contribute.
