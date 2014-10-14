---
layout: post
title: Launching an SSH Session
category: The Semaphore platform
---

To launch an SSH session on Semaphore you'll need to add
a [public SSH key]() to your account settings.

After your build or deploy is finished, Semaphore lets you start
an identical build environment where you can run and debug your build
steps manually.

To launch such a build environment, visit the build or deploy page
and click on the Launch SSH button above your thread's output.

<img src="/docs/assets/img/ssh-session/create-ssh-session-1.png" class="img-responsive">

<img src="/docs/assets/img/ssh-session/create-ssh-session-2.png" class="img-responsive">

Semaphore will start a build machine identical to the
machine your build or deploy used. It will pull the same Git commit,
and export the same custom files and environment variables.

<img src="/docs/assets/img/ssh-session/create-ssh-session-3.png" class="img-responsive">

To access the started SSH session, copy the SSH command to your terminal.
