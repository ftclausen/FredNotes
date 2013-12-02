---
layout: post
title: "Bash history expansion cheatsheet"
date: 2013-12-02 12:11
categories: general
---

Often I forget the precise letter incantation for a particular 
bash history expansion shortcut and the bash manual page is crying out
for a tabular form of these history expansions. So I decided to make 
one here for quick reference.

## Event Designator (Line entry in history list)

| Shortcut | Purpose | Example |
| ---------|---------|---------|
| ! | Start a history substitution | ! |
| !n | Refer to command *n* in history | !5 |
| !-n | Refer to current command minus *n* | !-5 |
| !! | Refer to previous command | !! |
| !string | Refer to the most recent command *starting with* "string" | !ls |
| !?string? | Refer to the most recent command *containing* "string" | !?ls? |
| !# | The entire command line type so far | echo !# back at ya |

