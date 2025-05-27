# MaruChat (まるチャット / 마루챗)

## 🇰🇷 개요 (Korean)

**MaruChat**은 실시간 방송 중 발생하는 상황을 관찰하여,
마치 실제 시청자처럼 자연스럽고 개성 있는 채팅을 자동으로 생성하는 AI 챗봇입니다.

OBS나 방송 플랫폼에 종속되지 않으며, 화면, 오디오, 텍스트 등 다양한 정보를 분석하여
게임 승리, 실수, 후원, 클러치 장면 등 다양한 상황에 맞는 리액션을 생성합니다.

### 🔧 주요 기능

* 방송 중 시각/청각 정보 분석
* 실제 시청자처럼 자연스러운 채팅 생성
* AI 캐릭터 프리셋 지원 (말투, 성격 설정 가능)
* Twitch, YouTube, 기타 플랫폼 유연한 연동 예정

---

## 🇺🇸 Overview (English)

**MaruChat** is an AI chatbot that observes what’s happening during a livestream
and generates natural, characterful chat messages as if it were a real viewer.

It doesn’t just echo the streamer — instead, it reacts to the scene, gameplay, or event
with appropriate and lively comments that enhance viewer engagement.

### 🔧 Key Features

* Visual/audio input detection from live streams
* Human-like chat generation with personality presets
* Designed to be platform-agnostic (Twitch, YouTube, etc.)
* Expandable for use with various broadcast sources

---

## 🇯🇵 概要 (Japanese)

**MaruChat（まるチャット）** は、ライブ配信中の状況を観察し、
まるで本物の視聴者のように自然でキャラクター性のあるコメントをリアルタイムで自動投稿するAIチャットボットです。

配信者の代弁ではなく、配信の流れに応じたリアクションや応援コメントなどを投稿します。

### 🔧 主な機能

* 映像・音声など配信中の情報を解析
* 視聴者目線でのリアクションコメント生成
* 性格や口調が選べるキャラクタープリセット
* Twitch / YouTubeなどに対応（予定）

---

## 💬 사용 예시 / Sample Scenarios

> 🎮 보스 클리어 → “와! 방금 그거 진짜 쩔었어!!”
> 💸 후원 발생 → “え、今のスパチャすごっ！まるもドキドキした〜！”
> 😱 실수 장면 → “oh noooo ㅋㅋㅋㅋ 이건 편집각”

---

## 📁 프로젝트 구조

```plaintext
MaruChat/
├── src/              # 핵심 코드 모듈
│   ├── detector/     # 방송 상황 인식
│   ├── responder/    # AI 문장 생성
│   └── platform/     # Twitch / YouTube 연동
├── README.md
└── requirements.txt
```

---

## 🧩 향후 계획

* 커스터마이징 가능한 프롬프트 UI 개발
* 스트리머 스타일에 따른 챗봇 성격 세분화
* 감정 인식 및 상황별 반응 정확도 향상
* 클라우드 배포 / SaaS 연동 등 서비스화 준비
