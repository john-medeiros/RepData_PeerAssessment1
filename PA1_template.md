


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>reproduce-research/PA1_template.md at master · shlake/reproduce-research</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="shlake/reproduce-research" name="twitter:title" /><meta content="reproduce-research - Repository for use in the JHU Reproducible Research Coursera Course" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/3809325?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/3809325?v=3&amp;s=400" property="og:image" /><meta content="shlake/reproduce-research" property="og:title" /><meta content="https://github.com/shlake/reproduce-research" property="og:url" /><meta content="reproduce-research - Repository for use in the JHU Reproducible Research Coursera Course" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/NjAxNTI0Njo5MjkwMDUzMjk1OGU1MWFiOWZiMzZhOGY3ZTk1OThkOTpmZTc1YmFiYzZlYmFkMmFlODc1ODQwNTIyODM0OWFkMGRkZjkzNWMwZjM0MGI1ZTQ4YjljOGJkMzU2MjI3N2Nm--986a49c4918d64dfa74606523fc6a2eebebb2e26">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="BB4AE06B:1F55:4D22443:557E1794" name="octolytics-dimension-request_id" /><meta content="6015246" name="octolytics-actor-id" /><meta content="john-medeiros" name="octolytics-actor-login" /><meta content="0e4393eddc82373770a60d8b595f2f9d83b7b40c407bad19db8a7c181ba168c6" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="john-medeiros">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="Otv7w5ZkGgEPC1/9F06YciffqdzT6Hf2X2h5GFJ9PYINaBZRLux1miq/4dIA8n7Qkfy02c+n1rjoPwkPg1XB3Q==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-10789d1d56bfe8c960a6caf2954ab053c3fac748d581415395f986779781b4a7.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-8b4acc27f06d948d9a73d77849e0fe0b98d8636c85e2fe0e6c4b8762dec9fd3d.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="62b85260d6deaadccdaa2c3c0e0b0c94">

      
  <meta name="description" content="reproduce-research - Repository for use in the JHU Reproducible Research Coursera Course">
  <meta name="go-import" content="github.com/shlake/reproduce-research git https://github.com/shlake/reproduce-research.git">

  <meta content="3809325" name="octolytics-dimension-user_id" /><meta content="shlake" name="octolytics-dimension-user_login" /><meta content="22897010" name="octolytics-dimension-repository_id" /><meta content="shlake/reproduce-research" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="22897010" name="octolytics-dimension-repository_network_root_id" /><meta content="shlake/reproduce-research" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/shlake/reproduce-research/commits/master.atom" rel="alternate" title="Recent Commits to reproduce-research:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/shlake/reproduce-research/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/shlake/reproduce-research/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
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
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:john-medeiros"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new..."
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
    <span title="shlake/reproduce-research">This repository</span>
  </div>
    <a class="dropdown-item" href="/shlake/reproduce-research/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="#"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@john-medeiros" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/6015246?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">john-medeiros</strong>
        </div>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/john-medeiros" data-ga-click="Header, go to profile, text:your profile">
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

        <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="fDc/0P37eKVeiaJg+L5EXYpboijQeJpdyFuo/iqTRSWUIonVQ/sL3vsFSnF7ijTcJL28/W2pzzATSTK5Qyu+Cg==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="46sGssibHhjrW/rF3TyepdYlr7lmTt3dJWKpnrkb5kC1KTXsBUEpYyq7LNA/QDlob/w2raVHrHPzrcLHtfmXjw==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="22897010" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/shlake/reproduce-research/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/shlake/reproduce-research/watchers">
          0
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

    <form accept-charset="UTF-8" action="/shlake/reproduce-research/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="v99AG1fqZvAVZhtVALyWIypaHExeQLBPBqVG9L/pKFMWvm2al5a7X4agRYDvnvVDcAvETa+tJZYf2judpRfXaA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar shlake/reproduce-research"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/shlake/reproduce-research/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/shlake/reproduce-research/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="HXQWO09al5LT2/7wmAoZ67fq9w0oRefKq5K9DNW5UDw76U9qHHcd9iFcyaMc4VcFrIyVFeQx77oYvvNkmu0MmA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star shlake/reproduce-research"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/shlake/reproduce-research/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/shlake/reproduce-research/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="1BYtl6VsfE4l+bXrSIseJD+fTteX42ZXzC/qcy7ACBGZ3F7IhXHS5h/XelMJMz6purYMtEI59D093K/Ah2aFkQ==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of shlake/reproduce-research to your account"
                aria-label="Fork your own copy of shlake/reproduce-research to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/shlake/reproduce-research/network" class="social-count">0</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/shlake" class="url fn" itemprop="url" rel="author"><span itemprop="title">shlake</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/shlake/reproduce-research" data-pjax="#js-repo-pjax-container">reproduce-research</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/shlake/reproduce-research/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/shlake/reproduce-research" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /shlake/reproduce-research">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/shlake/reproduce-research/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /shlake/reproduce-research/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/shlake/reproduce-research/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /shlake/reproduce-research/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/shlake/reproduce-research/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /shlake/reproduce-research/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/shlake/reproduce-research/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /shlake/reproduce-research/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/shlake/reproduce-research/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /shlake/reproduce-research/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/shlake/reproduce-research.git" readonly="readonly">
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
           value="git@github.com:shlake/reproduce-research.git" readonly="readonly">
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
           value="https://github.com/shlake/reproduce-research" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="G+ykzQGvVc6s+MoQEQqq91/AcZ1Kvz7/8HSnKNyh9C5qd0kqZo4FNT7iFOW71bji+FisfyABG/wi0hUkuYVnLA==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="0mOxUxEZ5szdMb9/+Rc/ff+Wuqv3uLwsEJ43L+Tr9ycTF6Cku0kh9OgJfC+8mbg/mVUuGMFMQYjEJbR79Jneeg==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NEU11kTUzg/eTaGwVf0bnI68f2TDtNRFHRL63Tp0EH3agEYa+rhDC1xRmYHlISW9xn0iZNEu8129flui5jfmYg==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save shlake/reproduce-research to your computer and use it in GitHub Desktop." aria-label="Save shlake/reproduce-research to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/shlake/reproduce-research/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of shlake/reproduce-research as a zip file"
                   title="Download the contents of shlake/reproduce-research as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/shlake/reproduce-research/blob/cdfa41d748809ae3c5f68c65b87981ddbae8a191/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:d21b0bfec3d83eb8bf2f64e097af976f -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
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
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/shlake/reproduce-research/blob/master/PA1_template.md"
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
    <a href="/shlake/reproduce-research/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/shlake/reproduce-research" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">reproduce-research</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@shlake" class="avatar" height="24" src="https://avatars1.githubusercontent.com/u/3809325?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/shlake" rel="author">shlake</a></span>
        <time datetime="2014-08-17T23:17:44Z" is="relative-time">Aug 17, 2014</time>
        <div class="commit-title">
            <a href="/shlake/reproduce-research/commit/cdfa41d748809ae3c5f68c65b87981ddbae8a191" class="message" data-pjax="true" title="final program and fingures">final program and fingures</a>
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
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@shlake" height="24" src="https://avatars1.githubusercontent.com/u/3809325?v=3&amp;s=48" width="24" />
            <a href="/shlake">shlake</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/shlake/reproduce-research/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/shlake/reproduce-research/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/shlake/reproduce-research/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/shlake/reproduce-research/edit/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="OWCpBXk4Xk/G2hinJY2Zn3T8661yBJ1jMhDyj5XXKQnwsSqP8BwrfVI1oAO3PuZ8G26+1WVEJqopahLJQurTpw==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/shlake/reproduce-research/delete/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="krUVhhn+AVdNEuzX56lpZ7VaDNgxqnB2xYmn7SflLuNuyyK39J+toHHHN4L5vbia92ruSs7lCBhyTjn1Wie6Jw==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        249 lines (161 sloc)
        <span class="file-info-divider"></span>
      7.508 kB
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Peer Assessment 1</div></td>

  <td><div>html_document</div></td>
  </tr>
  </tbody>
</table>

<p><em>Intro and Data Source from Course assignment description</em></p>

<h2><a id="user-content-introduction" class="anchor" href="#introduction" aria-hidden="true"><span class="octicon octicon-link"></span></a>Introduction</h2>

<p>This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.</p>

<h2><a id="user-content-data-source" class="anchor" href="#data-source" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Source</h2>

<p><strong>Dataset</strong> Available here: <a href="https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip">https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip</a></p>

<p><strong>Fileformat</strong> CSV</p>

<p>17,568 observations</p>

<p><strong>Variables:</strong></p>

<ul>
<li><p><em>steps</em>: Number of steps taking in a 5-minute interval (missing values are coded as NA)</p></li>
<li><p><em>date</em>: The date on which the measurement was taken in YYYY-MM-DD format</p></li>
<li><p><em>interval</em>: Identifier for the 5-minute interval in which measurement was taken</p></li>
</ul>

<h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-r"><pre><span class="pl-smi">activity</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>./activity.csv<span class="pl-pds">"</span></span>)
summary(<span class="pl-smi">activity</span>)</pre></div>

<pre><code>##      steps               date          interval   
##  Min.   :  0.0   2012-10-01:  288   Min.   :   0  
##  1st Qu.:  0.0   2012-10-02:  288   1st Qu.: 589  
##  Median :  0.0   2012-10-03:  288   Median :1178  
##  Mean   : 37.4   2012-10-04:  288   Mean   :1178  
##  3rd Qu.: 12.0   2012-10-05:  288   3rd Qu.:1766  
##  Max.   :806.0   2012-10-06:  288   Max.   :2355  
##  NA's   :2304    (Other)   :15840
</code></pre>

<h2><a id="user-content-total-number-of-steps-taken-per-day" class="anchor" href="#total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>Total Number of Steps Taken Per Day</h2>

<h3><a id="user-content-histogram-of-total-number-of-steps-taken-per-day" class="anchor" href="#histogram-of-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>Histogram of total number of steps taken per day</h3>

<div class="highlight highlight-r"><pre>hist(tapply(<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">main</span> <span class="pl-k">=</span> paste(<span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken per Day<span class="pl-pds">"</span></span>), <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Sum of Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shlake/reproduce-research/blob/master/figure/historgram.png" target="_blank"><img src="/shlake/reproduce-research/raw/master/figure/historgram.png" alt="plot of chunk historgram" style="max-width:100%;"></a> </p>

<h3><a id="user-content-calculate-mean-and-median-total-number-of-steps-taken-per-day" class="anchor" href="#calculate-mean-and-median-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>Calculate mean and median total number of steps taken per day</h3>

<div class="highlight highlight-r"><pre><span class="pl-smi">meanSteps</span> <span class="pl-k">&lt;-</span> mean(tapply(<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
<span class="pl-smi">medianSteps</span> <span class="pl-k">&lt;-</span> median(tapply(<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
print(paste0(<span class="pl-s"><span class="pl-pds">"</span>Mean total number of steps taken per day is: <span class="pl-pds">"</span></span>, <span class="pl-smi">meanSteps</span>), <span class="pl-v">digits</span> <span class="pl-k">=</span> <span class="pl-c1">2</span>)</pre></div>

<pre><code>## [1] "Mean total number of steps taken per day is: 10766.1886792453"
</code></pre>

<div class="highlight highlight-r"><pre>print(paste0(<span class="pl-s"><span class="pl-pds">"</span>Median total number of steps taken per day is: <span class="pl-pds">"</span></span>, <span class="pl-smi">medianSteps</span>))</pre></div>

<pre><code>## [1] "Median total number of steps taken per day is: 10765"
</code></pre>

<h2><a id="user-content-average-daily-activity-pattern" class="anchor" href="#average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>Average daily activity pattern</h2>

<h3><a id="user-content-time-series-plot-interval-with-max-number-of-steps" class="anchor" href="#time-series-plot-interval-with-max-number-of-steps" aria-hidden="true"><span class="octicon octicon-link"></span></a>Time Series Plot, Interval with Max number of steps</h3>

<div class="highlight highlight-r"><pre><span class="pl-smi">avgStepsInt</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">mean</span>, <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
plot(names(<span class="pl-smi">avgStepsInt</span>), <span class="pl-smi">avgStepsInt</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Time Series Plot<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>5-minute Intervals<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Avg Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shlake/reproduce-research/blob/master/figure/activitypattern.png" target="_blank"><img src="/shlake/reproduce-research/raw/master/figure/activitypattern.png" alt="plot of chunk activitypattern" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre><span class="pl-c">## which.max gives index number of the max 5-minute value, so to get the</span>
<span class="pl-c">## max value - which is a lable, make the label a numeric</span>

print(paste0(<span class="pl-s"><span class="pl-pds">"</span>Interval <span class="pl-pds">"</span></span>, as.numeric(names(which.max(<span class="pl-smi">avgStepsInt</span>))) , <span class="pl-s"><span class="pl-pds">"</span> contains the maximum number of steps.<span class="pl-pds">"</span></span>))</pre></div>

<pre><code>## [1] "Interval 835 contains the maximum number of steps."
</code></pre>

<h2><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing Missing Values</h2>

<p>Calculate and report the total number of missing values in the dataset</p>

<div class="highlight highlight-r"><pre>print(paste0(<span class="pl-s"><span class="pl-pds">"</span>There are <span class="pl-pds">"</span></span>, sum(is.na(<span class="pl-smi">activity</span>)) , <span class="pl-s"><span class="pl-pds">"</span> missing values in the dataset.<span class="pl-pds">"</span></span>))</pre></div>

<pre><code>## [1] "There are 2304 missing values in the dataset."
</code></pre>

<h3><a id="user-content-strategy-for-filling-in-missing-values-in-the-dataset" class="anchor" href="#strategy-for-filling-in-missing-values-in-the-dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a>Strategy for filling in missing values in the dataset</h3>

<p>My initial strategy was to </p>

<ul>
<li>calculate the mean number of steps per day</li>
<li>calucalte the mean number of steps per time interval</li>
<li>take the average of the above 2 means</li>
</ul>

<p>But after taking the mean number of steps per day, I realized that there are days with NA which could not be averaged with the mean of the interval. So my final strategy was:</p>

<ul>
<li>calculate the mean number of steps per time interval</li>
</ul>

<h3><a id="user-content-create-a-new-dataset" class="anchor" href="#create-a-new-dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a>Create a new dataset</h3>

<p>Using the above strategy replace the missing values in the activity dataset with the new mean</p>

<div class="highlight highlight-r"><pre><span class="pl-c">## make a copy of activity so to change the copy and not the original</span>
<span class="pl-smi">activityNoNA</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">activity</span>

<span class="pl-smi">meanInterval</span> <span class="pl-k">&lt;-</span>tapply(<span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">activity</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">mean</span>, <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)

<span class="pl-c">## create an index of NAs and loop through the index in the activityNoNA file</span>
<span class="pl-c">## replacing NAs with the mean for that interval</span>

<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> which(is.na(<span class="pl-smi">activityNoNA</span>)))
    {
    <span class="pl-smi">activityNoNA</span>[<span class="pl-smi">i</span>,<span class="pl-c1">1</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">meanInterval</span>[((<span class="pl-smi">i</span><span class="pl-k">-</span><span class="pl-c1">1</span>)<span class="pl-k">%%</span><span class="pl-c1">288</span>)<span class="pl-k">+</span><span class="pl-c1">1</span>]
    }

<span class="pl-c">##new dataset is activityNoNA</span></pre></div>

<h3><a id="user-content-historgram-with-new-dataset" class="anchor" href="#historgram-with-new-dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a>Historgram with new Dataset</h3>

<div class="highlight highlight-r"><pre>hist(tapply(<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">main</span> <span class="pl-k">=</span> paste(<span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken per Day<span class="pl-pds">"</span></span>), <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Sum of Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shlake/reproduce-research/blob/master/figure/newHistorgram.png" target="_blank"><img src="/shlake/reproduce-research/raw/master/figure/newHistorgram.png" alt="plot of chunk newHistorgram" style="max-width:100%;"></a> </p>

<h3><a id="user-content-calculate-mean-and-median-total-number-of-steps-taken-per-day-1" class="anchor" href="#calculate-mean-and-median-total-number-of-steps-taken-per-day-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Calculate mean and median total number of steps taken per day</h3>

<div class="highlight highlight-r"><pre><span class="pl-smi">meanSteps</span> <span class="pl-k">&lt;-</span> mean(tapply(<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
<span class="pl-smi">medianSteps</span> <span class="pl-k">&lt;-</span> median(tapply(<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-smi">sum</span>), <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
print(paste0(<span class="pl-s"><span class="pl-pds">"</span>Mean total number of steps taken per day is: <span class="pl-pds">"</span></span>, <span class="pl-smi">meanSteps</span>), <span class="pl-v">digits</span> <span class="pl-k">=</span> <span class="pl-c1">2</span>)</pre></div>

<pre><code>## [1] "Mean total number of steps taken per day is: 10766.1886792453"
</code></pre>

<div class="highlight highlight-r"><pre>print(paste0(<span class="pl-s"><span class="pl-pds">"</span>Median total number of steps taken per day is: <span class="pl-pds">"</span></span>, <span class="pl-smi">medianSteps</span>))</pre></div>

<pre><code>## [1] "Median total number of steps taken per day is: 10766.1886792453"
</code></pre>

<p>The value for mean in my new file is the same in as the original file. The median for my new file is now the same as the mean. </p>

<p>Imputing missing data for missing data increased the number of steps taken per day. </p>

<h2><a id="user-content-difference-in-activity-patterns-between-weeekdays-and-weekends" class="anchor" href="#difference-in-activity-patterns-between-weeekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Difference in Activity Patterns Between Weeekdays and Weekends?</h2>

<p>For this analysis the dataset with NAs replaced will be used, activityNoNA</p>

<h3><a id="user-content-adding-new-variable-for-weekendweekday" class="anchor" href="#adding-new-variable-for-weekendweekday" aria-hidden="true"><span class="octicon octicon-link"></span></a>Adding new variable for weekend/weekday</h3>

<p>Add a new column to the new activity file specifying the day of the week.
Then the data will be plotted as a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis).</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">weekend</span> <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>)

<span class="pl-smi">dayWeek</span> <span class="pl-k">&lt;-</span> c()

<span class="pl-c">## Check for day of week as a weekend, if not, it's a weekday</span>
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span>length(<span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
    {
    <span class="pl-k">if</span> (any(weekdays(as.Date(<span class="pl-smi">activityNoNA</span>[<span class="pl-smi">i</span>,<span class="pl-c1">2</span>])) <span class="pl-k">==</span> <span class="pl-smi">weekend</span>)) 
        {
            <span class="pl-c">##add "weekend"" to new column for that row</span>
            <span class="pl-smi">dayWeek</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>  }
            <span class="pl-c">##else add "weekday"" to new column for that row</span>
        <span class="pl-k">else</span> { <span class="pl-smi">dayWeek</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>
         }
    }
<span class="pl-c">## Combine activity file with dayweek column</span>

    <span class="pl-smi">activityNoNA</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">activityNoNA</span>,<span class="pl-smi">dayWeek</span>)</pre></div>

<h3><a id="user-content-weekdayweekend-charts" class="anchor" href="#weekdayweekend-charts" aria-hidden="true"><span class="octicon octicon-link"></span></a>Weekday/weekend charts</h3>

<p>Time series plot of 5-minute interval</p>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">lattice</span>)

<span class="pl-c">##split dataset into weekend rows and weekday rows</span>
<span class="pl-c">## change the resulting lists to dataframes</span>

<span class="pl-smi">a</span> <span class="pl-k">&lt;-</span> split(<span class="pl-smi">activityNoNA</span>, <span class="pl-smi">activityNoNA</span><span class="pl-k">$</span><span class="pl-smi">dayWeek</span>)
<span class="pl-smi">wkDays</span> <span class="pl-k">&lt;-</span> do.call(<span class="pl-smi">rbind.data.frame</span>,<span class="pl-smi">a</span>[<span class="pl-c1">1</span>])
<span class="pl-smi">wkEnd</span> <span class="pl-k">&lt;-</span> do.call(<span class="pl-smi">rbind.data.frame</span>,<span class="pl-smi">a</span>[<span class="pl-c1">2</span>])


<span class="pl-smi">avgStepsIntwkDay</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">wkDays</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">wkDays</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">mean</span>)
<span class="pl-smi">avgStepsIntwkEnd</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">wkEnd</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-smi">wkEnd</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">mean</span>)


<span class="pl-smi">intPlotwd</span> <span class="pl-k">&lt;-</span> as.data.frame(cbind(<span class="pl-smi">avgStepsIntwkDay</span>, as.numeric(as.character((names(<span class="pl-smi">avgStepsInt</span>))))))
<span class="pl-smi">intPlotwe</span> <span class="pl-k">&lt;-</span> as.data.frame(cbind(<span class="pl-smi">avgStepsIntwkEnd</span>, as.numeric(as.character((names(<span class="pl-smi">avgStepsInt</span>))))))

<span class="pl-smi">df.intPlotwe</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">intPlotwe</span>, rep(<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>,<span class="pl-c1">288</span>))
<span class="pl-smi">df.intPlotwd</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">intPlotwd</span>, rep(<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>,<span class="pl-c1">288</span>))

colnames(<span class="pl-smi">df.intPlotwd</span>) <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>avgSteps<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>dayweek<span class="pl-pds">"</span></span>)
colnames(<span class="pl-smi">df.intPlotwe</span>) <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>avgSteps<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>dayweek<span class="pl-pds">"</span></span>)


<span class="pl-smi">intPlot</span> <span class="pl-k">&lt;-</span> rbind(<span class="pl-smi">df.intPlotwd</span>, <span class="pl-smi">df.intPlotwe</span>)


xyplot(<span class="pl-smi">avgSteps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span> <span class="pl-k">|</span> <span class="pl-smi">dayweek</span>, <span class="pl-smi">intPlot</span>, <span class="pl-v">layout</span><span class="pl-k">=</span>c(<span class="pl-c1">1</span>,<span class="pl-c1">2</span>),
<span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,<span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Time Series Plot<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>5-minute Intervals<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Avg Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shlake/reproduce-research/blob/master/figure/weekDayWeekEnd.png" target="_blank"><img src="/shlake/reproduce-research/raw/master/figure/weekDayWeekEnd.png" alt="plot of chunk weekDayWeekEnd" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
      <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05119s from github-fe123-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-dea2e78f4b34a1f3429ade94f98bd25fad6bbe8d28635a93d9caeb68e3c2d258.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-f2bb67dd64e6f69f40f179e8bdddd466056de1bf6e2e88b013c8367c41ad703d.js"></script>
      
      
  </body>
</html>

