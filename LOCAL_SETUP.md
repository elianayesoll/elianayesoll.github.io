# 로컬에서 Jekyll 사이트 확인하기

## 사전 준비
1. **Ruby 설치** (아직 설치하지 않은 경우)
   - https://rubyinstaller.org/ 에서 Ruby+Devkit 버전 다운로드
   - 설치 후 터미널을 재시작하세요

## 실행 방법

### 1단계: 의존성 설치
```powershell
bundle install
```

### 2단계: 로컬 서버 실행
```powershell
bundle exec jekyll serve
```

### 3단계: 브라우저에서 확인
서버가 시작되면 다음 주소에서 확인할 수 있습니다:
- **로컬 주소**: http://localhost:4000
- **네트워크 주소**: http://127.0.0.1:4000

## 주의사항
- `_config.yml` 파일을 수정한 경우 서버를 재시작해야 합니다
- 서버를 중지하려면 `Ctrl + C`를 누르세요

## 문제 해결
- Ruby가 설치되지 않았다면 위의 RubyInstaller를 먼저 설치하세요
- `bundle install` 오류가 발생하면 `bundle update`를 시도해보세요

