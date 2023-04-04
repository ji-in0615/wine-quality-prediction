# Wine-quality-prediction
This project is about the prediction of red wine quality using different machine learning algorithms.

## About the dataset
Wine Quality dataset is public available for research in the University of California, Irvine Machine Learning repository created by Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) in 2009. This repository has two datasets of red and white wine samples which consists of inputs includes objective tests (e.g. PH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).

## Variable
### Organic acid
[유기산 → 풍미에 중요한 역할]

- fixed acidity (결합산, 고정산도) - 산의 농도에 90% 이상 차지 <br>
주로 타르타르산, 사과산 으로 이루어져 있으며 와인의 산도 제어 → 함량이 적을수록 좋음. <br>
- 타르타르산, 주석산 (tartaric acid) - 가장 비중이 큼 <br>
와인에서 가장 중요한 산으로 포도에만 다량 존재하는 산. <br>
pH에 밀접한 영향을 미침 <br>
와인을 마실 때 좋지 않은 감촉을 유발하므로 될 수 있으면 제거하는 편이 좋음. <br>
- 사과산 (malic acid) <br>
주석산에 비해 불안정하며 쉽게 다른 물질로 변하기 때문에 완성된 와인에는 사과 <br>
산이 적을수록 안정성이 높음. <br>
알코올 발효를 거치면, 맛이 부드러워지고 품질이 개선됨. <br>
- citric acid (구연산, 시트르산 수치) - 약한 유기산, 산의 농도에 거의 영향 X <br>
와인의 신선함을 올려주는 역할, 산성화에 밀접한 연관을 미침. <br>
소량으로 발견되는 구연산은 와인에 신선함과 풍미를 더해줌. <br>

### Volatile acid
와인의 향과 연관, 낮을 수록 좋음. <br>
과일향이 가득한 와인인지, 식초가 되는 과정으로 넘어가는지 판가름할 수 있는 기준 <br>


### Sugar
- residual sugar (잔여 설탕) <br>
발효 후 잔류하는 설탕의 양 <br>
와인의 단맛을 올려줌 <br>


### Salinity
-  chlorides (염화물, 소금 함유량) <br>
와인에 들어있는 소금의 양. <br>
와인의 짠맛의 원인. 와인의 신맛을 좌우하는 성분. <br>


### Sulfur dioxide
-  free sulfur dioxide (유리 이산화황) <br>
자유형태의 SO2 (산소 포화도 : 산소와 결합한 비율) <br>
원하지 않는 박테리아와 효모를 죽여 와인을 오래 보관하는 역할. <와인의 보관도를 높여줌> <br>
→ 분자, 미생물 성장과 포도주의 산화 방지 <br>

- total sulfur dioxide (총 이산화황) <br>
저농도에서는 거의 검출되지 않지만, 50ppm 이상의 SO2 농도에서는 와인의 향에 영향을 미침. <br>

- sulphates (황산염) <br>
SO2 수준에 기여할 수 있는 와인 첨가제로서, 항균 및 항산화 작용.


### Concentration
- density(수분 밀도) : 와인의 밀도, 무게감


### Sourness
- pH (산성도, 수소 이온 지수) <br>
산의 강도 혹은 해리도를 나타내는 지표로서 수소이온 농도를 뜻함. <br>
향미, 색, 미생물학적 안정성, 단백질 안정성, 산화, 아황산 첨가량에 직접 영향을 미침 <br>
와인의 pH는 2.8-4.0의 범위로서 수치가 낮을수록 미생물에 대한 저항력은 강해지지만, 신맛도 강해짐. <br>
pH가 낮을수록 향이 좋아지며 신선한 맛이 나고, 발효가 진행되어 더 좋은 와인을 만들 수 있음. <br>
이상적인 pH : 3.4 이하 (레드 와인) <br>

### Alcohol
- alcohol(알코올 도수) : 와인의 알콜 함량 퍼센트. <br>
함량이 높을수록 와인에 단맛을 주고, 매끄러운 바디감을 줌. <br>

### Subordination Variable
- quality(품질) : 감각 데이터를 기반으로 0~10 등급 (종속변수)
