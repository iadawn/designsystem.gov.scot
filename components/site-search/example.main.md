---
layout: example
parent: component.site-search
type: example
index: 0
---

<div class="ds_site-search">
    <form role="search" class="ds_site-search__form">
        <label class="ds_site-search__label visually-hidden" for="site-search">Search</label>

        <div class="ds_site-search__input-group">
            <input name="q" required="" id="site-search" class="ds_site-search__input" type="text" placeholder="Search" autocomplete="off">
            
            <button type="submit" title="search" class="ds_site-search__button  button  button--primary">
                <svg class="ds_icon  ds_site-search__icon" role="img"><use xlink:href="/assets/patternlib/images/icons/icons.stack.svg#search"></use></svg>

                <span class="visually-hidden">Search mygov.scot</span>
            </button>
        </div>
    </form>
</div>
