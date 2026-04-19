# 박진형 | AI Engineer

https://portpolio.tmpark.space/

AI 모델 학습/최적화부터 엣지 디바이스 배포까지, 온프레미스 환경에서의 AI 솔루션을 개발하고 있습니다.

현재 **루커스(Lukus) AI연구소**에서 Edge AI 시스템 및 음성 AI 파이프라인을 설계/개발하고 있습니다.

## Tech Stack

**AI / ML** : PyTorch · YOLOv5/v8 · Hugging Face · Qwen · LoRA · llama.cpp · GGUF · Ollama · Faster-Whisper · CTranslate2 · Silero-VAD · Piper TTS

**Backend** : Python · FastAPI · aiohttp · Docker · WebSocket · MQTT · SQLite · Nginx · PM2 · FastMCP

**Edge AI** : NVIDIA Jetson (Orin/Nano) · Kneron KL630 · Rockchip RK3588 (RKNN) · CUDA · ONNX · onnx-graphsurgeon · ESP32 / ESP-IDF

## Projects

> 상세 프로젝트 문서는 [**Portfolio**](https://github.com/tommyjin2894/portfolio) 레포에서 확인할 수 있습니다.

| Project | Description |
|---------|-------------|
| AIBOO Edge AI 음성 비서 | 공공기관(보훈부) 노인 케어 — Jetson Orin 기반 STT/LLM/TTS + IoT 센서 연동, 단독 개발 |
| Multi-NPU 모델 포팅 | Kneron KL630 + Rockchip RK3588 객체 탐지 모델 양자화/포팅 (int8/16 mix, ONNX 그래프 편집) |
| Piper TTS 한국어 Fine-tuning | `ko_KR-korean-medium` 베이스 추가 학습 — 학습 재개 자동화 + 15개 ckpt 정성 비교 |
| Fire/PPE Detection | YOLOv5 6클래스 학습 + RTSP 멀티 스트림 Streamlit 대시보드 (mAP@0.5 84.7%) |
| Qwen LoRA Fine-tuning | 합성 데이터 → LoRA → GGUF Q4_K_M → Ollama 로컬 배포 풀 파이프라인 |
| MCP 도구 릴레이 서버 | FastMCP 기반 3계층 WebSocket 릴레이 + AES 토큰 인증 + 자동 재연결 |

## Contact

- Email: tommyjin2894@gmail.com
- LinkedIn: [linkedin.com/in/진형-박-30ba07311](https://www.linkedin.com/in/진형-박-30ba07311/)
- HuggingFace: [huggingface.co/tommyjin](https://huggingface.co/tommyjin)
