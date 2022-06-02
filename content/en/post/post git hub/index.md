---
title: Version control. Git.
subtitle: 

# Summary for listings and search engines
summary: Here you can learn about version control.

# Link this post with a project
projects: []

# Date published
date: '2022-05-07T00:00:00Z'

# Date updated
lastmod: '2022-05-07T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---

## Information.

Git - eto raspredelennyy instrument kontrolya versiy, kotoryy nemnogo slozhneye v ispol'zovanii, chem SVN i drugiye instrumenty kontrolya versiy. Chtoby oblegchit' ponimaniye, eta stat'ya podrobno opisyvayet ispol'zovaniye Git s pomoshch'yu grafiki, chtoby bystro osvoit' Git. Osnovnyye komandy pokazany na risunke. Iz risunka vyshe vidno, chto Git kontseptual'no razdelen na 3 bol'shiye oblasti: rabocheye prostranstvo, lokal'nyy sklad i udalennyy sklad. Sushchestvuyet takzhe oblast' vremennogo khraneniya, takzhe nazyvayemaya indeksnoy oblast'yu. Davayte posmotrim, chto delayet kazhdaya oblast'. Klyuchevym momentom, kotoryy otrazhayet Git, yavlyayetsya raspredelennoye upravleniye versiyami v tom, chto u nego yest' lokal'noye khranilishche. Fakticheski obychnaya rabota po upravleniyu versiyami vypolnyayetsya v lokal'noy biblioteke. - Rabochaya oblast': Na samom dele eto nash rabochiy katalog v operatsionnoy sisteme. My mozhem prosmatrivat' komandy upravleniya faylami operatsionnoy sistemy (naprimer, cherez komandu ls v Linux). - Lokal'nyy repozitoriy: v rabochey oblasti yest' skrytyy katalog .git. Etot katalog i yego soderzhimoye takzhe yavlyayutsya chast'yu rabochey oblasti, no yavlyayutsya lokal'nym repozitoriyem Git. On ispol'zuyetsya dlya
Ещё
1 166 / 5 000
Результаты перевода
Git is a distributed version control tool that is slightly more difficult to use than SVN and other version control tools. To make it easier to understand, this article details the use of Git with graphics to quickly learn Git. The main commands are shown in the figure.
From the figure above, you can see that Git is conceptually divided into 3 large areas: the workspace, the local store, and the remote store. There is also a temporary storage area, also called an index area. Let's see what each area does. The key point that Git reflects is distributed versioning in that it has local storage. In fact, the normal versioning work is done in the local library.

 - Workspace: This is actually our working directory in the operating system. We can view the file management commands of the operating system (for example, through the ls command in Linux).
 - Local repository: There is a hidden .git directory in the workspace. This directory and its contents are also part of the workspace, but are a local Git repository. It is used for
