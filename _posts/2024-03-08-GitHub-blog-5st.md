---
layout: single
title: "깃허브(GitHub) 블로그 05 : 이미지 경로 오류"
tags:
  - Github
  - Blog
---
### 이미지 경로 오류
카테고리 기능을 추가하고 결과를 확인 하는데 이미지가 안 읽어와서 또 무슨 오류인가 싶었다.
카테고리 기능은 url을 통해 분류 된다.

- 카테고리 추가 전

```
https://yoon-beom.github.io/GitHub-blog-1st/
```
- 카테고리 blog 추가 후

```
https://yoon-beom.github.io/blog/GitHub-blog-1st/
```
- 이미지의 경로는 상대경로로 상위 폴더로 올라가서 현재 폴더에서 images 파일에 들어 가는 것이다.

```
![GitHub-blog-14](../images/2024-03-08-GitHub-blog-4st/GitHub-blog-14.png)
```


### 카테고리 적용 전 경로

![GitHub-blog-15](../images/2024-03-08-GitHub-blog-5st/GitHub-blog-15.png)

## 카테고리 적용 후 경로

![GitHub-blog-16](../images/2024-03-08-GitHub-blog-5st/GitHub-blog-16.png)

- 여기서 카테고리 적용 하는 게시글은 ../../ 로 쓰면 이미지가 읽히지만 그렇게 되면 편집기에서는 사진이 안읽힌다는 문제가 있다.