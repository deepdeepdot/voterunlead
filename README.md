# VoteRunLead

### Pages

* https://voterunlead.org/events/ (Emmilie)
* https://voterunlead.org/about/ (Pedro)
* https://voterunlead.org/stories-testimonials/
* https://voterunlead.org/about/team/ (Rosa)
* https://voterunlead.org/about/board-of-directors/
* https://voterunlead.org/about/advisory-board-2/
* https://voterunlead.org/leaders/in-the-news-3/ (e


### Maintainer

| Page                       | Maintainer    | Global Elements
| ----------------------------------------------------------------------------
|events                    |Emmilie       |Search, Menu, "donate", "register", "don't miss out", Footer
|about                     |Pedro         |Search, Menu, Campaigning buttons, "donate", "join now", "don't miss out", Footer
|stories-testimonials      |              |
|about/team                |Rosa          |Search, Menu, Campaigning buttons, "donate", "join now", "don't miss out", Footer
|about/board-of-directors  |              |
|about/advisory-board-2    |              |
|leaders/in-the-news-3     |              |


### Global components

1) Header
    * Search + social media
    * Top Menu

2) Content
    * Donate
    * Join button
    * Campaining buttons

3) Footer
    * Don't miss out
    * Links and social media



### Process

I have cloned few of the pages (ie about, team, events) from the Wordpress site, voterunlead.org and included a CSS link to `vote-run-lead-overrides.css`. We'll be editing this CSS file, which ultimately will become the content for the CSS overrides in stage.

Here it's my initial CSS override for the menus

```css
    body {
        font-family: 'Source Sans Pro', sans-serif;
        --feminist-patriot-purple:  #2b296b;
        --run-as-you-are-red: #DD3E55;
        --barrier-breaker-blue: #5859A3;
    }

    h1, h2, h3, h4, h5, h6,
    nav.navbar {
        font-family: 'Montserrat', sans-serif;
        background-color: var(--feminist-patriot-purple);
        color: white;
    }

    .navbar-light .navbar-nav > .nav-item > .nav-link {
        color: white;
    }

    a {
        color: var(--feminist-patriot-purple);
    }

    a:focus, a:visited, a:active {
        color: var(--run-as-you-are-red);
    }
```

