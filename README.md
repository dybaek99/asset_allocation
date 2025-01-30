📌 파이썬 자산배분/가치지표 시스템 구축

📍 프로젝트 개요

본 프로젝트는 자산배분 및 투자 판단을 지원하기 위해 시장 데이터 및 주요 가치지표 데이터를 수집·분석하는 시스템을 구축하는 것을 목표로 합니다.

🛠 개발 환경 / 기술 스택

언어: Python

데이터 분석: pandas, numpy

시각화: matplotlib

데이터 소스: KRX, Yahoo Finance, ecos.bok.or.kr, KOFIA BIS, valueline, FRED, gurufocus, 빗썸

🎯 주요 기능

✅ 시장 데이터를 기반으로 최적의 자산배분 전략 정의

✅ PER, PBR, 배당수익률 등 핵심 가치지표 데이터 수집 및 분석

✅ 시계열 데이터를 활용한 투자 성과 시각화


📂 주요 프로그램 목록
프로그램	기능	용도
crawling_marketdata.ipynb	시장 데이터를 사용한 자산배분 프로그램	자산배분
crawling_fundguide.ipynb	fundguide 데이터 크롤링	종목선정
crawling_wics_value.ipynb	valueline 국내주식 가치지표 크롤링	종목선정
Magnificent_Seven.ipynb	Magnificent Seven 종목 그래프 시각화	종목선정
crawling_virtual_currency.ipynb	가상화폐 시세데이터 시각화	마켓타이밍
crawling_fred_indicators.ipynb	FRED 거시 경제 지표 데이터 크롤링	거시지표
