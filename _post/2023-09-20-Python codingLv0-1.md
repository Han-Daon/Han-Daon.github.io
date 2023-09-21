---
title:  "덧셈식 출력하기"
categories:
  - codingtest

toc: true
toc_sticky: true
 
date: 2023-09-21
last_modified_at: 2023-09-21
---
a, b = map(int, input().strip().split(' '))
c = a + b
print('{} + {} = {}'.format(a,b,c))
