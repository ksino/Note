





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-d7137690e30123bade38abb082ac79f36cc7a105ff92e602405f53b725465cab.css" integrity="sha256-1xN2kOMBI7reOKuwgqx582zHoQX/kuYCQF9TtyVGXKs=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-5c0265e045a9b6ed940bb92c652bb4647ab001ab7a20322bcfcd98bdf100e6b6.css" integrity="sha256-XAJl4EWptu2UC7ksZSu0ZHqwAat6IDIrz82YvfEA5rY=" media="all" rel="stylesheet" />
  
  
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/site-9badff1160428596c4d3259460ba1fb73c4f2997ee2a0767ba28e6c1720d5553.css" integrity="sha256-m63/EWBChZbE0yWUYLoftzxPKZfuKgdnuijmwXINVVM=" media="all" rel="stylesheet" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>learn-regex/README-cn.md at master · zeeshanu/learn-regex · GitHub</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/16267321?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="zeeshanu/learn-regex" property="og:title" /><meta content="https://github.com/zeeshanu/learn-regex" property="og:url" /><meta content="learn-regex - Learn regex the easy way" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="3D17:2EF52:312254:4ADC26:59E13836" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="3D17:2EF52:312254:4ADC26:59E13836" name="octolytics-dimension-request_id" /><meta content="sea" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="Y2IyMjllZWY3YTk3ZDI1NDM1ZDc3ZThhMDQ5NGIwMTBhYjdmNzgxYWNjYTkzNmZiYjhjYWE1NjE0YTg3N2Q2NHx7InJlbW90ZV9hZGRyZXNzIjoiMTgzLjI0MC4yMDIuNiIsInJlcXVlc3RfaWQiOiIzRDE3OjJFRjUyOjMxMjI1NDo0QURDMjY6NTlFMTM4MzYiLCJ0aW1lc3RhbXAiOjE1MDc5MzIyMjIsImhvc3QiOiJnaXRodWIuY29tIn0=">


  <meta name="html-safe-nonce" content="4e95ede51c3ded7121dd10ba1bceac946f4dc915">

  <meta http-equiv="x-pjax-version" content="e6fe0106087d055a6670d2eee766525c">
  

      <link href="https://github.com/zeeshanu/learn-regex/commits/master.atom" rel="alternate" title="Recent Commits to learn-regex:master" type="application/atom+xml">

  <meta name="description" content="learn-regex - Learn regex the easy way">
  <meta name="go-import" content="github.com/zeeshanu/learn-regex git https://github.com/zeeshanu/learn-regex.git">

  <meta content="16267321" name="octolytics-dimension-user_id" /><meta content="zeeshanu" name="octolytics-dimension-user_login" /><meta content="98029592" name="octolytics-dimension-repository_id" /><meta content="zeeshanu/learn-regex" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="98029592" name="octolytics-dimension-repository_network_root_id" /><meta content="zeeshanu/learn-regex" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/zeeshanu/learn-regex/blob/master/README-cn.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        <header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
      <a class="header-logo-invertocat my-0" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
        <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      </a>

    </div>

    <div class="HeaderMenu HeaderMenu--bright d-flex flex-justify-between flex-auto">
        <nav class="mt-0">
          <ul class="d-flex list-style-none">
              <li class="ml-2">
                <a href="/features" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:features" data-selected-links="/features /features/project-management /features/code-review /features/project-management /features/integrations /features">
                  Features
</a>              </li>
              <li class="ml-4">
                <a href="/business" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:business" data-selected-links="/business /business/security /business/customers /business">
                  Business
</a>              </li>

              <li class="ml-4">
                <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                  Explore
</a>              </li>

              <li class="ml-4">
                    <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:marketplace" data-selected-links=" /marketplace">
                      Marketplace
</a>              </li>
              <li class="ml-4">
                <a href="/pricing" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:pricing" data-selected-links="/pricing /pricing/developer /pricing/team /pricing/business-hosted /pricing/business-enterprise /pricing">
                  Pricing
</a>              </li>
          </ul>
        </nav>

      <div class="d-flex">
          <div class="d-lg-flex flex-items-center mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/zeeshanu/learn-regex/search" class="js-site-search-form" data-scoped-search-url="/zeeshanu/learn-regex/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/zeeshanu/learn-regex/blob/master/README-cn.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

          </div>

        <span class="d-inline-block">
            <div class="HeaderNavlink px-0 py-2 m-0">
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fzeeshanu%2Flearn-regex%2Fblob%2Fmaster%2FREADME-cn.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
                <span class="text-gray">or</span>
                <a class="text-bold text-white no-underline" href="/join?source=header-repo" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
            </div>
        </span>
      </div>
    </div>
  </div>
</header>


  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      





    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav ">
      <div class="repohead-details-container clearfix container ">

        <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fzeeshanu%2Flearn-regex"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/zeeshanu/learn-regex/watchers"
     aria-label="377 users are watching this repository">
    377
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fzeeshanu%2Flearn-regex"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/zeeshanu/learn-regex/stargazers"
      aria-label="13231 users starred this repository">
      13,231
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fzeeshanu%2Flearn-regex"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/zeeshanu/learn-regex/network" class="social-count"
       aria-label="1160 users forked this repository">
      1,160
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/zeeshanu" class="url fn" rel="author">zeeshanu</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/zeeshanu/learn-regex" data-pjax="#js-repo-pjax-container">learn-regex</a></strong>

</h1>

      </div>
      
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/zeeshanu/learn-regex" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /zeeshanu/learn-regex" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/zeeshanu/learn-regex/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /zeeshanu/learn-regex/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">14</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/zeeshanu/learn-regex/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /zeeshanu/learn-regex/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">3</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/zeeshanu/learn-regex/projects" class="js-selected-navigation-item reponav-item" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /zeeshanu/learn-regex/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


  <a href="/zeeshanu/learn-regex/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /zeeshanu/learn-regex/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/zeeshanu/learn-regex/blob/28f40b4f03548930218a4fd003635fc92cb49c63/README-cn.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:3ce401d7053f6a3d4a6b3be6ada39baa -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/zeeshanu/learn-regex/blob/master/README-cn.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/zeeshanu/learn-regex/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/zeeshanu/learn-regex"><span>learn-regex</span></a></span></span><span class="separator">/</span><strong class="final-path">README-cn.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/zeeshanu/learn-regex/commit/0c3228afabd23fc0829e5dff84a47175839f392b" data-pjax>
          0c3228a
        </a>
        <relative-time datetime="2017-09-12T16:00:50Z">Sep 12, 2017</relative-time>
      </span>
      <div>
        <img alt="@MariaBat" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/18451010?v=4&amp;s=40" width="20" />
        <a href="/MariaBat" class="user-mention" rel="contributor">MariaBat</a>
          <a href="/zeeshanu/learn-regex/commit/0c3228afabd23fc0829e5dff84a47175839f392b" class="message" data-pjax="true" title="Greek translation (#95)

* First commit

* Greek Translation

* Greek Translation">Greek translation (</a><a href="https://github.com/zeeshanu/learn-regex/pull/95" class="issue-link js-issue-link" data-url="https://github.com/zeeshanu/learn-regex/issues/95" data-id="256447768" data-error-text="Failed to load issue title" data-permission-text="Issue title is private">#95</a><a href="/zeeshanu/learn-regex/commit/0c3228afabd23fc0829e5dff84a47175839f392b" class="message" data-pjax="true" title="Greek translation (#95)

* First commit

* Greek Translation

* Greek Translation">)</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>15</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="zeeshanu" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=zeeshanu"><img alt="@zeeshanu" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/16267321?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="AndyZhuang" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=AndyZhuang"><img alt="@AndyZhuang" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2154218?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="yuhwan" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=yuhwan"><img alt="@yuhwan" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/19233714?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="xrr2016" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=xrr2016"><img alt="@xrr2016" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/18013127?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="tldzyx" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=tldzyx"><img alt="@tldzyx" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/5987706?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="syncxplus" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=syncxplus"><img alt="@syncxplus" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/16495682?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="syaning" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=syaning"><img alt="@syaning" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/7125133?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="ponsfrilus" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=ponsfrilus"><img alt="@ponsfrilus" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/176002?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="mujdatcicek" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=mujdatcicek"><img alt="@mujdatcicek" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/7440211?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="MariaBat" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=MariaBat"><img alt="@MariaBat" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/18451010?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="lzljbsc" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=lzljbsc"><img alt="@lzljbsc" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/28795484?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="loichu" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=loichu"><img alt="@loichu" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/14270237?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="binafor" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=binafor"><img alt="@binafor" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/4032371?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="coolguy001tv" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=coolguy001tv"><img alt="@coolguy001tv" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/936825?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="AbelZhou" href="/zeeshanu/learn-regex/commits/master/README-cn.md?author=AbelZhou"><img alt="@AbelZhou" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/2128345?v=4&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@zeeshanu" height="24" src="https://avatars3.githubusercontent.com/u/16267321?v=4&amp;s=48" width="24" />
            <a href="/zeeshanu">zeeshanu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@AndyZhuang" height="24" src="https://avatars2.githubusercontent.com/u/2154218?v=4&amp;s=48" width="24" />
            <a href="/AndyZhuang">AndyZhuang</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@yuhwan" height="24" src="https://avatars0.githubusercontent.com/u/19233714?v=4&amp;s=48" width="24" />
            <a href="/yuhwan">yuhwan</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@xrr2016" height="24" src="https://avatars3.githubusercontent.com/u/18013127?v=4&amp;s=48" width="24" />
            <a href="/xrr2016">xrr2016</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@tldzyx" height="24" src="https://avatars2.githubusercontent.com/u/5987706?v=4&amp;s=48" width="24" />
            <a href="/tldzyx">tldzyx</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@syncxplus" height="24" src="https://avatars3.githubusercontent.com/u/16495682?v=4&amp;s=48" width="24" />
            <a href="/syncxplus">syncxplus</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@syaning" height="24" src="https://avatars3.githubusercontent.com/u/7125133?v=4&amp;s=48" width="24" />
            <a href="/syaning">syaning</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@ponsfrilus" height="24" src="https://avatars2.githubusercontent.com/u/176002?v=4&amp;s=48" width="24" />
            <a href="/ponsfrilus">ponsfrilus</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@mujdatcicek" height="24" src="https://avatars1.githubusercontent.com/u/7440211?v=4&amp;s=48" width="24" />
            <a href="/mujdatcicek">mujdatcicek</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@MariaBat" height="24" src="https://avatars3.githubusercontent.com/u/18451010?v=4&amp;s=48" width="24" />
            <a href="/MariaBat">MariaBat</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@lzljbsc" height="24" src="https://avatars1.githubusercontent.com/u/28795484?v=4&amp;s=48" width="24" />
            <a href="/lzljbsc">lzljbsc</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@loichu" height="24" src="https://avatars2.githubusercontent.com/u/14270237?v=4&amp;s=48" width="24" />
            <a href="/loichu">loichu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@binafor" height="24" src="https://avatars3.githubusercontent.com/u/4032371?v=4&amp;s=48" width="24" />
            <a href="/binafor">binafor</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@coolguy001tv" height="24" src="https://avatars0.githubusercontent.com/u/936825?v=4&amp;s=48" width="24" />
            <a href="/coolguy001tv">coolguy001tv</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@AbelZhou" height="24" src="https://avatars0.githubusercontent.com/u/2128345?v=4&amp;s=48" width="24" />
            <a href="/AbelZhou">AbelZhou</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/zeeshanu/learn-regex/raw/master/README-cn.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/zeeshanu/learn-regex/blame/master/README-cn.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/zeeshanu/learn-regex/commits/master/README-cn.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      484 lines (331 sloc)
      <span class="file-info-divider"></span>
    17.5 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><br>
<p align="center">
<a href="https://camo.githubusercontent.com/d2e5827a412359c7593575adf876db23d4d50747/68747470733a2f2f692e696d6775722e636f6d2f6259776c3756662e706e67" target="_blank"><img src="https://camo.githubusercontent.com/d2e5827a412359c7593575adf876db23d4d50747/68747470733a2f2f692e696d6775722e636f6d2f6259776c3756662e706e67" alt="Learn Regex" data-canonical-src="https://i.imgur.com/bYwl7Vf.png" style="max-width:100%;"></a>
</p><br>
<h2><a href="#翻译" aria-hidden="true" class="anchor" id="user-content-翻译"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>翻译:</h2>
<ul>
<li><a href="/zeeshanu/learn-regex/blob/master/README.md">English</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-es.md">Español</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-fr.md">Français</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-cn.md">中文版</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-ja.md">日本語</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-ko.md">한국어</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-tr.md">Turkish</a></li>
<li><a href="/zeeshanu/learn-regex/blob/master/README-gr.md">Greek</a></li>
</ul>
<h2><a href="#什么是正则表达式" aria-hidden="true" class="anchor" id="user-content-什么是正则表达式"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>什么是正则表达式?</h2>
<blockquote>
<p>正则表达式是一组由字母和符号组成的特殊文本, 它可以用来从文本中找出满足你想要的格式的句子.</p>
</blockquote>
<p>一个正则表达式是在一个主体字符串中从左到右匹配字符串时的一种样式.
"Regular expression"这个词比较拗口, 我们常使用缩写的术语"regex"或"regexp".
正则表达式可以从一个基础字符串中根据一定的匹配模式替换文本中的字符串、验证表单、提取字符串等等.</p>
<p>想象你正在写一个应用, 然后你想设定一个用户命名的规则, 让用户名包含字符,数字,下划线和连字符,以及限制字符的个数,好让名字看起来没那么丑.
我们使用以下正则表达式来验证一个用户名:</p>
<p><br><br></p>
<p align="center">
  <a href="/zeeshanu/learn-regex/blob/master/img/regexp-en.png" target="_blank"><img src="/zeeshanu/learn-regex/raw/master/img/regexp-en.png" alt="Regular expression" style="max-width:100%;"></a>
</p>
<p>以上的正则表达式可以接受 <code>john_doe</code>, <code>jo-hn_doe</code>, <code>john12_as</code>.
但不匹配<code>Jo</code>, 因为它包含了大写的字母而且太短了.</p>
<h1><a href="#目录" aria-hidden="true" class="anchor" id="user-content-目录"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>目录</h1>
<ul>
<li><a href="#1-%E5%9F%BA%E6%9C%AC%E5%8C%B9%E9%85%8D">1. 基本匹配</a></li>
<li><a href="#2-%E5%85%83%E5%AD%97%E7%AC%A6">2. 元字符</a>
<ul>
<li><a href="#21-%E7%82%B9%E8%BF%90%E7%AE%97%E7%AC%A6-">2.1 点运算符 .</a></li>
<li><a href="#22-%E5%AD%97%E7%AC%A6%E9%9B%86">2.2 字符集</a>
<ul>
<li><a href="#221-%E5%90%A6%E5%AE%9A%E5%AD%97%E7%AC%A6%E9%9B%86">2.2.1 否定字符集</a></li>
</ul>
</li>
<li><a href="#23-%E9%87%8D%E5%A4%8D%E6%AC%A1%E6%95%B0">2.3 重复次数</a>
<ul>
<li><a href="#231--%E5%8F%B7">2.3.1 * 号</a></li>
<li><a href="#232--%E5%8F%B7">2.3.2   号</a></li>
<li><a href="#233--%E5%8F%B7">2.3.3 ? 号</a></li>
</ul>
</li>
<li><a href="#24--%E5%8F%B7">2.4 {} 号</a></li>
<li><a href="#25--%E7%89%B9%E5%BE%81%E6%A0%87%E7%BE%A4">2.5 (...) 特征标群</a></li>
<li><a href="#26--%E6%88%96%E8%BF%90%E7%AE%97%E7%AC%A6">2.6 | 或运算符</a></li>
<li><a href="#27-%E8%BD%AC%E7%A0%81%E7%89%B9%E6%AE%8A%E5%AD%97%E7%AC%A6">2.7 转码特殊字符</a></li>
<li><a href="#28-%E9%94%9A%E7%82%B9">2.8 锚点</a>
<ul>
<li><a href="#281--%E5%8F%B7">2.8.1 ^ 号</a></li>
<li><a href="#282--%E5%8F%B7">2.8.2 $ 号</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#3-%E7%AE%80%E5%86%99%E5%AD%97%E7%AC%A6%E9%9B%86">3. 简写字符集</a></li>
<li><a href="#4-%E5%89%8D%E5%90%8E%E5%85%B3%E8%81%94%E7%BA%A6%E6%9D%9F%E5%89%8D%E5%90%8E%E9%A2%84%E6%9F%A5">4. 前后关联约束(前后预查)</a>
<ul>
<li><a href="#41--%E5%89%8D%E7%BD%AE%E7%BA%A6%E6%9D%9F%E5%AD%98%E5%9C%A8">4.1 ?=... 前置约束(存在)</a></li>
<li><a href="#42--%E5%89%8D%E7%BD%AE%E7%BA%A6%E6%9D%9F-%E6%8E%92%E9%99%A4">4.2 ?!... 前置约束-排除</a></li>
<li><a href="#43---%E5%90%8E%E7%BD%AE%E7%BA%A6%E6%9D%9F-%E5%AD%98%E5%9C%A8">4.3 ?&lt;= ... 后置约束-存在</a></li>
<li><a href="#44--%E5%90%8E%E7%BD%AE%E7%BA%A6%E6%9D%9F-%E6%8E%92%E9%99%A4">4.4 ?&lt;!... 后置约束-排除</a></li>
</ul>
</li>
<li><a href="#5-%E6%A0%87%E5%BF%97">5. 标志</a>
<ul>
<li><a href="#51-%E5%BF%BD%E7%95%A5%E5%A4%A7%E5%B0%8F%E5%86%99-case-insensitive">5.1 忽略大小写 (Case Insensitive)</a></li>
<li><a href="#52-%E5%85%A8%E5%B1%80%E6%90%9C%E7%B4%A2-global-search">5.2 全局搜索 (Global search)</a></li>
<li><a href="#53-%E5%A4%9A%E8%A1%8C%E4%BF%AE%E9%A5%B0%E7%AC%A6-multiline">5.3 多行修饰符 (Multiline)</a></li>
</ul>
</li>
<li><a href="#%E9%A2%9D%E5%A4%96%E8%A1%A5%E5%85%85">额外补充</a></li>
<li><a href="#%E8%B4%A1%E7%8C%AE">贡献</a></li>
<li><a href="#%E8%AE%B8%E5%8F%AF%E8%AF%81">许可证</a></li>
</ul>
<h2><a href="#1-基本匹配" aria-hidden="true" class="anchor" id="user-content-1-基本匹配"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1. 基本匹配</h2>
<p>正则表达式其实就是在执行搜索时的格式, 它由一些字母和数字组合而成.
例如: 一个正则表达式 <code>the</code>, 它表示一个规则: 由字母<code>t</code>开始,接着是<code>h</code>,再接着是<code>e</code>.</p>
<pre>"the" =&gt; The fat cat sat on <a href="#learn-regex"><strong>the</strong></a> mat.
</pre>
<p><a href="https://regex101.com/r/dmRygT/1">在线练习</a></p>
<p>正则表达式<code>123</code>匹配字符串<code>123</code>. 它逐个字符的与输入的正则表达式做比较.</p>
<p>正则表达式是大小写敏感的, 所以<code>The</code>不会匹配<code>the</code>.</p>
<pre>"The" =&gt; <a href="#learn-regex"><strong>The</strong></a> fat cat sat on the mat.
</pre>
<p><a href="https://regex101.com/r/1paXsy/1">在线练习</a></p>
<h2><a href="#2-元字符" aria-hidden="true" class="anchor" id="user-content-2-元字符"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2. 元字符</h2>
<p>正则表达式主要依赖于元字符.
元字符不代表他们本身的字面意思, 他们都有特殊的含义. 一些元字符写在方括号中的时候有一些特殊的意思. 以下是一些元字符的介绍:</p>
<table>
<thead>
<tr>
<th align="center">元字符</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">.</td>
<td>句号匹配任意单个字符除了换行符.</td>
</tr>
<tr>
<td align="center">[ ]</td>
<td>字符种类. 匹配方括号内的任意字符.</td>
</tr>
<tr>
<td align="center">[^ ]</td>
<td>否定的字符种类. 匹配除了方括号里的任意字符</td>
</tr>
<tr>
<td align="center">*</td>
<td>匹配&gt;=0个重复的在*号之前的字符.</td>
</tr>
<tr>
<td align="center">+</td>
<td>匹配&gt;=1个重复的+号前的字符.</td>
</tr>
<tr>
<td align="center">?</td>
<td>标记?之前的字符为可选.</td>
</tr>
<tr>
<td align="center">{n,m}</td>
<td>匹配num个大括号之前的字符 (n &lt;= num &lt;= m).</td>
</tr>
<tr>
<td align="center">(xyz)</td>
<td>字符集, 匹配与 xyz 完全相等的字符串.</td>
</tr>
<tr>
<td align="center">|</td>
<td>或运算符,匹配符号前或后的字符.</td>
</tr>
<tr>
<td align="center">\</td>
<td>转义字符,用于匹配一些保留的字符 <code>[ ] ( ) { } . * + ? ^ $ \ |</code></td>
</tr>
<tr>
<td align="center">^</td>
<td>从开始行开始匹配.</td>
</tr>
<tr>
<td align="center">$</td>
<td>从末端开始匹配.</td>
</tr></tbody></table>
<h2><a href="#21-点运算符-" aria-hidden="true" class="anchor" id="user-content-21-点运算符-"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1 点运算符 <code>.</code></h2>
<p><code>.</code>是元字符中最简单的例子.
<code>.</code>匹配任意单个字符, 但不匹配换行符.
例如, 表达式<code>.ar</code>匹配一个任意字符后面跟着是<code>a</code>和<code>r</code>的字符串.</p>
<pre>".ar" =&gt; The <a href="#learn-regex"><strong>car</strong></a> <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>
<p><a href="https://regex101.com/r/xc9GkU/1">在线练习</a></p>
<h2><a href="#22-字符集" aria-hidden="true" class="anchor" id="user-content-22-字符集"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2 字符集</h2>
<p>字符集也叫做字符类.
方括号用来指定一个字符集.
在方括号中使用连字符来指定字符集的范围.
在方括号中的字符集不关心顺序.
例如, 表达式<code>[Tt]he</code> 匹配 <code>the</code> 和 <code>The</code>.</p>
<pre>"[Tt]he" =&gt; <a href="#learn-regex"><strong>The</strong></a> car parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>
<p><a href="https://regex101.com/r/2ITLQ4/1">在线练习</a></p>
<p>方括号的句号就表示句号.
表达式 <code>ar[.]</code> 匹配 <code>ar.</code>字符串</p>
<pre>"ar[.]" =&gt; A garage is a good place to park a c<a href="#learn-regex"><strong>ar.</strong></a>
</pre>
<p><a href="https://regex101.com/r/wL3xtE/1">在线练习</a></p>
<h3><a href="#221-否定字符集" aria-hidden="true" class="anchor" id="user-content-221-否定字符集"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.1 否定字符集</h3>
<p>一般来说 <code>^</code> 表示一个字符串的开头, 但它用在一个方括号的开头的时候, 它表示这个字符集是否定的.
例如, 表达式<code>[^c]ar</code> 匹配一个后面跟着<code>ar</code>的除了<code>c</code>的任意字符.</p>
<pre>"[^c]ar" =&gt; The car <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>
<p><a href="https://regex101.com/r/nNNlq3/1">在线练习</a></p>
<h2><a href="#23-重复次数" aria-hidden="true" class="anchor" id="user-content-23-重复次数"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3 重复次数</h2>
<p>后面跟着元字符 <code>+</code>, <code>*</code> or <code>?</code> 的, 用来指定匹配子模式的次数.
这些元字符在不同的情况下有着不同的意思.</p>
<h3><a href="#231--号" aria-hidden="true" class="anchor" id="user-content-231--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.1 <code>*</code> 号</h3>
<p><code>*</code>号匹配 在<code>*</code>之前的字符出现<code>大于等于0</code>次.
例如, 表达式 <code>a*</code> 匹配以0或更多个a开头的字符, 因为有0个这个条件, 其实也就匹配了所有的字符. 表达式<code>[a-z]*</code> 匹配一个行中所有以小写字母开头的字符串.</p>
<pre>"[a-z]*" =&gt; T<a href="#learn-regex"><strong>he</strong></a> <a href="#learn-regex"><strong>car</strong></a> <a href="#learn-regex"><strong>parked</strong></a> <a href="#learn-regex"><strong>in</strong></a> <a href="#learn-regex"><strong>the</strong></a> <a href="#learn-regex"><strong>garage</strong></a> #21.
</pre>
<p><a href="https://regex101.com/r/7m8me5/1">在线练习</a></p>
<p><code>*</code>字符和<code>.</code>字符搭配可以匹配所有的字符<code>.*</code>.
<code>*</code>和表示匹配空格的符号<code>\s</code>连起来用, 如表达式<code>\s*cat\s*</code>匹配0或更多个空格开头和0或更多个空格结尾的cat字符串.</p>
<pre>"\s*cat\s*" =&gt; The fat<a href="#learn-regex"><strong> cat </strong></a>sat on the <a href="#learn-regex">con<strong>cat</strong>enation</a>.
</pre>
<p><a href="https://regex101.com/r/gGrwuz/1">在线练习</a></p>
<h3><a href="#232--号" aria-hidden="true" class="anchor" id="user-content-232--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.2 <code>+</code> 号</h3>
<p><code>+</code>号匹配<code>+</code>号之前的字符出现 &gt;=1 次.
例如表达式<code>c.+t</code> 匹配以首字母<code>c</code>开头以<code>t</code>结尾,中间跟着任意个字符的字符串.</p>
<pre>"c.+t" =&gt; The fat <a href="#learn-regex"><strong>cat sat on the mat</strong></a>.
</pre>
<p><a href="https://regex101.com/r/Dzf9Aa/1">在线练习</a></p>
<h3><a href="#233--号" aria-hidden="true" class="anchor" id="user-content-233--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.3 <code>?</code> 号</h3>
<p>在正则表达式中元字符 <code>?</code> 标记在符号前面的字符为可选, 即出现 0 或 1 次.
例如, 表达式 <code>[T]?he</code> 匹配字符串 <code>he</code> 和 <code>The</code>.</p>
<pre>"[T]he" =&gt; <a href="#learn-regex"><strong>The</strong></a> car is parked in the garage.
</pre>
<p><a href="https://regex101.com/r/cIg9zm/1">在线练习</a></p>
<pre>"[T]?he" =&gt; <a href="#learn-regex"><strong>The</strong></a> car is parked in t<a href="#learn-regex"><strong>he</strong></a> garage.
</pre>
<p><a href="https://regex101.com/r/kPpO2x/1">在线练习</a></p>
<h2><a href="#24--号" aria-hidden="true" class="anchor" id="user-content-24--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4 <code>{}</code> 号</h2>
<p>在正则表达式中 <code>{}</code> 是一个量词, 常用来一个或一组字符可以重复出现的次数.
例如,  表达式 <code>[0-9]{2,3}</code> 匹配最少 2 位最多 3 位 0~9 的数字.</p>
<pre>"[0-9]{2,3}" =&gt; The number was 9.<a href="#learn-regex"><strong>999</strong></a>7 but we rounded it off to <a href="#learn-regex"><strong>10</strong></a>.0.
</pre>
<p><a href="https://regex101.com/r/juM86s/1">在线练习</a></p>
<p>我们可以省略第二个参数.
例如, <code>[0-9]{2,}</code> 匹配至少两位 0~9 的数字.</p>
<p>如果逗号也省略掉则表示重复固定的次数.
例如, <code>[0-9]{3}</code> 匹配3位数字</p>
<pre>"[0-9]{2,}" =&gt; The number was 9.<a href="#learn-regex"><strong>9997</strong></a> but we rounded it off to <a href="#learn-regex"><strong>10</strong></a>.0.
</pre>
<p><a href="https://regex101.com/r/Gdy4w5/1">在线练习</a></p>
<pre>"[0-9]{3}" =&gt; The number was 9.<a href="#learn-regex"><strong>999</strong></a>7 but we rounded it off to 10.0.
</pre>
<p><a href="https://regex101.com/r/Sivu30/1">在线练习</a></p>
<h2><a href="#25--特征标群" aria-hidden="true" class="anchor" id="user-content-25--特征标群"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.5 <code>(...)</code> 特征标群</h2>
<p>特征标群是一组写在 <code>(...)</code> 中的子模式. 例如之前说的 <code>{}</code> 是用来表示前面一个字符出现指定次数. 但如果在 <code>{}</code> 前加入特征标群则表示整个标群内的字符重复 N 次. 例如, 表达式 <code>(ab)*</code> 匹配连续出现 0 或更多个 <code>ab</code>.</p>
<p>我们还可以在 <code>()</code> 中用或字符 <code>|</code> 表示或. 例如, <code>(c|g|p)ar</code> 匹配 <code>car</code> 或 <code>gar</code> 或 <code>par</code>.</p>
<pre>"(c|g|p)ar" =&gt; The <a href="#learn-regex"><strong>car</strong></a> is <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>
<p><a href="https://regex101.com/r/tUxrBG/1">在线练习</a></p>
<h2><a href="#26--或运算符" aria-hidden="true" class="anchor" id="user-content-26--或运算符"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.6 <code>|</code> 或运算符</h2>
<p>或运算符就表示或, 用作判断条件.</p>
<p>例如 <code>(T|t)he|car</code> 匹配 <code>(T|t)he</code> 或 <code>car</code>.</p>
<pre>"(T|t)he|car" =&gt; <a href="#learn-regex"><strong>The</strong></a> <a href="#learn-regex"><strong>car</strong></a> is parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>
<p><a href="https://regex101.com/r/fBXyX0/1">在线练习</a></p>
<h2><a href="#27-转码特殊字符" aria-hidden="true" class="anchor" id="user-content-27-转码特殊字符"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.7 转码特殊字符</h2>
<p>反斜线 <code>\</code> 在表达式中用于转码紧跟其后的字符. 用于指定 <code>{ } [ ] / \ + * . $ ^ | ?</code> 这些特殊字符. 如果想要匹配这些特殊字符则要在其前面加上反斜线 <code>\</code>.</p>
<p>例如 <code>.</code> 是用来匹配除换行符外的所有字符的. 如果想要匹配句子中的 <code>.</code> 则要写成 <code>\.</code> 以下这个例子 <code>\.?</code>是选择性匹配<code>.</code></p>
<pre>"(f|c|m)at\.?" =&gt; The <a href="#learn-regex"><strong>fat</strong></a> <a href="#learn-regex"><strong>cat</strong></a> sat on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>
<p><a href="https://regex101.com/r/DOc5Nu/1">在线练习</a></p>
<h2><a href="#28-锚点" aria-hidden="true" class="anchor" id="user-content-28-锚点"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.8 锚点</h2>
<p>在正则表达式中, 想要匹配指定开头或结尾的字符串就要使用到锚点. <code>^</code> 指定开头, <code>$</code> 指定结尾.</p>
<h3><a href="#281--号" aria-hidden="true" class="anchor" id="user-content-281--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.8.1 <code>^</code> 号</h3>
<p><code>^</code> 用来检查匹配的字符串是否在所匹配字符串的开头.</p>
<p>例如, 在 <code>abc</code> 中使用表达式 <code>^a</code> 会得到结果 <code>a</code>. 但如果使用 <code>^b</code> 将匹配不到任何结果. 因为在字符串 <code>abc</code> 中并不是以 <code>b</code> 开头.</p>
<p>例如, <code>^(T|t)he</code> 匹配以 <code>The</code> 或 <code>the</code> 开头的字符串.</p>
<pre>"(T|t)he" =&gt; <a href="#learn-regex"><strong>The</strong></a> car is parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>
<p><a href="https://regex101.com/r/5ljjgB/1">在线练习</a></p>
<pre>"^(T|t)he" =&gt; <a href="#learn-regex"><strong>The</strong></a> car is parked in the garage.
</pre>
<p><a href="https://regex101.com/r/jXrKne/1">在线练习</a></p>
<h3><a href="#282--号" aria-hidden="true" class="anchor" id="user-content-282--号"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.8.2 <code>$</code> 号</h3>
<p>同理于 <code>^</code> 号, <code>$</code> 号用来匹配字符是否是最后一个.</p>
<p>例如, <code>(at\.)$</code> 匹配以 <code>at.</code> 结尾的字符串.</p>
<pre>"(at\.)" =&gt; The fat c<a href="#learn-regex"><strong>at.</strong></a> s<a href="#learn-regex"><strong>at.</strong></a> on the m<a href="#learn-regex"><strong>at.</strong></a>
</pre>
<p><a href="https://regex101.com/r/y4Au4D/1">在线练习</a></p>
<pre>"(at\.)$" =&gt; The fat cat. sat. on the m<a href="#learn-regex"><strong>at.</strong></a>
</pre>
<p><a href="https://regex101.com/r/t0AkOd/1">在线练习</a></p>
<h2><a href="#3-简写字符集" aria-hidden="true" class="anchor" id="user-content-3-简写字符集"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3. 简写字符集</h2>
<p>正则表达式提供一些常用的字符集简写. 如下:</p>
<table>
<thead>
<tr>
<th align="center">简写</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">.</td>
<td>除换行符外的所有字符</td>
</tr>
<tr>
<td align="center">\w</td>
<td>匹配所有字母数字, 等同于 <code>[a-zA-Z0-9_]</code></td>
</tr>
<tr>
<td align="center">\W</td>
<td>匹配所有非字母数字, 即符号, 等同于: <code>[^\w]</code></td>
</tr>
<tr>
<td align="center">\d</td>
<td>匹配数字: <code>[0-9]</code></td>
</tr>
<tr>
<td align="center">\D</td>
<td>匹配非数字: <code>[^\d]</code></td>
</tr>
<tr>
<td align="center">\s</td>
<td>匹配所有空格字符, 等同于: <code>[\t\n\f\r\p{Z}]</code></td>
</tr>
<tr>
<td align="center">\S</td>
<td>匹配所有非空格字符: <code>[^\s]</code></td>
</tr>
<tr>
<td align="center">\f</td>
<td>匹配一个换页符</td>
</tr>
<tr>
<td align="center">\n</td>
<td>匹配一个换行符</td>
</tr>
<tr>
<td align="center">\r</td>
<td>匹配一个回车符</td>
</tr>
<tr>
<td align="center">\t</td>
<td>匹配一个制表符</td>
</tr>
<tr>
<td align="center">\v</td>
<td>匹配一个垂直制表符</td>
</tr>
<tr>
<td align="center">\p</td>
<td>匹配 CR/LF (等同于 <code>\r\n</code>)，用来匹配 DOS 行终止符</td>
</tr></tbody></table>
<h2><a href="#4-前后关联约束前后预查" aria-hidden="true" class="anchor" id="user-content-4-前后关联约束前后预查"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4. 前后关联约束(前后预查)</h2>
<p>前置约束和后置约束都属于<strong>非捕获簇</strong>(用于匹配不在匹配列表中的格式).
前置约束用于判断所匹配的格式是否在另一个确定的格式之后.</p>
<p>例如, 我们想要获得所有跟在 <code>$</code> 符号后的数字, 我们可以使用正向向后约束 <code>(?&lt;=\$)[0-9\.]*</code>.
这个表达式匹配 <code>$</code> 开头, 之后跟着 <code>0,1,2,3,4,5,6,7,8,9,.</code> 这些字符可以出现大于等于 0 次.</p>
<p>前后关联约束如下:</p>
<table>
<thead>
<tr>
<th align="center">符号</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">?=</td>
<td>前置约束-存在</td>
</tr>
<tr>
<td align="center">?!</td>
<td>前置约束-排除</td>
</tr>
<tr>
<td align="center">?&lt;=</td>
<td>后置约束-存在</td>
</tr>
<tr>
<td align="center">?&lt;!</td>
<td>后置约束-排除</td>
</tr></tbody></table>
<h3><a href="#41--前置约束存在" aria-hidden="true" class="anchor" id="user-content-41--前置约束存在"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1 <code>?=...</code> 前置约束(存在)</h3>
<p><code>?=...</code> 前置约束(存在), 表示第一部分表达式必须跟在 <code>?=...</code>定义的表达式之后.</p>
<p>返回结果只满足第一部分表达式.
定义一个前置约束(存在)要使用 <code>()</code>. 在括号内部使用一个问号和等号: <code>(?=...)</code>.</p>
<p>前置约束的内容写在括号中的等号后面.
例如, 表达式 <code>(T|t)he(?=\sfat)</code> 匹配 <code>The</code> 和 <code>the</code>, 在括号中我们又定义了前置约束(存在) <code>(?=\sfat)</code> ,即 <code>The</code> 和 <code>the</code> 后面紧跟着 <code>(空格)fat</code>.</p>
<pre>"(T|t)he(?=\sfat)" =&gt; <a href="#learn-regex"><strong>The</strong></a> fat cat sat on the mat.
</pre>
<p><a href="https://regex101.com/r/IDDARt/1">在线练习</a></p>
<h3><a href="#42--前置约束-排除" aria-hidden="true" class="anchor" id="user-content-42--前置约束-排除"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2 <code>?!...</code> 前置约束-排除</h3>
<p>前置约束-排除 <code>?!</code> 用于筛选所有匹配结果, 筛选条件为 其后不跟随着定义的格式
<code>前置约束-排除</code>  定义和 <code>前置约束(存在)</code> 一样, 区别就是 <code>=</code> 替换成 <code>!</code> 也就是 <code>(?!...)</code>.</p>
<p>表达式 <code>(T|t)he(?!\sfat)</code> 匹配 <code>The</code> 和 <code>the</code>, 且其后不跟着 <code>(空格)fat</code>.</p>
<pre>"(T|t)he(?!\sfat)" =&gt; The fat cat sat on <a href="#learn-regex"><strong>the</strong></a> mat.
</pre>
<p><a href="https://regex101.com/r/V32Npg/1">在线练习</a></p>
<h3><a href="#43---后置约束-存在" aria-hidden="true" class="anchor" id="user-content-43---后置约束-存在"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.3 <code>?&lt;= ...</code> 后置约束-存在</h3>
<p>后置约束-存在 记作<code>(?&lt;=...)</code> 用于筛选所有匹配结果, 筛选条件为 其前跟随着定义的格式.
例如, 表达式 <code>(?&lt;=(T|t)he\s)(fat|mat)</code> 匹配 <code>fat</code> 和 <code>mat</code>, 且其前跟着 <code>The</code> 或 <code>the</code>.</p>
<pre>"(?&lt;=(T|t)he\s)(fat|mat)" =&gt; The <a href="#learn-regex"><strong>fat</strong></a> cat sat on the <a href="#learn-regex"><strong>mat</strong></a>.
</pre>
<p><a href="https://regex101.com/r/avH165/1">在线练习</a></p>
<h3><a href="#44--后置约束-排除" aria-hidden="true" class="anchor" id="user-content-44--后置约束-排除"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.4 <code>?&lt;!...</code> 后置约束-排除</h3>
<p>后置约束-排除 记作 <code>(?&lt;!...)</code> 用于筛选所有匹配结果, 筛选条件为 其前不跟着定义的格式.
例如, 表达式 <code>(?&lt;!(T|t)he\s)(cat)</code> 匹配 <code>cat</code>, 且其前不跟着 <code>The</code> 或 <code>the</code>.</p>
<pre>"(?&lt;!(T|t)he\s)(cat)" =&gt; The cat sat on <a href="#learn-regex"><strong>cat</strong></a>.
</pre>
<p><a href="https://regex101.com/r/8Efx5G/1">在线练习</a></p>
<h2><a href="#5-标志" aria-hidden="true" class="anchor" id="user-content-5-标志"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5. 标志</h2>
<p>标志也叫修饰语, 因为它可以用来修改表达式的搜索结果.
这些标志可以任意的组合使用, 它也是整个正则表达式的一部分.</p>
<table>
<thead>
<tr>
<th align="center">标志</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">i</td>
<td>忽略大小写.</td>
</tr>
<tr>
<td align="center">g</td>
<td>全局搜索.</td>
</tr>
<tr>
<td align="center">m</td>
<td>多行的: 锚点元字符 <code>^</code> <code>$</code> 工作范围在每行的起始.</td>
</tr></tbody></table>
<h3><a href="#51-忽略大小写-case-insensitive" aria-hidden="true" class="anchor" id="user-content-51-忽略大小写-case-insensitive"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.1 忽略大小写 (Case Insensitive)</h3>
<p>修饰语 <code>i</code> 用于忽略大小写.
例如, 表达式 <code>/The/gi</code> 表示在全局搜索 <code>The</code>, 在后面的 <code>i</code> 将其条件修改为忽略大小写, 则变成搜索 <code>the</code> 和 <code>The</code>, <code>g</code> 表示全局搜索.</p>
<pre>"The" =&gt; <a href="#learn-regex"><strong>The</strong></a> fat cat sat on the mat.
</pre>
<p><a href="https://regex101.com/r/dpQyf9/1">在线练习</a></p>
<pre>"/The/gi" =&gt; <a href="#learn-regex"><strong>The</strong></a> fat cat sat on <a href="#learn-regex"><strong>the</strong></a> mat.
</pre>
<p><a href="https://regex101.com/r/ahfiuh/1">在线练习</a></p>
<h3><a href="#52-全局搜索-global-search" aria-hidden="true" class="anchor" id="user-content-52-全局搜索-global-search"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.2 全局搜索 (Global search)</h3>
<p>修饰符 <code>g</code> 常用语执行一个全局搜索匹配, 即(不仅仅返回第一个匹配的, 而是返回全部).
例如, 表达式 <code>/.(at)/g</code> 表示搜索 任意字符(除了换行) + <code>at</code>, 并返回全部结果.</p>
<pre>"/.(at)/" =&gt; The <a href="#learn-regex"><strong>fat</strong></a> cat sat on the mat.
</pre>
<p><a href="https://regex101.com/r/jnk6gM/1">在线练习</a></p>
<pre>"/.(at)/g" =&gt; The <a href="#learn-regex"><strong>fat</strong></a> <a href="#learn-regex"><strong>cat</strong></a> <a href="#learn-regex"><strong>sat</strong></a> on the <a href="#learn-regex"><strong>mat</strong></a>.
</pre>
<p><a href="https://regex101.com/r/dO1nef/1">在线练习</a></p>
<h3><a href="#53-多行修饰符-multiline" aria-hidden="true" class="anchor" id="user-content-53-多行修饰符-multiline"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.3 多行修饰符 (Multiline)</h3>
<p>多行修饰符 <code>m</code> 常用语执行一个多行匹配.</p>
<p>像之前介绍的 <code>(^,$)</code> 用于检查格式是否是在待检测字符串的开头或结尾. 但我们如果想要它在每行的开头和结尾生效, 我们需要用到多行修饰符 <code>m</code>.</p>
<p>例如, 表达式 <code>/at(.)?$/gm</code> 表示在待检测字符串每行的末尾搜索 <code>at</code>后跟一个或多个 <code>.</code> 的字符串, 并返回全部结果.</p>
<pre>"/.at(.)?$/" =&gt; The fat
                cat sat
                on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>
<p><a href="https://regex101.com/r/hoGMkP/1">在线练习</a></p>
<pre>"/.at(.)?$/gm" =&gt; The <a href="#learn-regex"><strong>fat</strong></a>
                  cat <a href="#learn-regex"><strong>sat</strong></a>
                  on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>
<p><a href="https://regex101.com/r/E88WE2/1">在线练习</a></p>
<h2><a href="#贡献" aria-hidden="true" class="anchor" id="user-content-贡献"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>贡献</h2>
<ul>
<li>报告问题</li>
<li>开放合并请求</li>
<li>传播此文档</li>
<li>直接和我联系 <a href="mailto:ziishaned@gmail.com">ziishaned@gmail.com</a> 或 <a href="https://twitter.com/ziishaned"><img src="https://camo.githubusercontent.com/1e087b64058f101f01e1183e2ae522aab49ff408/68747470733a2f2f696d672e736869656c64732e696f2f747769747465722f75726c2f68747470732f747769747465722e636f6d2f7a69697368616e65642e7376673f7374796c653d736f6369616c266c6162656c3d466f6c6c6f772532302534307a69697368616e6564" alt="Twitter URL" data-canonical-src="https://img.shields.io/twitter/url/https/twitter.com/ziishaned.svg?style=social&amp;label=Follow%20%40ziishaned" style="max-width:100%;"></a></li>
</ul>
<h2><a href="#许可证" aria-hidden="true" class="anchor" id="user-content-许可证"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>许可证</h2>
<p>MIT © <a href="mailto:ziishaned@gmail.com">Zeeshan Ahmed</a></p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.11289s from unicorn-1776820943-nc09j">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha256-B2nQiwimpgbJqLq5UZ3+8Qvx3E0kKVsk+HgfjDgi7eE=" src="https://assets-cdn.github.com/assets/frameworks-0769d08b08a6a606c9a8bab9519dfef10bf1dc4d24295b24f8781f8c3822ede1.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha256-mu/ifkGf0f65rRkFmbNIfxT8R3IqTwI6+AVoABRNuZc=" src="https://assets-cdn.github.com/assets/github-9aefe27e419fd1feb9ad190599b3487f14fc47722a4f023af8056800144db997.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

