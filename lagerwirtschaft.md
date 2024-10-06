---
language: @(Projekt.shortlang)
author:  @(Autor['name'])
email: @(Autor['mail'])
title: @(Projekt.title)
pagetitle: @(Projekt.pagetitle)
subtitle: @(Projekt.subtitle)
shorttitle: @(Projekt.shorttitle)
cover: @(Projekt.cover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
---
# @title

<h3>@subtitle</h3>

![Titelbild](images/titelbild.png "Titelbild")

@(br)
@author@(br)
@mymail

@(br)
@date@(br)
Git: @git
