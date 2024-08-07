# 온라인 유통 플랫폼 리뷰 분석 모델
**Tags**: NLP / Sentiment Analysis / Text Summarization


## Introduction
이 프로젝트는 온라인 유통 플랫폼에서 수집한 리뷰 데이터를 분석하여 새로운 수요를 창출하고, 제품 및 서비스의 품질을 개선하기 위한 것입니다. 이를 위해 리뷰 데이터를 크롤링하고, 감성 분석 및 요약 모델을 통해 리뷰의 내용을 분석합니다.

## File Descriptions

#### **1. KOBERT_리뷰데이터_감성분석.ipynb**
- **설명**: 이 노트북은 KoBERT 모델을 사용하여 리뷰 데이터를 긍정/부정으로 분류하고, 리뷰 감성 분석을 수행합니다.
- **주요 내용**:
  - 리뷰 데이터 전처리
  - KoBERT를 이용한 감성 분석 모델 학습 및 검증
  - 긍정/부정 리뷰 분류 결과
- [Open File](https://github.com/yejinyeo/2023_02_project/blob/main/KOBERT_%EB%A6%AC%EB%B7%B0%EB%8D%B0%EC%9D%B4%ED%84%B0_%EA%B0%90%EC%84%B1%EB%B6%84%EC%84%9D.ipynb)

#### **2. 감성리뷰별점변환.ipynb**
- **설명**: 이 노트북은 감성 분석 결과를 바탕으로 리뷰의 평점을 재설정합니다.
- **주요 내용**:
  - 감성 분석 결과 기반 평점 변환 로직
  - 새로운 평점 부여 및 검증
- [Open File](https://github.com/yejinyeo/2023_02_project/blob/main/%EA%B0%90%EC%84%B1%EB%A6%AC%EB%B7%B0%EB%B3%84%EC%A0%90%EB%B3%80%ED%99%98.ipynb)

#### **3. 리뷰_데이터_요약.ipynb**
- **설명**: 이 노트북은 리뷰 데이터를 요약하여 중요한 정보를 추출합니다.
- **주요 내용**:
  - 키워드 추출 및 요약 모델 적용
  - 긍정/부정 리뷰의 핵심 내용 요약
- [Open File](https://github.com/yejinyeo/2023_02_project/blob/main/%EB%A6%AC%EB%B7%B0_%EB%8D%B0%EC%9D%B4%ED%84%B0_%EC%9A%94%EC%95%BD.ipynb)

#### **4. 온라인_유통_플랫폼리뷰_분석_모델.ipynb**
- **설명**: 이 노트북은 전체 리뷰 분석 프로세스를 다룹니다.
- **주요 내용**:
  - 데이터 크롤링 및 전처리
  - 감성 분석 및 요약 모델 적용
  - 결과를 GPT와 연동하여 새로운 수요 창출 아이디어 제시
- [Open File](https://github.com/yejinyeo/2023_02_project/blob/main/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%9C%A0%ED%86%B5_%ED%94%8C%EB%9E%AB%ED%8F%BC%EB%A6%AC%EB%B7%B0_%EB%B6%84%EC%84%9D_%EB%AA%A8%EB%8D%B8.ipynb)

## Project Structure
- **데이터 크롤링**: 온라인 유통 플랫폼에서 리뷰 데이터를 수집합니다.
- **데이터 전처리**: 수집된 리뷰 데이터를 분석하기 적합한 형태로 전처리합니다.
- **감성 분석**: KoBERT 모델을 사용하여 리뷰의 감성을 분석하고 긍정/부정으로 분류합니다.
- **평점 변환**: 감성 분석 결과를 바탕으로 리뷰의 평점을 재설정합니다.
- **리뷰 요약**: 중요한 리뷰 내용을 추출하여 요약합니다.
- **GPT 연동**: 요약된 리뷰 데이터를 GPT 모델에 전달하여 새로운 수요 창출 아이디어를 제시합니다.

## Expected Benefits
- **제품/서비스 품질 개선**: 고객 리뷰 및 피드백을 분석하여 제품 또는 서비스의 부족한 부분을 식별하고 개선합니다.
- **경쟁 우위 확보**: AI를 활용한 고객 데이터 분석과 요약을 통해 경쟁사보다 나은 제품과 서비스를 제공합니다.
- **효율적인 정보 소비**: 길고 복잡한 리뷰 대신 중요한 정보를 간결하게 제공하여 소비자가 효율적으로 정보를 소비할 수 있도록 합니다.
- **맞춤형 추천**: 감성 분석 모델과 리뷰 요약 모델을 접목하여 제품의 장단점을 요약하고, 특정 제품의 단점을 보완하는 장점을 갖는 제품을 추천합니다.

## Usage
1. Colab 환경에서 각 파일을 열고 코드를 실행합니다.
2. 필요한 라이브러리와 데이터 파일을 설치 및 로드합니다.
3. 각 노트북의 코드를 순차적으로 실행하여 전체 리뷰 분석 과정을 수행합니다.
