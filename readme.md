## Classic_MIDI : 19개 작곡가들의 악보 분석

### Lily pond를 이용해서 작곡 파일을 분석, 새로운 악보를 만듭니다
### 데이터셋 원 출처 : kaggle classic midi

#### 1) 쇼팽 가곡의 음계 확인
#### 음계를 학습한 LSTM으로 새롭게 제작

##### 악보 예시 (100 노트)
![image](https://user-images.githubusercontent.com/114221089/217759092-f84a206f-8cc7-4787-a2c3-22434e9f06e2.png)

#### 2) 리스트 가곡의 음계 학습

##### 악보 예시 (150노트) 
###### * 위에서 다운로드 가능(mid)

![image](https://user-images.githubusercontent.com/114221089/219665880-f4a6e8ef-7d4f-4269-98a1-bd359ff7d691.png)

#### 3) 알베니스 음계 학습
##### 실패로 확인

![image](https://user-images.githubusercontent.com/114221089/221347064-3544ad60-23c8-455b-9db3-e3b391dcf6fc.png)


###### 과적합 되었다 vs threshold에 빠진 것이다.

#### 4) 베토벤 음계 학습
##### epoch 150회시 아래 내용

![image](https://user-images.githubusercontent.com/114221089/221347109-8e1a6d32-dfbb-4796-86f8-b5748396207d.png)


#### 수정중
