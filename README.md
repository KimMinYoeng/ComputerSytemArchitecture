#**2조** markdown, git 협업 실습
---
| Name          | Student Number         | User Name   |
| ------------- |:----------------------:|------------:|
| 김민영         | 2012136024             |KimMinYoeng  |
| 김승태         | 2012136028             |seungtaeKim  |
| 김지구         | 2012136037             |zmfhtodna    |
| 정병훈         | 2012136115             |JungByungHoon|


## **범죄예방!** 스마트 반지와 드론

1. 필요성

  1.1 사회적 약자를 대상으로 한 범죄 증가
  - 최근 성폭행 버스납치 사건처럼 사회적 약자를 대상으로 한 범죄증가
[관련기사1](http://www.kyeongin.com/main/view.php?key=20160905010001127)
[관련기사2](http://www.hani.co.kr/arti/society/society_general/745689.html)

  1.2 범죄 예방 시스템 및 위치추적 능력 부족
   - 이미 범죄가 일어나 신고를 했음에도 불구하고 피해자의 위치를 빠르고 정  확하게 찾아서 대처하지 못함
   - 신고자의 위치를 파악하는 시스템은 약 30%로 낮은 정확도를 보임
[관련기사][link]
[link]: http://www.hani.co.kr/arti/society/society_general/745689.html

  1.3 범죄 발생 후 대처 시스템 부족
   - 범죄를 예방하는 것은 고사하고 이미 발생한 범죄에 대해 신고가 들어온 사건에 대해서도 제대로 대처하지 못함
   - 신고가 들어온 장소를 신속 정확하게 찾지 못하거나, 인근 기동순찰대에 연락을 취해 다발적으로 대응하지 못하기 때문
   -  1.2에 근본적인 원인이 있음

2. 프로젝트 목적
 - 현재 사획적 약자에 대한 범죄 증가 문제와 이에 대한 대처 시스템과 이를 예방하기 위한 시스템 또한 문제가 많은 상황이다. 그에 대한 문제점을 분석한 결과 범죄율 증가를 예방하기 위한 근본적인 문제는 현 시스템에 문제가 있다는 점이었는데, 가장 많이 사용되고 있는 위치 추적 시스템의 정확도와 회신률이 상당히 낮다는 점이었다.
 - 이 프로젝트를 통해서 보다 정확한 위치 파악과 신속한 정보 전달을 통해서 범죄 예방율을 높이는 것이 주 목적이 되겠다.

3. 프로젝트 예상 산출물
    
    3.1. 구조
    
	![alt text](https://github.com/KimMinYoeng/ComputerSystemArchitecture/blob/master/system%20architecture.JPG?raw=true "Logo Title Text 1")
	
	 3.2. 기능
	- 감시 드론의 촬영 기능을 이용한 정확한 위치 파악 및 데이터 전송
	- 반지에 부착된 버튼을 이용하여 위급한 상황에서 신속한 반응

	
	3.3. 시나리오_초범과 마주 쳤을 때의 상황
	- 길을 가던 사용자가 초범과 마추쳐서 위기감을 느끼고 착용하고 있는 반지의 버튼을 누른다
	- 근처에 있는 경비 드론이 반지에서 보내는 신호를 인식한다.
	- 경비드론이 신호가 발생한 위치로 이동하여 현장의 영상을 실시간으로 경찰측으로 전송한다.
	- 부가적으로, 사용자는 재범이 정해진 거리 내에 있을 경우 스마트 반지로 위험 신호(진동)를 받을 수 있다. - 전자발찌와 연동

4. 기존 관련 사례
    
    4.1. 님브반지(*NIMB RING*)
    
     ![alt text](https://github.com/KimMinYoeng/ComputerSystemArchitecture/blob/master/NIMBRING.PNG?raw=true)
     > **team NIMB**
     we are making Nimb to be a cool-looking smart device that would compliment the users' style and help them stay safe and protected on the go.
     
    -  웨어러블 스마트 기기인 범죄예방 방지 스마트 반지로 위급시 반지 하단부의 버튼을 3초간 누르면 사용자가 지정해둔 가족이나 지인, 그리고 경찰서와 보안업체에까지 사용자의 SOS메시지가 자동으로 전송된다. 
   -  만약 실수로 버튼을 3초간 눌렀을 경우 사용자 스마트폰으로도 동시에 20초간 취소할 수 있는 알림이 뜬다.                                  

  
    
    
	4.2 드론(Drone)
	
	![alt text][logo]

[logo]:https://github.com/KimMinYoeng/ComputerSystemArchitecture/blob/master/Drone.png?raw=true "Logo Title Text 2"               

- 하늘을 나는 드론은 이미 한국에서도 경찰과 소방에서 감시용, 발화점을 찾는 용도로 운용

- 일본에서 처음 시행한 경찰 드론은 불법 비행용 드론을 잡는데 운용

* **제품 차이점 :  드론이 사용자의 위치 데이터를 입력 받아 정확한 위치와 영상을 인근 경찰에 제공**