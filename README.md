# bizanalytics-data

부경대학교 비즈니스 애널리틱스(2026) 수업용 데이터 미러다.
강의 노트북의 `balab.py` 로더가 첫 실행 시 이 저장소에서 파일을 내려받는다.
수업 목적의 미러이며, 라이선스와 이용조건은 각 원 출처를 따른다.

| 파일 | 데이터 | 원 출처 |
|---|---|---|
| `online_retail_ii.csv.gz` | Online Retail II (107만 거래) | [UCI ML Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii) (CC BY 4.0) |
| `cookie_cats.csv` | Cookie Cats 모바일 게임 A/B 테스트 | [Kaggle: Mobile Games A/B Testing](https://www.kaggle.com/datasets/yufengsui/mobile-games-ab-testing) |
| `hour.csv` | Capital Bikeshare 시간별 대여·날씨 (17,379시간) | [UCI ML Repository](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset) (CC BY 4.0) |
| `garments_worker_productivity.csv` | 봉제공장 팀별 일별 생산성 (1,197행) | [UCI ML Repository](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees) (CC BY 4.0) |
| `telco.csv` | Telco Customer Churn | IBM 샘플 데이터셋 |
| `wholesale_customers.csv` | Wholesale Customers (440곳) | [UCI ML Repository](https://archive.ics.uci.edu/dataset/292/wholesale+customers) (CC BY 4.0) |
| `aps/aps_failure_training_set.csv` `aps/aps_failure_test_set.csv` | APS Failure at Scania Trucks (7.6만 대) | [UCI ML Repository](https://archive.ics.uci.edu/dataset/421/aps+failure+at+scania+trucks) (원본 첫 20줄 고지문 유지) |
| `m5_ca1_subset.pkl` | M5 Forecasting (Walmart) CA_1 매장 300품목 서브셋 | [M5 Competition](https://www.kaggle.com/competitions/m5-forecasting-accuracy) 공개 데이터의 교육용 발췌 |
| `flotation_hourly.csv` | 광산 부유선별 실공정 시간별 집계 (4,097행) | [Kaggle: Quality Prediction in a Mining Process](https://www.kaggle.com/datasets/edumagalhaes/quality-prediction-in-a-mining-process) |
| `criteo_uplift_sample.pkl` | Criteo Uplift Modeling v2.1 계통추출 1/10 서브샘플 | [Criteo AI Lab](https://ailab.criteo.com/criteo-uplift-prediction-dataset/) |
| `supply_chain_logistics_problem.xlsx` | Brunel 물류 네트워크 (9,215 주문) | [figshare](https://doi.org/10.6084/m9.figshare.7558679) |
| `citibike_station_information.json` `citibike_station_status.json` | Citi Bike GBFS 정류장 스냅샷 | [Citi Bike System Data](https://citibikenyc.com/system-data) (수업 재현성을 위한 고정 스냅샷) |

Olist 이커머스 데이터는 이 미러에 두지 않고 로더가 Hugging Face 공개 미러에서 직접 받는다.
