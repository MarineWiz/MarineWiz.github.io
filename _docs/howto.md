---
title: "사용 방법"
permalink: /docs/howto/
excerpt: "마린위즈는 발주자의 다양한 요구사항을 반영한 고품질 SW를 저렴한 비용으로 빠르게 개발 가능한 조선해양특화 SW통합개발도구이다."
last_modified_at: 2020-04-13T21:36:11-04:00
redirect_from:
  - /theme-setup/
toc: true
---
#### MarineWiz 기반 SW개발
  1. 프로젝트 생성
      - 프로젝트 생성 화면에서 제작하고자 하는 응용프로그램의 템플릿을 선택한다.프로젝트 생성 화면은 MarineWiz를 실행하거나, 메뉴바에서 「File > New Project」를 선택했을 때 출력된다.
      - 프로젝트의 이름과 저장 위치(기본 : C:\Users\Name\Desktop)를 설정한 후 OK 버튼을 클릭한다. 저장 위치를 변경할 경우 Find버튼을 클릭한다.
      ![프로젝트생성화면](https://user-images.githubusercontent.com/45934727/79210055-3b5b3180-7e7f-11ea-8c17-48b5065effb6.png)
      - 프로젝트 생성 화면에서 설정한 값(프로젝트 이름, 저장 위치)을 확인한다.
      - 프로젝트에서 제작하려는 응용프로그램 메인화면의 너비와 높이를 설정한 후 OK버튼을 클릭하여 프로젝트 정보를 저장한다. CANCEL 클릭하면 설정한 너비와 높이를 무시하고 기본 크기(1000 * 60)로 프로젝트 정보가 저장된다.
      ![image](https://user-images.githubusercontent.com/45934727/77055550-6edba500-6a14-11ea-9e7b-7e38d08a79f4.png)
      - 프로젝트 생성 화면에서 설정한 값(프로젝트 이름, 저장 위치)을 확인한다.
      - 프로젝트에서 제작하려는 응용프로그램 메인화면의 너비와 높이를 설정한 후 OK버튼을 클릭하여 프로젝트 정보를 저장한다. CANCEL 클릭하면 설정한 너비와 높이를 무시하고 기본 크기(1000 * 60)로 프로젝트 정보가 저장된다.
  2. 응용 프로그램 구성
      - 프로젝트 작업 화면에서 컴포넌트 목록창의 컴포넌트를 Drag & Drop하여 응용프로그램의 GUI를 구성한다.
      - 응용프로그램의 GUI를 구성하는 컴포넌트를 선택하여 속성 값을 설정한다.
      ![image](https://user-images.githubusercontent.com/45934727/77055672-a9454200-6a14-11ea-88eb-19e05e1f0976.png)
  3. 데이터 바인딩
      - 메뉴바에서 「File > Add Library(DLL) Files」를 클릭해서 프로젝트에 필요한 DLL을 Import한다. Import된 DLL은 솔루션 탐색기의 package폴더에 저장된다.
      ![image](https://user-images.githubusercontent.com/45934727/77056032-34263c80-6a15-11ea-9bba-a1233b191798.png)
      - 데이터를 바인딩하기 위한 컴포넌트를 선택한 후 오른쪽 마우스 버튼을 클릭하여 「Attached Data From...」을 클릭한다.
      ![image](https://user-images.githubusercontent.com/45934727/77056186-6fc10680-6a15-11ea-8f49-90ffa1928e60.png)
      - DLL을 선택한다.
      - 내부 함수를 선택한다. 『class DatabaseAccessManager > List GetDataFrom()』 선택
      - 「Next」 버튼을 클릭한다.
      ![image](https://user-images.githubusercontent.com/45934727/77056309-954e1000-6a15-11ea-8f85-7208fe3c8c97.png)
      - 데이터 바인딩 대상 컴포넌트, 선택한 DLL 파일, 내부 함수를 확인한다.
      - 바인딩 데이터의 갱신 주기를 설정한다.
      - 차트 컴포넌트의 데이터 범위를 설정한다.
      - 「Finish」버튼을 클릭한다.
      ![image](https://user-images.githubusercontent.com/45934727/77056440-be6ea080-6a15-11ea-9187-7e3a48ec34bf.png)
  4. 저장
      - 메뉴바에서 「File > Save」을 클릭한다.
      - 메뉴바에서 「Build > Build(B)」를 클릭한다.
      - Console화면이 생성되고, Build 정보가 출력된다.
      - Build가 완료되면 「프로젝트 저장위치\Bin\Debug」폴더에 exe 파일이 생성된다.
      ![image](https://user-images.githubusercontent.com/45934727/77057819-dfd08c00-6a17-11ea-86b5-9f278f5c9969.png)
  5. Build
      - 메뉴바에서 「Build > Build(B)」를 클릭한다.
      - Console화면이 생성되고, Build 정보가 출력된다.
      - Build가 완료되면 「프로젝트 저장위치\Bin\Debug」폴더에 exe 파일이 생성된다.
      ![image](https://user-images.githubusercontent.com/45934727/77056699-245b2800-6a16-11ea-9154-4ce05f777bd8.png)
  6. 응용 프로그램 실행
      - 「프로젝트명.exe」을 더블클릭하여 실행시키면 응용프로그램의 동작을 확인할 수 있다.
      ![image](https://user-images.githubusercontent.com/45934727/77056981-9895cb80-6a16-11ea-9e17-efd552dc51e2.png)

#### Library 기반 SW개발
  - 프로젝트 생성
  - 응용 프로그램 구성
  - 데이터 바인딩
  - 저장
  - Build
  - 응용 프로그램 실행
