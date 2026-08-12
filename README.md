# Python Fundamentals Study

Python 기초 문법부터 코드 구조화, 객체지향 프로그래밍까지 수업에서 학습한 내용을 주제별로 정리한 저장소입니다.

---

## Overview

### Input, Output
`01.input_output.ipynb`

Python 프로그램의 기본 흐름을 이해하기 위한 기초 학습입니다.

- Input / Output
- Variable & Data Type
- String / List / Set / Dictionary
- Condition
- Loop
- Function

**Focus**
- 데이터를 입력받고 처리한 뒤 결과를 출력하는 기본 흐름 이해
- 조건문과 반복문을 활용한 로직 구성
- 함수를 통한 코드 재사용

---

### Module, Package, Library
`02_module_package_library.ipynb`

기능을 분리하고 재사용하기 위한 Python 코드 구조를 학습했습니다.

- Module / Package / Library
- `import` 사용 방법
- Custom Module `calc.py`
- Custom Package
- Python Standard Library
- `requests`
- `pandas`

**Focus**
- 하나의 파일에 기능을 모으지 않고 역할별로 분리
- 직접 작성한 모듈과 패키지를 `import`하여 재사용
- 외부 라이브러리를 활용하는 기본 방식 이해

---

### Class, Object-Oriented Programming, Exception Handling
`03.class_object_oriented_programming_exception_handling.ipynb`

데이터와 기능을 객체 단위로 구조화하는 방법을 학습했습니다.

- Class / Object / Instance
- `__init__()` / `self`
- Instance Method
- Class Variable / Static Method
- Inheritance
- Overriding
- Polymorphism
- Exception Handling

**Focus**
- 클래스와 객체의 역할 이해
- 상속과 다형성을 활용한 기능 확장
- 예외 상황을 고려한 안정적인 코드 작성

---

## Repository Structure

```text
python-fundamentals/
│
├── README.md
├── 01.input_output.ipynb
├── 02_module_package_library.ipynb
├── 03_class_object_oriented_programming_exception_handling.ipynb
│
├── calc.py
│
└── my_package/
    ├── __init__.py
    ├── calculator.py
    └── message.py
```

## Learning Flow

```text
Basic Syntax
    ↓
Function & Data Structure
    ↓
Module & Package
    ↓
Class & Object
    ↓
Inheritance & Polymorphism
    ↓
Exception Handling
```

기초 문법을 익힌 후 **코드 재사용 → 구조화 → 객체지향 설계** 순서로 학습 범위를 확장했습니다.

---

## Tech

- Python
- Jupyter Notebook
- pandas
- requests

---
