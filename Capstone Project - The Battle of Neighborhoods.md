





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-67V2J9Se2CifJlftk9/cExHGvxd7N9b9EdGnQEpszu99Ogeecilu9jIDxoCkx3zNLfB9ArraXW0J03qyVmN0Uw==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-e7318add1f7e055d040edb0f75aaa0ba.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-m3Ej6i/Pcrccby7PC+1McGjyuF9icy/BSv8IAj6kU0sgVl3Pf6ZIBwb01ST1x2Rb+q5z5trV9y2W8woD58qK0A==" rel="stylesheet" href="https://github.githubassets.com/assets/github-f4279344f797f282848193392bae6f6f.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>Coursera_Capstone/Capstone Project - The Battle of Neighborhoods.md at master · gnokit/Coursera_Capstone</title>
    <meta name="description" content="A repository for the assignment of Applied Data Science Capstone course - gnokit/Coursera_Capstone">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars3.githubusercontent.com/u/155364?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="gnokit/Coursera_Capstone" /><meta name="twitter:description" content="A repository for the assignment of Applied Data Science Capstone course - gnokit/Coursera_Capstone" />
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/155364?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="gnokit/Coursera_Capstone" /><meta property="og:url" content="https://github.com/gnokit/Coursera_Capstone" /><meta property="og:description" content="A repository for the assignment of Applied Data Science Capstone course - gnokit/Coursera_Capstone" />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDIzOTIyMTkwOjFlMTk1MWIxZjhlN2RlZWQzMjVkODExMDkzYzdhMTVjZjRlNzQyMTgxZmFiMmNiM2VhYjQwYmRhYTEwNzA2YzM=--8d22933fa0c34fe98f5ad62ca86278529215d7e0">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="10E1:169B:7F2A51:B37EC6:5D2AC52F" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="10E1:169B:7F2A51:B37EC6:5D2AC52F" /><meta name="octolytics-dimension-region_edge" content="ap-south-1" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-actor-id" content="36091390" /><meta name="octolytics-actor-login" content="PayyalaNiranjan" /><meta name="octolytics-actor-hash" content="e236f558c0a3689d11c6dc80c960a644387d5e7730cd79a0e60ffd21083b899b" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="d04dbf8189471633414c3e573376c6cb">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="PayyalaNiranjan">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MDZkOGY2NzFjMDBhNmVkMDVjYjUyNDFkMWY5ZmMyNmQyM2YyNmUzY2E1NjJlOWZjMzk2MTgwYjc2ZGQwZTU5YXx7InJlbW90ZV9hZGRyZXNzIjoiMTA2LjIwMy42MC4xNjAiLCJyZXF1ZXN0X2lkIjoiMTBFMToxNjlCOjdGMkE1MTpCMzdFQzY6NUQyQUM1MkYiLCJ0aW1lc3RhbXAiOjE1NjMwODQwNzksImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PULL_PANDA_HOMEPAGE,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,DISPLAY_COMMENTER_FULL_NAME">

  <meta name="html-safe-nonce" content="bd207ac1b305c7737da15c1ebd51b1b2bc078f0f">

  <meta http-equiv="x-pjax-version" content="41b9ff63b8f4ee38c8cca1ecdadf550e">
  

      <link href="https://github.com/gnokit/Coursera_Capstone/commits/master.atom" rel="alternate" title="Recent Commits to Coursera_Capstone:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/gnokit/Coursera_Capstone git https://github.com/gnokit/Coursera_Capstone.git">

  <meta name="octolytics-dimension-user_id" content="155364" /><meta name="octolytics-dimension-user_login" content="gnokit" /><meta name="octolytics-dimension-repository_id" content="147900019" /><meta name="octolytics-dimension-repository_nwo" content="gnokit/Coursera_Capstone" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="147900019" /><meta name="octolytics-dimension-repository_network_root_nwo" content="gnokit/Coursera_Capstone" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-enabled" content="true">



  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="147900019" data-scoped-search-url="/gnokit/Coursera_Capstone/search" data-unscoped-search-url="/search" action="/gnokit/Coursera_Capstone/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=satZ5E8HbmhirdDir5kI9UxzdOT2lLDq5OA2fZywQr5oAZbXhhfvzyVq3F9WtQIxrHAaRjotm3ek+s82F3pQUA=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      
    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>

    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-label="View profile and more" aria-expanded="false" aria-haspopup="false" href="https://github.com/PayyalaNiranjan">
      <img class="avatar" src="https://avatars1.githubusercontent.com/u/36091390?s=40&amp;v=4" width="20" height="20" alt="@PayyalaNiranjan" />
      PayyalaNiranjan
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="SHa+6UrVtBlkjAddLJEbnvSZrLPBL6Kj25cb/UxZDtZW0KFh5qiU5+twUYx1jhC6JsW/IMffxVptLRFnGCDY+w==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/gnokit">gnokit</a>
    /
    <a class="Header-link" href="/gnokit/Coursera_Capstone">Coursera_Capstone</a>

</div>
    </div>

    <div class="Header-item position-relative d-none d-lg-flex">
      

    </div>

    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:36091390" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="gnokit/Coursera_Capstone">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/gnokit/Coursera_Capstone/issues/new" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
<details class="details-overlay details-reset">
  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@PayyalaNiranjan" class="avatar" src="https://avatars1.githubusercontent.com/u/36091390?s=40&amp;v=4" height="20" width="20">
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/PayyalaNiranjan" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">PayyalaNiranjan</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit " aria-haspopup="dialog" role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:155364,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:36091390,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;}}" data-hydro-click-hmac="051d4eeab994f00c5b8cbd6010ccf44c7de9346d82cf6fc2436dcd37b462c94c">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <g-emoji alias="thought_balloon" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4ad.png">💭</g-emoji>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
                <span>Free to Connect</span>
          </div>
        </div>
      </div>
</summary>    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="lip1U9Rz1enoS8jvyjsfBfULftHGWUY5STyIlr0CjHYGtEy07ff43Hu9J58pBfMb73Xk3bg5H8PTLy5CzalRlg==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value="Free to Connect"
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-07-14T12:01:19+05:30">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-07-14T12:31:19+05:30">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-07-14T15:31:19+05:30">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-07-14T23:59:59+05:30">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-07-14T23:59:59+05:30">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit"  class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button"  class="width-full js-clear-user-status-button btn ml-2 js-user-status-exists">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/PayyalaNiranjan" data-ga-click="Header, go to profile, text:your profile">Your profile</a>
    <a role="menuitem" class="dropdown-item" href="/PayyalaNiranjan?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/PayyalaNiranjan?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/PayyalaNiranjan?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>


    <div role="none" class="dropdown-divider"></div>
    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Hf8NXFCYHLu3gznWA/jwf5QufF6/kqwB/fQ2B7yZ/A0DWRLU/OU8RTh/bwda5/tbRnJvzbliy/hLTjyd6OAqIA==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  








  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="mtvZjPz71ZYe5inUyPm2eKCJZpwk/ZF0A7Np4+maQaoKDfl+7FyDMotcZE4EWty4I25yKAcJjgaF23+5BTpvmg==" />      <input type="hidden" name="repository_id" value="147900019">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:147900019,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;,&quot;user_id&quot;:36091390}}" data-hydro-click-hmac="a490adaa93b9756587a593c39c3ac6f0f52e4ef51c60b907cd9337a918a2bdd1" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/gnokit/Coursera_Capstone/watchers"
          aria-label="2 users are watching this repository">
          2
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/gnokit/Coursera_Capstone/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="+l8exZDSvcYpJWPQ/37ml4f/PZ8anIU8l8IqAN18a4n0rCyP/2oXLN4VKy9sPfvIP+NB17KL4ju885BB36/MkA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar gnokit/Coursera_Capstone" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:147900019,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;,&quot;user_id&quot;:36091390}}" data-hydro-click-hmac="23826aaa1502206af8c3a8ef4521cb8d7405c09d13c45c54b74f469a56d9b438" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/gnokit/Coursera_Capstone/stargazers"
           aria-label="0 users starred this repository">
           0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/gnokit/Coursera_Capstone/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="QICRIBxen627tJzIzgwpbk5ii4XuaQxjZ77K5P3FFUPOp96asskO2kIzreUq/K+7aMaVA1/AJKzjBLBUHmID8A==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star gnokit/Coursera_Capstone" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:147900019,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;,&quot;user_id&quot;:36091390}}" data-hydro-click-hmac="98aa771bce024d7d6729ef26b36b6f3f105154b36ff3c2f5ebc9c269349bdbe9" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/gnokit/Coursera_Capstone/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/gnokit/Coursera_Capstone/fork" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="eCMSzw+IgfAaA/ngaQ+okHwRUexflFNVBBPX3CqFX3Xl7/0S78qIZsha656NW7rhQx+qsxrZ6kN4JIfVBB5Xjw==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:147900019,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;,&quot;user_id&quot;:36091390}}" data-hydro-click-hmac="b727b9555683a61f5725b36473a1975de79be56c992c1ff8c29dfa5da5a4f8f6" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of gnokit/Coursera_Capstone to your account" aria-label="Fork your own copy of gnokit/Coursera_Capstone to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
</button></form>
    <a href="/gnokit/Coursera_Capstone/network/members" class="social-count"
       aria-label="14 users forked this repository">
      14
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=155364" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/gnokit">gnokit</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/gnokit/Coursera_Capstone">Coursera_Capstone</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /gnokit/Coursera_Capstone" href="/gnokit/Coursera_Capstone">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /gnokit/Coursera_Capstone/issues" href="/gnokit/Coursera_Capstone/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /gnokit/Coursera_Capstone/pulls" href="/gnokit/Coursera_Capstone/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /gnokit/Coursera_Capstone/projects" href="/gnokit/Coursera_Capstone/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /gnokit/Coursera_Capstone/wiki" href="/gnokit/Coursera_Capstone/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy /gnokit/Coursera_Capstone/security/advisories" href="/gnokit/Coursera_Capstone/security/advisories">
      <svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /gnokit/Coursera_Capstone/pulse" href="/gnokit/Coursera_Capstone/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /gnokit/Coursera_Capstone" href="/gnokit/Coursera_Capstone">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /gnokit/Coursera_Capstone/issues" href="/gnokit/Coursera_Capstone/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /gnokit/Coursera_Capstone/pulls" href="/gnokit/Coursera_Capstone/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /gnokit/Coursera_Capstone/projects" href="/gnokit/Coursera_Capstone/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /gnokit/Coursera_Capstone/wiki" href="/gnokit/Coursera_Capstone/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy /gnokit/Coursera_Capstone/security/advisories" href="/gnokit/Coursera_Capstone/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /gnokit/Coursera_Capstone/pulse" href="/gnokit/Coursera_Capstone/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /gnokit/Coursera_Capstone/community" href="/gnokit/Coursera_Capstone/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  
    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/gnokit/Coursera_Capstone/blob/38216a7fca3fadf9d2b0582048ce2f1bd90ea95f/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:8d50f02437293c5bb738b665464d7297 -->
      

    <div class="d-flex flex-items-start flex-shrink-0 mb-2 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target">master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/gnokit/Coursera_Capstone/ref-list/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/gnokit/Coursera_Capstone/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="Capstone Project - The Battle of Neighborhoods.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/gnokit/Coursera_Capstone"><span>Coursera_Capstone</span></a></span></span><span class="separator">/</span><strong class="final-path">Capstone Project - The Battle of Neighborhoods.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/gnokit/Coursera_Capstone/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="Capstone Project - The Battle of Neighborhoods.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="author" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=155364" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/gnokit"><img class="avatar" src="https://avatars0.githubusercontent.com/u/155364?s=40&amp;v=4" width="20" height="20" alt="@gnokit" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=155364" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/gnokit">gnokit</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="add flow diagram and more explanation" class="link-gray" href="/gnokit/Coursera_Capstone/commit/38216a7fca3fadf9d2b0582048ce2f1bd90ea95f">add flow diagram and more explanation</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/gnokit/Coursera_Capstone/commit/38216a7fca3fadf9d2b0582048ce2f1bd90ea95f" data-pjax>38216a7</a>
          <relative-time datetime="2018-10-04T01:33:20Z">Oct 4, 2018</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link" aria-haspopup="dialog">
          <span><strong>1</strong> contributor</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/gnokit/Coursera_Capstone/contributors/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md/list" preload>
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
        </details-dialog>
      </details>
    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      420 lines (307 sloc)
      <span class="file-info-divider"></span>
    20.1 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/gnokit/Coursera_Capstone/raw/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/gnokit/Coursera_Capstone/blame/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/gnokit/Coursera_Capstone/commits/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/gnokit/Coursera_Capstone/edit/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="EEQWOKuBh2TvzWZ6AuHjNmhlOgg4pavEGHcY6/bJrxN8KzckNQTzHrRNC4l2U2yWphsNK7BODUmLQY1e5zhGqQ==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/gnokit/Coursera_Capstone/delete/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="fAbiS7UTwm74VRDvGT0utUJkaEkQbXkjhUJSmgogNMv4EgWAtqAbNi3Rpu34gtJGCflDjUlFQ4n3LRuGEAKlIw==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete the file in your fork of this project" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><h1><a id="user-content-find-location-to-build-new-cinema-in-hong-kong" class="anchor" aria-hidden="true" href="#find-location-to-build-new-cinema-in-hong-kong"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find Location to Build New Cinema in Hong Kong</h1>
<p>Capstone Project - The Battle of Neighbourhoods</p>
<h2><a id="user-content-introduction" class="anchor" aria-hidden="true" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Introduction</h2>
<h4><a id="user-content-would-you-recommend-a-location-in-hong-kong-to-open-a-new-cinema" class="anchor" aria-hidden="true" href="#would-you-recommend-a-location-in-hong-kong-to-open-a-new-cinema"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>"Would you recommend a location in Hong Kong to open a new cinema?"</h4>
<p>My boss, the stakeholder wants to <strong>open a new cinema as company's new business</strong>.</p>
<p>He explains that watching movie is a part of whole afternoon or night activities. Cinema should have <strong>many restaurants and shopping places nearby</strong>. Transportation is also an important factor. Customer can walk to cinema within <strong>5 minutes</strong> from <strong>public transport facilities</strong> is perfect.</p>
<p>He wants me concentrated on selection of cinema location according to its nearby environment. Cinema facility and rental price is not my concern. He lists out his <strong>top 10 favourite cinemas</strong> in Hong Kong with rating.</p>
<p>I work with my teammates and select <strong>5 possible locations</strong> to build the cinema. Which location should be suggested to the stakeholder?</p>
<h2><a id="user-content-data" class="anchor" aria-hidden="true" href="#data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data</h2>
<p>According to the question, following data are required.</p>
<h3><a id="user-content-1-geographic-coordinate-of-hong-kong-cinemas" class="anchor" aria-hidden="true" href="#1-geographic-coordinate-of-hong-kong-cinemas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1. Geographic coordinate of Hong Kong cinemas</h3>
<p>I need to <strong>compare 5 possible locations with current cinemas</strong> in Hong Kong. Therefore, I need to find a list of Hong Kong cinema and cinemas' geographic coordinates. Luckily, I can find the list and coordinates from the website <a href="https://hkmovie6.com/cinema" rel="nofollow">https://hkmovie6.com/cinema</a> . the data is downloaded and converted into dataframe. the first 5 entries are shown on below table.</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Chinese Name</th>
<th>Address</th>
<th>Latitude</th>
<th>Longitude</th>
</tr>
</thead>
<tbody>
<tr>
<td>Emperor Cinemas - Entertainment Building</td>
<td>英皇戲院 - 娛樂行</td>
<td>3/F, Emperor Cinemas Entertainment Building, 3...</td>
<td>22.281453</td>
<td>114.154230</td>
</tr>
<tr>
<td>The Coronet @ Emperor Cinemas - Entertainment ...</td>
<td>The Coronet @ 英皇戲院 - 娛樂行</td>
<td>3/F, Emperor Cinemas Entertainment Building, 3...</td>
<td>22.281453</td>
<td>114.154230</td>
</tr>
<tr>
<td>Emperor Cinemas - Tuen Mun</td>
<td>英皇戲院 - 屯門新都商場</td>
<td>3/F, New Town Commercial Arcade, 2 Tuen Lee St...</td>
<td>22.390776</td>
<td>113.975983</td>
</tr>
<tr>
<td>Broadway Circuit - CYBERPORT</td>
<td>百老匯戲院 - 數碼港</td>
<td>Shop L1 - 3, Level 1, the Arcade, 100 Cyberpor...</td>
<td>22.261067</td>
<td>114.129825</td>
</tr>
<tr>
<td>Broadway Circuit - PALACE IFC</td>
<td>百老匯戲院 - PALACE IFC</td>
<td>Podium L1, IFC Mall, 8 Finance Street, Central</td>
<td>22.285545</td>
<td>114.157979</td>
</tr>
</tbody>
</table>
<h3><a id="user-content-2-geographic-coordinates-of-5-possible-cinema-addresses" class="anchor" aria-hidden="true" href="#2-geographic-coordinates-of-5-possible-cinema-addresses"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2. Geographic coordinates of 5 possible cinema addresses</h3>
<p>Geographic coordinates of 5 possible cinemas are required and I can use Google Map API to find this information.</p>
<table>
<thead>
<tr>
<th>Location</th>
<th>Address</th>
<th>Latitude</th>
<th>Longitude</th>
</tr>
</thead>
<tbody>
<tr>
<td>L1</td>
<td>Sau Mau Ping Shopping Centre, Sau Mau Ping</td>
<td>22.319503</td>
<td>114.232187</td>
</tr>
<tr>
<td>L2</td>
<td>Tuen Mun Ferry, Tuen Mun</td>
<td>22.371780</td>
<td>113.966039</td>
</tr>
<tr>
<td>L3</td>
<td>Un Chau Shopping Centre, Cheung Sha Wan</td>
<td>22.337280</td>
<td>114.156457</td>
</tr>
<tr>
<td>L4</td>
<td>Prosperity Millennia Plaza, North Point</td>
<td>22.291698</td>
<td>114.208168</td>
</tr>
<tr>
<td>L5</td>
<td>Tsuen Fung Centre Shopping Arcade, Tsuen Wan</td>
<td>22.372112</td>
<td>114.119317</td>
</tr>
</tbody>
</table>
<h3><a id="user-content-3-favourite-cinema-list-of-stakeholders" class="anchor" aria-hidden="true" href="#3-favourite-cinema-list-of-stakeholders"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3. Favourite cinema list of stakeholders</h3>
<p>The favourite cinema list of stakeholder is an important information that I can <strong>use it as profile to select the best location</strong>.</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Rating</th>
</tr>
</thead>
<tbody>
<tr>
<td>Broadway Circuit - MONGKOK</td>
<td>4.5</td>
</tr>
<tr>
<td>Broadway Circuit - the ONE</td>
<td>4.5</td>
</tr>
<tr>
<td>Grand Ocean</td>
<td>4.3</td>
</tr>
<tr>
<td>The Grand Cinema</td>
<td>3.4</td>
</tr>
<tr>
<td>AMC Pacific Place</td>
<td>2.3</td>
</tr>
<tr>
<td>UA IMAX @ Airport</td>
<td>1.5</td>
</tr>
</tbody>
</table>
<h3><a id="user-content-4-eating-shopping-and-public-transportation-facility-around-cinema" class="anchor" aria-hidden="true" href="#4-eating-shopping-and-public-transportation-facility-around-cinema"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4. Eating, Shopping and Public transportation facility around cinema</h3>
<p>The recommended cinema location needs to have many eating and shopping venues nearby. Convenient public transport is also required.
These data can be found by using FourSquare API to find these venues around the location. the radius of exploration distance is set to 500 meters, which is about 5 minutes walking distance.</p>
<p>Following type of venue category will be used for the study</p>
<pre><code>'Food, Shop &amp; Service, Bus Stop, Metro Station, Nightlife Spot, Arts &amp; Entertainment'
</code></pre>
<p>Let's use FourSquare API to query some venues around the first cinema (英皇戲院 - 娛樂行) in the cinema list. Only first 5 venues in the category are shown below.</p>
<ul>
<li>
<p>Metro Station</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Tips</th>
<th>Users</th>
<th>Visits</th>
</tr>
</thead>
<tbody>
<tr>
<td>MTR Central Station (港鐵中環站)</td>
<td>22.281911</td>
<td>114.158406</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>MTR Hong Kong Station (港鐵香港站)</td>
<td>22.284926</td>
<td>114.158314</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
</li>
<li>
<p>Bus Stop</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Tips</th>
<th>Users</th>
<th>Visits</th>
</tr>
</thead>
<tbody>
<tr>
<td>Seymour Road / Robinson Road Bus Stop 西摩道／羅便臣道巴士站</td>
<td>22.280465</td>
<td>114.150347</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Douglas Street Bus Stop 德忌利士街巴士站</td>
<td>22.283273</td>
<td>114.156910</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Hang Seng Bank Headquarters / Connaught Road C...</td>
<td>22.284741</td>
<td>114.156404</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>HSBC Headquarters Bus Stop 匯豐總行巴士站</td>
<td>22.280577</td>
<td>114.159446</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Dr. Sun Yat-Sen Museum Bus Stop 孫中山紀念館巴士站</td>
<td>22.279132</td>
<td>114.152743</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
</li>
<li>
<p>Food</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Tips</th>
<th>Users</th>
<th>Visits</th>
</tr>
</thead>
<tbody>
<tr>
<td>Mana! Fast Slow Food</td>
<td>22.282921</td>
<td>114.154651</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Good Luck Thai Food (鴻運泰國美食)</td>
<td>22.281165</td>
<td>114.155296</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Soul Food</td>
<td>22.281668</td>
<td>114.152495</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Chiu Lung Fast Food (昭隆美食)</td>
<td>22.282659</td>
<td>114.156753</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Sun Hing Fast Food (新興美食)</td>
<td>22.282521</td>
<td>114.156717</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
</li>
<li>
<p>Arts &amp; Entertainment</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Tips</th>
<th>Users</th>
<th>Visits</th>
</tr>
</thead>
<tbody>
<tr>
<td>Tai Kwun Centre for Heritage and Arts (大館古蹟及藝術館)</td>
<td>22.281668</td>
<td>114.154216</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Wah Tung China Arts Limited (華通陶瓷藝術有限公司)</td>
<td>22.283046</td>
<td>114.152723</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Ravenel Fine Arts Limited 睿芙奧</td>
<td>22.281819</td>
<td>114.156906</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Ben Brown Fine Arts</td>
<td>22.281853</td>
<td>114.157285</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>KONG Arts Space</td>
<td>22.281751</td>
<td>114.153300</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
</li>
</ul>
<h2><a id="user-content-methodology" class="anchor" aria-hidden="true" href="#methodology"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Methodology</h2>
<p>With above data, I can use content-based recommendation technique to resolve the problem.</p>
<p>Combine with FourSquare API which provides how many venues in different category of Hong Kong cinemas, a matrix which captured characteristic of venues nearby cinema are built. Stakeholder's favourite list is the profile to combine with the matrix to become a weighted matrix of favourite cinema.</p>
<p>The weighted matrix can be applied on 5 target locations with venues information to generate a ranking result. the top one on the ranking list can be recommended to the stakeholder.</p>
<p>Before building the matrix, I must prepare the required data and apply some data analysis.</p>
<h3><a id="user-content-data-cleansing-and-preparation" class="anchor" aria-hidden="true" href="#data-cleansing-and-preparation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data Cleansing and Preparation</h3>
<p>Some duplicated cinemas are found. These cinemas are some "Special House" inside cinema and should be removed</p>
<p>Duplicated records</p>
<table>
<thead>
<tr>
<th></th>
<th>Name</th>
<th>Chinese Name</th>
<th>Address</th>
<th>Latitude</th>
<th>Longitude</th>
</tr>
</thead>
<tbody>
<tr>
<td>5</td>
<td>Cinema City VICTORIA (Causeway Bay)</td>
<td>Cinema City VICTORIA (銅鑼灣)</td>
<td>2-8 Sugar Street, Causeway Bay, Hong Kong</td>
<td>22.279805</td>
<td>114.187126</td>
</tr>
<tr>
<td>6</td>
<td>Diamond Suite VIP House @ Cinema City VICTORIA...</td>
<td>Diamond Suite VIP House @ Cinema City VICTORIA...</td>
<td>2-8 Sugar Street, Causeway Bay, Hong Kong</td>
<td>22.279805</td>
<td>114.187126</td>
</tr>
<tr>
<td>28</td>
<td>tde Grand Cinema</td>
<td>The Grand Cinema</td>
<td>2/F, Elements, 1 Austin Road West, Kowloon</td>
<td>22.304118</td>
<td>114.161466</td>
</tr>
<tr>
<td>29</td>
<td>tde Grand SC Starsuite</td>
<td>The Grand SC Starsuite</td>
<td>2/F, Elements, 1 Austin Road West, Kowloon</td>
<td>22.304118</td>
<td>114.161466</td>
</tr>
<tr>
<td>0</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>英皇戲院 - 娛樂行</td>
<td>3/F, Emperor Cinemas Entertainment Building, 3...</td>
<td>22.281453</td>
<td>114.154230</td>
</tr>
<tr>
<td>1</td>
<td>tde Coronet @ Emperor Cinemas - Entertainment ...</td>
<td>The Coronet @ 英皇戲院 - 娛樂行</td>
<td>3/F, Emperor Cinemas Entertainment Building, 3...</td>
<td>22.281453</td>
<td>114.154230</td>
</tr>
<tr>
<td>43</td>
<td>BEA IMAX @ UA iSQUARE</td>
<td>BEA IMAX @ UA iSQUARE</td>
<td>7/F, iSQUARE, 63 Nathan Road, Tsimshatsui</td>
<td>22.296648</td>
<td>114.171974</td>
</tr>
<tr>
<td>46</td>
<td>Phoenix Club @ UA iSQUARE</td>
<td>鳯凰影院 @ UA iSQUARE</td>
<td>7/F, iSQUARE, 63 Nathan Road, Tsimshatsui</td>
<td>22.296648</td>
<td>114.171974</td>
</tr>
<tr>
<td>49</td>
<td>UA iSQUARE</td>
<td>UA iSQUARE</td>
<td>7/F, iSQUARE, 63 Nathan Road, Tsimshatsui</td>
<td>22.296648</td>
<td>114.171974</td>
</tr>
<tr>
<td>42</td>
<td>BEA IMAX @ UA Cine Moko</td>
<td>BEA IMAX @ UA Cine Moko</td>
<td>L4, MOKO, 193 Prince Edward Road West, Mongkok...</td>
<td>22.323800</td>
<td>114.172000</td>
</tr>
<tr>
<td>48</td>
<td>UA Cine Moko</td>
<td>UA Cine Moko</td>
<td>L4, MOKO, 193 Prince Edward Road West, Mongkok...</td>
<td>22.323800</td>
<td>114.172000</td>
</tr>
<tr>
<td>44</td>
<td>BEA IMAX @ UA MegaBox</td>
<td>BEA IMAX @ UA MegaBox</td>
<td>Level 11, MegaBox, Enterprise Square 5, 38 Wan...</td>
<td>22.319533</td>
<td>114.208555</td>
</tr>
<tr>
<td>45</td>
<td>BEA Oscars Club @ UA MegaBox</td>
<td>BEA Oscars Club @ UA MegaBox</td>
<td>Level 11, MegaBox, Enterprise Square 5, 38 Wan...</td>
<td>22.319533</td>
<td>114.208555</td>
</tr>
<tr>
<td>51</td>
<td>UA MegaBox</td>
<td>UA MegaBox</td>
<td>Level 11, MegaBox, Enterprise Square 5, 38 Wan...</td>
<td>22.319533</td>
<td>114.208555</td>
</tr>
</tbody>
</table>
<p>The cinema '新光戲院大劇場' and '大館' in the cinema list should not be considered as cinema in Hong Kong. These records must be removed too. Finally, there are 58 cinemas in Hong Kong will be used to resolve the problem.</p>
<p>Display first 5 records of Hong Kong Cinemas after cleansing.</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Address</th>
<th>Latitude</th>
<th>Longitude</th>
</tr>
</thead>
<tbody>
<tr>
<td>Emperor Cinemas - Entertainment Building</td>
<td>3/F, Emperor Cinemas Entertainment Building, 3...</td>
<td>22.281453</td>
<td>114.154230</td>
</tr>
<tr>
<td>Emperor Cinemas - Tuen Mun</td>
<td>3/F, New Town Commercial Arcade, 2 Tuen Lee St...</td>
<td>22.390776</td>
<td>113.975983</td>
</tr>
<tr>
<td>Broadway Circuit - CYBERPORT</td>
<td>Shop L1 - 3, Level 1, the Arcade, 100 Cyberpor...</td>
<td>22.261067</td>
<td>114.129825</td>
</tr>
<tr>
<td>Broadway Circuit - PALACE IFC</td>
<td>Podium L1, IFC Mall, 8 Finance Street, Central</td>
<td>22.285545</td>
<td>114.157979</td>
</tr>
<tr>
<td>Cinema City VICTORIA (Causeway Bay)</td>
<td>2-8 Sugar Street, Causeway Bay, Hong Kong</td>
<td>22.279805</td>
<td>114.187126</td>
</tr>
</tbody>
</table>
<p>Now I can use the FourSquare API to explore nearby venues of Hong Kong cinemas. Total 2223 venues are found from FourSquare.</p>
<p>Display first 5 records as example</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Cinema Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Name</th>
<th>Tips</th>
<th>Users</th>
<th>Visits</th>
</tr>
</thead>
<tbody>
<tr>
<td>Food</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>22.282921</td>
<td>114.154651</td>
<td>Mana! Fast Slow Food</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Food</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>22.281165</td>
<td>114.155296</td>
<td>Good Luck Thai Food (鴻運泰國美食)</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Food</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>22.281668</td>
<td>114.152495</td>
<td>Soul Food</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Food</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>22.282659</td>
<td>114.156753</td>
<td>Chiu Lung Fast Food (昭隆美食)</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>Food</td>
<td>Emperor Cinemas - Entertainment Building</td>
<td>22.282521</td>
<td>114.156717</td>
<td>Sun Hing Fast Food (新興美食)</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
<p>Number of venues in each category</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Count</th>
</tr>
</thead>
<tbody>
<tr>
<td>Shop &amp; Service</td>
<td>874</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>704</td>
</tr>
<tr>
<td>Food</td>
<td>518</td>
</tr>
<tr>
<td>Arts &amp; Entertainment</td>
<td>65</td>
</tr>
<tr>
<td>Metro Station</td>
<td>61</td>
</tr>
<tr>
<td>Nightlife Spot</td>
<td>1</td>
</tr>
</tbody>
</table>
<p>Explore venues around the target locations and show the value count in each category.</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Count</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bus Stop</td>
<td>36</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>30</td>
</tr>
<tr>
<td>Food</td>
<td>12</td>
</tr>
<tr>
<td>Metro Station</td>
<td>4</td>
</tr>
<tr>
<td>Arts &amp; Entertainment</td>
<td>1</td>
</tr>
</tbody>
</table>
<p>As only one venue is found in 'Nightlife Spot' category, and no 'Nightlife Spot' venue is found in 5 target locations, the category is removed.</p>
<p>Moreover, no tips, users, and visits count is found. These columns are dropped too. Finally, 2222 venues are found in Hong Kong cinema list and 83 venues are found in target locations list.</p>
<table>
<thead>
<tr>
<th>Location</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>L1</td>
<td>0.0</td>
<td>1.0</td>
<td>0.0</td>
<td>0.0</td>
<td>3.0</td>
</tr>
<tr>
<td>L2</td>
<td>0.0</td>
<td>4.0</td>
<td>2.0</td>
<td>0.0</td>
<td>1.0</td>
</tr>
<tr>
<td>L3</td>
<td>0.0</td>
<td>9.0</td>
<td>4.0</td>
<td>1.0</td>
<td>9.0</td>
</tr>
<tr>
<td>L4</td>
<td>1.0</td>
<td>9.0</td>
<td>2.0</td>
<td>1.0</td>
<td>5.0</td>
</tr>
<tr>
<td>L5</td>
<td>0.0</td>
<td>13.0</td>
<td>4.0</td>
<td>2.0</td>
<td>12.0</td>
</tr>
</tbody>
</table>
<p>Stakeholder's favourite cinemas</p>
<table>
<thead>
<tr>
<th></th>
<th>Name</th>
<th>Rating</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>Broadway Circuit - MONGKOK</td>
<td>4.5</td>
</tr>
<tr>
<td>1</td>
<td>Broadway Circuit - the ONE</td>
<td>4.5</td>
</tr>
<tr>
<td>2</td>
<td>Grand Ocean</td>
<td>4.3</td>
</tr>
<tr>
<td>3</td>
<td>tde Grand Cinema</td>
<td>3.4</td>
</tr>
<tr>
<td>4</td>
<td>AMC Pacific Place</td>
<td>2.3</td>
</tr>
<tr>
<td>5</td>
<td>UA IMAX @ Airport</td>
<td>1.5</td>
</tr>
</tbody>
</table>
<h3><a id="user-content-data-analysis" class="anchor" aria-hidden="true" href="#data-analysis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data Analysis</h3>
<p>Check the data type of variables</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Data Type</th>
</tr>
</thead>
<tbody>
<tr>
<td>Arts &amp; Entertainment</td>
<td>float64</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>float64</td>
</tr>
<tr>
<td>Food</td>
<td>float64</td>
</tr>
<tr>
<td>Metro Station</td>
<td>float64</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>float64</td>
</tr>
</tbody>
</table>
<p>All datatype is numeric</p>
<p>Generates descriptive statistics that summarize the central tendency,
dispersion and shape of a dataset's distribution</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>count</td>
<td>57.000000</td>
<td>57.000000</td>
<td>57.000000</td>
<td>57.000000</td>
<td>57.000000</td>
</tr>
<tr>
<td>mean</td>
<td>1.140351</td>
<td>12.350877</td>
<td>9.087719</td>
<td>1.070175</td>
<td>15.333333</td>
</tr>
<tr>
<td>std</td>
<td>2.430745</td>
<td>9.510316</td>
<td>8.018462</td>
<td>0.820706</td>
<td>10.736010</td>
</tr>
<tr>
<td>min</td>
<td>0.000000</td>
<td>1.000000</td>
<td>0.000000</td>
<td>0.000000</td>
<td>2.000000</td>
</tr>
<tr>
<td>25%</td>
<td>0.000000</td>
<td>5.000000</td>
<td>2.000000</td>
<td>1.000000</td>
<td>6.000000</td>
</tr>
<tr>
<td>50%</td>
<td>0.000000</td>
<td>9.000000</td>
<td>6.000000</td>
<td>1.000000</td>
<td>11.000000</td>
</tr>
<tr>
<td>75%</td>
<td>1.000000</td>
<td>21.000000</td>
<td>16.000000</td>
<td>1.000000</td>
<td>30.000000</td>
</tr>
<tr>
<td>max</td>
<td>12.000000</td>
<td>30.000000</td>
<td>27.000000</td>
<td>4.000000</td>
<td>30.000000</td>
</tr>
</tbody>
</table>
<p>Cinema really has many 'Bus Stop', 'Food', 'Shop &amp; Service' venues around. However, it is unusual that a cinema has 4 metro stations nearby (within 500 meters).</p>
<p>Display cinema contains 3 or more 'Metro Station' around</p>
<table>
<thead>
<tr>
<th></th>
<th>Category</th>
<th>Cinema Name</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Name</th>
</tr>
</thead>
<tbody>
<tr>
<td>609</td>
<td>Metro Station</td>
<td>Broadway Circuit - the ONE</td>
<td>22.297150</td>
<td>114.172230</td>
<td>MTR Tsim Sha Tsui Station (港鐵尖沙咀站)</td>
</tr>
<tr>
<td>610</td>
<td>Metro Station</td>
<td>Broadway Circuit - the ONE</td>
<td>22.304787</td>
<td>114.171664</td>
<td>MTR Jordan Station (港鐵佐敦站)</td>
</tr>
<tr>
<td>611</td>
<td>Metro Station</td>
<td>Broadway Circuit - the ONE</td>
<td>22.295573</td>
<td>114.173652</td>
<td>MTR East Tsim Sha Tsui Station (港鐵尖東站)</td>
</tr>
<tr>
<td>2180</td>
<td>Metro Station</td>
<td>LUX tdeatre</td>
<td>22.305477</td>
<td>114.188624</td>
<td>MTR Whampoa Station (港鐵黃埔站)</td>
</tr>
<tr>
<td>2181</td>
<td>Metro Station</td>
<td>LUX tdeatre</td>
<td>22.309115</td>
<td>114.182668</td>
<td>MTR Ho Man Tin Station (港鐵何文田站)</td>
</tr>
<tr>
<td>2182</td>
<td>Metro Station</td>
<td>LUX tdeatre</td>
<td>22.303110</td>
<td>114.181630</td>
<td>Mtr Hung Hom Station Platform 2</td>
</tr>
<tr>
<td>2183</td>
<td>Metro Station</td>
<td>LUX tdeatre</td>
<td>22.303085</td>
<td>114.181160</td>
<td>Mtr Hung Hom Station Platform 4</td>
</tr>
</tbody>
</table>
<p>The venue 'Mtr Hung Hom Station Platform 4' is duplicated and should be removed.</p>
<p>Plot the distribution of other variables</p>
<p><a target="_blank" rel="noopener noreferrer" href="/gnokit/Coursera_Capstone/blob/master/output_114_1.png"><img src="/gnokit/Coursera_Capstone/raw/master/output_114_1.png" alt="png" style="max-width:100%;"></a></p>
<p>The distribution of other variables are quite similar. Now check their <strong>Pearson Correlation</strong></p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>Arts &amp; Entertainment</td>
<td>1.000000</td>
<td>0.494525</td>
<td>0.414387</td>
<td>0.389271</td>
<td>0.506590</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>0.494525</td>
<td>1.000000</td>
<td>0.893873</td>
<td>0.563799</td>
<td>0.896388</td>
</tr>
<tr>
<td>Food</td>
<td>0.414387</td>
<td>0.893873</td>
<td>1.000000</td>
<td>0.583749</td>
<td>0.872533</td>
</tr>
<tr>
<td>Metro Station</td>
<td>0.389271</td>
<td>0.563799</td>
<td>0.583749</td>
<td>1.000000</td>
<td>0.499546</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>0.506590</td>
<td>0.896388</td>
<td>0.872533</td>
<td>0.499546</td>
<td>1.000000</td>
</tr>
</tbody>
</table>
<p>It seems that 'Bus Stop', 'Shop &amp; Service' and 'Food' category are highly correlated.
Find <strong>P-Value</strong> of the variables</p>
<p>By convention, when the p-value is:</p>
<ul>
<li>&lt; 0.001 we say there is strong evidence that the correlation is significant,</li>
<li>&lt; 0.05; there is moderate evidence that the correlation is significant,</li>
<li>&lt; 0.1; there is weak evidence that the correlation is significant, and</li>
<li>is &gt;  0.1; there is no evidence that the correlation is significant.</li>
</ul>
<table>
<thead>
<tr>
<th></th>
<th>Category</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>Arts &amp; Entertainment</td>
<td>strong</td>
<td>strong</td>
<td>moderate</td>
<td>moderate</td>
<td>strong</td>
</tr>
<tr>
<td>1</td>
<td>Bus Stop</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
</tr>
<tr>
<td>2</td>
<td>Food</td>
<td>moderate</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
</tr>
<tr>
<td>3</td>
<td>Metro Station</td>
<td>moderate</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
</tr>
<tr>
<td>4</td>
<td>Shop &amp; Service</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
<td>strong</td>
</tr>
</tbody>
</table>
<p>The correlation between 'Bus Stop', 'Food', 'Metro Station' and 'Shop &amp; Service' are statistically significant, and the coefficient of &gt; 0.5 shows that the relationship is positive</p>
<p>Stakeholder's favourite cinema list</p>
<table>
<thead>
<tr>
<th></th>
<th>Name</th>
<th>Rating</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>Broadway Circuit - MONGKOK</td>
<td>4.5</td>
</tr>
<tr>
<td>1</td>
<td>Broadway Circuit - the ONE</td>
<td>4.5</td>
</tr>
<tr>
<td>2</td>
<td>Grand Ocean</td>
<td>4.3</td>
</tr>
<tr>
<td>3</td>
<td>tde Grand Cinema</td>
<td>3.4</td>
</tr>
<tr>
<td>4</td>
<td>AMC Pacific Place</td>
<td>2.3</td>
</tr>
<tr>
<td>5</td>
<td>UA IMAX @ Airport</td>
<td>1.5</td>
</tr>
</tbody>
</table>
<p>Stakeholder further explain that the rating is a range from 1.0 (worst) to 5.0 (best).</p>
<p>Let's visualize the location of cinemas, target location and stakeholder's favourite cinemas on the map</p>
<p><a target="_blank" rel="noopener noreferrer" href="/gnokit/Coursera_Capstone/blob/master/cinema_map.JPG"><img src="/gnokit/Coursera_Capstone/raw/master/cinema_map.JPG" alt="map" style="max-width:100%;"></a></p>
<p>Most of Hong Kong cinemas (blue circle) and stakeholder's favourite cinemas (red circle) location are built near main road and centralized in urban area of Hong Kong.
The target locations (yellow circle) of new cinema are not near to main road.</p>
<h3><a id="user-content-machine-learning" class="anchor" aria-hidden="true" href="#machine-learning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Machine Learning</h3>
<p>Now, let's use <strong>Content-Based</strong> or <strong>Item-Item recommendation systems</strong>. In this case, I am going to try to figure out the boss's favourite new cinema location by counting number of nearby venues and ratings given.</p>
<p>Following diagram explain the steps to create the recommendation
<a target="_blank" rel="noopener noreferrer" href="/gnokit/Coursera_Capstone/blob/master/content-base-filtering.PNG"><img src="/gnokit/Coursera_Capstone/raw/master/content-base-filtering.PNG" alt="content-base-filtering" style="max-width:100%;"></a></p>
<ol>
<li>
<p>Normalize the values of venues dataframe by using MinMaxScaler method and display the first 5 records</p>
<table>
<thead>
<tr>
<th>Cinema Name</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>AMC Pacific Place</td>
<td>0.666667</td>
<td>0.413793</td>
<td>0.296296</td>
<td>0.333333</td>
<td>0.678571</td>
</tr>
<tr>
<td>Broadway Circuit - CINEMAtdEQUE</td>
<td>0.250000</td>
<td>0.827586</td>
<td>0.481481</td>
<td>0.333333</td>
<td>0.821429</td>
</tr>
<tr>
<td>Broadway Circuit - CYBERPORT</td>
<td>0.000000</td>
<td>0.034483</td>
<td>0.037037</td>
<td>0.000000</td>
<td>0.035714</td>
</tr>
<tr>
<td>Broadway Circuit - HOLLYWOOD</td>
<td>0.083333</td>
<td>0.206897</td>
<td>0.000000</td>
<td>0.333333</td>
<td>0.142857</td>
</tr>
<tr>
<td>Broadway Circuit - KINGSWOOD GINZA</td>
<td>0.000000</td>
<td>0.068966</td>
<td>0.000000</td>
<td>0.000000</td>
<td>0.000000</td>
</tr>
</tbody>
</table>
</li>
<li>
<p><strong>Boss Profile</strong> - Join above data with boss's favourite list.</p>
<table>
<thead>
<tr>
<th></th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>0.166667</td>
<td>0.965517</td>
<td>0.666667</td>
<td>0.666667</td>
<td>1.000000</td>
</tr>
<tr>
<td>1</td>
<td>0.250000</td>
<td>0.689655</td>
<td>1.000000</td>
<td>1.000000</td>
<td>1.000000</td>
</tr>
<tr>
<td>2</td>
<td>0.250000</td>
<td>0.586207</td>
<td>0.629630</td>
<td>0.666667</td>
<td>1.000000</td>
</tr>
<tr>
<td>3</td>
<td>0.083333</td>
<td>0.137931</td>
<td>0.074074</td>
<td>0.666667</td>
<td>0.035714</td>
</tr>
<tr>
<td>4</td>
<td>0.666667</td>
<td>0.413793</td>
<td>0.296296</td>
<td>0.333333</td>
<td>0.678571</td>
</tr>
<tr>
<td>5</td>
<td>0.000000</td>
<td>0.103448</td>
<td>0.074074</td>
<td>0.333333</td>
<td>0.357143</td>
</tr>
</tbody>
</table>
</li>
<li>
<p><strong>Recommendation Component</strong> - Dot product to get the weight of rating on each category according to stakeholder's favourite list.</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Weighted Rating</th>
</tr>
</thead>
<tbody>
<tr>
<td>Arts &amp; Entertainment</td>
<td>4.766667</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>11.544828</td>
</tr>
<tr>
<td>Food</td>
<td>11.251852</td>
</tr>
<tr>
<td>Metro Station</td>
<td>13.900000</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>15.517857</td>
</tr>
</tbody>
</table>
</li>
<li>
<p>Normalize the values of target venues by using same MinMaxScaler</p>
<table>
<thead>
<tr>
<th>Location</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>L1</td>
<td>0.000000</td>
<td>0.000000</td>
<td>0.000000</td>
<td>0.000000</td>
<td>0.035714</td>
</tr>
<tr>
<td>L2</td>
<td>0.000000</td>
<td>0.103448</td>
<td>0.074074</td>
<td>0.000000</td>
<td>-0.035714</td>
</tr>
<tr>
<td>L3</td>
<td>0.000000</td>
<td>0.275862</td>
<td>0.148148</td>
<td>0.333333</td>
<td>0.250000</td>
</tr>
<tr>
<td>L4</td>
<td>0.083333</td>
<td>0.275862</td>
<td>0.074074</td>
<td>0.333333</td>
<td>0.107143</td>
</tr>
<tr>
<td>L5</td>
<td>0.000000</td>
<td>0.413793</td>
<td>0.148148</td>
<td>0.666667</td>
<td>0.357143</td>
</tr>
</tbody>
</table>
</li>
<li>
<p><strong>Recommendation List</strong> - With the boss's profile and the complete list of cinemas and their venues count in hand, I am going to take the weighted average of every location based on the profile and recommend the top location that most satisfy it. Following table shows the estimated rating of 5 target locations</p>
<table>
<thead>
<tr>
<th></th>
<th>Location</th>
<th>Address</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Rating</th>
</tr>
</thead>
<tbody>
<tr>
<td>4</td>
<td>L5</td>
<td>Tsuen Fung Centre Shopping Arcade, Tsuen Wan</td>
<td>22.372112</td>
<td>114.119317</td>
<td>0.372980</td>
</tr>
<tr>
<td>2</td>
<td>L3</td>
<td>Un Chau Shopping Centre, Cheung Sha Wan</td>
<td>22.337280</td>
<td>114.156457</td>
<td>0.234543</td>
</tr>
<tr>
<td>3</td>
<td>L4</td>
<td>Prosperity Millennia Plaza, North Point</td>
<td>22.291698</td>
<td>114.208168</td>
<td>0.187982</td>
</tr>
<tr>
<td>1</td>
<td>L2</td>
<td>Tuen Mun Ferry, Tuen Mun</td>
<td>22.371780</td>
<td>113.966039</td>
<td>0.025860</td>
</tr>
<tr>
<td>0</td>
<td>L1</td>
<td>Sau Mau Ping Shopping Centre, Sau Mau Ping</td>
<td>22.319503</td>
<td>114.232187</td>
<td>0.009726</td>
</tr>
</tbody>
</table>
</li>
</ol>
<h2><a id="user-content-results" class="anchor" aria-hidden="true" href="#results"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Results</h2>
<pre><code>I should recommend the location "L5" of address "Tsuen Fung Centre Shopping Arcade, Tsuen Wan" to the stakeholder.
</code></pre>
<p>The result is reasonable. Location "L5" has the greatest number of venues in category "Bus Stop", "Food", "Metro Station" and "Shop &amp; Service".</p>
<table>
<thead>
<tr>
<th>Location</th>
<th>Arts &amp; Entertainment</th>
<th>Bus Stop</th>
<th>Food</th>
<th>Metro Station</th>
<th>Shop &amp; Service</th>
</tr>
</thead>
<tbody>
<tr>
<td>L1</td>
<td>0.0</td>
<td>1.0</td>
<td>0.0</td>
<td>0.0</td>
<td>3.0</td>
</tr>
<tr>
<td>L2</td>
<td>0.0</td>
<td>4.0</td>
<td>2.0</td>
<td>0.0</td>
<td>1.0</td>
</tr>
<tr>
<td>L3</td>
<td>0.0</td>
<td>9.0</td>
<td>4.0</td>
<td>1.0</td>
<td>9.0</td>
</tr>
<tr>
<td>L4</td>
<td>1.0</td>
<td>9.0</td>
<td>2.0</td>
<td>1.0</td>
<td>5.0</td>
</tr>
<tr>
<td>L5</td>
<td>0.0</td>
<td>13.0</td>
<td>4.0</td>
<td>2.0</td>
<td>12.0</td>
</tr>
</tbody>
</table>
<p>Moreover, these categories are most concerned by the stakeholder according to profile rating</p>
<pre><code>Shop &amp; Service          15.517857
Metro Station           13.900000
Bus Stop                11.544828
Food                    11.251852
Arts &amp; Entertainment     4.766667
</code></pre>
<p>Therefore, Location "L5" should be recommended to the stakeholder</p>
<h2><a id="user-content-discussion" class="anchor" aria-hidden="true" href="#discussion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Discussion</h2>
<p>Number of venues of 5 target locations are below the average.</p>
<p>Average count of venues in Hong Kong Cinema</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Average Count</th>
</tr>
</thead>
<tbody>
<tr>
<td>Arts &amp; Entertainment</td>
<td>1.140351</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>12.350877</td>
</tr>
<tr>
<td>Food</td>
<td>9.087719</td>
</tr>
<tr>
<td>Metro Station</td>
<td>1.052632</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>15.333333</td>
</tr>
</tbody>
</table>
<p>Average count of venues in 5 target locations</p>
<table>
<thead>
<tr>
<th>Category</th>
<th>Average Count</th>
</tr>
</thead>
<tbody>
<tr>
<td>Arts &amp; Entertainment</td>
<td>0.2</td>
</tr>
<tr>
<td>Bus Stop</td>
<td>7.2</td>
</tr>
<tr>
<td>Food</td>
<td>2.4</td>
</tr>
<tr>
<td>Metro Station</td>
<td>0.8</td>
</tr>
<tr>
<td>Shop &amp; Service</td>
<td>6.0</td>
</tr>
</tbody>
</table>
<p>I should contact local commercial property agents to find more suitable locations. Moreover, FourSquare is not popular in Hong Kong, the data maybe out-dated or unreliable, the report should gather more data from other location data source such as Google Place API.</p>
<h2><a id="user-content-conclusion" class="anchor" aria-hidden="true" href="#conclusion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Conclusion</h2>
<p>The stakeholder's problem is resolved. Stakeholder wants to find the best place to build a new cinema in Hong Kong, and the factors of "best location" is based on the number of venues in eating, shopping, transportation category around the location. Stakeholder also provide his favourite list of cinema to further explain what the "best location" is. Content-based filtering machine learning technique is the most suitable method to resolve the problem. It combines stakeholder's preference and cinema profile to make the recommendation result.</p>
<p>The 5 target locations of new cinema may not be a good choice. As the weighting matrix is developed, I can quickly pick other locations and make the recommendation again.</p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>

    <div class="Popover anim-scale-in js-tagsearch-popover"
     hidden data-tagsearch-url="/gnokit/Coursera_Capstone/find-symbols"
     data-tagsearch-ref="master"
     data-tagsearch-path="Capstone Project - The Battle of Neighborhoods.md"
     data-tagsearch-lang="Markdown"
     data-hydro-click="{&quot;event_type&quot;:&quot;code_navigation.click_on_symbol&quot;,&quot;payload&quot;:{&quot;action&quot;:&quot;click_on_symbol&quot;,&quot;repository_id&quot;:147900019,&quot;ref&quot;:&quot;master&quot;,&quot;client_id&quot;:&quot;1545115932.1560519501&quot;,&quot;originating_request_id&quot;:&quot;10E1:169B:7F2A51:B37EC6:5D2AC52F&quot;,&quot;originating_url&quot;:&quot;https://github.com/gnokit/Coursera_Capstone/blob/master/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods.md&quot;,&quot;referrer&quot;:&quot;https://github.com/gnokit/Coursera_Capstone&quot;,&quot;user_id&quot;:36091390}}"
     data-hydro-click-hmac="7ace09e4d53aca80a4fecc5d5e5483fcfbbc501dff949da6b364affff9ceaa05">
  <div class="Popover-message Popover-message--large Popover-message--top-left TagsearchPopover mt-1 mx-auto Box box-shadow-large">
    <div class="TagsearchPopover-content js-tagsearch-popover-content overflow-auto">
    </div>
  </div>
</div>



  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 <span title="0.40201s from unicorn-6c4ddbc957-k692q">GitHub</span>, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-mxKcLKe1PSS00TpWBTYMDM5u/3N8fjH9TViQqKljWBkiZs0e3hXU4gTaJjqaopJliYDhnsgZKVwkbEuvbEX9TQ==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-96c669c6.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-fGWKs1xKCBTTpsgg5C4/axMQGijlMBYE9papaEJGRY45RpgFihkhiUIATw2+C3aVJZ3wyeXz6MNSP9Eh4y+tOw==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-4652d74a.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

