---
title: Lesson Five
---
aaaaaaaaaaaaaaaaaaa



he configuration above adds a new setting, public_folder. While media_folder specifies where uploaded files are saved in the repo, public_folder indicates where they are found in the published site. Image src attributes use this path, which is relative to the file where it's called. For this reason, we usually start the path at the site root, using the opening /.

If public_folder is not set, Netlify CMS defaults to the same value as media_folder, adding an opening / if one is not included.
