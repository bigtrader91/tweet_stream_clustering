# Tweet_stream_clustering(feat. NewJeans)
트위터API 를 통해서 실시간(streaming) 트윗을 카프카로 저장 및 처리하여 Spark streaming을 통해서 카프카에 있는 스트리밍 데이터를 읽고 정제한 다음 DW에 저장. DW에 있는 테이블을 읽어 SparkML로 트윗 메시지의 내용을 각나라 언어별로 군집화.

## 💾 Projcet 구조
![image](https://user-images.githubusercontent.com/88607278/214727221-80701f1c-c81b-48c8-8070-dc81021beb22.png)

## :bell: Purpose
- spark에서 stream 데이터 처리가 어떻게 이루어지는지 확인

## 💾 Data(api)
- [StreaminClient](https://docs.tweepy.org/en/stable/streamingclient.html?highlight=StreamingClient)

- ![image](https://user-images.githubusercontent.com/88607278/214729303-ea479c85-0152-4526-b004-f84245750645.png)




## 📚 Tech Stacks
- Spark, Hadoop, Kafka

## 환경설정
- GCP에서 4개의 인스턴스 생성 후 master 1대, worker 3대로 클러스터 구성
- 드라이버 : yarn
- zeppelin에서 모든 작업 진행




 ## 프로젝트에 대한 자세한 내용
 - [블로그](https://nothing-error.pysyntax.com/entry/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%89%B4%EC%A7%84%EC%8A%A4-%ED%8A%B8%EC%9C%97-%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%EB%A7%81-2-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D)
