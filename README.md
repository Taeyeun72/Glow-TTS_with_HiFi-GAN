# Glow-TTS_with_HiFi-GAN

- Data Preprocessing.ipynb: 데이터 전처리
- Example.wav: Glow-TTS + HiFi-GAN.ipynb로부터 생성한 TTS Sample
  - 이 파일은 Glow-TTS를 batch_size=32로 337k step, HiFi-GAN을 batch_size=4로 400k step 학습하여 만든 TTS 모델로부터 생성되었습니다.
  - Text-to-Speech.pdf에서 제공되는 데모와는 다소 다른 모델입니다.
  - RTX 4090으로 Glow-TTS를 2~3일, HiFi-GAN을 2~3일 학습시켰습니다.
- Glow-TTS + HiFi-GAN.ipynb: Glow-TTS와 HiFi-GAN을 구현한 모델 두 개를 약간 수정하여 합친 최종 TTS 모델 구현
- Text-to-Speech.pdf: 2023년 1학기 서울시립대학교의 캡스톤디자인 최종 발표때 사용한 ppt 자료
