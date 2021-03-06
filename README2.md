# Covid19와 금융데이터 EDA

- 코로나바이러스감염증-19(COVID-19) 현황 누적 데이터 (2021.01.28)
- 누적 확진자 수만 카운팅 되어있어서 일일 확진자로 전처리가 필요함

    ![](README2/_2021-04-06_11.13.35.png)

- decideCnt(t)-decideCnt(t-1) : dailyCnt 로 생성

    ![](README2/_2021-04-06_11.25.30.png)

- 일별 확진자수 추이와 일별 확진율(일별 확진자 / 검사 진행 수)을 시각화해보면 다음과 같다.

    ![](README2/_2021-04-06_11.29.41.png)

    ![](README2/_2021-04-06_11.30.04.png)

    ---

    ### Summary

    - 금융빅데이터랩은 보안이 철저해서 데이터나 분석 결과를 가지고 나올 수는 없었지만, 우리가 집계한 일별 확진자별로 어떤 항목에 소비가 늘었고 줄었는지를 약 3천만 개의 실제 데이터를 보면서 확인할 수 있는 흥미로운 프로젝트였다.
    - 기억에 남는 점을 몇 가지 정리해보면 다음과 같다. 3월 1차 대유행 이후로 ,
        1. 소주 소비량이 맥주소비량을 앞질렀다.

            ⇒ 가설) 여유롭게 마시지 못하고, 영업시간 제한으로 인해 빠르게 식사를 끝내야하기 때문에?

        2. 체육시설에 대한 소비는 3월 이후 증가한 적이 없다.

            ⇒ 가설) 실내 집단감염에 대한 우려로 실내 체육시설 제한을 강하게 시행했기 때문에?

        3. 자동차 수리점의 매출이 증가했다.

            ⇒ 가설) 공공 교통시설 내에서의 감염 우려로 자차 이용이 증가했고, 따라서 정비 건수가 증가했다.
