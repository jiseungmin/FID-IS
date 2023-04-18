## Fréchet Inception Distance(FID) / Inception Score(IS)  
GAN 모델에서 생성된 이미지 합성의 품질을 평가하기 위한 평가 지표이다.

## Fréchet Inception Distance(FID)  
생성된 이미지와 실제 이미지 간의 차이을 측정하기 위해 사용된다.  
FID가 낮을수록 생성된 이미지가 실제 이미지와 유사함을 나타낸다.

## Inception Score(IS)  
생성된 이미지의 퀄리티와 다양성을 측정하기 위해 사용된다.  
IS가 높을수록 생성된 이미지가 다양하면서도 질이 높을을 나타낸다.

## StyleGAN2-ADA FID  
![image](https://user-images.githubusercontent.com/98318326/232775473-e7e0cb87-87c7-4821-857a-54f47382ec63.png)  
StyleGAN2-ADA 학습된 모델에서 50000장을 뽑아 계산하였음.(왼쪽 orignal, 오른쪽 StyleGan2-ada)
![FID_Image](https://user-images.githubusercontent.com/98318326/232466544-733051c3-cd3b-4300-83f8-b7cf6621dfe2.png)  
FID : 40.39585332718843

## StyleGan2-ADA IS / Original-Image IS
Original Image (2000장)  
(1.64908, 0.14787318)  
avg = 1.64908  
stddev = 0.14787318  

StyleGan2-ada Result Image (2000장)  
(2.4132752, 0.12536855)  
avg : 2.4132752  
stddev : 0.12536855
