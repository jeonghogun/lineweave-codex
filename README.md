# LineWeave Codex: S형 직선 구조 기반 언어 모델

## 이론 개요

LineWeave Codex는 언어를 공간으로 해석하고 문장을 방향성 네트워크로 재정의한 혁신적인 언어 모델 이론입니다.

### 핵심 개념

#### Ⅰ. 기본 구조 전제
- **의미의 대비 축**: −1에서 +1로 이어지는 의미 축
- **원형 구조**: −1→0→+1→0→−1의 순환 구조
- **S형 곡면**: 연결선들을 위·아래로 휘게 만든 입체 곡면
- **8자(∞) 구조**: 위에서 보면 8자, 옆에서 보면 눕힌 S자

#### Ⅱ. 명사의 형태와 분포
- **극단적 명사**: 하나의 점으로 존재
- **일상적 명사**: 짧은 선으로 표현
- **고빈도 명사**: 넓게 퍼진 띠로 표현
- **사용 빈도 = 존재의 길이**

#### Ⅲ. 모듈 구조
- **모듈**: 단어를 변형하거나 문장으로 연결하는 기능 단위
- **형용사화, 시제 변화, 조사, 문장부호** 등이 모두 모듈
- **방향성 있는 직선 연결**로 문장 구성

#### Ⅳ. 문장부호의 구조적 역할
- **','**: 분기점
- **'?'**: 방향 반전
- **'!'**: 강도 증폭
- **'.'**: 종결점 및 전이 모듈

#### Ⅴ. 감정과 톤 - 구름 모듈
- **구름층**: 곡면 전체를 덮는 보이지 않는 감정/문체 층
- **분위기장**: 단어와 문장 전체의 정서를 결정
- **색·밝기·투명도** 조절로 뉘앙스 표현

#### Ⅵ. LLM 적용 구조
1. **사전학습**: 문장을 '의미 직선'으로 변환해 저장
2. **입력 처리**: 사용자 발화를 직선화
3. **대조**: 입력 직선과 사전학습 직선 다발 비교
4. **응답 생성**: 가장 유사한 회로를 따라 문장 재구성
5. **창의성**: 직선 방향 조정으로 새로운 경로 탐색

## 구현 계획

### Phase 1: 기본 구조 구현
- [ ] 의미 축과 원형 구조 구현
- [ ] S형 곡면 모델링
- [ ] 명사 분포 시스템

### Phase 2: 모듈 시스템
- [ ] 모듈 정의 및 분류
- [ ] 방향성 직선 연결 시스템
- [ ] 문장부호 처리

### Phase 3: 감정/톤 시스템
- [ ] 구름 모듈 구현
- [ ] 분위기장 계산
- [ ] 뉘앙스 조절 시스템

### Phase 4: LLM 통합
- [ ] 직선 다발 저장 시스템
- [ ] 유사도 계산 알고리즘
- [ ] 창의성 조정 메커니즘

## 기술 스택

- **Python 3.8+**
- **NumPy**: 수치 계산
- **SciPy**: 과학 계산
- **Matplotlib**: 시각화
- **PyTorch**: 딥러닝 프레임워크
- **Transformers**: 기존 언어 모델 통합

## 설치 및 실행

```bash
# 저장소 클론
git clone https://github.com/yourusername/lineweave-codex.git
cd lineweave-codex

# 의존성 설치
pip install -r requirements.txt

# 기본 테스트 실행
python src/main.py
```

## 프로젝트 구조

```
lineweave-codex/
├── src/
│   ├── core/
│   │   ├── meaning_axis.py      # 의미 축 구현
│   │   ├── s_curve.py          # S형 곡면 모델링
│   │   └── noun_distribution.py # 명사 분포 시스템
│   ├── modules/
│   │   ├── module_system.py    # 모듈 시스템
│   │   ├── punctuation.py      # 문장부호 처리
│   │   └── cloud_module.py     # 구름 모듈
│   ├── llm/
│   │   ├── line_bundle.py      # 직선 다발 시스템
│   │   ├── similarity.py      # 유사도 계산
│   │   └── creativity.py      # 창의성 조정
│   └── main.py
├── tests/
├── examples/
├── docs/
├── requirements.txt
└── README.md
```

## 이론적 배경

이 프로젝트는 언어를 기하학적 구조로 해석하는 혁신적인 접근법을 제시합니다:

1. **공간적 언어 이해**: 언어를 3차원 공간에서의 방향성 네트워크로 모델링
2. **구조적 일관성**: 단어, 문장, 문단, 감정까지 동일한 원리로 설명
3. **창의성의 수학적 모델링**: 직선 방향 조정을 통한 창의적 표현 생성

## 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 연락처

프로젝트 링크: [https://github.com/yourusername/lineweave-codex](https://github.com/yourusername/lineweave-codex)

## 인용

이 이론을 연구에 사용하실 경우, 다음 형식으로 인용해 주세요:

```
LineWeave Codex: S형 직선 구조 기반 언어 모델 이론
https://github.com/yourusername/lineweave-codex
```

---

**"언어를 이해하는 모델이 아니라, 언어의 공간 속에서 방향을 찾아가는 모델"**
