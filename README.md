# v1-split-keyboard
[V1] 나만의 키보드 만들기

## 필요 기능
- 분할 키보드
- 텐키리스(87키) 형태
- B 키가 양쪽에 달려 있어야 함
- 상단에 커스텀 가능한 매크로 키 배열
  - 로지텍 G913 TKL 참고 (제품링크 : https://www.logitechg.com/ko-kr/products/gaming-keyboards/g913-tkl-wireless.html)
  - F1 ~ F12 바로 위에 배치할 계획
- 추가로 매크로 키 배열이 엄청 많으면 좋겠다.

## 키보드 레이아웃 제작 사이트
http://www.keyboard-layout-editor.com/#/

## Raw Data
위 사이트에 들어가서 `</> Raw Data` 탭을 클릭해서 붙여넣기 하면 된다.
![click `</> Raw Data` tab](https://github.com/soboti/v1-split-keyboard/assets/109705692/487f089e-8708-4e3d-9aec-da8562496909)

### 좌측
```
[{x:1.5,c:"#5e5e5e",t:"#ffffff",a:7},"M1","M2","M3","M4",{x:0.5},"M5","M6"],
[{y:0.25,c:"#ea4221",t:"#000000"},"ESC",{x:0.5,c:"#cccccc"},"F1","F2","F3","F4",{x:0.5},"F5","F6"],
[{y:0.25,c:"#c8c3b8",a:4},"`\n\n\n\n\n\n\n\n\n~",{c:"#cccccc"},"!\n\n\n\n\n\n\n\n\n1","@\n\n\n\n\n\n\n\n\n2","#\n\n\n\n\n\n\n\n\n3","$\n\n\n\n\n\n\n\n\n4","%\n\n\n\n\n\n\n\n\n5","^\n\n\n\n\n\n\n\n\n6","&\n\n\n\n\n\n\n\n\n7"],
[{c:"#c8c3b8",a:7,w:1.5},"Tab",{c:"#cccccc"},"Q","W","E","R","T","Y"],
[{c:"#c8c3b8",w:1.75},"Caps",{c:"#cccccc"},"A","S","D","F","G","H"],
[{c:"#c8c3b8",w:2.25},"Shift",{c:"#cccccc"},"Z","X","C","V","B"],
[{c:"#c8c3b8",w:1.5},"Ctrl",{w:1.25},"Win",{w:1.25},"Alt"],
[{r:-30,y:2,w:3.25},"Space"]
```
![left-split-keyboard-layout](https://github.com/soboti/v1-split-keyboard/assets/109705692/5c5b3585-a2f7-4381-b481-931dbc00665e)


### 우측
```
[{x:0.5,c:"#5e5e5e",t:"#ffffff",a:7},"M7","M8","M9","M10",{x:0.5},"M11","M12","M13","M14",{x:0.5},"M15","M16","M17"],
[{y:0.25,x:0.5,c:"#cccccc",t:"#000000"},"F5","F6","F7","F8",{x:0.5},"F9","F10","F11","F12",{x:0.5},"Print Screen","Scroll Lock","Pause"],
[{y:0.25,c:"#ffe08d"},"6",{c:"#cccccc"},"7","8","9","0","-","=",{c:"#c8c3b8",w:2},"Backspace",{x:0.5,c:"#63696a",t:"fffffff"},"Insert","Home","Page Up"],
[{x:0.5,c:"#cccccc",t:"#000000"},"Y","U","I","O","P","{","}",{c:"#c8c3b8",w:1.5},"|",{x:0.5,c:"#63696a",t:"fffffff"},"Delete","End","Page Down"],
[{x:0.75,c:"#cccccc",t:"#000000"},"H","J","K","L",":","\"",{c:"#c8c3b8",w:2.25},"Enter"],
[{y:-0.5,x:9.5,c:"#63696a",t:"fffffff"},"M18",{x:1},"M19"],
[{y:-0.5,x:0.25,c:"#ffe08d",t:"#000000"},"B",{c:"#cccccc"},"N","M","<",">","?",{c:"#c8c3b8",w:2.75},"Shift",{x:1.5,c:"#ea4221"},"↑"],
[{x:1.75,c:"#ffe08d",w:1.25},"한/영",{x:2,c:"#c8c3b8",w:1.25},"Alt",{w:1.25},"FN",{w:1.5},"Ctrl",{x:0.5,c:"#ea4221"},"←","↓","→"],
[{y:0.5,x:9.5,c:"#63696a",t:"fffffff"},"M20","M21","M22"],
[{r:30,y:-3.25,x:4,c:"#c8c3b8",t:"#000000",w:2.75},"Space"]
```
![right-split-keyboard-layout](https://github.com/soboti/v1-split-keyboard/assets/109705692/354e41ee-dca4-4dcb-93eb-2e2fcc43866d)

