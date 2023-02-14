# UiPath 개발표준 정의서

## 목차

1.	자동화 품질점검 기준
	1.	모듈화
	1.	유지보수성
	1.	가독성
	1.	유연성
	1.	안정성
	1.	확장성
1.	라이브러리 관리
	1.	라이브러리 등록
	1.	라이브러리 다운로드
	1.	주요 라이브러리 권장 버전
1.	계정관리
	1.	Orchestrator의 Credential에 저장 방법
	1.	Windows Credential 적용 방법
	1.	Robot 계정 관리
1.	WORKFLOW DESIGN
	1.	Layout
	1.	Data
	1.	프로젝트 관련 파일관리
	1.	Context Settings
	1.	Error Handling
	1.	Keep it clean
	1.	Code 재사용
1.	NAMING RULE
	1.	Process Naming Rule
	1.	Workflow Naming Rule
	1.	변수 Naming Rule
	1.	인수 Naming Rule
	1.	Asset/Credential Naming Rule
1.	주석
	1.	Workflow 주석
	1.	Activity 주석
1.	로그
	1.	로그 출력 규칙
	1.	기입 필수/권장 로그
1.	UIPATH AUTOMATION
	1.	Desktop Automation
	1.	Image automation
	1.	UI Synchronization
1.	개발소스 관리
	1.	공용 모듈 관리(라이브러리/공용프로세스)
	1.	Snippets 이용
	1.	Orcehstrator 게시
	1.	REFrameWork Template 등록
1.	프로젝트 환경 표준 관리
	1.	UiPath Studio/Robot 환경 표준
	1.	스크립트 작성시 유의사항
	1.	프로젝트 관련 파일 관리
	1.	담당자 결과 알림 방안
1.	FRAMEWORK 적용
	1.	RE-Framework 소개
	1.	RE-Framework 시작하기
	1.	Custom Workflow 기본 형식
1.	개발 후 진행 업무
	1.	UAT(User Acceptance Testing)
	1.	QA(Quality Assurance)
	1.	인수인계(운영)
	1.	그 외


##1.	자동화 품질점검 기준
	1.	모듈화
	-프로세스를 여러 개의 독립적인 Workflow로 분리함으로써 단위 개발 및 테스트가 가능하도록 구성
	-재사용 가능한 컴포넌트 및 Workflow를 추출하여 여러 프로젝트에 범용적으로 사용 가능.

	1.	유지보수성
	-프로젝트 구조 및 개발 표준 준수

	1.	가독성
	-표준화된 프로세스 구조를 사용하여 명확한 개발 절차 수립
	-Workflow 파일, 액티비티, 인수 및 변수에 의미 있는 이름 부여

	1.	유연성
	-외부 설정 파일 또는 Orchestrator에 환경변수를 저장하여 테스트 및 운영 환경에서의 자동화 수행이 용이하도록 구성

	1.	안정성
	-예외 처리 및 에러 보고를 적절히 사용
	-실시간 실행 시 진행현황 조회 가능하도록 구성

	1.	확장성
	-프로세스에 신규 케이스 추가 가능한 구조로 구성
