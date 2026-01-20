# googLeNet


<img width="930" height="387" alt="image" src="https://github.com/user-attachments/assets/bb5af5ef-ca02-4e04-bdbb-0611ac807c58" />

### 특징
- googLeNet은 VGG처럼 깊은 구조를 만들기 위해 나왔는데 세로 뿐만 아닌 가로로 깊고 넓은 구조로 네트워크 만듦.
- 즉, VGG처럼 세로방향으로 깊은 네트워크가 아닌 세로, 가로 둘 다 깊게 만듦.
- 가로 방향으로 넓을 수 있었던 이유는 인셉션 구조를 활용해서임.

### 인셉션 모듈
<img width="451" height="250" alt="image" src="https://github.com/user-attachments/assets/c54cfc88-3c99-4f07-b750-88cd0cf91fc6" />

- 인셉션 구조는 다양한 크기의 필터를 병렬로 적용해 여로 스케일의 특징을 동시에 추출하게 만든 똑똒한 구조.

### 버틀렛 구조
<img width="442" height="237" alt="image" src="https://github.com/user-attachments/assets/81f6e68c-0b52-4fa0-81d2-74e823267be6" />

- 버틀렛 구조는 1x1 Conv를 해줘 채널의 수를 줄이고 비선형성 추가해주는 역할을 한다.

### global average pooling

<img width="293" height="337" alt="image" src="https://github.com/user-attachments/assets/31082fd8-74e3-4599-b84e-0629fca9b756" />


### Auxiliary classifier
<img width="310" height="341" alt="image" src="https://github.com/user-attachments/assets/5e55d2b0-40d6-46f0-b8db-566d2268cfe6" />
