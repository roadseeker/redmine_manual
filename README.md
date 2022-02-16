# redmine_manual


## 레드마인 설치
### Docker 설치하기
1. 사용자 등록하기
   
    *  프로젝트 각 사용자는 자신의 로그인 계정을 등록한다

        ![redmine_image-001](https://user-images.githubusercontent.com/5433728/154022850-c73e74e5-4060-4fd7-9705-9db36e320c71.png)

    * 등록시 주의점

        * First name  란에 이름을 Last name 란에 성을 적는 것으로 한다.(이유: 이 경익으로 보기 위함)
        * Login을 본인 메일계정으로 등록한다. - 잊지않기 위해 사용자는 자주 잊는다
        * 패스워드는 프로젝트에 정한 규칙으로 동일하게 등록한다. - 잊지 않기 위해 사용자는 자주 잊는다.

---
2. 사용자 활성화하기

    * **_활성화_** 버튼을 클릭하면 사용자가 로그인 할 수 있다

        ![redmine_image-005](https://user-images.githubusercontent.com/5433728/154023905-521317dc-def3-459e-9b6d-fbdb41f12f8e.png)

    * 계정 활성화 후 **_언어_** 와  **_시간대_** 를 설정해 준다

        ![redmine_image-009](https://user-images.githubusercontent.com/5433728/154029072-617f415f-c0bd-4891-9ff0-91b58c23717d.png)

---
3. 새프로젝트 등록하기

    * 관리자 권한으로 프로젝트를 생성한다. 

        ![redmine_image-003](https://user-images.githubusercontent.com/5433728/154024396-334b590c-3010-45d0-88c3-f71535f0feaf.png)

    * **_새 프로젝트_** 버튼을 클릭하여 신규 프로젝트를 등록한다.

        * 식별자는 영문으로 작성함

        ![redmine_image-004](https://user-images.githubusercontent.com/5433728/154061595-5df41063-ad06-4d36-a13a-78eff7cc8d0b.png)
---
4. 프로젝트에 신규 구성

    * 관리하고자하는 프로젝트를 선택하고(예제: 모바일이커머스신규구축) 설정 메뉴에서 구성원을 프로젝트에 배정한다.  
    * 화면에서 새 구성원을 선택한다.
    * 모바일이커머스신규구축에 관련된 사용자를 프로젝트 구성원으로 등록한다. 

        ![redmine_image-006](https://user-images.githubusercontent.com/5433728/154061602-b6cfac4d-e6e2-48ed-9e01-73b999a913f2.png)
    
    * 사용자를 선택하여 프로젝트의 구성원으로 배정한다. 프로젝트에 등록된 사용자에게 모바일 이커머스신규구축 프로젝트가 보여진다. 
   

        ![redmine_image-007](https://user-images.githubusercontent.com/5433728/154061604-337827e6-6876-43e9-af3f-d7917069af87.png)

    * 모바일이커머스신규구축에 등록된 사용자는 프로젝트에 참여하여 본인에게 배정된 일감을 확인하고 관리할 수 있다 

        ![redmine_image-008](https://user-images.githubusercontent.com/5433728/154061606-cdae5827-7e36-4347-aa93-6624f8a1f678.png)

---
5. 일감유형, 일감상태, 업무흐름 코드 한글화 

    * 영문화 된 코드 값들을 한글화 한다. - 사용자가 읽고 이해하기 편하게 하기 위해

    * 일감유형 한글화
        * 일감유형이 영문으로 표시된 상태이다.
        ![redmine_image-010](https://user-images.githubusercontent.com/5433728/154028395-d43f6898-5f67-4e7b-b791-15b0218831eb.png)
        * 변경하고자 하는 일감유형을 선택하고 일감명칭을 한글로 변경한다.
        ![redmine_image-011](https://user-images.githubusercontent.com/5433728/154028397-0861a3ff-53a7-4898-a973-a7d447791c6d.png)
        * 일감유형 한글화가 완료된 상태이다.
        ![redmine_image-012](https://user-images.githubusercontent.com/5433728/154028398-4fbde627-6a2e-4621-bed9-1fde9d091536.png)


    * 일감상태 한글화
        * 일감유형의 한글화와 동일하다.
        ![redmine_image-014](https://user-images.githubusercontent.com/5433728/154028404-7052706e-26e1-472e-8fe9-5c9f9c4ae83c.png)

    * 역할 및 권한 한글화
        * 일감유형의 한글화와 동일하다.
        ![redmine_image-015](https://user-images.githubusercontent.com/5433728/154028406-2bbd21f8-038e-44c4-8358-3f8fff51c23a.png)

    * 코드값 한글화(문서범주, 일감 우선순위, 작업분류(시간추적))
        * 일감유형의 한글화와 동일하다.
        ![redmine_image-017](https://user-images.githubusercontent.com/5433728/154028409-c746510d-7dd3-4631-be4c-e40d1ea2dc53.png)

---
6. 일감유형 신규 등록 시 편집기능

    * 일감유형을 신규 생성하면 역할에 따른 업무 흐름을 편집 할 수 있다.
    * 일감유형에 따라 진행상태를 변경할 수 있는 권한과 범위를 지정한다. 
    * 아래의 예는 회의의 업무 흐름을 정의한다. 
    * 예를 들어 일감상태가 신규인 경우 관리자는 진행 또는 완료 상태를 해당 일감을 업데이트 할 수 있다. 
    * 진행중일 경우에는 완료만 가능하다.

    * **_편집_** 을 클릭한다. 
        ![redmine_image-020](https://user-images.githubusercontent.com/5433728/154028416-891503f1-bf3c-4e79-9718-c7f370e6738a.png)

    *  각 일감 상태별 혀용되는 일감 상태를 선택한 후 **_저장_** 을 클릭한다. 
        ![redmine_image-022](https://user-images.githubusercontent.com/5433728/154028423-1f7248e2-857a-4ddf-8a66-3847ba652754.png)


    * 일감 상태를 변경할 수 있는 권한을 보여준다.
        ![redmine_image-021](https://user-images.githubusercontent.com/5433728/154028420-48f0ce11-58e7-4f6b-9044-2cb265d07d5a.png)

    * 신규로 **_회의_** 일감유형 등록이 완료된 상태이다.
        ![redmine_image-023](https://user-images.githubusercontent.com/5433728/154028425-3a1d8e08-d011-40e1-b48d-b0bf42c27513.png)

---
7. 일감등록 
    * 일감은 수행해야할 작업목록으로 작업자를 배정하고, 진행상태를 관리하고, 진척율을 관리할 수 있다.

    1. 개별 등록
        * **_새 일감만들기_** 버튼을 클릭하여 신규일감을 등록한다. 
            * 유형: 일감유형에서 정의한 코드값이 보여진다. (default: 새기능 - 일감유형 관리에서 디폴트값을 정의한다.)
            * 제목: 일감의 제목을 등록한다.
            * 설명: **_편집_** 을 클릭하여 해당 일감의 상세 내용을 등록한다.
            * 상태: 최초 등록 시 **_일감상태 관리_** 에서 디폴트 값으로 지정한 **_신규_**  값이이 보여진다.
                * 일감 담당자는 작업의 진척에 따라 일감상태를 변경한다. (신규->진행->완료)
            * 우선순위: 일감의 긴급성을 등록한다. 
            * 담당자: 일감을 수행할 담당자를 지정한다.
            * 상위일감: 해당 일감이 소속된 상위 일감의 번호를 지정한다. 
                * 상위일감을 지정한 경우 하이라키 구조로 간트차트에 보여진다. 
            * 시작시간: 작업시작일을 등록한다. 
            * 완료시간: 작업완료일을 등록한다. 
            * 진척도: 일감 담당자가 작업의 진척을 기록한다. (개발시작-10% / 개발완료-80% / 테스트와료-90% / PL 확인 100% 등으로 프로젝트 내부에서 약속한 값으로 기준을 정하여 관리한다.)
            * 작업시간기록: 일감담당자가 작업시간을 기록한다.

        * 일감등록 화면이다. 
            ![redmine_image-024](https://user-images.githubusercontent.com/5433728/154028428-0bef0591-ba22-42a6-9b66-0b56eea62565.png)  
        * 작업시간 등록 후 일감등록이 완료된 상태의 화면이다.
            * 일감 담당자가 해당 일감에 대한 작업시간을 기록함으로써 추정시간과 실제 작업시간의 차이 분석하여 이후 작업시간 배정에 참고할 수 있다. 
            ![redmine_image-041](https://user-images.githubusercontent.com/5433728/154053981-33be8d86-5b0d-4af1-81cc-b65692a81448.png)
    

    2. 다건 등록 
        * 등록해야 할 일감이 많은 경우 엑셀(cvs) 파일을 이용하여 등록한다. 
        * 다건 업로드용 예제 파일
            [쇼핑엔티_WBS_레드마인_업로드.csv](https://github.com/roadseeker/redmine_manual/files/8068922/redmine_upload_wbs_example.csv)

        * 다건 업로드 cvs 파일 예시 화면이다.

            ![redmine_image-040](https://user-images.githubusercontent.com/5433728/154028475-248ad74e-655a-495f-8224-42ce08b20302.png)

        * 새 일감만들기 옆의  **_..._** 클릭하여 **_가져오기_** 선택한다.

            ![redmine_image-018](https://user-images.githubusercontent.com/5433728/154028411-e01b472c-1600-43f5-a925-3ef08fb689a4.png)

        * **_일감 가져오기_** 화면의 파일 선택버튼을 클릭한다.  

            ![redmine_image-029](https://user-images.githubusercontent.com/5433728/154028443-79ec2bf7-89c0-4720-9cb2-25b3ddb9530a.png)

        * 옵션을 선택한다. 
            * 구분자: 쉼표(,)
            * 묶음기호: 큰따옴표
            * 인코딩: EUC-KR
            * 날자형식: YYYY-MM-DD
            ![redmine_image-030](https://user-images.githubusercontent.com/5433728/154028445-6f2775b2-b1b5-49bb-9b7e-fcae01e5edb3.png)
        * 엑셀(cvs) 파일의 필드와 레드마인의 항록과 연결정보를 설정한다. 대부분 디폴트값으로 선택된다.
        * Relations mapping Unique Id 값으로 사용될 필드와 상위일감 정보가 등록 필드를 선택한다. 
            ![redmine_image-036](https://user-images.githubusercontent.com/5433728/154028460-c0f5cb34-2223-4002-9ffd-af3683b0507b.png) 
        * **_가져오기_** 버튼을 클릭하면 진행상태가 보여진다. 
            ![redmine_image-032](https://user-images.githubusercontent.com/5433728/154028448-7832e318-b27f-4566-a415-a34502a5ec38.png) 
        * 완료된 화면이다. 
            ![redmine_image-037](https://user-images.githubusercontent.com/5433728/154028465-2fc8a9de-0e94-4a2e-a1fd-822e9bcecc10.png)
        * 일감목록을 화면을 확인하면 다건으로 등록된 목록이 보여진다. 
            ![redmine_image-038](https://user-images.githubusercontent.com/5433728/154028470-8bbd716c-02b9-4c82-ae9d-badb39099646.png)
        * 간트 차트로 보여지는 일감 목록이다. 
            ![redmine_image-039](https://user-images.githubusercontent.com/5433728/154028473-a413426e-b39a-4c49-a795-d3039c0199d9.png)