<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&text=HOSE%20JOO&fontSize=50&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Data%20Pipeline%20%26%20GenAI&descSize=18&descAlign=62&descAlignY=58" />

### 백엔드 개발자 주호세입니다

수학과 출신으로 LG CNS에서 6년째 백엔드를 맡고 있습니다.
설비 제어 시스템 운영에서 시작해 레거시 마이그레이션, 실시간 데이터 파이프라인을 거쳐
지금은 RAG와 Agentic AI를 실제 업무 시스템에 붙이는 일을 하고 있습니다.

문제를 알고리즘 수준에서 다시 정의하는 것과, 그걸 운영 환경에서 안 죽게 만드는 것 사이의
간격을 메우는 데 관심이 많습니다.

<br>

## 해온 일

**실시간 CDC 파이프라인 구축** · Debezium, Kafka, AWS Lambda
MQ와 DB 프로시저에 의존하던 데이터 동기화가 최대 20분까지 지연되던 문제를,
Debezium으로 DB 변경 이벤트를 직접 감지하고 Kafka를 거쳐 Lambda Consumer가 처리하는
서버리스 CDC 아키텍처로 재설계했습니다. 프로시저에 집중되던 부하를 분산시켜 동기화 지연을 5초 이내로 줄였습니다.

**규정 문서 기반 RAG QA 시스템** · OpenSearch, 하이브리드 검색
55개 업무 규정 문서를 파싱·정제해 지식베이스로 만들고, 키워드와 벡터를 결합한 하이브리드 검색을 적용했습니다.
문서 성격과 도메인에 맞춰 인덱스를 8개로 분리해 검색 정밀도를 높이고,
콜드 스타트로 인한 초기 질의 지연은 warm-up 처리로 해소했습니다.

**Agentic AI 기반 문서 검토 자동화** · 온프레미스 LLM
하도급 품의서 검토 프로세스를 자동화했습니다. 가이드 문서를 Markdown으로 구조화해 입력을 정규화하고,
검토 단계를 분해해 병렬 처리로 처리 시간을 단축했습니다.
응답은 항상 규정 근거를 인용하도록 구성해 할루시네이션을 억제했습니다.

**디자인 자동화 시스템** · Figma API, Weaviate, Redis
REST API로 수집한 디자인 자산을 벡터 DB에 적재해 기존 리소스 기반의 화면 생성을 구현했습니다.
대량 생성 요청은 Redis 기반 비동기 큐로 처리해 트래픽 부하를 분산시켰습니다.

**Delphi → Spring 레거시 전환** · Spring, Spring Batch
노후 독촉 시스템을 Spring 기반 백엔드로 전환하며 전담 엔지니어를 맡았습니다.
대량 소송 데이터를 다루는 배치를 Spring Batch로 재설계해 처리 프로세스를 안정화했습니다.

**설비 제어 로직 최적화** · C#, Oracle PL/SQL
Stacker Crane 입출고 우선순위를 위치 기반 알고리즘으로 재설계해
불필요한 크레인 이동과 대기시간을 줄이고, 생산 공정 전반의 가동률을 끌어올렸습니다.

<br>

## 기술 스택

| | |
|---|---|
| **주력** | Java, Spring Boot, JPA, MyBatis, Python |
| **데이터** | Kafka, Debezium, Oracle, MySQL, Redis, OpenSearch, Weaviate |
| **AI** | RAG, Agentic AI, LLM Serving, Machine Learning |
| **인프라** | AWS (SAA), Docker, Jenkins |
| **그 외** | C#, VB.NET |

<br>

## 링크

- 기술 블로그 &nbsp;[hose0728.tistory.com](https://hose0728.tistory.com/)
- 백준 &nbsp;[solved.ac/hose123](https://solved.ac/hose123)

<br>

<div align="center">

<a href="https://github.com/DenverCoder1/github-readme-streak-stats">
  <img src="./profile/streak.svg" alt="GitHub Streak" />
</a>
<a href="https://solved.ac/hose123">
  <img width="360" src="https://mazassumnida.wtf/api/v2/generate_badge?boj=hose123" alt="Solved.ac" />
</a>

</div>
