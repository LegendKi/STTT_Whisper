# Gradio를 활용한 다기능 번역 모델 배포 (with whisper)
Open AI의 Whisper를 활용해 Gradio 인터페이스 상에서 마이크 녹음, 음원 파일 업로드, 유튜브 url을 입력으로 번역을 수행하는 시스템을 구현하였습니다.

## 팀원구성
- 기현우
- 양소현
- 이아윤
- 서경호

## 번역 프로세스

![image](https://github.com/LegendKi/STTT_Whisper/assets/90371644/c15f9ede-6c23-4433-8af8-60cbf062103a)

마이크로 직접 녹음, 음원 파일 업로드, 유튜브 url input을 gradio에서 업로드하고 번역 도착 언어를 선택하면 Whisper로 STT와 Translate를 수행하여 detect된 음성의 언어와 번역된 텍스트가 gradio 인터페이스에 출력되는 시스템을 제작하였습니다.

https://github.com/LegendKi/STTT_Whisper/assets/90371644/d150e5f3-09c0-4637-bfc3-4a4b8c962afa

## 개발 기간
- 2024.4.9 ~ 2024.4.16

## Requirements
- python == 3.10.14
- pytube == 15.0.0
- gradio == 3.50.2
- ffmpeg == 7.0
