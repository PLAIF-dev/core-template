# Core Template

조직에서 공통으로 쓸 수 있는 Issue, Pull Request, License 등을 가져다 쓸 수 있는 Template Repository 입니다.

## 1. How it works

github의 자체 기능을 활용하여, template 파일로 설정되어 있는 이 Repository의 파일을 기반으로 Repository를 만든다.

template 파일들의 git log들은 같이 생성되지 않는다.

## 2. How to use

- Template을 이용하여 Repository 만들기

  (1) 일반적인 방식

  - 새 repository 만들기 클릭
  ![Screenshot 2023-05-15 at 6 02 03 PM](https://github.com/PLAIF-dev/core-template/assets/52237605/99e1d8ac-2602-4742-b871-bfecf5ff8023)
  - Repository Template에서 선택 후 `Create Repository` 클릭
  ![Screenshot 2023-05-15 at 5 59 43 PM](https://github.com/PLAIF-dev/core-template/assets/52237605/78585f26-ac87-4016-8c63-4042717fe026)
  ![Screenshot 2023-05-15 at 6 07 25 PM](https://github.com/PLAIF-dev/core-template/assets/52237605/99502949-60bf-4953-82e9-9c9737202f82)

  (2) 새 방식

  - `core-template` repository 로 와서, `Use template` 클릭
  ![Screenshot 2023-05-15 at 6 11 22 PM](https://github.com/PLAIF-dev/core-template/assets/52237605/9d849c3e-d95a-4113-b76a-cac9cef83bf9)

- 이 파일인 `README.md` 파일을 프로젝트에 맞게 수정하기

## 3. Repository Naming Convention

리파지토리를 만들 때 이름의 규칙을 정해주셔야합니다. 모든 리파지토리 제목은 [snake_case](https://ko.wikipedia.org/wiki/%EC%8A%A4%EB%84%A4%EC%9D%B4%ED%81%AC_%ED%91%9C%EA%B8%B0%EB%B2%95)로 작성되며, 각 리파지토리 이름 앞에는 팀 명이 적혀져 있어야합니다.

팀 명칭과 그에 리파지토리 명칭은 다음 규칙을 따라야 합니다.
| 팀 명칭 | 리파지토리 명칭 |
|------------|------------|
|   Vision   |   vs_*   |
|   Motion   |   mo_*   |
|   Software   |   sw_*   |

예를 들어, **Vision 팀에서 PiecePicking 프로젝트**를 한다고 하면, **vs_piece_picking**이 되야 합니다.
**Motion 팀에서 Ros2 프로젝트**를 한다고 하면, **mo_ros2**라고 해야합니다.
