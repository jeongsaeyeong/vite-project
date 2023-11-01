# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유
1. [vite](https://ko.vitejs.dev/guide/)

Vite는 빠르고 간결한 모던 웹 프로젝트 개발 경험에 초점을 맞춰 탄생한 빌드 도구이며, 두 가지 컨셉을 중심으로 하고 있습니다.

- 개발 시 네이티브 ES Module을 넘어 더욱 다양한 기능을 제공합니다. 
- 번들링 시, Rollup 기반의 다양한 빌드 커맨드를 사용할 수 있습니다. 

Vite는 합리적인 기본 설정을 제공합니다. 프레임워크 지원이나 다른 도구와의 통합은 플러그인을 통해 가능합니다. 

## 트러블 슈팅
- git 업로드 설정: 시작부터 오류가 났다. 
<details>
<summary>git 업로드 설정</summary>
` unable to access 'https://github.com/jeongsaeyeong/vite-project.git/': The requested URL returned error: 403 `

이러한 일이 일어나는 것은 remote 해서 연결한 내 주소와 아이디, 비밀번호가 일치하지 않아서 그렇다. 이를 해결하는 방법은 여러 가지가 있다. 

1) git remote -v를 해서 remote 된 주소가 내 주소가 맞는지 확인한다. 
2) 주소가 맞다면, 자격 증명 관리자 > windows 자격 증명 > 내 깃헙 주소 > 사용자 이름(github 이름)과 암호(github 비밀번호)를 수정한다. 