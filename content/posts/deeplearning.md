---
title: "PointNetLK for Point Cloud Registration"
date: 2024-08-06T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "https://github.com/SmartZhuo/Project-Thesis_FAU/blob/main/image/mymarker1.png?raw=true" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

# PointNetLK: Lessons Learned for Beginners in Deep Learning and Point Cloud Registration
PointNetLK is built upon the PointNet model, a novel and widely-used approach for extracting features from point clouds, originally developed by Zhang et al. PointNetLK applies the Lucas-Kanade (LK) algorithm to approximate the transformation matrix between point clouds.

For beginners in deep learning or point cloud registration, here are some important lessons:

1. Clarify Your Use Case
It's crucial to understand your target application and how users will interact with your model. Consider whether you need to classify point clouds, match point clouds for pose estimation, or something else entirely. Once you know your use case, consider the specific scenarios involved. For instance, if you're working on point cloud registration, you should determine whether your source point cloud is partial or contains significant noise. Clarifying your use case will help you focus your literature search and avoid wasting time on irrelevant methods.

In my project, the goal is to perform point cloud registration to estimate the pose of a robot. The target point cloud is predefined, but the source point cloud must be obtained through a camera. As a result, the source point cloud is often noisy and partial.

Given this scenario, my literature search focuses on:

1. Identifying methods for noise and outlier removal.
2. Finding techniques that offer better accuracy and robustness when dealing with noisy and partial source point clouds.




![Static Badge](https://img.shields.io/badge/FAU-FAPS-GREEN)

See the opensource code:  
https://github.com/SmartZhuo/Project-Thesis_FAU

