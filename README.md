### 숙명여자대학교 소프트웨어학부 2학년

데이터가 적거나 한쪽으로 치우쳐 있을 때 모델을 어떻게 학습시키고 검증할지에 관심이 있음

**활동**
- 정보보안학회 SISS (2026.03~)
- 제6회 숙명여대 프로그래밍 경진대회(SMUPC) 동상 (2026.09)
- SW중심대학사업단 클라우드 Intensive 교육과정(AWS) 수료 (2026.08)

**프로젝트**

- **[이미지 스테가노그래피 보존성·탐지 연구](https://github.com/lucyjeremy/sns-image-steganography)** · 개인, SISS 16주\
  카카오톡, 인스타그램 등 6개 플랫폼의 압축을 거친 뒤에도 이미지에 숨긴 정보가 남는지 실험함. PyTorch로 탐지 모델을 만들어 실제 사진에서 DCT 99.2%, LSB 89.5% 정확도를 얻음.

- **[실시간 이상거래 탐지 (FDS)](https://github.com/2wjddls2/AWS-Intensive-FDS-Project)** · 3인 팀, 모델 담당\
  사기 거래가 1~2%뿐인 데이터로 XGBoost를 학습시켜 SageMaker에 배포함. 사기 확률에 따라 자동 승인, 담당자 검토, 차단으로 나누고 검토·차단 사유는 Bedrock으로 설명함. 테스트에서 사기 22건 중 21건을 잡아냄.

- **[유튜브 숏폼 vs 롱폼 반응 분석](https://github.com/lucyjeremy/youtube)** · 2인 팀, 전처리·모델링\
  요리 채널 영상 400개를 IQR로 정제(320개)하고, 좋아요율과 댓글률만으로 숏폼/롱폼을 분류함. 로지스틱 회귀 정확도 90.62%.

- **[약지기](https://github.com/jiong2222/team43.yakzigi)** · 3인 팀, 백엔드·통합\
  돌봄자가 약봉투를 찍으면 OCR로 약 정보를 읽어 Firestore에 저장하고, 노인에게 복약 알람을 주는 앱.

- **[숙명 SW 비교과 Hub](https://github.com/lucyjeremy/sookmyung-sw-hub)** · 개인 · [사이트](https://lucyjeremy.github.io/sookmyung-sw-hub/)\
  교내외 여러 사이트에 흩어진 SW 비교과 정보를 한곳에서 찾을 수 있게 만든 웹 서비스 (React, Vite).

**기술**
Python · PyTorch · TensorFlow · scikit-learn · XGBoost\
AWS (SageMaker, Lambda, Bedrock) · Firebase Firestore · MySQL\
C · Java · JavaScript (React)
