---
layout: post
title:  "6회차. 리액트 네이티브 투두 어플만들기 / 결과"
date:   2018-02-11 16:32:00
author: 이상현
categories: 로컬(모각코)
---

# 6회차. 리액트 네이티브 투두 어플만들기 / 결과

## 결과

프로젝트는 [깃허브](https://github.com/isseebx123/ReactTodoApp)로 관리하기로 한다.

### UI 제작

지난번 작업에 이어서, 이번엔 큰 틀안에 들어갈 하나하나의 아이템을 의미하는 ToDo를 생성한다.
ToDo 컴포넌트는 ToDo.js에 정의하며, App.js에서 ScrollView안에 ToDo를 추가한다.
나중에 일정 추가를 요청할 때마다 ToDo 컴포넌트를 추가적으로 생성하여 ScrollView에 넣음으로써
주요 기능을 구현할 수 있을 것으로 보인다.

### 오류

1. Server Disconneted
> 프로젝트 연결이후 빌드를 완료, Reload를 통해 한번 UI를 받아왔지만,
코드 수정이후 Hot Reload 또는 Reload를 사용하면 그 이후부터 동일한 에러가 계속발생한다.
로그에서는 디버깅 모드를 통해 스마트폰을 직접연결하거나, 동일한 wifi내에서 개발하기를 권고하는데
두 경우 모두 해보고 있지만 해결되지 않는다.

2. Hot Reloading Failed
> 코드를 수정하고 저장을 하였는데, 핫 리로드를 수행중에 뜨는 로딩아이콘이 뜨지 않거나,
핫 리로드를 시도하는데 그 결과로 오류가 발생한다.

3. 안드로이드 Expo에서 프로젝트 인식 불가
> 컴파일, 런타임에러가 아닌 Expo앱에서 인식 자체가 되지 않는다. Expo에서 Share를 통해
QR code로 접근하거나, usb로 접근해 보았지만 두 경우 모두 이 현상이 발생한다.

<pre>
우분투로 원만하게 진행했던 지난 리액트 네이티브 영화앱과 날씨앱에 비해서, 윈도우로 진행을 시도하는 Todo앱은
Expo로 개발하려고 하니 상당한 오류가 발생하였다. 이 부분들이 해결되어야 제대로 공부가 진행될 수 있을 것 같다.
아니면 우분투로 다시 개발해야될 것이다.
</pre>
