# Braker : oneM2M 기반 급발진 사고 예방 및 운전 자세 교정 시스템 (작성중)

## 프로젝트 소개 

고령 운전자 증가 및 급발진 주장 사고가 사회적 이슈가 됨에 따라, 올바른 페달 밟기 자세와 무릎 위치를 실시간으로 모니터링하여 사고를 미연에 방지하고자 함.

## 핵심 기능
- 무릎 거리 센서를 통한 하체 위치 교정 피드백.
- 압력 센서를 통한 페달 오인 방지 및 뒤꿈치 위치 확인.
- oneM2M 표준 플랫폼을 활용한 센서 데이터의 안정적인 저장 및 웹 모니터링 연동.

## 기술 스택 
- Hardware: Arduino Uno R4 Wi-Fi (내장 Wi-Fi 모듈 활용)
- Sensors: 초음파 센서(무릎 거리 측정), 압력 센서(뒤꿈치 위치 확인)
- Platform: oneM2M (Mobius/Ocean) - 국제 표준 사물인터넷 플랫폼 활용
- Frontend: Vue.js
- Communication: HTTP/REST API (R4 Wi-Fi <-> oneM2M Server)



## 테스트 진행 

상황 1 : 올바른 자세 유지 시
![Uploading image.png…]()

