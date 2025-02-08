# Interview-Helper

## :sound: Intro.

[프로젝트 설명]




## :man_student: Members

- [C089014 김민규](https://github.com/mingyu2157/)
- [C089017 김수민](https://github.com/cc089017/)
- [C089065 최정환](https://github.com/JeongHwan0208/)
- [C093299 홍민기](https://github.com/mingimouse/)



## :computer: Code Convention

#### 01. 변수, 함수, 인스턴스

변수, 함수, 인스턴스를 작성할 때는 `Camel Case`를 사용한다.

```
camelCase
```

#### 02. 함수명 작성

함수명을 작성할 때는 동사+명사 형태로 구성한다.

```
getUserInformation()
```

#### 03. Class, Constructor

Class, Constructor를 작성할 때는 `Pascal Case`를 사용한다.

```
CamelCase
```

#### 04. Constant

상수명의 경우 대문자와 밑줄을 사용해 명명한다.

```
CONSTANT_VALUE
```

#### 05. Flag로 사용되는 변수

프로그래밍에서 상태를 기록하고 처리흐름을 제어하기 위한 boolean 변수 (조동사+flag종류로 구성)

```
isNun, hasNum
```

#### 06. Tab Depth

탭 간격은 4칸으로 정의한다.



## :computer: Git Commit Convention

#### 01. Commit Message 구조

| 태그이름         | 설명                                                         |
| ---------------- | ------------------------------------------------------------ |
| Add              | 새로운 기능을 추가할 경우                                    |
| Fix              | 버그를 고친 경우                                             |
| Design           | CSS등 사용자 UI 디자인 변경                                  |
| !BREAKING CHANGE | 커다란 API 변경의 경우                                       |
| !HOTFIX          | 급하게 치명적인 버그를 고쳐야 하는 경우                      |
| Refactor         | 프로덕션 코드 리팩토링                                       |
| Comment          | 필요한 주석 추가 및 변경                                     |
| Modify           | 문서를 수정한 경우                                           |
| Test             | 테스트 추가, 테스트 리팩토링 (프로덕션 코드 변경X)           |
| Chore            | 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우 (프로덕션 코드 변경X) |
| Rename           | 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우           |
| Remove           | 파일을 삭제하는 작업만 수행하는 경우                         |

- **제목**: `태그명: 제목` 형식으로 작성

- **본문**: 변경사항을 자세히 명시 (무엇을 변경했는지, 왜 변경했는지 설명)

#### 02. PR 규칙

```bash
# 등록
add Chapter명 by username
ex) add Chapter9 by 홍민기

# 수정
modify Chapter명 by username
ex) modify Chapter9 by 홍민기
```

