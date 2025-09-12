# Node.js Version Management Guide

본 프로젝트는 최신 기술 스택 **Next.js 15**, **React 19**를 기반으로 개발됩니다.  
이에 따라 Node.js 버전은 **22.x (LTS 예정)** 을 권장합니다.

---

## 개발 환경 (Windows)

Windows에서는 **nvm-windows**를 사용하여 Node.js 버전을 관리합니다.

### 설치

1. [nvm-windows Releases](https://github.com/coreybutler/nvm-windows/releases)에서 `nvm-setup.exe` 다운로드
2. 설치 경로 지정 (기본값: `C:\Program Files\nvm`)
3. Node.js 설치 경로 지정 (기본값: `C:\Program Files\nodejs`)

### 주요 명령어

```powershell
# 설치 가능한 Node.js 버전 목록 확인
nvm list available

# Node.js 22 설치
nvm install 22

# 설치된 버전 확인
nvm list

# Node.js 22 사용
nvm use 22

# 현재 사용 버전 확인
node -v
```
