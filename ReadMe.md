# Azure 실습 - SKcc 4조


## 1. Azure IaaS 환경 구축

- VM 생성
  - 한국 중부 / 한국 남부 
  - 이미징
- VNET 생성 및 인터넷 접속여부
- VMSS 오토스케일링 설정 및 정상 동작 여부

## 2. CDN 환경 구축
 - Blob 생성
 - CDN 생성, 설정 및 캐싱 기능 정상 동작 유무
   -  각 index.html에서 다른 이미지 출력

## 3. 부하 분산 서비스를 구축 및 트래픽 분산 확인
- LB 생성
  - 각 VMSS 별 LB 생성
- LB 통한 부하 분산 정상 동작 유무
- Traffic Manager 생성
  - 가중치 활용
- Traffic Manager 통한 지역별 다른 웹서비스 제공

## 4. 보안 설정 
- 각종 Network Security Group Port 오픈
  - 인바운드 규칙 설정 (http 개방, ssh 제약)

## 5. 최종 결과물
- 웹서비스 컨텐츠 GitHub 게시
  
  ### [한국 중부 - 웹페이지](./korea_mid_index/index.html)
  ### [한국 남부 - 웹페이지](./korea_south_index/index.html)
  
  ### **웹사이트 결과물** [http://team04-tm.trafficmanager.net/](http://team04-tm.trafficmanager.net/)
