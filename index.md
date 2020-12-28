## 브릿지허브 통합 매뉴얼

# 사전 준비 : 
 RS485 배선 위치 선정(월패드, 싱크하부, 배전반 등)
 ‘브릿지 - 스마트홈’ 앱 다운로드
 

# 사전 준비품 : 
스마트폰(아이폰7, 갤럭시7 이상(BLE 4.2), 절연장갑, RS485 배선용 공구(드라이버, 니퍼, *RJ45 랜툴(코맥스의 경우)

0. 제품 구성 확인
 - 브릿지 허브 1개
 - 케이블 1쌍 : 1. +/- 전선, ( + 빨간색, - 검은색) / RS485 통신선 ( 녹색 485A / 흰색 485B ) 
  - 케이블 선 색상 확인 ( 하단 사진 참조  VCC - 빨간색, GND - 검은색, 485A - 녹색, 485B - 흰색 )

1. 설치 설명서
 - 절연 장갑 차단 및 전기 안전 확보 ( 220V 전원 차단 )  
 - 월패드 전원 OFF 
 - 월패드 하단 나사 2개 풀기 ( 월패드마다 다를 수 있음 )
 - 월패드를 들어 올려 벽에서 분리
 - 경우에 따라, 월패드 전원, 통신(IDE 케이블) 분리, LAN 케이블 분리
 - 12V 전원 단자 +(빨)/-(검) 극 결선 
 - RS485 A/B 결선 
 - 차단기 올리기, 월패드 전원 연결 후 전원 ON -> 브릿지 허브 본체 빨간 LED 확인
 - RS485 - 브릿지 허브 본체 결선 ( 패킷 상태는 차후 앱 사용시 확인 )

2. 사용설명서 작성 ( 영상 촬영 )

 2-1. 내 브릿지 등록 ( 사용자당 1개, 1번만 가능, * 이후 삭제시 재등록 가능 )
  - 앱 실행 후, ‘주변 브릿지 탐색’ -> ‘브릿지 탐색 시작’ -> ‘BritzyHub’ 선택 -> ‘브릿지 신규 등록’ 
   -> 이름, 월패드, 건물명, 입력 ->

 2-2 WIFI 설정 
  2-1 완료 후, ‘주변 WIFI(2.4gh) 목록 갱신’ -> 주변 WIFI 검색 -> 자신의 WIFI AP 선택 -> 비밀번호 입력 -> 장치 재시작 -> 녹색 LED 점등 시 정상

 2-3 장치 등록 : ‘내브릿지’ 선택 후, 하단의 + 버튼 클릭 -> 장치 이름, 장치 종류, 동작 방식 (OnOff 만 선택) -> 장치 등록 클릭

 2-4 패킷 캡쳐 및 장치에 패킷 저장 : ‘내 브릿지’ 선택 -> ‘브릿지관리’ -> ‘이 브릿지의 패킷 신호 탐색’ -> 하단 ‘패킷 필터 설정’ -> 중단 ‘패킷 필터 상태’ -> ‘모두 허용’ : 모든 패킷이 캡쳐됨 
 -> ‘필터 사용’ : 사용자가 설정한 필터 값에 맞는 패킷만 캡쳐됨

 이후 월패드에서 전등 on/off 등 장치 사용 -> ‘패킷 조회’ 


You can use the [editor on GitHub](https://github.com/BritzyHub/Britzy/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BritzyHub/Britzy/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
