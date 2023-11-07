
<div style="text-align:center">
<img width="400" alt="image" src="https://github.com/BITSdrive/.github/assets/126750984/5f88c11f-aed7-481b-bdb3-d5879e56dfae">
</div>
<br/>


# BITS

> Beyond Identification: Traveling Securely<br/>
> 2023.08 ~ 2023.11 <br/>
> 금오공과대학교 메디컬it융합공학과 학생으로 이뤄진 프로젝트 팀입니다.

<br/>

## Abstract
> 카 쉐어링 서비스에서 무면허 운전자(ex.면허증 도용)를 식별하기 위해 1차 검증(면허증 사진과
> 현재 얼굴 사진 업로드) 와 2차 검증(운전자석에서 시간간격으로 실시간 얼굴 식별) 하는 시스템
> 
<br/>
<br/>
<br/>

## 👩 팀 구성원

| 이름 | 소속 (`23기준) | github | 역할 |
| --- | --- | --- | -- |
| 김한결 | 금오공과대학교 메디컬it융합공학과 |[@Kyeol1125](https://github.com/Kyeol1125)|DeepLearing Model Training, BackEnd Server|
| 김재광 | 금오공과대학교 메디컬it융합공학과 | [@jieykim](https://github.com/jieykim) |DeepLearing Model Inference |
| 김민경 | 금오공과대학교 메디컬it융합공학과 | [@mmiini](https://github.com/mmiini) | FrontEnd App, BackEnd Server|
| 박소윤 | 금오공과대학교 메디컬it융합공학과 | [@sy0106](https://github.com/sy0106) | FrontEnd App, BackEnd Server |


<br/>
<br/>
<br/>

## 🚀 Stacks

### Infra

<p>
  <img height=27em src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white"/></a>&nbsp
  <img height=27em src="https://img.shields.io/badge/Firebase Cloud Messaging-FFCA28?style=flat&logo=Firebase&logoColor=white"/></a>&nbsp
  <img height=27em src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white"/></a>&nbsp
</p>

### Database(DB)

<p>
  <img height=27em src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=PostgreSQL&logoColor=white"/></a>&nbsp
</p>

### Frameworks

<p>
  <img height=27em src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=Flutter&logoColor=white"/></a>&nbsp
</p>

### AI/DL

<p>
  <img height=27em src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white"/></a>&nbsp
  


<br/>
<br/>
<br/>

## System Structure


<br/>
<br/>

## ⚙ Repository
<br/>


- **AI-Model &nbsp; : &nbsp; ArcFace**
  
<br/>
<br/>
<br/>
<br/>

- **Back-End Server &nbsp; : &nbsp; AWS Severless**

    
    
    > <b>AWS Serverless<b> 를 사용하면 인프라 관리, 확장성, 고가용성 및 보안과 같은 고려 사항을 줄이고 애플리케이션을 빠르게 개발하고 배포할 수 있습니다. 또한 사용량에 따라 비용을 최적화할 수 있으며, 트래픽이 증가해도 자동으로 처리할 수 있어서 스케일링에 대한 걱정을 덜어줍니다. 
    
    
    
    - 핵심 기술
        - <b>AWS Lambda<b>: Lambda함수는 서버리스 컴퓨팅 플랫폼으로, 코드 실행에 필요한 컴퓨팅 자원을 자동으로 할당하고 트리거 이벤트 (예: HTTP 요청, 파일 업로드, 메시지 큐)에 응답하여 코드 실행을 트리거합니다.
        - <b>Amazon API Gateway<b>: API Gateway는 HTTP 요청을 받아들이고 Lambda 함수와 연동하여 RESTful API를 빌드하고 관리하는 데 사용됩니다.
        - <b>Amazon S3<b>: Amazon S3는 객체 스토리지 서비스로, 파일 저장 및 정적 웹 호스팅에 사용됩니다. 서버리스 웹 애플리케이션의 정적 리소스를 호스팅하기에 적합합니다.
        - <b>EC2<b> : AWS에서 제공하는 가상 서버 호스팅 서비스입니다. 이 서비스를 통해 사용자는 가상 머신 (인스턴스)을 프로비저닝하고 실행할 수 있습니다.
        - <b>IAM<b> : AWS 계정 내에서 사용자 및 리소스에 대한 액세스를 관리하고 제어하는 서비스입니다.


<br/>
<br/>
<br/>
<br/>


- **Front-End App &nbsp; : &nbsp; DRIVEAUTH**
    
    <div style="text-align:center">
    <img src="https://github.com/BITSdrive/.github/assets/126750984/4b4a4e74-fde4-4f6c-943d-ebaab250093d" alt="VideoSearcher" width = "300" height="300" />
    </div>
    
    <br/>

    > <b>DRIVEAUTH</b> 는 얼굴 식별의 <b>1차 인증<b>을 위한 면허증과 현재 사진 업로드, 그리고
    2차 인증의 모델 추론 결과를 어플 사용자에게 반환하기 위한 Front-End <b>Android Application</b>입니다.


    
    - 핵심 기술
        - **1차 인증**을 위한 면허증과 현재 사진 업로드
        - *FireBase*를 이용한 모델 추론 결과 받은 후 알람

## DRIVEAUTH App

| 1| 2| 3 | 4 |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/BITSdrive/.github/assets/126750984/e8c1f5f1-52ef-4342-a6b0-a6d8c1f8ac5c" alt="app_page1" width = "500"/> | <img src="https://github.com/BITSdrive/.github/assets/126750984/938d9b1e-84ed-4660-b8da-78f7121ebc17" alt="app_page2" width = "500"/>  | <img src="https://github.com/BITSdrive/.github/assets/126750984/f15b0a21-7f01-4bf7-b47b-7bd16d2c67d9" alt="app_page3" width = "500"/>  | <img src="https://github.com/BITSdrive/.github/assets/126750984/87bfc77d-113e-47e8-8064-05a35db10335" alt="app_page4" width = "500"/>  |


| 5 | 6| 7 | 8 |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/BITSdrive/.github/assets/126750984/da090b52-d40a-4226-8ecb-fbff2f7212eb" alt="app_page5" width = "500"/> | <img src="https://github.com/BITSdrive/.github/assets/126750984/483b8a00-7ce2-41ea-8eaa-5a20ebeb223e" alt="app_page6" width = "500"/>  | <img src="https://github.com/BITSdrive/.github/assets/126750984/b18e5f4d-0160-431e-98c7-82ea3f298944" alt="app_page7" width = "500"/>  | <img src="https://github.com/BITSdrive/.github/assets/126750984/6b284b05-236e-4880-a54e-95eff7c91110" alt="app_page8" width = "500"/>  |

<br/>
<br/>
<br/>

