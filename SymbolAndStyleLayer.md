# Shared Style Layer

> 반복되는 스타일을 미리 컴포넌트화 시켜 다른 레이어에 쉽게 적용할 수 있도록함

- 텍스트 : 상단 Insert에 Styled Text를 이용해 바로 접근가능

## Symbols

> 규칙이 동일하게 적용된 디자인을 재사용할 수 있도록 하는 레이어 유형. 컴포넌트의 개념 대표적으론 스테이스 바

- Master 수정 (더블클릭) : 심볼의 최상위 객체를 수정함 ( 해당 심볼로 생성된 모든 객체가 바뀜 )
- 심볼 재정의 (인스펙터 창의 Override에서 수정) : 해당 객체만 수정 
- 동일한 높이와 넓이를 가지면, 동일한 패밀리로 인식하여 스케치에서 변경할수 있도록 제공해줌

- 심볼을 제작시 주의 점
    - 라인 오브젝트 : border가 아트보트 바깥으로 나갈수 있음 -\> inside 로 설정
    - 그림자를 포함한 경우 : 그림자가 아트 바깥으로 나감 
        1. 아트보드의 크기를 늘리는 방법
        2. 추가적인 뷰를 만들고 그림자를 포함해서 심볼로 만듬
    - 아이콘을 심볼로 만드는 경우 : 심볼의 크기가 다를 수 있음
        - 추가적인 뷰(래퍼)를 만들어 심볼을 만듬
        
- icon/(이름) : 이 방법으로 심볼을 만들면, 같은 크기의 심볼끼리 폴더링됌(*)
- convet outline 이 된 icon 위에 컬러 박스를 얹고, 마스킹을 해주면, 색상과 아이콘을 쉽게 바꿀수 있음.
- Symbol은 Symbol 페이지로 넘어가서 make expotable을 눌러 익스포팅함
