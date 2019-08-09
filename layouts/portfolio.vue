<template lang="pug">
    section.hero.is-info.is-large
        .hero-head
            nav.navbar
            .container
                .navbar-brand
                a.navbar-item
                    img(src='https://bulma.io/images/bulma-type-white.png', alt='Logo')
                span.navbar-burger.burger(data-target='navbarMenuHeroB')
                    span
                    span
                    span
                #navbarMenuHeroB.navbar-menu
                .navbar-end
                    a.navbar-item.is-active
                    | Home
                    a.navbar-item
                    | Examples
                    a.navbar-item
                    | Documentation
                    span.navbar-item
                    a.button.is-info.is-inverted
                        span.icon
                        i.fab.fa-github
                        span Download
        .hero-body
            .container.has-text-centered
            p.title
                | Title
            p.subtitle
                | Subtitle
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
        <nuxt/> 
</template>

<script>
import 'bulma/css/bulma.css'
export default {
    
}
</script>
