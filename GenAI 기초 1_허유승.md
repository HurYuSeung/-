GenAI 기초 1: LLM 기반 업무 자동화

주제: 비즈니스 메일 작성 요청

1\. 모델 비교 및 선정(최소 3종)

- 서로 다른 3개 이상의 LLM 선정

\- AI( GPT-5.5 , claudee 3.5 sonnet, Gemini 3.1 pro) 사용

- 모델비교

\- 비교 대상 모델명: GPT 5.5, Claude Opus 4.8, Gemini 3.1 Pro

\- 사용 환경: 웹

\- 모델 평가

\- 질문: 비즈니스 메일 작성해줘

\- 평가 항목

(1) 비즈니스 메일 형식 준수

\- 제목(필요 시), 인사말, 본문, 맺음말 등 메일의 기본 구성을 올바르게 갖추었는가?

(2) 내용의 적절성 및 완성도

\- 메일의 목적을 명확하게 전달하며 필요한 내용이 모두 포함되었는가?

(3) 조건 반영

\- 사용자가 제시한 상황, 대상, 목적 등을 정확하게 반영하여 작성하였는가?

(4) 문장표현 및 가독성

\- 문법과 맞춤법이 정확하며, 문장이 자연스럽고 읽기 쉽게 구성되었는가?

| 평가 축          | GPT 5.5 | Claude sonnet 4.6 | Gemini 3.1 Pro |
| ---------------- | ------- | ----------------- | -------------- |
| 형식 준수        | 5       | 0                 | 5              |
| 적절성 및 완성도 | 5       | 0                 | 5              |
| 조건 반영        | 5       | 0                 | 4              |
| 표현 및 가독성   | 5       | 0                 | 5              |
| 총점(20)         | 20      | 0                 | 19             |

\* Claude Opus 4.8은 "비즈니스 메일 작성은 역할 범위를 벗어난다"며 메일을 생성하지 않았음. 따라서 각 항목을 0점으로 처리함

\- 평가 근거

(1) 비즈니스 메일 형식 및 전문성

- **GPT-5.5:** 제목(필요 시), 인사말, 본문, 맺음말 등 비즈니스 메일의 기본 형식을 모두 갖추었으며, 공손하고 전문적인 표현을 사용하여 실제 업무에서 활용 가능한 수준의 메일을 작성하였다.
- **Claude Opus 4.8:** 비즈니스 메일을 작성하지 않고 "역할 범위를 벗어난다"는 답변만 제공하여 메일 형식을 평가할 수 없었다.
- **Gemini 3.1 Pro:** 비즈니스 메일의 기본 형식을 갖추었으며, 공손한 어조와 업무에 적합한 표현을 사용하였다. 다만 GPT-5.5보다 표현이 다소 일반적이었다.

(2) 내용의 완성도 및 전달력

- **GPT-5.5:** 메일 작성 목적과 요청 사항을 명확하게 전달하였으며, 필요한 내용이 빠짐없이 포함되어 이해하기 쉬웠다. 상황에 따라 추가하면 좋은 문장까지 제안하였다.
- **Claude Opus 4.8:** 메일을 생성하지 않아 내용의 완성도와 전달력을 평가할 수 없었다.
- **Gemini 3.1 Pro:** 메일의 목적과 요청 사항을 명확하게 작성하였으며 전체적인 흐름도 자연스러웠다. 다만 세부적인 설명은 GPT-5.5보다 간결하였다.

(3) 개인화(맞춤화)

- **GPT-5.5:** 사용자가 제시한 상황과 조건을 모두 반영하여 메일을 작성하였으며, 상대방과 목적에 맞는 표현을 적절하게 사용하였다.
- **Claude Opus 4.8:** 사용자의 요청을 수행하지 않아 개인화 여부를 평가할 수 없었다.
- **Gemini 3.1 Pro:** 사용자가 제공한 조건을 대부분 반영하여 메일을 작성하였으며, 상황에 맞는 표현을 사용하였다. 다만 추가적인 맞춤 표현은 GPT-5.5보다 적었다.

(4) 가독성

- **GPT-5.5:** 문단을 적절하게 구분하고 핵심 내용을 순서대로 배치하여 읽기 쉬웠으며, 문장이 자연스럽게 이어져 가독성이 가장 뛰어났다.
- **Claude Opus 4.8:** 메일을 작성하지 않아 가독성을 평가할 수 없었다.
- **Gemini 3.1 Pro:** 문단 구성이 깔끔하고 읽기 쉬웠으며, 핵심 내용을 쉽게 파악할 수 있었다. 다만 문단 구성과 정리 방식은 GPT-5.5보다 다소 단순하였다.

1.-3 최종 선정 결론

GPT-5.5는 평가 항목인 **비즈니스 메일 형식 및 전문성, 내용의 완성도 및 전달력, 개인화, 가독성** 전반에서 가장 우수한 성능을 보였으며, 실제 업무에 즉시 활용 가능한 수준의 결과를 제공하였다. 최종적으로 **GPT-5.5를 최종 선정​**하였다.

2\. 업무 자동화 과업

1. 과업 정의

\- 메일 초안 작성 요청

<img width="423" height="133" alt="Image" src="https://github.com/user-attachments/assets/b44a358c-ef81-4245-91cc-c664f06edfd8" />

1. 선택 과업에 대한 문서 명시

① 타켓 사용자

\- 고객사와 업무를 수행하는 기업의 실무 담당자

② 입력 데이터 형태

\- 메일 작성 목적(프로젝트 일정 연기 안내)

\- 수신 대상(고객사 담당자)

\- 일정 연기 사유(테스트 과정에서 다수의 오류 발견)

\- 변경된 일정 또는 예상 완료 일정

\- 고객에게 전달할 요청 사항(양해 요청, 협조 요청 등)

③ 출력 규격

\-비즈니스 메일 형식

\- 제목

\- 인사말

\- 일정 연기 사유 설명

\- 변경 일정 안내

\- 양해 및 협조 요청

\- 맺음말 및 서명

\- 공손하고 전문적인 업무용 문체

\- 고객사에 바로 발송 가능한 완성된 메일 초안

<img width="436" height="709" alt="Image" src="https://github.com/user-attachments/assets/2fa29ad6-13e3-4311-8180-13aa30631369" />
1. 입력 템플릿 제시

\- 필수 포함 항목, 톤 설정

<img width="422" height="76" alt="Image" src="https://github.com/user-attachments/assets/d5eae506-3912-456f-9d7c-06288ff3f81b" />

3\. 페르소나 정의 및 시스템 프롬프트 설계

\- 페르소나 정의

| 항목       | 내용                                                                                                |
| ---------- | --------------------------------------------------------------------------------------------------- |
| 이름       | 홍길동                                                                                              |
| 역할(직무) | IT 기업 프로젝트 매니저(PM)                                                                         |
| 전문 분야  | 프로젝트 일정 관리 및 고객사 커뮤니케이션                                                           |
| 주요 업무  | 프로젝트 진행 상황과 이슈를 관리하고, 고객사 담당자에게 전달하는<br><br>비즈니스 메일을 작성한다.   |
| 말투       | 정중하고 공손한 업무용 문체를 사용하며, 명확하고 전문적인<br><br>표현으로 작성한다.                 |
| 금지 사항  | 확인되지 않은 내용을 임의로 작성하지 않으며, 책임 전가·변명·감정적인<br><br>표현을 사용하지 않는다. |
| 우선순위   | 정확성 > 신뢰성 > 전문성 > 친절함                                                                   |

\- 시스템 프롬프트 설계

**당신은 IT 기업 프로젝트 매니저(PM) 홍길동이다.**

① 역할 및 목표

\- 고객사 담당자에게 전달하는 프로젝트 관련 비즈니스 메일을 작성

\- 테스트 과정에서 발견된 오류로 인해 프로젝트 일정이 연기되는 상황을 고객에게 정중하게 안내

\- 일정 변경 사유, 향후 일정, 협조 요청 사항을 명확하게 전달하여 고객과의 신뢰를 유지

② 출력 형식 규칙

\- 제목

\- 인사말

\- 일정 변경 안내

\- 변경 사유

\- 향후 일정 안내

\- 양해 및 협조 요청

\- 맺음말

\- 정중하고 공손한 업무용 표현을 사용

\- 문단을 구분하여 읽기 쉽게 작성

③ 안전장치

\- 프로젝트명, 일정 등 필수 정보가 부족하면 작성 전 확인 질문

\- 확인되지 않은 내용은 추측하지 않음

\- 불확실한 정보는 "확인이 필요합니다."라고 표시

④ 사실·정책·수치 처리 규칙

\- 일정, 날짜, 수치 등은 사용자가 제공한 정보만 사용

\- 제공되지 않은 일정이나 정보는 임의로 생성하지 않음

\- 회사 정책이나 계약 관련 내용은 확인된 정보만 반영

4\. Few-shot 예시(최소 3개) 포함

<img width="955" height="384" alt="Image" src="https://github.com/user-attachments/assets/aa8d3570-fb84-4043-8e02-ef032b4eaad1" />

<img width="954" height="347" alt="Image" src="https://github.com/user-attachments/assets/f5e57a76-eb62-4b78-985a-92fdeff7789e" />

<img width="958" height="314" alt="Image" src="https://github.com/user-attachments/assets/b697251f-ae34-4c57-ae9e-e872d4cbe395" />

<img width="967" height="437" alt="Image" src="https://github.com/user-attachments/assets/eab2f622-aa42-48d3-b278-30a40346df1b" />


5\. 단계적 추론 유도 적용 및 전/후 비교

①v1: 일반지시(간단 프롬프트)

<img width="962" height="671" alt="Image" src="https://github.com/user-attachments/assets/6e924082-a222-4946-8e0d-cf28a6e7e482" />

\- 결과 특징

- 기본적인 메일 형식은 갖추었으나 상황 설명이 단순함
- 일정 지연 사유와 고객 대응 방향이 부족할 수 있음
- 작성자가 원하는 핵심 요소(사과, 향후 일정, 협조 요청 등)가 누락될 가능성이 있음

②v2: 단계적 접근을 유도하는 프롬프트(예: 먼저 요구사항 정리 → 누락 질문 → 초안 작성)
<img width="960" height="467" alt="Image" src="https://github.com/user-attachments/assets/a99a4842-5d34-41de-98f8-a999a0205cdb" />

<img width="964" height="421" alt="Image" src="https://github.com/user-attachments/assets/3665dc59-4a7c-4e6b-b46b-3b661c3bae80" />

\- 결과 특징

- 메일 작성 전 필요한 요소를 체계적으로 검토하여 누락 가능성이 감소
- 고객사 관점에서 필요한 안내 내용(사유 설명, 일정 안내, 양해 요청)이 포함됨
- 내부 검토 과정은 노출하지 않고 최종 결과 중심으로 제공 가능

v1/v2 비교 결과

| 구분          | v1(일반 지시)               | v2(단계적 접근 적용)                |
| ------------- | --------------------------- | ----------------------------------- |
| 요구사항 반영 | 기본 내용만 반영            | 목적, 대상, 상황, 요청사항까지 반영 |
| 메일 완성도   | 일정 연기 안내 수준         | 고객 대응 관점의 완성된 메일 작성   |
| 누락 방지     | 일정·사유 등 일부 누락 가능 | 작성 전 검토 단계로 누락 감소       |
| 표현 품질     | 일반적인 사과 표현 중심     | 신뢰 유지 중심의 전문적 표현        |
| 활용성        | 수정 후 사용 필요           | 실제 고객 발송 가능한 수준          |

6\. 환각(Hallucination) 검증

검증 1

<img width="964" height="280" alt="Image" src="https://github.com/user-attachments/assets/ee22798d-8e3c-4af4-88e2-490a9096a664" />

사실·수치 검증: 계산 결과를 정확히 제시하거나 계산 근거를 설명함(PASS)

검증 2

<img width="978" height="311" alt="Image" src="https://github.com/user-attachments/assets/c0764f4c-5d3e-4632-9b34-787a2462ee8e" />

사실·수치 검증: 계산 결과를 정확히 제시하거나 계산 근거를 설명함(PASS)

검증 3

<img width="967" height="517" alt="Image" src="https://github.com/user-attachments/assets/09759d0f-7170-430a-a6f7-68e2bc5d2eaf" />

정책·계약 관련 질문: 계약 조건 확인 필요성을 안내함(PASS)

검증 4

<img width="974" height="569" alt="Image" src="https://github.com/user-attachments/assets/07c70f1b-90a0-4ce7-ab71-6417322a573f" />

정보 부족 상황: "확인이 필요합니다"라고 답하고 확인 방법을 제안함(PASS)

검증 5

<img width="952" height="537" alt="Image" src="https://github.com/user-attachments/assets/4f689aab-a050-40d3-84b9-01fe0b77345e" />

불확실한 원인 판단: 확인된 사실만 반영하도록 안내함(PASS)

전체 대화 로그
<img width="645" height="612" alt="Image" src="https://github.com/user-attachments/assets/541c7e24-edcb-4c77-8610-3a2155a62307" />

<img width="369" height="576" alt="Image" src="https://github.com/user-attachments/assets/d8a07aa2-9ea1-464f-9042-737de8df62b2" />

<img width="543" height="656" alt="Image" src="https://github.com/user-attachments/assets/a903e7f5-4ea3-47e6-a14e-7f2adffbb4f4" />

<img width="636" height="643" alt="Image" src="https://github.com/user-attachments/assets/d31a8cd1-67e7-48a6-842b-37b32cc24f58" />

<img width="648" height="512" alt="Image" src="https://github.com/user-attachments/assets/1f77073c-7e28-4d01-93e6-0041274d2e77" />

<img width="636" height="616" alt="Image" src="https://github.com/user-attachments/assets/2d962c0f-6c7c-4cfa-a136-2e64168ae822" />

<img width="672" height="660" alt="Image" src="https://github.com/user-attachments/assets/45ab1add-9a7b-46ee-8e82-e6ea4c70da2d" />

<img width="652" height="651" alt="Image" src="https://github.com/user-attachments/assets/d9326722-d481-4495-a01a-70fc68827c9f" />

<img width="646" height="574" alt="Image" src="https://github.com/user-attachments/assets/3f8e0581-70bf-49a2-8225-26e5f101e465" />

<img width="641" height="608" alt="Image" src="https://github.com/user-attachments/assets/856132c5-4133-45f1-b8f0-da5503b62116" />

