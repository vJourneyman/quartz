---
title: "publishing"
date-created: 2022-10-12
day-of-week-created: Wed
date-updated: 
aliases: []
tags: []
status: unstarted
---

# publishing

[

### # Pushing Changes

[Quartz Documentation Source - hosting - pushing changes](https://quartz.jzhao.xyz/notes/hosting/#pushing-changes)

To see your changes on the internet, we need to push it them to GitHub. Quartz is a `git` repository so updating it is the same workflow as you would follow as if it were just a regular software project.

```shell
# Navigate to Quartz folder
h:
cd "Podcast\Nerd Journey\PublicGraph\quartz\content"

# Commit all changes
git add .
git commit -m "message describing changes"

# Push to GitHub to update site
git push origin hugo
```