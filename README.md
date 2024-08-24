# MoodRec

- 훈련하려면 !python main.py --data yelp --epoch 200 돌리기
- 그럼 자동으로 추천결과가 지정된 경로에 저장됨 (main.py line253에서 설정 가능)

- 데이터는 data/yelp 경로에 있음 (이름만 yelp고 우리 데이터)
- trnMat.pkl, tstMat.pkl은 각각 트레인,테스트용
- fullMat.pkl이 트레인,테스트 나누지 않은 풀버전

- 체크포인트는 saved_model 폴더에 저장됨
- saved_optim이 포함된 파일 사용하면 됨
