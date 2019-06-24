---
layout: example
parent: component.search-box
type: example

index: 0
---

<div class="search-box">
    <form role="search" class="search-box__form" method="GET" action="/search/">
        <label class="search-box__label hidden" for="search-box">Search</label>
        <input name="q" required="" id="search-box" class="search-box__input" type="text" placeholder="Search mygov.scot" autocomplete="off">

        <button type="submit" title="search" class="search-box__button  button  button--primary">
            <img alt="" class="search-box__icon" src="/assets/images/icons/search-white_@2x.png">
            <span class="hidden">Search mygov.scot</span>
        </button>
    </form>
</div>
