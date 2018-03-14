# Exporting

> 개발자에게 이미지 리소스를 제공하기 위해 내보내는 행동

- 네이밍 컨벤션
    - 대문자 금지
    - btn(종류)_home(화면)_start(이름)_n(상태)
    - n(normal), p(pressed), f(focus), d(disable),sel(selected),desel(deselect)
- 개별 리소스 export
    - Preset을 통해 Android / iOS 등과 같이 사용가
    - Size : 축적계수
    - Prefix/Subfix : @2x와 같이 iOS 에 대응하기 위해 사용함
    - Format : 포맷
    
- 소스 내보내기 
    CSS 속성 : 오브젝트 선택 > 우클릭 > Css Attributes
    
- 아트보드 내보내기 : 아트보드 자체를 내보내고 디자인을 공유할 떄 유용함
    - 바탕화면 드래그 앤 드랍으로도 가능

- 리소스 내보내기 (전체)
    - File > Export Artboard to PDF 를 통해 내보낼 수 있음
    
    
# 기타스킬 

- Slicing (조각내기) : Object를 Exporting이 가능한 영역으로 만들어줌
- Naming (이름 지정) : cmd + R 을 통해 이름을 재정의
    - 이름을 정해줄때 home/img와 같이 정해주면 폴더링이 자동으로 됌
- Arrange 
    - 드래그 앤 드랍
    - opt + cmd + 방향키위 : 한 단계의 위로 올리기
    - ctr + opt + cmd + 방향키위 : 맨 위로 올리기
    - opt + cmd + 방향키 아래 : 한 단계 아래로 내리기
    - ctr + opt + cmd + 방향키 아래 : 맨 아래로 내리기
    
- Round to Pixel : 오브젝트에 가장 근접한 픽셀에 맞춰줌 (cmd + p 를 통해 픽셀뷰로 볼 수 있음)
    - Arrange > Round to Pixel 
    - 복잡한 오브젝트를 가지고 있는 경우 > 계층별로 직접 지정해야함
    
- Pixel Fitting : 가장 근접한 픽셀로 작업함
    - preference > Layer > Pixel Fitting 
    
        

    