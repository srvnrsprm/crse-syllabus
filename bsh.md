
# Table of Contents

1.  [Introduction to Bash](#org892db74)
    1.  [What is a shell?](#org9b94cf0)
    2.  [What is Bash?](#orgcd4c206)
2.  [Basics of Bash](#org11e967f)
    1.  [Invoking Bash](#org77dacec)
    2.  [Simple Commands](#orgaf34517)
    3.  [Pipelines](#org01dc071)
    4.  [Tilde Expansion](#orgba29042)
    5.  [Brace expansion](#org85e4482)
    6.  [Looping constructs](#orgbd910a4)
        1.  [until](#orgaf5c84b)
        2.  [while](#org9be4797)
        3.  [for](#orgd040095)
    7.  [Using seq command](#org2422c45)
    8.  [Conditional constructs](#orge461e30)
        1.  [if statement](#org657217a)
        2.  [case statement](#org9e3175d)
        3.  [select statement](#org2e7f9bd)
    9.  [Redirections](#org13b05bc)
    10. [Using sleep command](#orgf7f470d)
    11. [Using export command](#org37e8c1c)
    12. [Common commands like date, ls, wc, locate, find](#org14bcdcf)
    13. [Using Aliases](#orgef56787)
    14. [Using backtick](#org7e7b95d)
3.  [Process Management](#org0a3311d)
    1.  [Process Lifecycle](#org7e13e50)
    2.  [Listing running processes](#orgd4f145a)
    3.  [Killing a process](#org7f665fd)
    4.  [Suspending a process](#org4c2c97a)
    5.  [Signals](#org8a2c701)
    6.  [Cron scripts](#org858e6f5)
    7.  [Exit code](#orgc6be9e0)
    8.  [Daemons and Services](#org12bb3cd)
4.  [User Management](#org92ac35f)
    1.  [Logging in](#org80c8e36)
    2.  [Changing password](#orgdde1e59)
    3.  [Users, groups and permissions](#org4bf4419)
    4.  [suid/sgid/sticky bits](#org631be10)
    5.  [Creating and deleting users and groups](#org0ab1804)
    6.  [sudo user](#org776f197)
    7.  [who](#org377e05f)
5.  [Network Management](#orgbe7c8ca)
    1.  [Network interfaces](#org03c349f)
    2.  [DNS lookups](#org231997c)
    3.  [ping](#orgc0fe4ea)
    4.  [netstat](#orgbc05eac)
    5.  [SSH](#orgaf25c13)
    6.  [tmux/screen](#org671d016)
    7.  [scp](#org95eabde)
6.  [I/O Redirection](#org18f9eb3)
    1.  [Read](#org25d152d)
    2.  [Redirecting input](#org8425bb6)
    3.  [Redirecting output](#org44039b5)
    4.  [Appending to redirect output](#org30dc9cc)
7.  [Environment Variables](#org8efb250)
    1.  [HOME](#orgbb85318)
    2.  [USER](#orgdb2280c)
8.  [Some popular external programs](#org9ea18ed)
    1.  [sed](#org6776be2)
    2.  [cal](#org0a888d7)
    3.  [grep](#orgc27e139)
    4.  [man](#org63104e8)
    5.  [info](#org847b416)
9.  [Startup Files](#org3dc9d81)
    1.  [.bashrc](#org151b6bf)
    2.  [.zshrc](#org236cdc3)
10. [Shell Arithmetic](#orge8db24d)
    1.  [Use of let, expr](#org91cd7b9)
    2.  [Double parantheses $(( ))](#orgbed0aed)
    3.  [Arithmetic expansion](#orgba122d9)


<a id="org892db74"></a>

# Introduction to Bash


<a id="org9b94cf0"></a>

## What is a shell?


<a id="orgcd4c206"></a>

## What is Bash?


<a id="org11e967f"></a>

# Basics of Bash


<a id="org77dacec"></a>

## Invoking Bash


<a id="orgaf34517"></a>

## Simple Commands


<a id="org01dc071"></a>

## Pipelines


<a id="orgba29042"></a>

## Tilde Expansion


<a id="org85e4482"></a>

## Brace expansion


<a id="orgbd910a4"></a>

## Looping constructs


<a id="orgaf5c84b"></a>

### until


<a id="org9be4797"></a>

### while


<a id="orgd040095"></a>

### for


<a id="org2422c45"></a>

## Using seq command


<a id="orge461e30"></a>

## Conditional constructs


<a id="org657217a"></a>

### if statement


<a id="org9e3175d"></a>

### case statement


<a id="org2e7f9bd"></a>

### select statement


<a id="org13b05bc"></a>

## Redirections


<a id="orgf7f470d"></a>

## Using sleep command


<a id="org37e8c1c"></a>

## Using export command


<a id="org14bcdcf"></a>

## Common commands like date, ls, wc, locate, find


<a id="orgef56787"></a>

## Using Aliases


<a id="org7e7b95d"></a>

## Using backtick


<a id="org0a3311d"></a>

# Process Management


<a id="org7e13e50"></a>

## Process Lifecycle


<a id="orgd4f145a"></a>

## Listing running processes


<a id="org7f665fd"></a>

## Killing a process


<a id="org4c2c97a"></a>

## Suspending a process


<a id="org8a2c701"></a>

## Signals


<a id="org858e6f5"></a>

## Cron scripts


<a id="orgc6be9e0"></a>

## Exit code


<a id="org12bb3cd"></a>

## Daemons and Services


<a id="org92ac35f"></a>

# User Management


<a id="org80c8e36"></a>

## Logging in


<a id="orgdde1e59"></a>

## Changing password


<a id="org4bf4419"></a>

## Users, groups and permissions


<a id="org631be10"></a>

## suid/sgid/sticky bits


<a id="org0ab1804"></a>

## Creating and deleting users and groups


<a id="org776f197"></a>

## sudo user


<a id="org377e05f"></a>

## who


<a id="orgbe7c8ca"></a>

# Network Management


<a id="org03c349f"></a>

## Network interfaces


<a id="org231997c"></a>

## DNS lookups


<a id="orgc0fe4ea"></a>

## ping


<a id="orgbc05eac"></a>

## netstat


<a id="orgaf25c13"></a>

## SSH


<a id="org671d016"></a>

## tmux/screen


<a id="org95eabde"></a>

## scp


<a id="org18f9eb3"></a>

# I/O Redirection


<a id="org25d152d"></a>

## Read


<a id="org8425bb6"></a>

## Redirecting input


<a id="org44039b5"></a>

## Redirecting output


<a id="org30dc9cc"></a>

## Appending to redirect output


<a id="org8efb250"></a>

# Environment Variables


<a id="orgbb85318"></a>

## HOME


<a id="orgdb2280c"></a>

## USER


<a id="org9ea18ed"></a>

# Some popular external programs


<a id="org6776be2"></a>

## sed


<a id="org0a888d7"></a>

## cal


<a id="orgc27e139"></a>

## grep


<a id="org63104e8"></a>

## man


<a id="org847b416"></a>

## info


<a id="org3dc9d81"></a>

# Startup Files


<a id="org151b6bf"></a>

## .bashrc


<a id="org236cdc3"></a>

## .zshrc


<a id="orge8db24d"></a>

# Shell Arithmetic


<a id="org91cd7b9"></a>

## Use of let, expr


<a id="orgbed0aed"></a>

## Double parantheses $(( ))


<a id="orgba122d9"></a>

## Arithmetic expansion

