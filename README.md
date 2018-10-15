## Gradient - yet another hexo theme.
![](https://i.imgur.com/QBA9Z3i.jpg)

[Check out the demo](https://randomadversary.com/Gradient/).

## Features
- Responsive
- Featured image

## External libraries used
- [Bootstrap 4 with Popper.js, and jQuery](https://getbootstrap.com/)
- [Font awesome](https://fontawesome.com/)

## Configuration
The configuration is done in `themes/gradient/_config.yml`
### Menu
The object key is the label and the value is the path.
```
menu:
  ARCHIVES: /archives
  RANDOM: '/categories/random/'
  CONTACT: /contact
  ABOUT: /
```

### Footer icons
```
social:
  twitter:
    url: 'https://twitter.com/'
    class: 'fab fa-twitter'
  github:
    url: 'https://github.com/RandomAdversary/Gradient'
    class: 'fab fa-github'
  bug report:
    url: 'https://github.com/RandomAdversary/Gradient/issues'
    class: 'fas fa-bug'
```

### Featured image
If the post doesn't contain the featured_image attribute, then the defult image is used.

`featured_image: ./img/default.jpg`

## Changelog
1.0 - Initial release.
