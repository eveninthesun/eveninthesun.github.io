---
layout: post
title:  "Visual Code extensions-paste images"
date:   2022-01-03 22:09:37 +0900
categories: VisualCode paste_images
---

<H1>Visual Studio Code Markdown 활용법 정리-1</H1>
<H1>Paste Images 확장 사용하기</H1>

# 설치

![](/assets/images/2021-12-23-11-35-10.png)

![](/assets/images/2021-12-23-11-36-07.png)

1. 비주얼 코드의 확장 탭에서 paste images를 설치한다.

# 설정

1. 원활한 사용을 위해 붙여넣기 되는 이미지는 images 라는 폴더 안에 쌓이도록 설정한다.

## 설정 진입

![](/assets/images/2021-12-23-11-37-30.png)

1. 확장 설정을 클릭한다

## 설정 변경

![](/assets/images/2021-12-23-11-38-31.png)

### 저장 위치 변경 : Path

1. ${currentFileDir}/images/ <- 다음과 같이 변경해준다.
2. 현재 폴더에 images 라는 폴더를 추가하여 해당 폴더 안에 이미지를 저장한다.

### 붙여넣기 설정 변경 : prefix

1. /assets/images/
2. 붙여넣기 실행 시 이미지 명 앞에 붙을 prefix를 지정한다.
3. 이를 지정하지 않으면 정상적으로 이미지가 출력되지 않는다.

# 테스트

1. [ALT] + [WIN] + [S] 로 이미지를 캡쳐한다.

2. [CTRL] + [ALT] + [V] 로 이미지를 붙여넣는다.

3. images 라는 폴더가 생성되고 이미지가 들어간 것을 확인 할 수 있다.

4. 미리보기 확인 ( [CTRL] + [SHIFT] + [V])

![](/assets/images/2021-12-23-11-45-49.png)

5. 깃허브에 푸시하여 웹에서도 정상적으로 붙는지 테스트한다.

![](/assets/images/2021-12-23-11-43-26.png)

6. 소스 제어 탭에 가보면 이미지와 파일이 생성된 걸 볼 수 있다.

https://github.com/eveninthesun/common/blob/common/settings/paste%20images.md