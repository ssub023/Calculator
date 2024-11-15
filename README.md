# 사칙연산 계산기

## 개요

Java를 사용하여 사칙연산을 수행할 수 있는 계산기를 구현한 것입니다. Swing을 이용하여 구성하였으며, 중위 표현식을 후위표현식으로 변환하여 계산을 수행합니다.

## 기능
* 기본적인 사칙연산(덧셈, 뺄셈, 곱셈, 나누셈)
* %계산
* 전체 수식 초기화
* 입력된 수식의 마지막 문자 삭제

## 코드 설명
* Calculator 클래스: 계산기 GUI와 기능을 구현한 클래스
* ButtonClickListener 클래스: 버튼 클릭 이벤트
* calculate: 입력된 수식을 계산하는 메소드
* fullTextParsing: 입력된 텍스트를 숫자와 연산자로 분리
* infixToPostfix: 중위 표현식을 후위표현식으로 변환
* evaluatePostifx: 후위표현식을 계산
* performOperation: 두 숫자와 연산자를 입력 받아 계산

## 실행화면
![계산기](https://github.com/user-attachments/assets/79addbb3-be95-452f-87f0-194b26deb060)
![계산기2](https://github.com/user-attachments/assets/02cf89fe-18c4-4be4-bd37-ffc1b3683dfe)
![계산기3](https://github.com/user-attachments/assets/90081b0b-a4c8-472f-b689-96adc6bcee35)

## 보완할 점
* %기능이 제대로 수행을 하지 못함
* 소수점 자리수 설정
* 예외 처리: 연산자가 잘못 입력되거나 숫자 없이 연산자가 입력되는 경우 오류 처리

## 개발 이력
* 2024.10.09: 텍스트 영역 및 버튼 생성
* 2024.10.10: 버튼 클릭 이벤트 처리
* 2024.10.12: 수식 계산 메소드 작성
* 2024.10.15: 계산 메소드 수정
* 2024.10.19: 중위 표현식을 후위 표현식으로 변환하는 메소드 작성
* 2024.10.20: 후위 표현식 계산 메소드 작성
* 2024.10.21: 연산 수행 메소드 작성
* 2024.10.22: 오류 수정
* 2024.10.25: 폰트 추가
* 2024.11.01: 최종 수정

## 커밋
* URL: https://github.com/ssub023/Calculator/commits?author=ssub023
* 캡쳐화면
![COMIT](https://github.com/user-attachments/assets/c99cb12e-d440-4f12-bdac-85ca403ac8e6)
