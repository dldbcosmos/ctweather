# ctweather
get information of weather with 3days
## 목적
OpenWeatherMap API를 활용하여 3일간의 날씨 정보를 조회하는 파이썬 클라이언트 소스코드입니다. 

날씨를 알고 싶은 도시와 시간(오늘, 내일, 모레)를 물어보면 해당 도시의 기온, 습도등의 정보를 얻을 수 있습니다.

### 사용 하기

1. 아래의 웹사이트에서 OpenWeather의 API KEY를 얻습니다.('owm_apikey.txt'에 api key를 입력합니다) 

    - <https://home.openweathermap.org/>
      
2. 필요 파이썬 패키지를 설치합니다.

    - 'python -m pip install -r requirements.txt'
        
3. 사용 예시
    - package 설치
      
      python -m pip install ctweather
      
      ![pip_img](https://github.com/user-attachments/assets/665a6585-043b-42ec-bdeb-9188e45d6951)

    - spacy 한글 
  
      python -m spacy download ko_core_news_sm
      
    - test
      
       from ctwther import wea
      
       wea.test('오늘 뉴욕 날씨는 어때')
      
      ![test_img](https://github.com/user-attachments/assets/407f0a48-49ea-43be-9214-addc4d00a8f4)
      
### requirements
    spacy==3.8.2
    ko_core_news_sm==3.8.0
    googletrans==4.0.0rc1

