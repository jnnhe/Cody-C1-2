# 맞춤형 학습 가이드 AI "HOW" 광고 프로젝트
"HOW로 당신의 성장을 완주하세요."

AI 멀티모달 생성 도구를 활용하여 제작한 8초 브랜드 숏폼 광고 프로젝트입니다.

## 1. 프로젝트 개요브랜드명: HOW (맞춤형 학습 가이드 AI)
총 러닝타임: 8초 (각 씬당 2초 균등 배분)캠페인 

목표: 친근한 캐릭터를 통해 학습자의 레벨업과 성장을 돕는 AI 광고

타겟: AI를 활용한 효율적인 학습법과 성장을 원하는 모든 학습자

톤앤매너: 밝고 청량한 블루/화이트 톤, 아기자기하고 친근한 요정 컨셉의 2D 벡터 애니메이션 무드

## 2. 사용 도구 파이프라인 (Multimodal Tool Pipeline)
### 이미지 생성 AI: 제미나이 나노바나나 (Gemini NanoBanana)
선택 이유: 캐릭터(HOW)의 고유한 외형(초롱초롱한 눈, 인형 같은 요정 실루엣, 물음표 머리)과 4개 씬의 키비주얼 및 자막 요소를 직관적이고 일관되게 생성하기 위해 선택.

역할: 캐릭터(HOW)의 고유 외형 및 4개 씬의 키비주얼 생성 (보유하고 있던 오리지널 캐릭터 설정을 바탕으로 최적화)
### 비디오·오디오 통합 생성 AI: OpenAI Sora (해상도: 1280x720)
선택 이유: 생성된 이미지를 바탕으로 8초 타임라인의 자연스러운 모션뿐만 아니라, 발랄한 BGM(페이드 인/아웃 적용)과 내레이션을 일체감 있게 동시에 출력하여 제작 효율성을 극대화하기 위해 선택.

역할: 생성된 이미지를 바탕으로 8초 타임라인의 모션, BGM(페이드 인/아웃), 내레이션을 일체감 있게 동시 생성통합 
### 편집 도구: 미리캔버스 (Miricanvas)
선택 이유: 최종 영상 파일의 컷 정돈 및 사운드 싱크, 자막 레이어 및 브랜드 배너 후가공을 위한 제한적 편집 용도로 활용.

역할: 최종 컷 정돈, 자막 레이어 및 브랜드 배너 후가공


## 3. 씬별 구성 (Scene Breakdown)
목표 메시지주요 화면 구성 및 프롬프트 요약
### Scene 1 HOW 소개 
<img width="345" height="192" alt="1" src="https://github.com/user-attachments/assets/15129c66-c88b-466c-b001-473e9722d4bd" />

입력 프롬프트 : "Cute and friendly doll-like fairy character with big sparkling eyes and a question-mark shaped hair topping, waving hello, bright blue and white palette, 2D vector animation style, soft teal interface background."

결과 : 초롱초롱한 눈의 요정 캐릭터가 카메라를 향해 손을 흔드는 바스트 샷(2초)

파일명 scene1.png

### Scene 2 맞춤형 경로 및 체크포인트 제안 
<img width="346" height="192" alt="2" src="https://github.com/user-attachments/assets/aeea742b-4c28-410c-ac99-15ed92c81510" />

입력 프롬프트 : "The fairy character pointing at a glowing digital roadmap screen with branching pathways and checkpoints, clean data flow background, 2D vector style."

결과 : 디지털 로드맵 스크린(갈래길과 체크포인트)을 가리키는 요정의 모습(2초)

파일명 scene2.png

### Scene 3 학습 성취감 및 동기부여
<img width="349" height="194" alt="image" src="https://github.com/user-attachments/assets/c267a4de-3f11-4c01-b344-f5b4f2687842" />

입력 프롬프트 : "The fairy character clapping happily while a student holds a tablet with 'LV UP' text, warm golden lighting effect, celebratory atmosphere, 2D vector style."

결과 : 박수치는 요정과 'LV UP' 태블릿을 든 학습자의 따뜻한 골드빛 컷(2초)

파일명 scene3.png

### Scene 4 브랜드 슬로건 CTA 각인
<img width="342" height="191" alt="image" src="https://github.com/user-attachments/assets/b3f8e5ae-7ddb-4d8d-a20c-b9c8e602e8a9" />

입력 프롬프트 : "Minimal typography title card, soft sky blue gradient background, clean brand banner layout, professional tech brand vibe."

결과 : 소프트한 스카이 블루 배경의 미니멀 타이포그래피 카드 샷(2초)

파일명 scene4.png


## 4. 프롬프트 수정 및 최적화 과정 (Prompt Iteration)수정 배경
: 초기 기획 단계에서는 캐릭터가 다소 차갑고 기계적인 로봇 형태로 표현되어 
브랜드가 지향하는 따뜻하고 친근한 학습 동반자의 이미지를 주기에 부족했습니다.

이에 따라 기존 캐릭터 자산을 반영하여 초롱초롱하고 귀여운 요정 인형 컨셉으로 전면 수정하였고, 
숏폼의 몰입감을 극대화하기 위해 전체 타임라인을 8초(각 씬당 2초 균등 배분)로 압축 조정했습니다.

### Before ➔ After 비교 :
Before: "A rigid blue robot character with a question-mark head, 10-second sequence..." 
(딱딱한 로봇 형태 및 긴 호흡)

After: "Cute and friendly doll-like fairy character with big sparkling eyes and a question-mark shaped hair topping, 8-second total sequence (2 seconds per scene)..." 
(친근한 요정 인형 캐릭터 및 속도감 있는 8초 타임라인 완성)

