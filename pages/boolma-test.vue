<template lang="pug">
    section.hero.is-success.is-fullheight
        // Hero head: will stick at the top
        .hero-head
            header.navbar
                .container
                    .navbar-brand
                    a.navbar-item
                        img(src='https://bulma.io/images/bulma-type-white.png' alt='Logo')
                    span.navbar-burger.burger(data-target='navbarMenuHeroC')
                        span
                        span
                        span
                    #navbarMenuHeroC.navbar-menu
                    .navbar-end
                        a.navbar-item.is-active
                        | Home
                        a.navbar-item
                        | Examples
                        a.navbar-item
                        | Documentation
                        span.navbar-item
                        a.button.is-success.is-inverted
                            span.icon
                            i.fab.fa-github
                            span Download
        // Hero content: will be in the middle
        .hero-body
            .container.has-text-centered
                h1.title
                    | Привет
                h2.subtitle
                    | Дима
        // Hero footer: will stick at the bottom
        .hero-foot
            nav.tabs.is-boxed.is-fullwidth
                .container
                    ul
                        li.is-active
                            a Overview
                        li
                            a Modifiers
                        li
                            a Grid
                        li
                            a Elements
                        li
                            a Components
                        li
                            a Layout

</template>
