# 공기질 측정 화재경보기
## mqtt 통신을 이용한 공기질 측정 화재경보기 애플리케이션 개발

> 목적 : 
> > - 공기질을 측정하여 LCD로 화면에 출력해주고 스마트폰에서도 손쉽게 확인 가능하다.
> > - 언제 어디서 일어날지 모르는 화재에 대비하여 위급상황 시 빠르게 대처할 수 있다.

> 개요 :
> > - 사용한 부품 : 가스센서, 공기질 측정 센서, 능동 부저, LCD
> > - 가스 센서(MQ2)를 통해 공기 중 유독 가스의 비율을 측정하고 분석
> > - 공기질 측정 센서(MQ135)를 통해 대기관련정보를 측정하고 LCD 센서에 정보 출력
> > - 앱을 통한 실시간 공기질 측정 가능
> > - 측정된 가스센서 값을 통해 위급 상황 시 부저를 울리고 119를 호출

> 서비스 설계 간략도
> > ![image](https://user-images.githubusercontent.com/60462925/103545699-452d3500-4ee5-11eb-887b-f813dff97dec.png)

> 작품 사진
> > 정면부
> > > <img src="https://user-images.githubusercontent.com/60462925/103639895-7152bf80-4f92-11eb-80d3-81cb8e457e07.png" width="300" height="300">

> > 내부 구조
> > > <img src="https://user-images.githubusercontent.com/60462925/103640059-b24ad400-4f92-11eb-8e0e-9c86a5b968ca.png" width="300" height="300">
> > > <img src="https://user-images.githubusercontent.com/60462925/103640073-b70f8800-4f92-11eb-99ea-6101e49cbb3a.png" width="300" height="300">

> 애플리케이션 실행 화면
> > 미세먼지 측정
> > > <img src="https://user-images.githubusercontent.com/60462925/103640168-e0301880-4f92-11eb-969b-505ce731bb07.png" width="300" height="300">

> > 유해가스 측정
> > > <img src="https://user-images.githubusercontent.com/60462925/103640183-e4f4cc80-4f92-11eb-8bc9-a92735eedef0.png" width="300" height="300">
> > > <img src="https://user-images.githubusercontent.com/60462925/103640189-e7572680-4f92-11eb-81fb-cb755219b1e7.png" width="300" height="300">
