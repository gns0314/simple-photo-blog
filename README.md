# simple-photo-blog
- https://picsum.photos/ api를 활용하여 랜덤하게 이미지를 30개 까지 보여주고 30개가 넘어가면 
``` confirm(
      "이미지가 30개 찼습니다. 모든 사진을 지우시겠습니까?"
    );
    if (confirmed) {
      gridContainer.innerHTML = "";
    }
```
을 통해 확인 클릭시 초기화 시켜주고, 취소 클릭시 이미지를 그대로 두게됩니다.
