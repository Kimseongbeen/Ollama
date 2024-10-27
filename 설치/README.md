1. 실행파일 다운로드

2. 환경변수 추가(C드라이브에 공간이 부족할 때)

사용자 변수 편집
OLLAMA_MODELS
변수 값 : 다른 드라이브의 OLLAMA 폴더


3. ngrok ollama 외부 포트
참고자료

https://github.com/ollama/ollama/blob/main/docs/faq.md#how-can-i-use-ollama-with-ngrok
https://github.com/ollama/ollama/issues/3215

ngrok http 11434 --url=(무료 도메인) --host-header="localhost:11434"