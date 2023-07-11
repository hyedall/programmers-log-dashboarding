# programmers-log-dashboarding

## 로그데이터 분석 대시보드 구축

[PPT](https://drive.google.com/file/d/1W8ISiGAbiBkxj9eWRlJfa2SGUfnvGiuz/view?usp=sharing)<br>
[보고서](https://drive.google.com/file/d/1aCX1noZLkykmk-zTApxAyYe6HJT1ythB/view?usp=sharing)

<aside>
📊 로그 데이터 분석 대시보드
[Fake-Apache-Log-Generator](https://github.com/kiritbasu/Fake-Apache-Log-Generator)를 통해 사용자 방문 로그 생성 후, 
S3적재 → Redshift 로드 → 태블로 대시보드 구축을 진행했습니다.

</aside>

### 기술 스택

Python, Tableau, Redshift

### 상세 내용

웹페이지 사용자 로그 더미 데이터를 생성후 변환하여, AWS S3에 적재, Redshift에 로드 후
태블로를 통해 일별 접속량 추이, 홈페이지 별 유입 도메인, 특성 별 자원 소모량, 접속량, 날짜 별 동시 접속자 수, 자원 소모량, 유입 도메인, 국가별 접속자 수를 시각화한 대시보드를 만들었습니다.  

### 주요성과

🔻 태블로 시각화 링크 

[https://public.tableau.com/app/profile/.13208461/viz/__16862389682980/1](https://public.tableau.com/app/profile/.13208461/viz/__16862389682980/1)

### 기여한 부분

태블로 대시보드 구축

### 아쉬운 점

더미 로그데이터가 시간당 균일하게 생성되다보니 시각화를 했을 때 균등한 분포를 보이는 모습이 아쉬웠음






