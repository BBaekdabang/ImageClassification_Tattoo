# ImageClassification_Tattoo
# 타투 종류 분류 프로젝트
<img width="800" img height="400" src="https://user-images.githubusercontent.com/113493692/211786927-691f5419-a1da-42e0-bac4-03fdb7dd8825.png">

#### 데이터셋 : Google Image Crawling

프로젝트 기간 : 2022.08.08. ~ 2022.08.19.

---

# 1. Subject
- 타투 입문자들이 늘어나는 반면 얻을 수 있는 정보에 대한 접근이 제한적
- 이미지 인식을 통한 타투 스타일 분류
- 입문자도 접근이 용이한 타투 플랫폼 구축

# 2. Dataset

<img width = '1000' img height = '400' src = 'https://user-images.githubusercontent.com/113493692/211788206-a331ec9b-a687-4b9a-98b6-d893893eeda9.png'>

Google Image를 통해 각 카테고리 별 1000장씩 Crawling

# 3. Model

<img width = '1000' img height = '400' src = 'https://user-images.githubusercontent.com/113493692/211788924-a4e2cc51-e0bd-40c8-b1a2-116e0844a550.png'>

## 3-1. Model Handling


AlexNet | VGG16/19 | ResNet50 | ResNet152
------------|------|-------|-----|
-Dense Change| -Transfer Learning | -Transfer Learning | -Transfer Learning
|| -Dense Change | -Dense Change | 
|| -ReduceLROnPlateau | -ReduceLROnPlateau | 

## 3-2. Result

- AlexNet
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211792434-8f185973-8dc9-434d-9dfa-14ed79ccabca.png'>

- VGG16/19
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211792784-b68f7236-bce9-4b0f-9c9c-15549aeff818.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211792805-22dbf8dd-14ee-41ba-a259-938ffad07b3e.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211792832-c0c8562f-612c-401a-b60e-e32f4c2f37d3.png'>

- ResNet50
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211793571-3ee5ddf5-243b-4b9d-8da9-31406381b08a.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211793605-e43de9d7-a9c6-41b5-861b-3ae093034818.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211793636-b840e404-b27b-48bf-8098-eced87be5813.png'>

- ResNet152
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211793977-33d6a77f-f060-4439-a80c-a4d6ede97496.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211794224-2b9f2b00-f2b8-43ca-b835-c9e23ddb767f.png'>
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211794050-b28430f4-cdde-41ef-9616-e78ecb28e836.png'>

# 4. Summary
<img width = '1000' img height = '450' src = 'https://user-images.githubusercontent.com/113493692/211794520-0bf35a7b-f0be-4610-a84a-b6f84b7c5da4.png'>
