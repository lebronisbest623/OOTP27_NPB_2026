# 기여 가이드

[English](./CONTRIBUTING.md)

The World Mod에 관심을 가져주셔서 감사합니다.

## 기여 방법

### 1. 이슈 제출

다음과 같은 내용은 GitHub Issues로 제보해 주세요.

- 선수 데이터 오류
- 누락된 선수
- 로고나 유니폼 문제
- 구장 문제
- FaceGen 문제
- 설치 문제
- 기능 제안

코딩은 필요 없습니다. 스크린샷, 파일명, 간단한 설명이 있으면 큰 도움이 됩니다.

### 2. Pull Request

퀵스타트 수정, 리소스 개선, 문서 업데이트는 Pull Request로 기여할 수 있습니다.

#### 방법 A: 웹 업로드

1. GitHub에서 이 저장소를 Fork합니다.
2. 본인 Fork에서 수정할 폴더로 이동합니다.
3. `Add file` -> `Upload files`를 클릭합니다.
4. 파일을 업로드합니다.
5. 변경사항을 커밋합니다.
6. `Contribute` -> `Open pull request`를 클릭합니다.
7. 변경 내용을 짧게 설명하고 Pull Request를 제출합니다.

#### 방법 B: Git 사용

##### 1단계: 저장소 Fork

GitHub 페이지에서 저장소를 Fork합니다.

##### 2단계: Clone

```bash
git clone https://github.com/내계정/the-world-mod.git
cd the-world-mod
```

##### 3단계: 파일 추가 또는 수정

파일은 아래 위치에 맞게 정리해 주세요.

| 콘텐츠 | 폴더 |
|--------|------|
| 퀵스타트 파일 | `THE_WORLD_MOD.quick/` |
| 유니폼 | `the-world-mod/uniform/` |
| 로고 | `the-world-mod/logos/` |
| FaceGen | `the-world-mod/fg_files/` |
| 구장 | `the-world-mod/ballparks/` |
| 문서 | 저장소 루트 |

##### 4단계: Commit & Push

```bash
git add .
git commit -m "기여 내용 설명"
git push
```

##### 5단계: Pull Request 생성

1. GitHub에서 본인 Fork로 이동합니다.
2. `Contribute` -> `Open pull request`를 클릭합니다.
3. 무엇을 왜 바꿨는지 설명합니다.
4. Pull Request를 제출합니다.

## 가이드라인

- 기존 배포 구조와 파일명 규칙을 최대한 유지해 주세요.
- 명확한 이유가 없다면 폴더 이름은 바꾸지 마세요.
- 라이선스나 출처가 중요한 자산을 수정할 경우, 가능하면 출처와 허용 범위를 함께 적어 주세요.
- 선수 데이터나 시각 리소스를 수정했다면 어떤 팀 또는 어떤 선수가 영향을 받는지 적어 주세요.

## 질문이 있나요?

어디에 어떻게 기여해야 할지 애매하면 이슈를 열어 주세요.
