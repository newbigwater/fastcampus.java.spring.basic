# 01. Development Environment

## 00. Environment

### 00.01 OS : Windows 11 x64

### 00.02 Development kit

- JDK 11
- IDE
    - STS3 : Eclipse + Spring & Spring boot PlugIn
        - STS4 : Only Spring boot
    - IntelliJ
- Web server
    - Apache Tomcat 9
- Web browser
    - Chrome
- Database
    - MySQL v5.7
- ETC
    - VSCode, Git, AWS, Maven

---

## 01. JDK Install

### 01.01 JDK 11 Download

- URL : [https://jdk.java.net/11/](https://jdk.java.net/11/)
    - OpenJDK Archive
        
        ![Untitled](./img/Untitled.png)
        
    - 11 version 중 암것나 선택
        - 11.0.2 Zip file 다운로드.
        - GA : General Availability : 배포 가능 버전
        
        ![Untitled](./img/Untitled%201.png)
        
        ![Untitled](./img/Untitled%202.png)
        
    
    ---
    

### 01.02 JDK 11 Install

- jdk 설치
    - C:\Java\jdk-11.0.2
        
        ![Untitled](./img/Untitled%203.png)
        
- 환경변수 설정
    - 환경변수 편집창
        - 시스템 변수
            - Path 변수 수정
                - jdk 설치 위치 복사 및 추가
                    - C:\Java\jdk-11.0.2
                - 최 상위에 위치 시킨다.
                    - 차후 java 기반 프로그램 설치 시 오류 발생 가능.
            - 새 시스템 변수 추가 : JAVA_HOME
                - Tomcat 때문에 설정한다.
    - 환경변수 편집창 확인 누르며 닫기
    - 설명 이미지
        
        ![Untitled](./img/Untitled%204.png)
        
        ![Untitled](./img/Untitled%205.png)
        
        ![Untitled](./img/Untitled%206.png)
        
        ![Untitled](./img/Untitled%207.png)
        
        ![Untitled](./img/Untitled%208.png)
        
        ![Untitled](./img/Untitled%209.png)
        
        ![Untitled](./img/Untitled%2010.png)
        
        ![Untitled](./img/Untitled%2011.png)
        

## 02. STS Install

### 02.01 STS3 Download

- URL : [https://github.com/spring-attic/toolsuite-distribution/wiki/Spring-Tool-Suite-3](https://github.com/spring-attic/toolsuite-distribution/wiki/Spring-Tool-Suite-3)
    - Spring Tool Suite3 wiki
        
        ![Untitled](./img/Untitled%2012.png)
        
    - 첫 번째 URL
        
        ![Untitled](./img/Untitled%2013.png)
        

---

## 03. IntelliJ Insall

### 03.01 IntelliJ Ultimate Download

> 무료판은 Sping boot만 된다.
유료판 30일 무료판 다운로드 후 사용
> 
- URL : [https://www.jetbrains.com/ko-kr/idea/download/?section=windows](https://www.jetbrains.com/ko-kr/idea/download/?section=windows)
    - ultimate version download
        
        ![Untitled](./img/Untitled%2014.png)
        

---

## 04. Web server Install

### 04.01 Apache Tomcat 9 Download

- URL : [https://tomcat.apache.org/download-90.cgi](https://tomcat.apache.org/download-90.cgi)
    - Tomcat 9 version download
        
        ![Untitled](./img/Untitled%2015.png)
        
        ![Untitled](./img/Untitled%2016.png)
        
        ![Untitled](./img/Untitled%2017.png)
        

<aside>
💡 * Java Spec
┌ SE : Standard edition - 일반
├ EE : Enterprise edition - 서버 ⇒ Tomcat은 EE 기반이다.
└ ME : Micro edition - 소형 기기

</aside>

---

## 05. Database Install

---

## 06. ETC

### 06.01 VSCode

- Expansion pack
    - Korean Language Pack
    - Prettier - Code formatter
    - open in browser
        - 기능 테스트
            - text.html file 생성
                - ! + enter
                    
                    ![Untitled](./img/Untitled%2018.png)
                    
                    ```html
                    <!DOCTYPE html>
                    <html lang="en">
                    <head>
                        <meta charset="UTF-8">
                        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                        <title>Document</title>
                    </head>
                    <body>
                        <h1>Hello!</h1>
                    </body>
                    </html>
                    ```
                    
                - Art + B
                    
                    ![Untitled](./img/Untitled%2019.png)
                    
                    ![Untitled](./img/Untitled%2020.png)
                    
    - indent-rainbow
    - Auto Rename Tag