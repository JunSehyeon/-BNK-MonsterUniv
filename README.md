<p align="center">
  <img src="./images/github_readme_logo.jpg" alt="Monster University hero" width="200" />
</p>

# Monster University Website

### 메인
![메인 스크린샷](https://github.com/user-attachments/assets/ed7a1dcd-aa04-4880-b52c-c55ed160d378)

### 로그인
![로그인](https://github.com/user-attachments/assets/4cbdd60f-77e8-417e-8213-06b9f1cba353)

## 통합정보시스템
![통합정보시스템](https://github.com/user-attachments/assets/9370ae3f-f78b-4846-8a84-8c6f4d7e0afb)

## 게시판
![게시판](https://github.com/user-attachments/assets/92a387f3-e4bf-4fd5-8722-2d0b4b461508)


### ▶ 시연 영상
- [YouTube 보러가기](https://youtu.be/UTVsuxLt-o4) | [Notion 버전](https://www.notion.so/MonsterUniv-JSP-Servlet-26cba5b0d4908016a2badf706197922b#26cba5b0d49080819ca1e01c27f63992)


> **HTML/CSS/JS + JSP/Servlet**로 구현한 “몬스터 대학교” 공식 웹사이트.  
> 입학·학사·학과 소개부터 공지/커뮤니티까지, 실제 대학 포털처럼 **빠르고 직관적인 UX**로 구성했습니다.

## 🚀 기술 스택

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Java, JSP, Servlet  
- **Database**: MySQL, Oracle  
- **Deployment**: Tomcat (On-Prem / VM), AWS EC2+RDS, 또는 컨테이너(K8s)  
- **Design**: Figma

---

## 아키텍처/ERD
![Architecture](https://github.com/user-attachments/assets/894004c3-7aaf-4f08-99f5-38f09a96a8b1)

## ✨ 주요 기능

- 📚 **학과/교과과정 페이지**: 전공별 커리큘럼·강의계획서 열람  
- 🗞 **공지·소식**: 학사공지/행사/채용 등 카테고리별 피드  
- 🧑‍🎓 **학생 서비스**: 로그인/회원가입, 마이페이지, 게시판/댓글  
- 🔎 **전역 검색**: 학과·과목·게시글 키워드 검색  

---

## 실행 방법 
1. 저장소를 클론합니다.
2. IDE(Eclipse/IntelliJ 등)에서 프로젝트를 Import 합니다.
3. DB(MySQL) 연결 후 실행합니다.

## 맡은 업무

1. 팀원 (피그마 협업 총괄 · 기획 · 문서 작업 · 기능 구현 담당)
프로젝트의 전체 흐름과 구조를 파악하고, 팀 내부 협업 방식 정립
초기 아이디어 정리부터 화면 구성, 주요 기능 정의까지 기획 단계에 적극적으로 참여
개발뿐만 아니라 문서 정리·Git 룰·협업 환경 구축 등 실무형 역할 수행

2. 피그마(Figma & FigJam) 기반 협업 총괄
FigJam을 활용하여 프로젝트 아이디어 수집, 플로우 차트, 유저 스토리 작성 등 협업 구조를 주도적으로 설계
팀원 모두가 동일한 방향으로 개발할 수 있도록 화면 흐름도, 페이지 연결 구조, 우선순위 정리 등을 문서화
피그마 보드 구성, 컴포넌트 배치, 화면 연결 구조 관리 등 협업 도구 운영 담당
디자인을 직접 맡기보다는 피그마 협업 전반 조율과 구조 정리에 집중
팀원 간 실시간 코멘트 관리, 태스크 정리, 업무 흐름 시각화 등 프로젝트 생산성 유지 역할 수행

3. 문서 작업 및 프로젝트 관리 문서 총괄
회의 내용 정리, 기능 요구사항 문서화, 개발 진행 상황 리포트 등 프로젝트 문서 대부분 직접 작성
기획 문서, 일정표, 화면 정의서 등 개발에 필요한 핵심 자료를 체계적으로 정리하여 팀원 공유
기능 우선순위, 작업 분배 내용, 개발 흐름을 문서화하여 전체 팀이 일관된 방향으로 개발하도록 지원
발표 자료 PPT 구성, 화면 캡처, 설명 구조 정리 등 문서 기반 결과물 제작 주도

4. Git 협업 규칙 수립 및 운영
main 브랜치 보호 전략, 팀원별 개인 브랜치 전략 등 Git 사용 원칙 직접 제안 및 정착
커밋 메시지 규칙, PR 방식, merge 순서 등 협업 프로세스 문서화
팀원들이 Git 사용에 어려움을 겪지 않도록 규칙 가이드 제공 및 문제 해결

5. 메인 페이지 및 회원 기능 일부 구현
메인 페이지 화면 구현 담당
로그인 / 회원가입 화면 및 기능 구현 담당
UI–Controller 연결 고려한 페이지 설계

6. 발표 및 시연 담당
최종 발표를 직접 준비하고 발표자로 참여
기획 의도, 시스템 구조, 개발 과정, 협업 방식 등 전체 프로젝트 내용을 설명
시연 흐름 구성, 자료 정리, 스토리라인 제작

## 개선 예정

- 비밀번호 해시(BCrypt), 예외 로깅 고도화
- 본 프로젝트는 JSP/Servlet 기반 MVC 아키텍처로 시작하여, 웹 개발의 기본 동작 원리를 직접 구현했습니다. 이후 Spring MVC로 리팩토링을 진행하여 유지보수성과 확장성을 강화할 예정입니다.
