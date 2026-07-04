---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# [Gist example]({{ "/gist-example/" | relative_url }})

layout: home
---

<style>
  .news-columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    align-items: start;
  }

  .news-column table {
    width: 100%;
  }

  @media (max-width: 500px) {
    .news-columns {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="news-columns" markdown="1">
<div class="news-column" markdown="1">

| Tech News |
|---|
| [HackerNews](https://news.ycombinator.com){:target="_blank" rel="noopener"} |
| [ARS Technica](https://arstechnica.com){:target="_blank" rel="noopener"} |
| [The Register](https://theregister.com){:target="_blank" rel="noopener"} |
| [Dark Reading](https://darkreading.com){:target="_blank" rel="noopener"} |
| [Bleeping Computer](https://bleepingcomputer.com){:target="_blank" rel="noopener"} |
| [Security Week](https://securityweek.com){:target="_blank" rel="noopener"} |
| [GovInfoSecurity](https://govinfosecurity.com){:target="_blank" rel="noopener"} |
| [InfoSecurity Magazine](https://infosecurity-magazine.com){:target="_blank" rel="noopener"} |
| [SANS ISC](https://isc.sans.edu/){:target="_blank" rel="noopener"} |

</div>
<div class="news-column" markdown="1">

| News / Random |
|---|
| [NY Times](https://nytimes.com){:target="_blank" rel="noopener"} |
| [Discover Gists](https://gist.github.com/discover){:target="_blank" rel="noopener"} |


| Shopping / Deals |
|--|
| [Slickdeals](https://slickdeals.net/){:target="_blank" rel="noopener"} |


</div>
</div>
