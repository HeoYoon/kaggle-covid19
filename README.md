# kaggle-covid19
https://www.kaggle.com/kimjihoo/coronavirusdataset

### 1. patient 데이터셋 정보
* id: 확진자의 id (n번째 확진자)
* sex: 성별
* birth_year: 출생 연도
* country: 국적
* Korea: 대한민국
* China: 중국
* Mongolia: 몽골
* region: 주 활동 지역 (광역시/도 단위)
* capital area: 수도권 (서울특별시/인천광역시/경기도)
* filtered at airport: 공항 검역 이후 활동하지 않은 경우
* Busan: 부산광역시
* Daegu: 대구광역시
* Daejeon: 대전광역시
* Gwangju: 광주광역시
* Ulsan: 울산광역시
* Gangwon-do: 강원도
* Chungcheongbuk-do: 충청북도
* Chungcheongnam-do: 충청남도
* Jeollabuk-do: 전라북도
* Jeollanam-do: 전라남도
* Gyeongsangbuk-do: 경상북도
* Gyeongsangnam-do: 경상남도
* Jeju-do: 제주도
* group: 특정 집단 관련
* Shincheonji Church: 신천지 관련
* Cheongdo Daenam Hospital: 청도대남병원 관련
* Eunpyeong St. Mary's Hospital: 은평성모병원 관련
* Onchun Church: 온천 교회 관련
* Myungsung Church: 명성 교회 관련
* Pilgrimage: 이스라엘 성지순례 관련
* infection_reason: 감염 경로
* visit to ooo: 감염 위험 나라/도시 방문
* contact with patient: 국내 확진자와 접촉
* contact with patient in ooo: 해외 확진자와 접촉
* residence in Wuhan: 중국 우한 거주
* pilgrimage to Israel: 이스라엘 성지순례
* infection_order: 감염 차수 (n차 감염)
* infected_by: 해당 확진자의 감염원 id
* contact_number: 접촉자 수
* confirmed_date: 확진 일자
* released_date: 퇴원 일자 (격리 해제 일자)
* deceased_date: 사망 일자
* state: 상태
* isolated: 입원 (격리)
* released: 퇴원 (격리 해제)
* deceased: 사망

### 2. route 데이터셋 정보
* id: 확진자의 id (n번째 확진자)
* date: 일자
* province: 특별시/광역시/도
* city: 시/군/구
* visit: 방문한 장소 (종류)
* airport: 공항
* hospital_isolated: 격리된 병원
* hospital: 대형급 병원 또는 보건소
* clinic: 의원급 병원
* hotel: 호텔
* store: 소형 가게
* market: 대형 마트
* restaurant: 식당
* cafe: 카페
* house: 집
* bus_terminal: 버스 터미널
* train_station: 기차역
* movie_theater: 영화관
* hair_salon: 미용실
* church: 교회
* etc: 기타 방문 장소
* latitude: 위도
* longitude: 경도

### 3. time 데이터셋 정보
* date: 일자
* acc_test: 누적 검사 수 (진행 중인 검사 포함)
* acc_negative: 누적 음성 결과 수
* acc_confirmed: 누적 양성 결과 수 (확진)
* acc_released: 누적 격리 해제 수
* acc_deceased: 누적 사망 수
* new_test: 신규 검사 수
* new_negative: 신규 음성 결과 수
* new_confirmed: 신규 양성 결과 수 (확진)
* new_released: 신규 격리 해제 수
* new_deceased: 사망 수
- 정보 출처 
https://www.kaggle.com/kimjihoo/coronavirusdataset/discussion/132753
