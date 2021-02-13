---
title: Troubleshooting sound in Linux
author: Tao He
date: 2019-04-27
category: Linux
layout: post
---
When your monitor connection is HDMI but the monitor doesn't have speakers. Sound works over HDMI, but not in the headphone jack. Some have the [opposite problem](https://askubuntu.com/questions/937617/no-hdmi-sound-on-intel-nuc-nuc5i3ryh).

You might want to know how to [set your default sound device](https://askubuntu.com/questions/1038490/how-do-you-set-a-default-audio-output-device-in-ubuntu-18-04/1233100#1233100), but that isn't the problem. The problem is: your desktop only sees HMDI as the output _even when you plug in a headset_.

Suggestions for solutions point to outdated [software packages
for older hardware](https://wiki.ubuntu.com/Audio/UpgradingAlsa/DKMS).

Sometimes, it is just plain frustrating.

GitBook is an amazing frontend style to present and organize contents (such as book chapters
and blogs) on Web. The typical to deploy GitBook at [Github Pages][1]
is building HTML files locally and then push to Github repository, usually to the `gh-pages`
branch. However, it's quite annoying to repeat such workload and make it hard for people do
version control via git for when there are generated HTML files to be staged in and out.

This theme takes style definition out of generated GitBook site and provided the template
for Jekyll to rendering markdown documents to HTML, thus the whole site can be deployed
to [Github Pages][1] without generating and uploading HTML bundle every time when there are
changes to the original repository.

[1]: https://pages.github.com
