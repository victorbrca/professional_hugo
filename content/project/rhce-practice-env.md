+++
# Date this page was created.
date = "2023-11-30"

# Project title.
title = "RHCE v8 Practice Enviroment"

# Project summary to display on homepage.
summary = "An RHCE v8 lab enviroment with practice exams."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "logo_mid.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["linux"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "Welcome-page.jpg"
caption = ""

+++


[victorbrca/rhce8-practice-env](https://github.com/victorbrca/rhce8-practice-env)

A repo that can be used to create a RHEL 8 lab environment, using Vagrant, VirtualBox, and Ansible. This environment can be used to practice for the RHCE v8 exam.

The lab environment consists of 1x control node (RHEL server with GUI), one local repo server, and 4x additional nodes.

    control
    repo
    node1
    node2
    node3
    node4

A few practice exams are also included.
