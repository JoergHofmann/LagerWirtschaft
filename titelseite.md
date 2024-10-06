---
title: @(Projekt.title)
linktitle: @(Projekt.shorttitle)
chapter: false
---
![](/images/@(Projekt.wwwCover))

<p style="text-align: center">
@(Autor.name)@(br)
Stand: @(Monat[heute.month].MMMM) @(heute.year)@(br)
Git: @(GetShortGITHash "")</p>
