# GAN

##### 정의

- Generative Adversarial Network
- 서로 대립하는 두 신경망을 경쟁시켜가며 결과물 생성 방법을 학습
- 위조지폐범과 경찰 (by 굿펠로우)

##### GAN 기본 구조

- 실제 이미지 -> 구분자(Discriminator)
- 생성자(Generator) -> 가짜이미지 -> 구분자

=> 생성자는 구분자를 속이고, 구분자는 생성자가 만든 이미지를 최대한 가짜라고 구분하도록 훈련

##### 예

- 사진을 고흐 풍 그림으로 그려지기
- 선으로만 그려진 만화 자동 채색
- 모자이크 없애기
- 자연어 문장 생성

