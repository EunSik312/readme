# readme
# 📘 AI 학습 정리

## 1. About GitHub, Markdown, Colab
- [GitHub 사용법](#github-사용법)
- [Markdown 문법](#markdown-문법)  
- [Colab 기초](#colab-기초)

## GitHub 사용법

### ✅ GitHub 계정 만드는 순서 (2025년 기준)

1. **웹 브라우저 열기**
   크롬(Chrome), 엣지(Edge), 사파리(Safari) 중 편한 걸 사용하세요.

2. **GitHub 웹사이트 접속**
   주소창에 아래 주소를 입력하고 Enter 누르세요: https://github.com

3. **회원가입 시작하기**
   화면 오른쪽 위 또는 중간에 있는 Sign up 버튼 클릭

4. **이메일 주소 입력**
   평소 자주 사용하는 이메일을 입력

5. **비밀번호 만들기**
   영어 대문자, 소문자, 숫자, 특수문자를 섞어 안전하게!
   예시: Git1234!hub

6. **사용자 이름(Username) 정하기**
   나만의 고유한 이름을 지어요 (다른 사람이 쓰고 있으면 불가)
   - 예시: jetsunmom, sungsookjang66 등
   - 영어, 숫자, 하이픈(-) 가능 (띄어쓰기 ❌)

### ✅ Repository 만들기 순서

1. **GitHub에 로그인 후 New Repository 클릭**
2. ![new](https://github.com/user-attachments/assets/3481a680-f677-403b-be8c-1fe59d5aa7cb)

3. **Repository 이름 입력**
4. **Public/Private 선택**
5. **README.md 파일 생성 체크**
6. **Create repository 버튼 클릭**
   
![create_repository](https://github.com/user-attachments/assets/8c2eb16b-8dfc-465a-88cd-d35770d12df0)
  
## Markdown 문법
# 제목
# 제목 1
## 제목 2
### 제목 3
#### 제목 4

# 강조
*기울임* 또는 _기울임_  
**굵게** 또는 __굵게__  
***굵고 기울임***  

# 목록
- 항목 1
- 항목 2
  - 하위 항목
* 또는 * 도 사용 가능

# 순서 있는 목록
1. 첫 번째
2. 두 번째
3. 세 번째
# 링크 메세지
[텍스트](https://example.com)
# 이미지
![대체 텍스트](https://example.com/image.png)
# 코드
###`코드`
# 여러 코드
###```언어
여러 줄의 코드
# 수평선
---
또는
***
# 인용문
> 인용문입니다.
>> 중첩 인용도 가능
# 체크리스트
- [ ] 할 일 1
- [x] 완료한 일



## Colab 기초  
![image](https://github.com/user-attachments/assets/6889f83e-4e58-44dc-acd9-b655ee17aa38)
![image](https://github.com/user-attachments/assets/928bc75e-f1f1-4a98-9e62-b567b2bba193)
✅ 코랩 기본 개념
항목	설명
실행 환경	웹 기반 파이썬 실행기 (Google 서버에서 실행됨)
파일 확장자	.ipynb (Jupyter Notebook 파일)
저장	Google Drive에 자동 저장 가능
장점	파이썬 설치 불필요, GPU/TPU 무료 지원

✅ 코랩 시작하기
https://colab.research.google.com 접속

새 노트북 만들기: 파일 → 새 노트북

코드 입력하고 실행:

셀에 파이썬 코드 입력

Shift + Enter 또는 왼쪽 실행 버튼 클릭

✅ 기본 사용법
📌 코드 셀 vs 텍스트 셀
코드 셀: 파이썬 코드 실행

텍스트 셀: Markdown 형식으로 설명, 수식 등 작성 가능

📌 코드 예시
python
복사
편집
Hello World 출력
print("Hello, Colab!")
📌 텍스트 셀 Markdown 예시
markdown
복사
편집
# 제목
## 부제목
**굵게**, *기울임*, `코드`

수식: $y = mx + b$
✅ 파일 다루기
python
복사
편집
from google.colab import files

파일 업로드
uploaded = files.upload()

파일 다운로드
files.download("example.txt")
✅ 라이브러리 설치
python
복사
편집
!pip install pandas
import pandas as pd
!는 셸 명령어 실행을 의미합니다.

✅ GPU 사용 설정
런타임 → 런타임 유형 변경

하드웨어 가속기: GPU 또는 TPU 선택
(여기에 Colab 내용 작성)

## 2. About Python3
- [Python basic](./docs/python3.md)
- https://www.w3schools.com
https://docs.google.com/document/d/19VkSDEzg3EgwLROp6Z0-3Bdayx0T_X4vmB3hQZFbOxY/edit?tab=t.0
## 3.  data structure / data sciencs

- [데이터 구조 개요](./data_structures.md)
- [Pandas](./pandas.md)
- [Numpy](./numpy.md)
- [Matplotlib](./Matplotlib.md)

## 4. Machine Learning

- [Machine Learning Basic](./ml_basic.md)
- [모델 훈련 및 평가](./ml_test.md)

## 5. OpenCV

- [OpenCV Basic](./OpenCV_basic.md)
- [이미지 처리](./image_test.md)

  
## 6. CNN(Convolution Neural Network
- [CNN_Basic](./CNN_basic.md)
- [CNN_자율주행 관련 코드](./cnn_test.md)

## 7. Ultralytics
- [Ultralytics_Basic](./Ultralytics_basic.md)
- [YOLOv8](./YOLOv8_test.md)
- [YOLOv12](./YOLOv12_test.md)
  
## 8. TensorRT vs PyTorch 
- [PyTorch_Basic](./PyTorch_basic.md)
- [TensorRT](./TensorRT_test.md)
- [YOLOv12](./YOLOv12_test.md)

## 9. TAO Toolkit on RunPod
- [TAO_사용법](.TAO_install.md)
- [TAO_Toolkit](.TAO_Toolkit.md)

## 10. 칼만필터, CARLA, 경로 알고리즘
- [kalman](.kalman.md)
- [CARLA_simulator](.CARLA.md)

## 11. ADAS & (ADAS TensorRT vs PyTorch)
- [adas_basic](.adas_basic.md)
- [TensorRT vs PyTorch 비교](.vs.md)
- 
