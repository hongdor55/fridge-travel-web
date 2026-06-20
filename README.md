# fridge-travel-web
# ✈️ 방구석 세계여행: 냉장고 파먹기 (Armchair World Travel: Fridge Foraging)

> **"지루한 냉파는 끝, 재료만 넣으면 여권 없이 떠나는 자취생 방구석 미식 여행!"**
> 
> 본 프로젝트는 대용량 식재료 처리가 시급한 1인 가구 및 요리 초보 자취생을 위한 **로컬스토리지 기반 이색 세계 요리 레시피 매칭 반응형 웹 서비스**입니다. 외부 서버나 데이터베이스 비용 없이 브라우저 단에서 안전하고 가볍게 구동되는 린(Lean) MVP 프로덕트입니다.

---

## 🎯 핵심 가치 (Core Value)

*   **식재료 업사이클링**: 애매하게 남은 잔여 식재료의 폐기를 최소화하여 자취생의 식비 절감 및 환경적 가치 창출.
*   **글로벌 미식 경험**: 늘 먹던 집밥 메뉴에서 벗어나, 남은 재료와 매칭되는 세계 각국의 이색 레시피 제공.
*   **진입 장벽 완화 (K-대체재)**: 구하기 힘들고 비싼 현지 특수 향신료 대신, 동네 마트나 편의점에서 구할 수 있는 한국식 대체 식재료 가이드 맵핑.

---

## ✨ 주요 기능 (Key Features)

### 1. 로컬스토리지 기반 식재료 재고 관리
*   로그인이나 별도의 서버 저장 없이 브라우저 내 `LocalStorage`를 활용한 식재료 데이터 유지.
*   자취방 필수 식재료 기반의 직관적인 멀티 선택 및 검색 UI.

### 2. 국가별 이색 레시피 매칭 엔진
*   사용자가 선택한 국가(태국, 이탈리아, 일본 등)의 레시피와 보유 재료를 실시간 대조.
*   재료 일치율(%) 스코어링 및 매칭 결과 정렬 알고리즘 탑재.

### 3. K-향신료 대체재 가이드 & 유튜브 온보딩
*   현지 특수 소스(예: 피시소스 ➔ 멸치액젓, 바질 ➔ 깻잎 등) 가이드를 제공하여 요리 실패 확률 최소화.
*   텍스트 조리법과 유튜브 미디어 가이드라인을 결합한 하이브리드 인앱 온보딩.

### 4. 게이미피케이션 요권 스탬프 시스템
*   특정 국가의 요리를 완성할 때마다 가상 여권에 디지털 스탬프를 획득하는 리텐션 유도 보상 체계.

---

## 🛠 기술 스택 (Tech Stack)

*   **Frontend**: Next.js (React), Tailwind CSS (모바일 퍼스트 반응형 UI)
*   **Database & State**: Browser LocalStorage (No-Server, Client-Side Data Integration)
*   **Deployment**: Vercel

---

## 🚀 시작하기 (Getting Started)

로컬 환경에서 프로젝트를 실행하려면 아래 명령어를 입력하세요.

```bash
# 저장소 복제
git clone [https://github.com/your-username/fridge-travel-web.git](https://github.com/your-username/fridge-travel-web.git)

# 폴더 이동
cd fridge-travel-web

# 의존성 패키지 설치
npm install

# 개발 서버 실행
npm run dev
