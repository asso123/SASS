# SASS 사용 거의 안함 SCSS를 사용한다  scss->사스라고 부름

![image](https://github.com/asso123/SASS/assets/129017021/0fe8e75d-3436-4833-9a91-ab0f9eb4412b)
-비주얼스튜디오에서 설치하기

#scss 컴파일 (하단에 Watching cscc 눌리기)
![image](https://github.com/asso123/SASS/assets/129017021/48b3a659-a370-4bc4-8884-aadf5a01cdad)

#css위치변경
![image](https://github.com/asso123/SASS/assets/129017021/3aac1b87-1986-49ef-ad93-d0471a2f84fa)
-셋팅->sass 검색 후 조금 내려서 아래 문구 찾기
```
Live Sass Compile › Settings: Formats
Set your exported CSS Styles, Formats & save location.
->edit in settings.json 클릭!

#savePath:null이면 scss파일과 같은 위치에 style.css가 생긴다
![image](https://github.com/asso123/SASS/assets/129017021/0c525bc8-a240-4cee-9639-9395fa1359a5)

요로케 뜬다

#~은 style.css를 의미, /는 style.css가 있는 폴더
![image](https://github.com/asso123/SASS/assets/129017021/04635876-0dd9-41e9-ad93-418ffba23e3a)

#scss파일이 있는 폴더의 상위요소에 생성
![image](https://github.com/asso123/SASS/assets/129017021/9e4289e9-60fb-4a40-a911-4299ce7c7631)

#주석처리방법
// 주석처리방법은 css로 컴파일되지 않는다
/**/ 주석처리방법은 css로 컴파일 된다

#변수만들기 -> $로 시작함,(영문, 숫자,-,_)만 사용 할 수 있음. 숫자로 시작할 수 없음

#partials(파샬)
-관련된 것따리 묶어서 분리/ 소스에 반복되는 부분ㅇ=들을 분리 분산시켜서 모듈화 시키는 기능

*partials(파샬)의 파밍명은 _로 시작하며
*불러들일때는 @import '파일명' 이때 파일명에 _는 포함시키지 않고 확장명도 포함시키지 않는다

cscc는 _로 시작하는 파일은 컴파일하지 않는다





