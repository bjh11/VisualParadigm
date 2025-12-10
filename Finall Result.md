<Online Education Platform 최종 결과 보고서>

1. 프로젝트 개요
1.1 프로젝트명
Online Education – 온라인 강의 플랫폼 시스템
1.2 프로젝트 목적
본 프로젝트는 학생·강사·관리자가 온라인에서 강의를 제공하고 학습 활동을 수행할 수 있는 통합 교육 플랫폼을 구축하는 데 목적이 있다.
시간과 장소에 구애받지 않고 학습자가 자유롭게 강의를 검색·수강하고, 강사는 교육 콘텐츠를 제공하며, 관리자는 전체 시스템 환경을 운영·관리할 수 있도록 한다.
1.3 시스템 주요 목표
- 학습자가 원하는 강의를 쉽게 탐색하고 수강할 수 있는 환경 제공
- 강사가 강의 콘텐츠를 효율적으로 업로드·관리할 수 있도록 지원
- 관리자 중심의 안정적인 시스템 운영 및 계정 관리 기능 제공
- 직관적인 UI를 통한 사용자 중심의 교육 플랫폼 제공

2. 시스템 요구사항 정의
2.1 액터 정의
- Student(학생): 강의를 검색·수강하며, 과제 제출 및 학습 활동을 수행하는 최종 사용자
- Instructor(강사): 강의 콘텐츠를 생성·업로드하고 수강생 진도를 관리하여 평가하는 사용자
- Administrator(관리자): 플랫폼 전체 운영을 담당하며 사용자 계정 및 시스템 설정을 관리하는 운영자

3. 유스케이스 정의서
3.1 주요 유스케이스 목록
- 강의 검색 (학생): 키워드, 카테고리, 강사명 등 조건으로 강의를 탐색
- 강의 수강 등록 (학생): 원하는 강의를 자신의 수강 목록에 추가
- 강의 시청/수강 (학생): 등록한 강의를 재생·학습
- 강의/콘텐츠 업로드 (강사): 강의 영상·자료 업로드 및 관리
- 진도/과제 채점	 (강사): 학생의 학습 결과물을 평가하고 피드백 제공
- 사용자 계정 관리 (관리자): 학생·강사 계정 생성, 수정, 비활성화, 삭제
- 시스템 설정 구성 (관리자): 카테고리, 정책, 서버 설정 등 시스템 환경 구성

4. UML 다이어그램
   
4.1 Use Case Diagram
   
<img width="1238" height="997" alt="Image" src="https://github.com/user-attachments/assets/cb62c513-5c41-4525-8f4a-a2f457baa6a6" />


4.2 Sequence Diagram

<img width="820" height="491" alt="Image" src="https://github.com/user-attachments/assets/e3a645b7-9cbe-40a1-8191-357a86b9d440" />


4.3 Class Diagram

<img width="690" height="1185" alt="Image" src="https://github.com/user-attachments/assets/dc7160ae-b999-42ab-b24e-18d68c24d77a" />


4.4 ER(Entity-Relationship) Diagram

<img width="966" height="340" alt="Image" src="https://github.com/user-attachments/assets/cd7df565-a10b-44a4-9798-dacf792580e1" />


5. UI 화면 설계
5.1 Student, Instructor, Admin Dashboard

6. 시스템 구조 및 기능 설명
6.1 학생(Student) 기능
- 강의 검색 및 필터링
- 강의 수강 등록
- 강의 콘텐츠(영상·자료) 시청
- 과제 제출
- 강사와의 질의·소통
- 본인 진도율 확인 및 학습 관리
6.2 강사(Instructor) 기능
- 강의 콘텐츠 업로드(영상, pdf, 실습 파일 등)
- 강의 정보 수정·관리
- 수강생 진도 모니터링
- 과제 및 평가 점수 입력
- 학습자 질문 응답
6.3 관리자(Admin) 기능
- 사용자 계정 생성·수정·삭제
- 강의 카테고리 관리
- 시스템 환경 설정
- 로그/모니터링
- 전체 플랫폼 유지·관리

7. 데이터베이스 구조
본 플랫폼은 Student, Instructor, Admin, Course, Enrollment, Lesson 테이블을 중심으로 구성되며 학생–수강–강의 간 다대다 관계를 관리하기 위해 Enrollment 엔티티를 사용하였다.

<img width="966" height="340" alt="Image" src="https://github.com/user-attachments/assets/cd7df565-a10b-44a4-9798-dacf792580e1" />


9. 결론
본 프로젝트를 통해 온라인 교육 플랫폼의 핵심 기능(강의 검색, 콘텐츠 제공, 진도 관리, 사용자 관리 등)을 체계적으로 분석하고 UML 기반의 구조 설계를 수행하였다.
Use Case, Sequence, Class, ERD, UI 설계까지 포함한 본 결과물은 실제 플랫폼 구현 과정에서 명확한 기준이 되는 시스템 정의 문서 역할을 하며, 확장성과 유지보수성을 고려한 구조로 설계되었다.
본 프로젝트를 통해 온라인 교육 플랫폼의 핵심 기능(강의 검색, 콘텐츠 제공, 진도 관리, 사용자 관리 등)을 체계적으로 분석하고 UML 기반의 구조 설계를 수행하였다.
Use Case, Sequence, Class, ERD, UI 설계까지 포함한 본 결과물은 실제 플랫폼 구현 과정에서 명확한 기준이 되는 시스템 정의 문서 역할을 하며, 확장성과 유지보수성을 고려한 구조로 설계되었다.
