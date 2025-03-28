
# Table of Contents

1.  [Introduction to Bash](#org1894c4a)
    1.  [What is a shell?](#org0fbc6e9)
    2.  [What is Bash?](#org2fc8550)
2.  [Basics of Bash](#org939b64a)
    1.  [Invoking Bash](#org36641f9)
    2.  [Simple Commands](#org2f74e2c)
    3.  [Pipelines](#orgeef6ac2)
    4.  [Tilde Expansion](#org6580e2d)
    5.  [Brace expansion](#org5cd9561)
    6.  [Looping constructs](#orgb8bf40e)
        1.  [until](#org29b6fd5)
        2.  [while](#orgffa46f4)
        3.  [for](#orgf14eb2e)
    7.  [Using seq command](#org091c5a7)
    8.  [Conditional constructs](#org7abb8f5)
        1.  [if statement](#orgadc8f0a)
        2.  [case statement](#org90daf9e)
        3.  [select statement](#orge1ffd00)
    9.  [Redirections](#orgce655fc)
    10. [Using sleep command](#orgfbbb109)
    11. [Using export command](#org76db9ca)
    12. [Common commands like date, ls, wc, locate, find](#org802e922)
    13. [Using Aliases](#orgd9a879d)
    14. [Using backtick](#org7340d40)
3.  [Process Management](#org2e322cc)
    1.  [Process Lifecycle](#org4f4927e)
    2.  [Listing running processes](#orgeeaaec7)
    3.  [Killing a process](#orgaa18749)
    4.  [Suspending a process](#org6c7c879)
    5.  [Signals](#org8174f88)
    6.  [Cron scripts](#org4a39db5)
    7.  [Exit code](#org59f5899)
    8.  [Daemons and Services](#orge66f736)
4.  [User Management](#org361752e)
    1.  [Logging in](#orgd265436)
    2.  [Changing password](#org2cc1809)
    3.  [Users, groups and permissions](#orge630eab)
    4.  [suid/sgid/sticky bits](#org83a5a19)
    5.  [Creating and deleting users and groups](#org5ff7dce)
    6.  [sudo user](#org008b634)
    7.  [who](#org93b705c)
5.  [Network Management](#orgec88c2a)
    1.  [Network interfaces](#org3dd7cfe)
    2.  [DNS lookups](#org230c7d3)
    3.  [ping](#orgd539cc3)
    4.  [netstat](#orge8d4ce5)
    5.  [SSH](#orgd1e775e)
    6.  [tmux/screen](#org4a8e22a)
    7.  [scp](#org2002ec5)
6.  [I/O Redirection](#orgdd08bb9)
    1.  [Read](#orge8ef4aa)
    2.  [Redirecting input](#orgff93568)
    3.  [Redirecting output](#orgbc1551a)
    4.  [Appending to redirect output](#orgdd23212)
7.  [Environment Variables](#orgfc81bba)
    1.  [HOME](#orgefbeccd)
    2.  [USER](#orgfac98f0)
8.  [Some popular external programs](#org6c22ae7)
    1.  [sed](#orga2d49d3)
    2.  [cal](#orgef90977)
    3.  [grep](#orge5bdb93)
    4.  [man](#org42f8dfd)
    5.  [info](#orgdfe4bdf)
9.  [Startup Files](#org9952a76)
    1.  [.bashrc](#orge79da3b)
    2.  [.zshrc](#org6c7b91b)
10. [Shell Arithmetic](#orgbee66af)
    1.  [Use of let, expr](#orgd1250be)
    2.  [Double parantheses $(( ))](#orga65ee9e)
    3.  [Arithmetic expansion](#org88dfc63)



<a id="org1894c4a"></a>

# Introduction to Bash


<a id="org0fbc6e9"></a>

## What is a shell?


<a id="org2fc8550"></a>

## What is Bash?


<a id="org939b64a"></a>

# Basics of Bash


<a id="org36641f9"></a>

## Invoking Bash


<a id="org2f74e2c"></a>

## Simple Commands


<a id="orgeef6ac2"></a>

## Pipelines


<a id="org6580e2d"></a>

## Tilde Expansion


<a id="org5cd9561"></a>

## Brace expansion


<a id="orgb8bf40e"></a>

## Looping constructs


<a id="org29b6fd5"></a>

### until


<a id="orgffa46f4"></a>

### while


<a id="orgf14eb2e"></a>

### for


<a id="org091c5a7"></a>

## Using seq command


<a id="org7abb8f5"></a>

## Conditional constructs


<a id="orgadc8f0a"></a>

### if statement


<a id="org90daf9e"></a>

### case statement


<a id="orge1ffd00"></a>

### select statement


<a id="orgce655fc"></a>

## Redirections


<a id="orgfbbb109"></a>

## Using sleep command


<a id="org76db9ca"></a>

## Using export command


<a id="org802e922"></a>

## Common commands like date, ls, wc, locate, find


<a id="orgd9a879d"></a>

## Using Aliases


<a id="org7340d40"></a>

## Using backtick


<a id="org2e322cc"></a>

# Process Management


<a id="org4f4927e"></a>

## Process Lifecycle


<a id="orgeeaaec7"></a>

## Listing running processes


<a id="orgaa18749"></a>

## Killing a process


<a id="org6c7c879"></a>

## Suspending a process


<a id="org8174f88"></a>

## Signals


<a id="org4a39db5"></a>

## Cron scripts


<a id="org59f5899"></a>

## Exit code


<a id="orge66f736"></a>

## Daemons and Services


<a id="org361752e"></a>

# User Management


<a id="orgd265436"></a>

## Logging in


<a id="org2cc1809"></a>

## Changing password


<a id="orge630eab"></a>

## Users, groups and permissions


<a id="org83a5a19"></a>

## suid/sgid/sticky bits


<a id="org5ff7dce"></a>

## Creating and deleting users and groups


<a id="org008b634"></a>

## sudo user


<a id="org93b705c"></a>

## who


<a id="orgec88c2a"></a>

# Network Management


<a id="org3dd7cfe"></a>

## Network interfaces


<a id="org230c7d3"></a>

## DNS lookups


<a id="orgd539cc3"></a>

## ping


<a id="orge8d4ce5"></a>

## netstat


<a id="orgd1e775e"></a>

## SSH


<a id="org4a8e22a"></a>

## tmux/screen


<a id="org2002ec5"></a>

## scp


<a id="orgdd08bb9"></a>

# I/O Redirection


<a id="orge8ef4aa"></a>

## Read


<a id="orgff93568"></a>

## Redirecting input


<a id="orgbc1551a"></a>

## Redirecting output


<a id="orgdd23212"></a>

## Appending to redirect output


<a id="orgfc81bba"></a>

# Environment Variables


<a id="orgefbeccd"></a>

## HOME


<a id="orgfac98f0"></a>

## USER


<a id="org6c22ae7"></a>

# Some popular external programs


<a id="orga2d49d3"></a>

## sed


<a id="orgef90977"></a>

## cal


<a id="orge5bdb93"></a>

## grep


<a id="org42f8dfd"></a>

## man


<a id="orgdfe4bdf"></a>

## info


<a id="org9952a76"></a>

# Startup Files


<a id="orge79da3b"></a>

## .bashrc


<a id="org6c7b91b"></a>

## .zshrc


<a id="orgbee66af"></a>

# Shell Arithmetic


<a id="orgd1250be"></a>

## Use of let, expr


<a id="orga65ee9e"></a>

## Double parantheses $(( ))


<a id="org88dfc63"></a>

## Arithmetic expansion

