# Loan Eligibility

<p align="center"><a href="https://github.com/pybsh/loan-eligibility/blob/main/README.md">한국어</a> · <a href="https://github.com/pybsh/loan-eligibility/blob/main/README.en_US.md">English</a></p>

> <b>대출 가능 여부 예측 분류 모델</b>

<img width="700" alt="21815be8-ca3e-4529-8467-280566a7fdbb" src="https://github.com/user-attachments/assets/60040a1f-a11e-44bd-861f-3d3bd5c0adb4" />
<img width="700" alt="737d7d3d-6137-4bcb-ba4a-692054011e39" src="https://github.com/user-attachments/assets/adbbc3b3-ec2f-4004-bfc2-57cdae2cac2a" />


## 프로젝트 소개

### 개요
- 사용 기술: Python, Pandas, Numpy
- 제작 기간: 1일
- 제작 인원: 1명
    <table>
        <tr>
        <td align="center">
            <a href="https://github.com/pybsh">
            <img src="https://avatars.githubusercontent.com/u/59782214?v=4?s=100" width="100px;" alt=""/><br /><sub><b>pybsh</b></sub></a><br />
            <a href="#" title="코드 작성">💻</a>
        </td>
        </tr>
    </table>

### 소개
자신의 인적사항을 입력해 대출이 가능한지 여부를 예측 분류하는 모델을 제작하고 탐구하였습니다.

### 탐구
- 대출 승인 여부는 연간 수입 대비 대출 금액과 가장 큰 상관관계를 가지고 있었습니다.
- 여러 모델 중 LightGBM이 정확도 93%로 가장 높았습니다.
- LightGBM의 특성 중요도는 연간 수입, 대출 이자율, 신용 점수가 높았습니다.

## 기타
- 사용한 데이터셋은 [Loan Approval Classification Dataset](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data) 입니다.
