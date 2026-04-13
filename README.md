# Tier-Game

분반 101 프론트엔드 6주차 팀 과제 및 개별 과제

---

여기서 pa8e를 확인하세요

[프랜차이즈 카페 브랜드 티어 리스트](https://parkjongbin0520-spec.github.io/tiergame/)

---

## 팀 프로젝트 할 일

커피 프랜차이즈 전문점 선호도 조사를 위한 드래그 앤 드롭 티어 메이커 만들기

1. 팀원 공통 할 일
  
  - 커피 프랜차이즈 이미지 준비 (1인당 2~3개 총 10개 내외)
    
  - 준비한 이미지는 저장소 내 `images` 폴더에 업로드
    
  - `tier-maker-member.html`의 아이템의 id 값을 고유하게 변경하고 이미지 태그와 항목 이름을 작성 후 저장소에 업로드
    
2. 팀장 할 일
  
  - 뼈대 코드 `tier-maker.html` 를 팀원 코드인 `tier-maker-member.html` 코드를 가이드하여 재구성
    
  - **flexbox** 속성을 활용하여 레이아웃 구성 (아이템 정렬 및 이동을 위한 구조)
    
  - 드래그 앤 드롭 기능이 정상 작동하는지 검토
    

---

## 팀원 코드 수정 방법

코드에 들어가면 이렇게 되어있습니다

```html
<!-- 팀원 아이템 시작 (주의: id 값은 팀원마다 고유하게 변경하세요) -->
<div
  class="item"
  draggable="true"
  ondragstart="drag(event)"
  onmouseover="showPreview(this)"
  id="item_yourname_1"
>
  <img src="./images/item_1.jpg" alt="항목 이름" />
  <div class="item-name">항목 이름 1</div>
</div>

<div
  class="item"
  draggable="true"
  ondragstart="drag(event)"
  onmouseover="showPreview(this)"
  id="item_yourname_2"
>
  <img src="./images/item_2.jpg" alt="항목 이름" />
  <div class="item-name">항목 이름 2</div>
</div>
<!-- 팀원 아이템 끝 -->
```

- ID 값이 `item_yourname_n` 으로 되어있는데 `megacoffee` (예시)로 바꾸거나 다른 이름으로 수정한다
  
- `img` 태그에서 `src` `alt` 값을 주제에 맞게 변경한다. (.png 깃허브에 업로드)
  
- 항목을 주제에 맞게 이름을 변경한다
  
- 저장소에 누가 올렸는지 알아볼 수 있게 업로드한다
  

### 코드 업로드 방법

1. 깃허브 저장소 `<> Code ▼` 좌측 `+` 버튼을 눌러 `Upload files` 선택
  
2. 파일 드래그 앤 드롭하거나 선택
  
3. Commit changes 선택하여 업로드 완료
  

### 이미지 업로드 방법

1. 깃허브 저장소 내 폴더 클릭하여 접근
  
2. 폴더 내 우측 상단에 `Add file ▼` 에서 `Upload files` 선택
  
3. 이미지 드래그 앤 드롭하거나 파일 선택
  
4. Commit changes 선택하여 업로드 완료
