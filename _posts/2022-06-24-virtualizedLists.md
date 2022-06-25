---
title: "VirtualizedLists should never be nested"
date: 2022-06-24T00:00:00+00:00
author: Seolhee Kim
layout: post
permalink: /react-native-VirtualizedLists-should-never-be-nested/
categories: Log
tags: ["react-native"]
---
- Warning Message:
```
VirtualizedLists should never be nested inside plain ScrollViews with the same orientation
because it can break windowing and other functionality - use another VirtualizedList-backed container instead.
```

- Solution:
http://daplus.net/javascript-react-native-%EB%8B%A4%EB%A5%B8-virtualizedlist-%EC%A7%80%EC%9B%90-%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88/
