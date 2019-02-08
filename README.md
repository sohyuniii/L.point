# ["제5회 L.POINT Big Data competition - Be The L.BA"](https://competition.lpoint.com/index.tran)

### 01. 공모 제출 및 방법

- 활용 데이터 
  1) 제공 데이터 : 온라인 행동 데이터, 상품분류정보 
  2) 외부 데이터 : 통계청, 기상청 등 공공데이터, 소셜 데이터 등 자유롭게 활용 
- 주제별 분석 Data 다운로드 : 2018년 12월 3일(월) ~ 2019년 1월 16일(수) 
  ※ 참가접수 완료팀(팀장)에 한해 다운로드 가능 
- 분석결과물 제출기한 : 2019년 1월 16일(수) 15:00까지 

### 02. 데이터 설명

주제 : Digital Trend Analyzer
  1) 분석 목적 : 온라인 행동 기반 트렌드 예측
  2) 데이터 구성 
  
    가. 분석 주제 : 온라인행동 데이터 및 상품분류 데이터를 활용하여 
        1) 주요 상품군별 온라인 선호지수 생성
        2) 상품군별 수요 트렌드 예측 및 인사이트 도출
        3) 1), 2)를 활용한 신규 서비스 제안
    나. 데이터 상세 설명
     - 분석데이터 기간 : 총 6개월(‘18년 4월 ~ 9월)
      - 제공 범위 : 롯데그룹 온라인 계열사의 구매 및 이용 이력(온라인 계열사는 임의로 선정)
      ※ 본 데이터는 가공된 샘플 데이터로 실제 시장 데이터와 차이가 있습니다.

### 03. 데이터 목록
- 상품구매 (Product)
    - CLNT_ID     : 방문자(Visitors)의 쿠키1)에 랜덤으로 부여된 고유 ID 
    - SESS_ID     : Web/App에 접속 후 세션이 시작될 때 부여된 고유 ID
    - HITS_SEQ    : Web/App에서 페이지 또는 화면 클릭, 검색 등 방문자의 행위에 대해 순서대로 배열된 일련번호
    - PD_C        : 구매한 상품의 코드(최소단위)
    - PD_ADD_NM   : 구매한 상품의 추가 정보
    - PD_BRA_NM   : 구매한 상품의 브랜드
    - PD_BUY_AM   : 구매한 상품 1개의 금액
    - PD_BUY_CT   : 구매한 상품의 수량

- 검색어1 (Search1)	
    - CLNT_ID	 : 방문자(Visitors)의 쿠키1)에 랜덤으로 부여된 고유 ID 
        ※ 기기, 브라우저 체제에 따라 다른 방문자로 인식되어 동일고객이라도 여러 개의 클라이언트ID를 보유할 수 있음
	  - SESS_ID	 : Web/App에 접속 후 세션이 시작될 때 부여된 고유 ID
        ※ 하나의 클라이언트ID에 여러 개의 세션ID가 발급될 수 있음
	  - KWD_NM	 : 검색창에 입력한 검색 키워드
	  - SEARCH_CNT	: 세션 내 해당 검색어 검색량
    
- 검색어2 (Search2)	
    - SESS_DT	    : 세션일자 (YYYYMMDD 형식으로 표시)
	  - KWD_NM	    : 검색창에 입력한 검색 키워드
	  - SEARCH_CNT	: 세션 내 해당 검색어 검색량


