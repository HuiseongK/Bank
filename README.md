# Bank
### 주제: 정기예금상품 가입고객에 대한 분석

### <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>age</th>
      <th>job</th>
      <th>marital</th>
      <th>education</th>
      <th>default</th>
      <th>balance</th>
      <th>housing</th>
      <th>loan</th>
      <th>contact</th>
      <th>day</th>
      <th>month</th>
      <th>duration</th>
      <th>campaign</th>
      <th>pdays</th>
      <th>previous</th>
      <th>poutcome</th>
      <th>deposit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>59</td>
      <td>admin.</td>
      <td>married</td>
      <td>secondary</td>
      <td>no</td>
      <td>2343</td>
      <td>yes</td>
      <td>no</td>
      <td>unknown</td>
      <td>5</td>
      <td>may</td>
      <td>1042</td>
      <td>1</td>
      <td>-1</td>
      <td>0</td>
      <td>unknown</td>
      <td>yes</td>
    </tr>
    <tr>
      <th>1</th>
      <td>56</td>
      <td>admin.</td>
      <td>married</td>
      <td>secondary</td>
      <td>no</td>
      <td>45</td>
      <td>no</td>
      <td>no</td>
      <td>unknown</td>
      <td>5</td>
      <td>may</td>
      <td>1467</td>
      <td>1</td>
      <td>-1</td>
      <td>0</td>
      <td>unknown</td>
      <td>yes</td>
    </tr>
    <tr>
      <th>2</th>
      <td>41</td>
      <td>technician</td>
      <td>married</td>
      <td>secondary</td>
      <td>no</td>
      <td>1270</td>
      <td>yes</td>
      <td>no</td>
      <td>unknown</td>
      <td>5</td>
      <td>may</td>
      <td>1389</td>
      <td>1</td>
      <td>-1</td>
      <td>0</td>
      <td>unknown</td>
      <td>yes</td>
    </tr>
    <tr>
      <th>3</th>
      <td>55</td>
      <td>services</td>
      <td>married</td>
      <td>secondary</td>
      <td>no</td>
      <td>2476</td>
      <td>yes</td>
      <td>no</td>
      <td>unknown</td>
      <td>5</td>
      <td>may</td>
      <td>579</td>
      <td>1</td>
      <td>-1</td>
      <td>0</td>
      <td>unknown</td>
      <td>yes</td>
    </tr>
    <tr>
      <th>4</th>
      <td>54</td>
      <td>admin.</td>
      <td>married</td>
      <td>tertiary</td>
      <td>no</td>
      <td>184</td>
      <td>no</td>
      <td>no</td>
      <td>unknown</td>
      <td>5</td>
      <td>may</td>
      <td>673</td>
      <td>2</td>
      <td>-1</td>
      <td>0</td>
      <td>unknown</td>
      <td>yes</td>
    </tr>
  </tbody>
</table>
</div>
#### 각 컬럼의 의미는 아래와 같습니다.

1-age: 개인의 나이를 나타냅니다.

2-job: 개인의 직업이나 직무를 설명합니다.

3-marital: 그 사람의 결혼 상태를 나타냅니다(예: 'married', 'single', 'divorced').

4-education: 개인의 교육 수준을 나타냅니다(예: 초등, 중등, 고등).

5-default: 해당 개인의 기본 신용이 있는지 여부를 나타냅니다('예', '아니요' 또는 '알 수 없음').

6-balance: 개인이 보유한 자산을 나타냅니다.

7-housing: 해당 개인이 주택 대출을 받았는지 여부를 표시합니다('예', '아니요' 또는 '알 수 없음').

8-loan: 개인 대출이 있는지 여부를 나타냅니다('예', '아니요' 또는 '알 수 없음').

9-contact: 개인에게 연락하는 데 사용되는 통신 방법을 설명합니다(예: '휴대폰', '전화').

10-day: 마지막 접촉이 발생한 요일을 나타냅니다.

11-month: 마지막 접촉이 발생한 달을 나타냅니다.

12-duration: 마지막 접촉 기간을 초 단위로 나타냅니다.

13-campagin: 이 캠페인 동안 이루어진 접촉 수를 나타냅니다.

14-pdays: 해당 사람에게 마지막으로 연락한 이후의 일수를 설명하며, 이전에 연락하지 않은 경우 -1을 나타냅니다.

15-previous: 이 캠페인 이전에 이루어진 접촉 수를 나타냅니다.

16-poutcome: 이전 마케팅 캠페인의 결과를 나타냅니다.

17-deposit: 정기예금 가입 여부('예' 또는 '아니요')을 나타내는 대상 변수입니다.
