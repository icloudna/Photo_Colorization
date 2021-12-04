
# 2021년 2학기 흑백사진 colorization 팀 프로젝트 with GAN

## 0. 노션 주소
https://www.notion.so/2021nlpsummary/CV-b4649d0a4b30471aaf42af1f717446d6

## 1. 스터디

팀원 모두 Computer Vision을 잘 알지 못하는 상태였기에, GAN 모델을 중점적으로한 CV 스터디 4주 간 진행

(i) 실전! GAN 프로젝트 Chapter 1,2,7,8 리뷰 및 코드 실습

(ii) Colorization 관련 논문 리뷰

Generative adversial nets (2014)

pix2pix : Image-to-Image Translation with Conditional Adversarial Networks (2016)

CGAN : Conditional Generative Adversarial Nets) (2014)

스터디 진행 후, 프로젝트 주제 선정

## 2. 프로젝트 (~2021.12.31)

(1) COCO DATASET 사용하여 training + GAN

![image](https://user-images.githubusercontent.com/87663692/144720093-44922a68-39a3-4a84-92f8-8334ff467772.png)

: 인물 컬러화가 잘 되지 않는 편. 다만 2번 모델보다 풍경 컬러화는 잘 되는 편

(2) ImageNET DATASET 사용하여 training + GAN with U-net 모델

![image](https://user-images.githubusercontent.com/87663692/144720094-fe0eb8c8-392b-49ce-8843-7455e6b74161.png)

: 1번 모델과는 달리 인물 컬러화가 매우 잘됨 

현재진행형중!!

-> 모델 epoch 100 시도

-> 두 모델간 차이가 어디에서 기인하는지 분석

-> 학회원들 흑백사진 수집





