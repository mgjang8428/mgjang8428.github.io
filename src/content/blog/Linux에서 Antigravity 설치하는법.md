---
title: 'Linux에서 Antigravity 설치 방법'
description: 'Linux에서 Antigravity를 설치하는 방법에 대해'
pubDate: '2026-11-14'
#updatedDate: '2000-01-01'  #options
heroImage: '../../assets/blog-placeholder-1.jpg'
---

Antigravity App v2.32.1 버전 기준</br>

1. Antigravity 홈페이지에서 Linux용 설치 파일 다운로드
https://antigravity.google/download/

2. 받은 파일을 압축해제
```
tar -zxvf ./Antigravity.tar.gz
```
3. 폴더 내부로 위치 이동
```
cd ./Antigravity/Antigravity-x64
```
4. chrome-sandbox 파일의 권한 수정
```
sudo chown root:root ./chrome-sandbox
sudo chmod 4755 ./chrome-sandbox
```
5. Antigravity 실행
```
./antigravity
```
<br/>

* 빠른 실행을 위한 바로가기, 링크는 별도의 작업이 필요합니다.
* Antigravity IDE는 같은 작업을 하되 폴더명 중간 공백을 없애야 합니다.
    * mv ./Antigravity IDE ./AntigravityIDE