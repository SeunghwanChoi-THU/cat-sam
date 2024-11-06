

<modeling>
set_infer_img: 입력 이미지를 모델에 할당하여 임베딩(img_features, interm_features) 생성
infer


<Encoders>
Wrapper의 형태로, nn.Module을 상속받고 기존 SAM의 인코더를 불러온 뒤 필요한 기능을 추가하는 방식