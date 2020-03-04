---
layout: example
parent: component.site-navigation
type: example
index: 0
---

<nav data-module="ds-mobile-navigation-menu">
    <button class="js-toggle-menu  ds_mobile-navigation__button" aria-expanded="false" aria-controls="mobile-navigation-menu">
        <span class="ds_site-header__control-text">Menu</span>

        <svg class="ds_icon  ds_site-header__control-icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#menu-21"></use></svg>
        <svg class="ds_icon  ds_site-header__control-icon--close  ds_site-header__control-icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#close-21"></use></svg>
    </button>

    <div id="mobile-navigation-menu" class="ds_mobile-navigation  ds_mobile-navigation" data-offsetselector=".ds_site-header">
        <div class="ds_mobile-navigation__content">

            <div class="ds_mobile-navigation__block">
                <ul class="ds_mobile-navigation__list">
                    <li class="ds_mobile-navigation__item">
                        <a data-device="mobile" data-header="header-link-1" href="#" class="ds_mobile-navigation__link">
                            Get started
                        </a>
                    </li>
                    <li class="ds_mobile-navigation__item">
                        <a data-device="mobile" data-header="header-link-2" href="#" class="ds_mobile-navigation__link">
                            Styles
                        </a>
                    </li>
                    <li class="ds_mobile-navigation__item">
                        <span class="ds_mobile-navigation__link  ds_current">
                            Components
                        </span>
                    </li>
                    <li class="ds_mobile-navigation__item">
                        <a data-device="mobile" data-header="header-link-4" href="#" class="ds_mobile-navigation__link">
                            Patterns
                        </a>
                    </li>
                </ul>
            </div>

            <button type="button" class="ds_mobile-navigation__backdrop  js-close-menu" aria-expanded="false" aria-controls="mobile-navigation-menu">
                <span class="visually-hidden">Close menu</span>
            </button>
        </div>
    </div>
</nav>

<nav class="ds_site-navigation">
    <ul class="ds_site-navigation__list">
        <li class="ds_site-navigation__item">
            <a data-device="desktop" data-header="header-link-1" href="#" class="ds_site-navigation__link">
                Get started
            </a>
        </li>
        <li class="ds_site-navigation__item">
            <a data-device="desktop" data-header="header-link-2" href="#" class="ds_site-navigation__link">
                Styles
            </a>
        </li>
        <li class="ds_site-navigation__item">
            <span class="ds_site-navigation__link  ds_current">
                Components
            </span>
        </li>
        <li class="ds_site-navigation__item">
            <a data-device="desktop" data-header="header-link-4" href="#" class="ds_site-navigation__link">
                Patterns
            </a>
        </li>
    </ul>
</nav>
