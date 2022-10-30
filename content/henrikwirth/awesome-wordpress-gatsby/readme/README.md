# Awesome Wordpress Gatsby Overview

An awesome list of resources about WordPress as a headless CMS with Gatsby

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/henrikwirth/awesome-wordpress-gatsby/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 henrikwirth/awesome-wordpress-gatsby](https://github.com/henrikwirth/awesome-wordpress-gatsby) · ⭐ 247 · 🏷️ Front-End Development

[ [Daily](/content/henrikwirth/awesome-wordpress-gatsby/README.md) / [Weekly](/content/henrikwirth/awesome-wordpress-gatsby/week/README.md) / Overview ]

---

<div align="center">
  <br /><br />
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" /></a>
  <br /><br /><br />
  <a href="https://wordpress.org/"><img width="150" height="150" align="center" src="https://github.com/henrikwirth/awesome-wordpress-gatsby/raw/master/media/wordpress-logo.svg" alt="WordPress"></a>
      <a href="https://www.gatsbyjs.org/"><img width="150" height="150" align="center" src="https://github.com/henrikwirth/awesome-wordpress-gatsby/raw/master/media/gatsby-logo.svg" alt="Gatsby"></a>
  <br /><br />
  <p>
    <b>
      A curated list of resources about WordPress as a headless CMS with Gatsby as a Static Site Generator (SSG).
    </b>
  </p>
  <br />
</div>

A **headless CMS** is a back-end only content management system (CMS). Its purpose is to serve content and make it accessible via an API (e.g. REST or GraphQL).

A **Static Site Generator (SSG)** is a framework or setup, that helps you to generate static websites (HTML/CSS/JS). The source of your data can be anything from local files (e.g. text files or markdown) to APIs (e.g. REST, GraphQL).

<br />

**Why Gatsby and WordPress?**

WordPress is one of the **most used CMS in the world** and therefore many people already know how to work with it. The typical front-end approach with PHP-based templates is getting more and more problematic in an environment where performance is key. The approach to use WordPress as a headless CMS with normal API calls through JavaScript already exists, but also has the downside of having to make requests to the server and rendering depending on the response. This adds time to load. **Gatsby instead, pre-renders the whole site at compile time** and therefore the user gets a **fully prepared static site on their first request**, making it one of the **best approaches for performance**. Another huge benefit is **security**, as your WordPress instance can be anywhere, even locally and you don't need to expose any of it to the user. **The static Gatsby site therefore, is not hackable.** Find further arguments for pros and cons in the resources below.

## Contents

<!-- TOC -->

*   [Communities](#communities)
*   [Articles and Talks](#articles-and-talks)
*   [Plugins](#plugins)
    *   [WordPress](#wordpress)
    *   [Gatsby](#gatsby)
*   [Free Tutorials / Courses](#free-tutorials--courses)
    *   [Written Tutorials](#written-tutorials)
    *   [Video Tutorials](#video-tutorials)
*   [Paid Tutorials / Courses](#paid-tutorials--courses)
*   [Starters](#starters)
*   [Themes](#themes)

<!-- /TOC -->

## Communities

If you need help with anything, there are some highly active communities.

**WPGraphQL**

*   [Slack Chat](https://wpgql-slack.herokuapp.com/)
*   [Spectrum Chat](https://spectrum.chat/wpgraphql)
*   [Twitter](https://twitter.com/wpgraphql)

**Gatsby**

*   [Discord Chat](https://gatsby.dev/discord)
*   [Reddit](https://www.reddit.com/r/gatsbyjs/)
*   [Stack Overflow](https://stackoverflow.com/questions/tagged/gatsby)

## Articles and Talks

List of articles and talks that elaborate on the technology stack in general.

*   2021.02: [Announcing Gatsby’s New WordPress Integration](https://www.gatsbyjs.com/blog/wordpress-integration)
*   2021.02: [Jason Bahl of WPGraphQL's role in the operating system for the web](https://www.youtube.com/watch?v=Me_A0HBYXx8)
*   2021.02: [Torque News Drop: Jason Bahl and WPGraphQL](https://www.youtube.com/watch?v=8SAdtU8HAwM)
*   2021.02: [Gatsby Launches New WordPress Integration, Expanding Support for Headless Architecture](https://wptavern.com/gatsby-launches-new-wordpress-integration-expanding-support-for-headless-architecture)
*   2020.11: [Announcing WPGraphQL v1.0](https://www.wpgraphql.com/2020/11/16/announcing-wpgraphql-v1/)
*   2020.07: [My Long Journey to a Decoupled WordPress Gatsby Site](https://css-tricks.com/my-long-journey-to-a-decoupled-wordpress-gatsby-site/)
*   2019.06: [Modern Web Development on the JAMstack
    ](https://www.netlify.com/oreilly-jamstack/) - A report from Netlify about Modern Web Development on the JAMStack, published by O'REILLY.

## Plugins

List of useful plugins to make WordPress and Gatsby work together. Ordered alphabetically.

### WordPress

#### Essential Plugins

*   [WPGraphQL](https://github.com/wp-graphql/wp-graphql) - [Documentation](https://docs.wpgraphql.com/) - WPGraphQL brings the power of GraphQL to your WordPress site.
*   [WPGatsby](https://wordpress.org/plugins/wp-gatsby/) - This plugin configures your WordPress site to be an optimized source for Gatsby.

#### WPGraphQL Extensions

*   [WPGraphQL Cors](https://github.com/funkhaus/wp-graphql-cors) - This FREE plugin from @kidunot89 and @byfunkhaus claims to enable authentication with WPGraphQL to “just work” by allowing you to set CORS headers that GraphQL will accept, which means WordPress default auth cookies can be accepted.
*   [Total Counts for WPGraphQL](https://github.com/builtbycactus/total-counts-for-wp-graphql) - This FREE plugin from @builtbycactus exposes total counts to connections in the WPGraphQL Schema.
*   [WPGraphQL Gutenberg](https://github.com/pristas-peter/wp-graphql-gutenberg) - Exposes Gutenberg blocks to the WPGraphQL API.
*   [WPGraphQL JWT Authentication](https://github.com/wp-graphql/wp-graphql-jwt-authentication) - Extends the WPGraphQL plugin to provide authentication using JWT (JSON Web Tokens).
*   [WPGraphQL Lock](https://github.com/valu-digital/wp-graphql-lock) - Enables query locking for WPGraphQL by implementing persisted GraphQL queries.
*   [WPGraphQL Meta](https://github.com/roborourke/wp-graphql-meta) - This FREE plugin from @robertorourke exposes meta registered via the WordPress register\_meta API to WPGraphQL.
*   [WPGraphQL Meta Query](https://github.com/wp-graphql/wp-graphql-meta-query) - Adds Meta\_Query support to the WPGraphQL Plugin for postObject query args.
*   [WPGraphQL Persisted Queries](https://github.com/Quartz/wp-graphql-persisted-queries) - This FREE plugin from @qz adds the ability to use Persisted Queries with WPGraphQL.
*   [WPGraphQL Offset Pagination](https://github.com/darylldoyle/wp-graphql-offset-pagination) - This FREE plugin from @enshrined adds basic offset pagination as opposed to the standard Cursor based pagination that ships with WPGraphQL.
*   [WPGraphQL Send Email](https://github.com/ashhitch/wp-graphql-send-mail) - This FREE plugin from @Ash\_Hitchcock allows you to send emails via a simple mutation. Includes the abilitty to restrict sending to trusted origins.

***

**Extensions for that use other plugins with WPGraphQL**

*   [QL Search](https://github.com/funkhaus/ql-search) - An extension that integrates SearchWP into WPGraphQL.
*   [WPGraphQL Content Blocks](https://github.com/Quartz/wp-graphql-content-blocks) - This FREE plugin from the folks at QZ.com exposes a way to query HTML content from WordPress Posts and Pages as “Blocks” (not related to Gutenberg) to bring more structure to your queried content.
*   [WPGraphQL Enable All Post Types (DalkMania)](https://github.com/DalkMania/wp-graphql-cpt) - This FREE plugin from @DalkMania automatically adds ALL registered post types to the WPGraphQL Schema.
*   [WPGraphQL Enable All Post Types (TylerBarnes)](https://github.com/TylerBarnes/wp-graphql-enable-all-post-types) - This FREE plugin from @tylbar automatically adds ALL registered post types to the WPGraphQL Schema.
*   [WPGraphQL Google Schema](https://github.com/izzygld/wp-graphql-google-schema) - This FREE plugin from @izzygld261 adds Google Schema support to WPGraphQL.
*   [WPGraphQL Gutenberg ACF](https://github.com/pristas-peter/wp-graphql-gutenberg-acf) - Exposes ACF blocks through GraphQL
*   [WPGraphQL MB (MetaBox)](https://github.com/DalkMania/wp-graphql-mb) - This FREE plugin from @DalkMania adds all registered metaboxes using [metabox.io](https://metabox.io/) to the WPGraphQL Schema.
*   [WPGraphQL MetaBox Relationships](https://github.com/hsimah-services/wp-graphql-mb-relationships) - This FREE plugin from @hsimah adds support for the [metabox.io](https://metabox.io/) Relationships field to WPGraphQL (when also using his wp-graphql-metabox plugin).
*   [WPGraphQL Polls](https://github.com/andrenoberto/wp-graphql-polls) - This FREE plugin from @andrenosouza allows you to interact with data from the WP-Polls plugin via GraphQL Queries and Mutations.
*   [WPGraphQL Polylang Extension](https://github.com/valu-digital/wp-graphql-polylang) - Extends WPGraphQL schema with language data from the Polylang plugin.
*   [WPGraphQL Tax Query](https://github.com/wp-graphql/wp-graphql-tax-query) - Adds Tax\_Query support to the WPGraphQL Plugin for postObject query args (WP\_Query).
*   [WPGraphQL WPML](https://github.com/rburgst/wp-graphql-wpml) - This FREE plugin from @rburgst extends the WPGraphQL schema with language data from the WPML plugin. In addition it turns off WPML default filters in order to be able to iterate over all posts regardless of language.
*   [WPGraphQL for Advanced Custom Fields](https://github.com/wp-graphql/wp-graphql-acf) - Exposes Advanced Custom Fields to the WPGraphQL Schema.
*   [WPGraphQL for BuddyPress](https://github.com/wp-graphql/wp-graphql-buddypress) - This FREE plugin from @RenatoNascAlves exposes BuddyPress data to WPGraphQL.
*   [WPGraphQL for Carbon Fields](https://github.com/matepaiva/wp-graphql-crb) - This FREE plugin from @matepaiva exposes fields registered using Carbon Fields to the WPGraphQL Schema.
*   [WPGraphQL for Custom Post Type UI](https://github.com/wp-graphql/wp-graphql-custom-post-type-ui) - This FREE plugin adds settings to Custom Post Type UI allowing you to set which Post Types and Taxonomies registered by CPTUI should display in the WPGraphQL Schema.
*   [WPGraphQL for FacetWP](https://github.com/hsimah-services/wp-graphql-facetwp) - This FREE plugin from @hsimah exposes filters on WPGraphQL queries to allow for faceted search with FacetWP.
*   [WPGraphQL for Gravity Forms](https://github.com/harness-software/wp-graphql-gravity-forms) - This FREE plugin from @KellenMace of @harness\_up exposes @gravityforms data to WPGraphQL, allowing you to query for forms, fields, entries, and more.
*   [WPGraphQL for Metabox](https://github.com/hsimah-services/wp-graphql-metabox) - This FREE plugin from @hsimah exposes fields registered using the popular <http://MetaBox.io> to the WPGraphQL Schema.
*   [WPGraphQL for Ninja Forms](https://github.com/toriphes/wp-graphql-ninja-forms) - This free plugin exposes forms created by the Ninja Forms plugin to the WPGraphQL Schema and allows for the forms to be submitted via GraphQL Mutations.
*   [WPGraphQL for Posts 2 Posts](https://github.com/harness-software/wp-graphql-posts-to-posts) - This FREE plugin from @KellenMace of @harness\_up automatically creates GraphQL connections for all of your Posts 2 Posts connections.
*   [WPGraphQL for SEOPress](https://github.com/ashhitch/wp-graphql-yoast-seo) - This FREE plugin from @moon\_meister exposes data managed by SEOPress to the WPGraphQL Schema, allowing for SEO data to be used in your headless applications.
*   [WPGraphQL for WooCommerce](https://github.com/wp-graphql/wp-graphql-woocommerce) - This FREE plugin exposes WooCommerce data to WPGraphQL allowing you to interact with your store’s data via GraphQL Queries and mutations.
*   [WPGraphQl Yoast SEO Plugin](https://github.com/ashhitch/wp-graphql-yoast-seo) - Exposes Yoast SEO data to the WPGraphQL Plugin.

#### Other helpful Plugins

*   [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) - [ACF PRO](https://www.advancedcustomfields.com/pro/)
*   [Headless Mode](https://wordpress.org/plugins/headless-mode/) - Headless mode sets up a redirect for all users trying to access the site. The only requests that are granted admission are ones that are either trying to access the REST API, the WP GraphQL API, or any logged-in user looking to access the headless install to edit or create posts.
*   [Polylang](https://wordpress.org/plugins/polylang/)
*   [WP JAMstack Deployments](https://github.com/crgeary/wp-jamstack-deployments) - WordPress plugin for JAMstack deployments on Netlify (and other platforms).

### Gatsby Plugins

*   [gatsby-image](https://www.gatsbyjs.org/packages/gatsby-image)
*   [gatsby-source-filesystem](https://www.gatsbyjs.org/packages/gatsby-source-filesystem)
*   [gatsby-source-wordpress](https://www.gatsbyjs.org/packages/gatsby-source-wordpress)

## Free Tutorials / Courses

**Note:** Since the release of gatsby-source-wordpress V4, it is the preferred over gatsby-source-graphql and therefore I will only list tutorials related to that approach.

### Written Tutorials

*   2019.11: [Guide to Gatsby WordPress Starter Advanced with Previews, i18n and more](https://dev.to/nevernull/overview-guide-to-gatsby-wordpress-starter-advanced-with-previews-i18n-and-more-583l) - A tutorial series starting with the basic setup of WordPress and Gatsby with WPGraphQL and then dives into more advanced subjects like deployments, previews, i18n and a page-builder like setup with ACF flexible cotent fields.
*   2019.08: [Live Previews with WordPress and Gatsby](https://justinwhall.com/live-previews-with-wordpress-gatsby/) - Tutorial showing how to use the theme’s higher order component to facilitate previews for WordPress posts and custom post types.
*   2019.08: [Gatsby with WPGraphQL, ACF and Gatbsy-Image](https://dev.to/nevernull/gatsby-with-wpgraphql-acf-and-gatbsy-image-72m) - A guide, that shows how to implement gatsby-image, so it can be used for WordPress media files.
*   2018.08: [Headless WordPress + Gatsby + Netlify continuous deployment](https://justinwhall.com/headless-wordpress-gatsby-netlify-continous-deployment/) - Guide showing how to create a WordPress + Gatsby + Netlify setup in a few simple steps.

### Video Tutorials

*   2019.11: [25+ Videos - Gatsby + WordPress (2019) Complete Course](https://whatjackhasmade.co.uk/series/gatsby-wordpress-2019/) - The series focuses on how we can use WordPress as a headless CMS with a GraphQL schema to interface with. After setting up our WordPress site and theme, we'll move onto Gatsby and how we can use our new schema to generate content for our Gatsby site, programmatically generating pages, converting Gutenberg blocks to React components and finishing off the chapter with a focus on SEO in Gatsby.
*   2019.07: [Gatsby + WordPress with WPGraphQL (with Jason Bahl) — Learn With Jason](https://www.youtube.com/watch?v=DH7I1xRrbxs) - In this stream, Jason Bahl teaches how to use WordPress with Advanced Custom Fields and WPGraphQL to create an powerful, flexible admin dashboard, then query and display that data in a Gatsby site.
*   2019.07: [Crash Course: Headless WordPress with WPGraphQL, ACF, and React](https://www.youtube.com/watch?v=9KGuI0UmpMw) - In this video, Alex Young (WPCasts) goes over how to get a simple headless WordPress setup with WPGraphQL and React.
*   2019.06: [Using WordPress with WPGraphQL](https://www.youtube.com/watch?v=aqEfEuVWqws) - In this video you will learn how to use GraphQL with WordPress using an awesome plugin named WPGraphQL and some extra cool stuff like GraphQL + Advanced Custom Fields.
*   2019.04: [WPGraphQL for ACF](https://www.youtube.com/watch?v=rIg4MHc8elg) - Jason Bahl shows how to use WPGraphQL for Advanced Custom Fields.
*   2018.07: [GraphQL with WordPress and Gutenberg - Jason Bahl - 2018 JavaScript for WordPress Conference
    ](https://www.youtube.com/watch?v=6CuM1PY9ESQ) - In this talk from the 2018 JavaScript for WordPress Conference, the Developer of the WP GraphQL Plugin, Jason Bahl, gives updated examples of how you can use GraphQL with WordPress and Gutenberg.

## Paid Tutorials / Courses

List of paid courses.

*   2021.01: [Building a Headless WordPress Site with Gatsby](https://www.linkedin.com/learning/building-a-headless-wordpress-site-with-gatsby) - This course is a step-by-step walk through using gatsby-source-wordpress plugin to create a fully functional headless Gatsby WordPress site with posts, pages, categories, tags, post navigation and other features.

## Starters

List of project starters, that you can clone and start building upon.

*   [Gatsby Starter - WordPress Twenty Twenty](https://github.com/henrikwirth/gatsby-starter-wordpress-twenty-twenty) - A port of the WordPress Twenty Twenty theme to Gatsby using the new gatsby-source-wordpress\@v4.
*   [Gatsby + WPGraphQL Blog Example](https://github.com/wp-graphql/gatsby-wpgraphql-blog-example) - Demo showing how to use WPGraphQL as the source for Gatsby Sites.
*   [Gatsby + Headless WordPress + Netlify Starter](https://github.com/justinwhall/gatsby-wordpress-netlify-starter) - A Gatsby + WordPress starter for continuous deployment to Netlify.
*   [Gatsby WordPress Starter Advanced](https://github.com/henrikwirth/gatsby-starter-wordpress-advanced) - An advanced Gatsby + WordPress starter, that is built along a tutorial series and works with ACF flexible content fields to create content blocks/layouts.
*   [Gatsby Starter Blog](https://github.com/zeevo/gatsby-starter-wordpress-blog) - Blog starter with enough features to be production ready out of the box.

## Themes

List of gatsby-themes that work with WordPress as a source, which you can use in your Gatsby setup.

*   [Twenty Nineteen Gatsby Theme](https://github.com/zgordon/twentynineteen-gatsby-theme) - A port of the Twenty Nineteen WordPress Theme over to Gatsby.
*   [Gatsby WordPress Publisher Theme
    ](https://github.com/staticfuse/gatsby-theme-publisher) - The Gatsby Publisher Theme allows you to create a headless (or decoupled) WordPress site. This theme will display all of your pages and posts in a static front-end built on React and Gatsby.

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/henrikwirth/awesome-wordpress-gatsby/blob/master/README.md/contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Henrik Wirth has waived all copyright and
related or neighboring rights to this work.

<!--- unicorn --->

