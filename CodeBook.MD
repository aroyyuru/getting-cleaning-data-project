


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>getting-cleaning-data-project/CodeBook.MD at master · aroyyuru/getting-cleaning-data-project</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="aroyyuru/getting-cleaning-data-project" name="twitter:title" /><meta content="getting-cleaning-data-project - Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course." name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/342996?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/342996?v=3&amp;s=400" property="og:image" /><meta content="aroyyuru/getting-cleaning-data-project" property="og:title" /><meta content="https://github.com/aroyyuru/getting-cleaning-data-project" property="og:url" /><meta content="getting-cleaning-data-project - Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course." property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTM2MzExNjk6MGZlNWI5YjNhNGY0YTY2MzAyM2ZhMjgzOGNjMzE2ZTQ6ZDcwNjcyNWUzMWNiNDBjMmM1ODE0ZTVlNjY0ZmMxNTUwNDQyZGZjZWExZjRhYjE0N2U4Njk0MjQyZmE5MGE5ZQ==--e98ba1c983ad295eab29cc338dbe0db7d7631bae">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="6CD5D357:1161:2A0FDA4:5607F32F" name="octolytics-dimension-request_id" /><meta content="13631169" name="octolytics-actor-id" /><meta content="aroyyuru" name="octolytics-actor-login" /><meta content="0c111dd750dd248d326cf2a9f3ad0f027c1c684c6eeef80b58925da34f40004e" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
      <meta class="js-ga-set" name="dimension4" content="Current repo nav">
    <meta name="is-dotcom" content="true">
        <meta name="hostname" content="github.com">
    <meta name="user-login" content="aroyyuru">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <!-- </textarea> --><!-- '"` --><meta content="authenticity_token" name="csrf-param" />
<meta content="1wDFTgqsSDdakm1w3LB9PW9KgrWkYfYIHz9hXIwCh6/LSkrMcIrfinq+o+uGL5KFr8ObvS53NgHhBvKsUB+hWg==" name="csrf-token" />
    <meta content="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-d3b5b3df2f65fc68f5e345a65ac963467f6c81cf28ea86808ec363627c646deb.css" integrity="sha256-07Wz3y9l/Gj140WmWsljRn9sgc8o6oaAjsNjYnxkbes=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-5c5f822f8fcc71f3c7ef329235cc20ddb312d1e4a952030b5cbcce6bc6938888.css" integrity="sha256-XF+CL4/McfPH7zKSNcwg3bMS0eSpUgMLXLzOa8aTiIg=" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="66f455c6719e9be482f1485001a46a01">

      
  <meta name="description" content="getting-cleaning-data-project - Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course.">
  <meta name="go-import" content="github.com/aroyyuru/getting-cleaning-data-project git https://github.com/aroyyuru/getting-cleaning-data-project.git">

  <meta content="342996" name="octolytics-dimension-user_id" /><meta content="aroyyuru" name="octolytics-dimension-user_login" /><meta content="19213479" name="octolytics-dimension-repository_id" /><meta content="aroyyuru/getting-cleaning-data-project" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="19213479" name="octolytics-dimension-repository_network_root_id" /><meta content="aroyyuru/getting-cleaning-data-project" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/aroyyuru/getting-cleaning-data-project/commits/master.atom" rel="alternate" title="Recent Commits to getting-cleaning-data-project:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      
      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/aroyyuru/getting-cleaning-data-project/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:aroyyuru"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="aroyyuru/getting-cleaning-data-project">This repository</span>
  </div>
    <a class="dropdown-item" href="/aroyyuru/getting-cleaning-data-project/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/aroyyuru"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@aroyyuru" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/13631169?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">aroyyuru</strong>

        </div>



        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/aroyyuru" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NmcHmlk+XIf6OJTWMi889Vzx7cUai2FeiAcn6M+gE4iLuASCnje3gK+SgSAHwvj7etjdYSvpO2YAKNV35X6X1A==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

    <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div class="pagehead repohead instapaper_ignore readability-menu">

      <div class="container">

        <div class="clearfix">
          
<ul class="pagehead-actions">

  <li>
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="/aSATOv9x8ENVbNOPUE27hLZcmRSpadtt0r19KKp9QAwHk3HUp6lCMmlNKR02FF+wAbdgTqjXsWmXRBGPHeJiA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="19213479" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/aroyyuru/getting-cleaning-data-project/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/aroyyuru/getting-cleaning-data-project/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="0e+eci72fYa08MYgx+4zfLEpvG33MRfn0whmECuuOfzxtJS9QPMra2HZfVmxeR8NIJrRHfD2eDrr8yzLPXoXOQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar aroyyuru/getting-cleaning-data-project"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/aroyyuru/getting-cleaning-data-project/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="x2U8PU4lH9kHNo3SKYZLvKqbLwrTDVnAdxSAHIpPe2xO8Gx2/oBVz8c374S+f2lW8A97ITKZDmMF8NutSRr8/g==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star aroyyuru/getting-cleaning-data-project"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/aroyyuru/getting-cleaning-data-project/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/fork" class="btn-with-count" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="6o4FI+3PKDek8/iWKtbTidCwQL43lT7iybFXGFv6CtEKrGWoiUdK/+AtCocBEg2z/bBFRTXPYEEgekqGOuP22w==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of aroyyuru/getting-cleaning-data-project to your account"
                aria-label="Fork your own copy of aroyyuru/getting-cleaning-data-project to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
</form>
    <a href="/aroyyuru/getting-cleaning-data-project/network" class="social-count">
      75
    </a>
  </li>
</ul>

          <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="mega-octicon octicon-repo"></span>
  <span class="author"><a href="/aroyyuru" class="url fn" itemprop="url" rel="author"><span itemprop="title">aroyyuru</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/aroyyuru/getting-cleaning-data-project" data-pjax="#js-repo-pjax-container">getting-cleaning-data-project</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

</h1>

        </div>
      </div>
    </div>

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline ">
        <div class="repository-sidebar clearfix">
          
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/aroyyuru/getting-cleaning-data-project/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/aroyyuru/getting-cleaning-data-project" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /aroyyuru/getting-cleaning-data-project">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/aroyyuru/getting-cleaning-data-project/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /aroyyuru/getting-cleaning-data-project/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/aroyyuru/getting-cleaning-data-project/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /aroyyuru/getting-cleaning-data-project/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/aroyyuru/getting-cleaning-data-project/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /aroyyuru/getting-cleaning-data-project/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/aroyyuru/getting-cleaning-data-project/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /aroyyuru/getting-cleaning-data-project/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/aroyyuru/getting-cleaning-data-project/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /aroyyuru/getting-cleaning-data-project/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

            <div class="only-with-full-nav">
                
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/aroyyuru/getting-cleaning-data-project.git" readonly="readonly" aria-label="HTTPS clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:aroyyuru/getting-cleaning-data-project.git" readonly="readonly" aria-label="SSH clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/aroyyuru/getting-cleaning-data-project" readonly="readonly" aria-label="Subversion checkout URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JIpcrnSQpSBdeek+Iq+yrajvjloX4ZxhCDzKwrLEv4+11tTtcsfhtdompY4jZc5IRCHmXsYkhgbCeP9e/21OYg==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="SZXF5C92WSfPF5l4Slopb2UZfghMHKzrksF/FfUOXrUBkFXFXhveEmThTym6XzsnEUme+K0P3o6N9MqvUHAhNQ==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="gGI1WIM6MV0PwRqmJn1lKXK3QmsxAUg6PJeY5c+58Rw0BWamdlrmJJSptFmOoqSrNZ9EarcRrmVYmIl7icB5oA==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>
  <a href="github-windows://openRepo/https://github.com/aroyyuru/getting-cleaning-data-project" class="btn btn-sm sidebar-button" title="Save aroyyuru/getting-cleaning-data-project to your computer and use it in GitHub Desktop." aria-label="Save aroyyuru/getting-cleaning-data-project to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-desktop-download"></span>
    Clone in Desktop
  </a>

              <a href="/aroyyuru/getting-cleaning-data-project/archive/master.zip"
                 class="btn btn-sm sidebar-button"
                 aria-label="Download the contents of aroyyuru/getting-cleaning-data-project as a zip file"
                 title="Download the contents of aroyyuru/getting-cleaning-data-project as a zip file"
                 rel="nofollow">
                <span class="octicon octicon-cloud-download"></span>
                Download ZIP
              </a>
            </div>
        </div>
        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/aroyyuru/getting-cleaning-data-project/blob/cabd30fca5dbdd8c633f40018e8490eb4c046040/CodeBook.MD" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:cfa99c2cf1baab75256b88a9b6361b3e -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
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
               href="/aroyyuru/getting-cleaning-data-project/blob/master/CodeBook.MD"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
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

    <div class="btn-group right">
      <a href="/aroyyuru/getting-cleaning-data-project/find/master"
            class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-nw"
            data-pjax
            data-hotkey="t"
            aria-label="Quickly jump between files">
        <span class="octicon octicon-list-unordered"></span>
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </div>

    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/aroyyuru/getting-cleaning-data-project" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">getting-cleaning-data-project</span></a></span></span><span class="separator">/</span><strong class="final-path">CodeBook.MD</strong>
    </div>
  </div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@aroyyuru" class="avatar" height="24" src="https://avatars0.githubusercontent.com/u/342996?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/aroyyuru" rel="author">aroyyuru</a></span>
        <time datetime="2014-04-27T19:11:53Z" is="relative-time">Apr 27, 2014</time>
        <div class="commit-title">
            <a href="/aroyyuru/getting-cleaning-data-project/commit/cabd30fca5dbdd8c633f40018e8490eb4c046040" class="message" data-pjax="true" title="Update run_analysis, README, and add CodeBook.MD for more complete info on data and variables">Update run_analysis, README, and add CodeBook.MD for more complete in…</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@aroyyuru" height="24" src="https://avatars0.githubusercontent.com/u/342996?v=3&amp;s=48" width="24" />
            <a href="/aroyyuru">aroyyuru</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/aroyyuru/getting-cleaning-data-project/raw/master/CodeBook.MD" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/aroyyuru/getting-cleaning-data-project/blame/master/CodeBook.MD" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/aroyyuru/getting-cleaning-data-project/commits/master/CodeBook.MD" class="btn btn-sm " rel="nofollow">History</a>
    </div>

      <a class="octicon-btn tooltipped tooltipped-nw"
         href="github-windows://openRepo/https://github.com/aroyyuru/getting-cleaning-data-project?branch=master&amp;filepath=CodeBook.MD"
         aria-label="Open this file in GitHub Desktop"
         data-ga-click="Repository, open with desktop, type:windows">
          <span class="octicon octicon-device-desktop"></span>
      </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/edit/master/CodeBook.MD" class="inline-form js-update-url-with-hash" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lH9TH7vCC2DLrDfB+LfqHOUmXUc/Mtu2JLtmneD+V0pWXcMU4TuIJ67jwzgoUusjsYKE2Su6t4+7HpPAnpE0Xg==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/aroyyuru/getting-cleaning-data-project/delete/master/CodeBook.MD" class="inline-form" data-form-nonce="dd64c790e1aedcb7c3bd7c4ef4eb98b1710706b2" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ZIr2xQcn//j8bFSHHcxR5CvIuT59qZeFagavrtHTJhqsfWKJ2mjAmqIWPD/YEAKKDZpMcr7ATA7DcSryimzYqg==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <span class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      50 lines (37 sloc)
      <span class="file-info-divider"></span>
    3.36 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h2><a id="user-content-getting-and-cleaning-data-project" class="anchor" href="#getting-and-cleaning-data-project" aria-hidden="true"><span class="octicon octicon-link"></span></a>Getting and Cleaning Data Project</h2>

<p>Heather Wade</p>

<h3><a id="user-content-description" class="anchor" href="#description" aria-hidden="true"><span class="octicon octicon-link"></span></a>Description</h3>

<p>Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.</p>

<h3><a id="user-content-source-data" class="anchor" href="#source-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Source Data</h3>

<p>A full description of the data used in this project can be found at <a href="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones">The UCI Machine Learning Repository</a></p>

<p><a href="https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip">The source data for this project can be found here.</a></p>

<h3><a id="user-content-data-set-information" class="anchor" href="#data-set-information" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Set Information</h3>

<p>The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. </p>

<p>The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.</p>

<h3><a id="user-content-attribute-information" class="anchor" href="#attribute-information" aria-hidden="true"><span class="octicon octicon-link"></span></a>Attribute Information</h3>

<p>For each record in the dataset it is provided: </p>

<ul>
<li>Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. </li>
<li>Triaxial Angular velocity from the gyroscope. </li>
<li>A 561-feature vector with time and frequency domain variables. </li>
<li>Its activity label. </li>
<li>An identifier of the subject who carried out the experiment.</li>
</ul>

<h3><a id="user-content-section-1-merge-the-training-and-the-test-sets-to-create-one-data-set" class="anchor" href="#section-1-merge-the-training-and-the-test-sets-to-create-one-data-set" aria-hidden="true"><span class="octicon octicon-link"></span></a>Section 1. Merge the training and the test sets to create one data set.</h3>

<p>After setting the source directory for the files, read into tables the data located in</p>

<ul>
<li>features.txt</li>
<li>activity_labels.txt</li>
<li>subject_train.txt</li>
<li>x_train.txt</li>
<li>y_train.txt</li>
<li>subject_test.txt</li>
<li>x_test.txt</li>
<li>y_test.txt</li>
</ul>

<p>Assign column names and merge to create one data set.</p>

<h2><a id="user-content-section-2-extract-only-the-measurements-on-the-mean-and-standard-deviation-for-each-measurement" class="anchor" href="#section-2-extract-only-the-measurements-on-the-mean-and-standard-deviation-for-each-measurement" aria-hidden="true"><span class="octicon octicon-link"></span></a>Section 2. Extract only the measurements on the mean and standard deviation for each measurement.</h2>

<p>Create a logcal vector that contains TRUE values for the ID, mean and stdev columns and FALSE values for the others.
Subset this data to keep only the necessary columns.</p>

<h2><a id="user-content-section-3-use-descriptive-activity-names-to-name-the-activities-in-the-data-set" class="anchor" href="#section-3-use-descriptive-activity-names-to-name-the-activities-in-the-data-set" aria-hidden="true"><span class="octicon octicon-link"></span></a>Section 3. Use descriptive activity names to name the activities in the data set</h2>

<p>Merge data subset with the activityType table to cinlude the descriptive activity names</p>

<h2><a id="user-content-section-4-appropriately-label-the-data-set-with-descriptive-activity-names" class="anchor" href="#section-4-appropriately-label-the-data-set-with-descriptive-activity-names" aria-hidden="true"><span class="octicon octicon-link"></span></a>Section 4. Appropriately label the data set with descriptive activity names.</h2>

<p>Use gsub function for pattern replacement to clean up the data labels.</p>

<h2><a id="user-content-section-5-create-a-second-independent-tidy-data-set-with-the-average-of-each-variable-for-each-activity-and-each-subject" class="anchor" href="#section-5-create-a-second-independent-tidy-data-set-with-the-average-of-each-variable-for-each-activity-and-each-subject" aria-hidden="true"><span class="octicon octicon-link"></span></a>Section 5. Create a second, independent tidy data set with the average of each variable for each activity and each subject.</h2>

<p>Per the project instructions, we need to produce only a data set with the average of each veriable for each activity and subject</p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>
      </div>
      <div class="modal-backdrop"></div>
    </div>
  </div>


    </div>

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.06811s from github-fe117-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" integrity="sha256-+Ec97OckLaaiDVIxNjSIGzl1xSzrqh5sOBV8DyYYVpE=" src="https://assets-cdn.github.com/assets/frameworks-f8473dece7242da6a20d52313634881b3975c52cebaa1e6c38157c0f26185691.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-7mQUuwycQ/5sSyawnsrzNebXbeAtkqFQrykqHSA0tyg=" src="https://assets-cdn.github.com/assets/github-ee6414bb0c9c43fe6c4b26b09ecaf335e6d76de02d92a150af292a1d2034b728.js"></script>
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

