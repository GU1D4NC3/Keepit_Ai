# 식단 영양소 계산 모델
### 메인 코드 : vision_api.ipynb
1. vision api를 사용하기 위한 인증키인 json 파일 경로 설정을 해줘야합니다.
   
```os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = '여기에 json 파일 경로를 입력해주세요'```

2. 모델을 돌리기 위한 이미지 파일 경로 설정을 해줘야 합니다.

```file_name = os.path.abspath('여기에 이미지 파일 경로를 입력해주세요')```

-----
### output.txt
- vision api를 사용해서 이미지 내의 객체를 검출한 결과를 txt 파일로 저장합니다.
-----
### nutrient_info.json
- vision api에서 검출된 객체의 영양소 정보를 저장해놓은 json 파일입니다.
- 여기서 감지된 객체 정보만을 가져와서 영양소를 계산합니다.

---
# 진통 주기 계산 모델(알고리즘)
### sufficient.ipynb
- 진통 주기에 대한 의학적 정보를 바탕으로 진진통과 가진통을 구별하고 진통을 계산합니다.
