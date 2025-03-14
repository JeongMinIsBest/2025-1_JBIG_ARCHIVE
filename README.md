# 2025-1학기 JBIG 주차별 학습 코드 아카이브 🔥

## 0. Colab Seaborn, Matplotlib 한글 깨짐 현상 해결

- 나눔 폰트 설치
```
!sudo apt-get install -y fonts-nanum
!sudo fc-cache -fv
!rm ~/.cache/matplotlib -rf
```
</br>

- 폰트 설정
```
import matplotlib.pyplot as plt
plt.rc('font', family='NanumBarunGothic') 
plt.rcParams['axes.unicode_minus'] =False
```
</br>

출처 : [구글 코랩(colab) seaborn, matplotlib 한글 깨짐 현상 해결방법](https://giveme-happyending.tistory.com/192)
