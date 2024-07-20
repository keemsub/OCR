project-root/
├── data/
│   ├── raw/                # 원본 데이터
│   ├── processed/          # 전처리된 데이터
│   ├── external/           # 외부 데이터
│   └── interim/            # 중간 단계 데이터
├── notebooks/              # Jupyter 노트북 파일
├── src/
│   ├── __init__.py         # 패키지 초기화 파일
│   ├── data/               # 데이터 관련 코드
│   │   ├── __init__.py
│   │   ├── make_dataset.py # 데이터 전처리 스크립트
│   ├── features/           # 특징 추출 코드
│   │   ├── __init__.py
│   │   ├── build_features.py
│   ├── models/             # 모델 정의 및 학습 코드
│   │   ├── __init__.py
│   │   ├── train_model.py
│   │   ├── predict_model.py
│   ├── visualization/      # 시각화 관련 코드
│   │   ├── __init__.py
│   │   ├── visualize.py
│   └── utils/              # 유틸리티 함수
│       ├── __init__.py
│       └── helper.py
├── tests/                  # 테스트 코드
│   ├── __init__.py
│   ├── test_data.py
│   ├── test_features.py
│   ├── test_models.py
│   └── test_visualization.py
├── models/                 # 학습된 모델 저장
├── reports/                # 보고서 및 결과물
│   ├── figures/            # 그림 및 시각화 결과
│   └── final_report.md     # 최종 보고서
├── config/                 # 설정 파일
│   └── config.yaml
├── requirements.txt        # 프로젝트 종속성
├── setup.py                # 패키지 설정 파일
├── README.md               # 프로젝트 설명서
└── .gitignore              # Git 무시 파일
