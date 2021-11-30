# Toy-Project
- toy-crolling [2021-12-16]
  : jsoup 을 이용한 웹페이지 크롤링 Maven Project 해당 크롤링 한 데이터는 엘라스틱 서치에 적재  
- toy-kafka-producer[2021-12-31]
  : kafka producer 엘라스틱 서치의 데이터를 이용하여 해당 데이터를 json 형식으로 변환후 카프카 topic (Lotto-Statistics)(로또 통계)로 SENDING
- toy-kafka-consumer[2021-01-16]
  : 해당 로또 데이터를 polling 하여 해당 데이터를 이용 RDBMS 에 저장
    사용기술 ( JPA 활용 ) 
- toy-viewer [미정]
  : 해당 RDBMS 조회후 해당 데이터를 화면에 뿌려주는 역할 
