# 안녕하세요! 저는 윤상민입니다.  

## 자기 소개  
저는 윤상민이라고 합니다. 1995년 1월 29일에 태어났고 올해 26세입니다.  
명덕외국어고등학교 프랑스어과를 졸업했고, 서울대학교에서 불어불문학과 전기정보공학을 복수전공했습니다.  
삼성전자 학부 연구장학생을 거쳐, 현재는 삼성전자 글로벌기술센터(GTC)에서 Jr. Computer Vision Engineer로 일하고 있습니다.  
제가 일하고 있는 GTC 요소기술팀은 삼성전자의 Smart Factory 원천 기술을 연구/개발하는 조직입니다.  
제가 속한 센서 파트에서는 기계공학 엔지니어, 전기/컴퓨터공학 엔지니어, 화학공학 엔지니어들이 힘을 합쳐 멋진 것들을 만듭니다.   
특히 Vision을 담당하는 제 소파트는 제조 라인에서 작업자가 수행하는 Object Detection 및 Classification 작업을 대체하는 검사 모듈을 개발하고 있습니다.  

## 엔지니어로서의 좌우명  
내 이름을 걸어도 부끄럽지 않은 멋진 것을 만드는 데 모든 것을 바치자.   

## 저는 이런 것들을 잘 할 수 있습니다.      
- Python(주력 언어), Java(https://github.com/sanspareilsmyn/java-study), Matlab(기초전자기학 및 연습 실습 조교)   
- 딥러닝과 머신러닝에 대한 지식  
- Tensorflow (https://github.com/sanspareilsmyn/tf-basic-code)  
- Scikit-Learn  
- 최상급 영어/프랑스어 회화 및 문서 작성 능력 (국제기구 인턴 경험)  
- 논문을 통한 지식 습득 & 핵심 내용을 나의 언어로 정리하는 능력 (https://github.com/sanspareilsmyn/what-i-have-read)  
- 컴퓨터공학 전반에 대한 지식 (https://github.com/sanspareilsmyn/tech-interview-question)  

## 저는 이런 것들을 만들어 보았습니다.
### 1. News Title Autocompletion and Transformer-based News Summarization (https://github.com/sanspareilsmyn/news-project)  

"뉴스 서비스를 사용하는 유저들이 어떻게 하면 자신이 원하는 뉴스를 더 빠르게 볼 수 있을까?"라는 고민에서 시작된 프로젝트입니다.   
퇴근하고 NLP를 혼자 공부하던 차에 공부한 것을 실생활과 밀접한 주제에 응용해보기 위해 이러한 주제를 골랐습니다.   
본 프로젝트를 통해 다음 2가지 기능을 구현해보았습니다.  
첫째, 유저가 검색어를 입력하면 그에 해당되는 기사 제목을 자동으로 완성하는 기능  
둘째, 후보 기사들의 본문을 Transformer 기반의 알고리즘으로 요약해서 완성된 제목과 함께 보여주는 기능  
<img width="499" alt="스크린샷 2020-10-24 오후 6 40 25" src="https://user-images.githubusercontent.com/52681837/97078646-7d341400-1628-11eb-87c3-394c8bb7f616.png">  

### 2. Friends Recommendation System with Star Wars Social Network (https://github.com/sanspareilsmyn/kaggle-starwars)  

[Node2Vec](https://arxiv.org/abs/1607.00653)이라는 멋있는 페이퍼를 읽고 영감을 받아서 만들어 본 프로젝트입니다.  
그래프 형태의 데이터로부터 Feature Vector를 추출하는 이 알고리즘을 스타워즈 대본에 적용해보았습니다.  
같은 장면에 몇 번 등장하는 지에 대한 Interaction dataset과 인물이 서로를 몇 번 대사에서 언급하는 지에 대한 Mention dataset을 이용해서  
인물관계를 가중치를 지닌 그래프를 변환하였고, 다시 이를 바탕으로 Node 별 Feature Vector를 추출했습니다.  
최종적인 결과물은 추출한 특성 벡터의 L2-Norm 연산을 통해 가장 가까운 인물 5인을 추려내는 것입니다.  
<img width="495" alt="스크린샷 2020-10-13 오후 8 22 55" src="https://user-images.githubusercontent.com/52681837/95854527-0da16780-0d92-11eb-980f-9c09e5a4ac2d.png">  

### 3. Data Acquisition and Processing Algorithm of Embedded Vision Sensor (https://github.com/sanspareilsmyn/samsung-summer-project)  

삼성전자 학부 연구장학생 여름 프로젝트입니다.  
입사 전 영상처리의 기본 내용과 기본적인 머신러닝 테크닉에 대해 공부해보면 좋겠다는 멘토님의 의견을 수렴해 주제를 정했습니다.  
차영상을 통해 물체의 움직임을 감지하는 알고리즘을 OpenCV로 구현한 뒤, 물체가 움직인 것으로 추측되는 영역에 대해 Histogram of Gradient(HoG)를 Feature로 추출했습니다.   
이를 Multi-class SVM을 통해 Object Classification을 구현해보는 굉장히 클래식한 Machine Learning 프로젝트였습니다.  
![5](https://user-images.githubusercontent.com/52681837/93693501-84ed2e00-fb3b-11ea-9a26-87d73f8b742b.JPG)  

### 4. Implementation of Deep-Learning-Based Active User Detection(AUD) Layer (https://github.com/sanspareilsmyn/lab-intern-project)  

서울대학교 이동통신연구실에서 이광복 교수님의 지도 하에 학부 4학년 때 학부연구생을 수행하며 만들어 본 결과물입니다.  
Autoencoder를 응용한 Active User Detection(AUD) Layer를 만드는 것을 목적으로 했습니다.  
Transmitter에서 N개의 장치에서 발생한 신호가 M차원의 특성 벡터로 변환된 뒤 Channel Layer를 거쳐 Receiver에 송신될 때,  
Receiver에서 Transmitter의 신호를 복원하는 이 문제를 Autoencoder의 형태로 모델링할 수 있다는 것이 핵심 주제였습니다.  
![image](https://user-images.githubusercontent.com/52681837/93707988-ce567100-fb6d-11ea-831b-a15d4527537d.png)  

## Contact  
E-mail : sanspareilsmyn@gmail.com  
Linkedin : https://www.linkedin.com/in/sangmin-yoon/
