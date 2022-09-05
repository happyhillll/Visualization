# [태블로 **<Gelato map in Rome🍦>**]([https://public.tableau.com/views/_16594472938490/1?:language=ko-KR&:display_count=n&:origin=viz_share_link)
## 결과물 
<img width="820" alt="image" src="https://user-images.githubusercontent.com/88447983/188470181-15ad6413-58d9-40a8-87ec-31407f4644ce.png">)
## 크롤링
- 셀레니움, 크롬 웹 드라이버로 구글맵 크롤링 시도 -> 실패 (가게별로 csv가 저장되는 형태는 가능하나, dataframe으로 만들어야함.)
- Instant Data Scraper : 크롬 확장툴 (구글맵 가게 이름, 주소, rating, 웹사이트, 리뷰 개수 등 크롤링 가능)
- xlsx 형태로 저장
## 전처리
- 신뢰도 있는 지도를 만들기 위해 리뷰 수가 1000개 이상인 가게만 수집 : tableau 내부 툴을 이용하여 조건 추가
- latitude 와 longitude가 null인 가게를 제외
## mapping
- longitude와 latitude를 차례대로 클릭하고, name을 세부정보에 두면 mapping 완료
- rating 색상, 크기, 레이블에 두기
- 맵은 상단 툴에서 '거리'로 
## rank
- rank 코드를 입력하고 sum을 해주어야 하며, 불연속성으로 꼭 바꿔주어야함
- 그 외로는 실수로 바꾸기 등등
## dashboard
- 가로로 설정한 뒤
- 각 자리에 시트 배치하고
- 이미지는 url 넣어주기

