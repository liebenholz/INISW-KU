## Database
A collection of interrelated data, a set of integrated, stored, shared and operational data.

<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"> <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white">


## Introduction to Database
### Condition of Database
- Integrated: 동일한 데이터가 중복되지 않도록 구성, 최소한의 중복 또는 통제된 중복만 허용
- Stored: 컴퓨터로 접근 가능한 물리적 저장 매체 저장
- Shared: 공동으로 소유하고 유지하며 이용하는 데이터
- Operational: 존재 목적이나 기능 수행에 꼭 필요한 데이터 집합
- Real-time Accessibility: 데이터 간의 밀접한 관계로 연결, 사용자의 어떤 요구에도 즉각 응답
- Continuous Evolution: 현실 세계의 상태를 정확히 반영, 동적으로 삽입/삭제/수정하여 데이터 유지
- **Concurrent Sharing**: 여러 사용자들이 동시에 이용, 같은 시간에 같은 데이터에 접근하여 이용
- Content Reference: 저장된 주소나 위치에의해서 참조하지 않고 사용자가 요구하는 데이터의 내용/값에 따라 참조

### DBMS
Database Management System
- A collection of programs
- **Manage the database structure**
- Controls access to the data stored in the database(by cursor)

Role of DBMS
- create databases
- insert, ~~update and delete~~ data
- sort and query data
- create form and report

Type of DBMS
- Hierarchical Database Model
- Network Database Mode
- **Relational Database Model**
- Object Relational Database Model

## SQL
Structured Query Language
- RDBMS의 데이터를 관리하기 위해 만들어진 언어로, 대부분 ISO 표준을 따름
- 자료의 검색과 관리, 데이터베이스 스키마 생성과 수정, 데이터베이스 객체 접근 조정 관리 등을 고안

DDL(Definition, 정의)
- CREATE
- DROP
- ALTER
- TRUNCATE

DML(Manipulation, 조작)
- INSERT
- UPDATE
- DELETE
- SELECT

DCL(Control, 제어)
- GRANT
- REVOKE

[Practice Notebook by SQLite3](https://github.com/liebenholz/INISW-KU/blob/main/01_Database/DB_0305.ipynb)

## ORM, RE
Object Relational Mapping
- **Programming technique** for converting data between incompatible type systems using objectoriented programming languages 
- Automatically mapping the database to business objects
- Programmers **focus more on business problems** and **less with data storage**
- 테이블 간의 관계보다 **데이터베이스 처리**에 집중해서 서비스를 제작할 것
  - [SNS System Integration Example: Why we should use ORM](https://github.com/liebenholz/INISW-KU/blob/main/01_Database/DB_0306-SNS.ipynb)

### SQLAlchemy 
SQLAlchemy is a well-regarded database toolkit and ORM implementation written in Python, and provides a generalized interface for creating and executing database-agnostic code **without needing to write SQL statements.**

- SQLAlchemy Core Practice Notebook [(1)](https://github.com/liebenholz/INISW-KU/blob/main/01_Database/DB_0306.ipynb) [(2)](https://github.com/liebenholz/INISW-KU/blob/main/01_Database/DB_0307.ipynb) [[SNS]](https://github.com/liebenholz/INISW-KU/blob/main/01_Database/DB_0307-SNS.ipynb)
