# MPM 요건정리 및 기능리스트

## 개요

평소 프로젝트를 열때 터미널에서 해당 프로젝트의 디렉토리를 찾고 여는데 불편함을 느꼈다.
따라서 프로젝트를 편하게 관리하고 단하나의 커맨드로 프로젝트를 오픈할수 있고 저장된 커맨드를 실행할수 있도록 하는 도구를 개발한다

## 기능요건

가장 필요로하는 기능은 커맨드 한번으로 그 프로젝트의 해당하는 서브 프로젝트를 여는것이다.  
예를들어 한 web프로젝트 안에 `api/` `front/` 와같이 나누어 관리되는 경우가 있는데, 이때 커맨드 한번으로 api, front를 vscode나 다른 에디터로 여는기능이다

### 프로젝트 관리

> 기능

- 프로젝트 등록
- 프로젝트 삭제
- 프로젝트 편집
- 프로젝트 리스트 보기

### 커맨드 관리

> 기능

- 커맨드 등록
- 커맨드 삭제