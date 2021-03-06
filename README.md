Demo: https://canhtran.github.io/maverick/


**Maverick** is a minimal Hugo blog theme base on [Listed](https://github.com/ronv/listed) by [Ronalds Vilciņš](https://github.com/ronv/). It inspires by Facebook Newsfeed or Twitter and designs for short articles.

This Hugo theme features several content sections, a responsive portfolio grid with hover effects, a timeline, and a Github comment.



Home Page             | List Posts
:-------------------------:|:-------------------------:
![](images/homescreen.png)  |  ![](images/listposts.png)


## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/canhtran/maverick.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing the Agency Theme successfully it requires a just a few more steps to get your site running.


### The config file

Take a look inside the [`exampleSite`](//github.com/digitalcraftsman/hugo-agency-theme/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/digitalcraftsman/hugo-agency-theme/blob/master/exampleSite/config.toml). To use it, copy the [`config.toml`](//github.com/digitalcraftsman/hugo-agency-theme/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change the strings in this theme.

### Github comment

The theme is integrated with [https://utteranc.es](https://utteranc.es) for Github comment. Utterance creates Github issue for each article. It uses Github issues for comments

1. Grant the access for Utterancs [https://github.com/apps/utterances](https://github.com/apps/utterances)
2. Modify the config file
```
  [params.comments]
    githubRepo = 'canhtran/maverick'
    theme = 'github-light'
```


### Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313/) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/canhtran/maverick/issues) to let me know. Or make directly a [pull request](https://github.com/canhtran/maverick/pulls).


## License

This theme is released under the Apache License 2.0 For more information read the [License](https://github.com/canhtran/maverick/blob/main/LICENSE).