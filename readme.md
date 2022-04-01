# GitHub CLI Notifications Extension 

[gh](https://github.com/cli/cli) extension to interact with GitHub notifications.

## Prerequisites
You need to install [fzf](https://github.com/junegunn/fzf) in order to use the interactive mode. Otherwise you will have to add the -s flag at all times.

## Installation
```
gh extension install daniel-leinweber/gh-notifications
```

## Usage 
```
> gh notifications # view unread notifications
> gh notifications -r # mark all notifications as read
> gh notifications -h # show help 
Usage: gh notifications [--flags]

View and search GitHub notifications. When using fzf you can
select the associated pull request or issue by hitting enter
to get more info on it.

Flags:
    -a      include all notifications 
    -r      mark all notifications as read 
    -s      print a static output list (do not use fzf)
    -p      show only participating or mention notifications
    -n      max number of notifications to show (default 30)
```
