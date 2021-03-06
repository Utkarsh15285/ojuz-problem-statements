지학이는 $n$개의 수 $a_{1}, a_{2}, \cdots, a_{n}$을 생각해 냈습니다. 심심한 지학이는 이 수들로 무엇을 할 지 생각해 보다가, 일단 $1, 2, \cdots, n$의 순열 $p_{1}, p_{2}, \cdots, p_{n}$을 생각해 냅니다.

임의의 자연수 $i$ ($1 \le i < n$)에 대해, $a_{p_{i}}$와 $a_{p_{i+1}}$를 이진법으로 나타냈을 때 1의 개수가 같거나 삼진법으로 나타냈을 때 1의 개수가 같다면, 순열 $p_{1}, p_{2}, \cdots, p_{n}$는 *아름다운 순열*로 정의됩니다.

$n$과 $a$가 주어질 때, 아름다운 순열의 개수를 구해봅시다.


### 입력 형식

첫 번째 줄에 $n$ ($2 \le n \le 20$)이 주어집니다. 두 번째 줄에 $10^{9}$를 넘지 않는 $n$개의 양의 정수가 공백을 사이로 두고 주어집니다.

### 출력 형식

답을 출력합니다.

### 예제


<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th style="width: 50%;">입력</th>
   <th style="width: 50%;">출력</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td class="code-font">3<br/>
5 1 6</td>
   <td class="code-font">2</td>
  </tr>
 </tbody>
</table>

### 참고

$5 = 12_{3}, 1=1_{3}$이고 $5=101_{2}, 6=110_{2}$이므로, $p_{1}=2, p_{2}=1, p_{3}=3$ (1 5 6)과 $p_{1}=3, p_{2}=1, p_{3}=2$ (6 5 1)은 아름다운 순열입니다.

25%의 테스트 케이스에 대해 $N \le 4.$
50%의 테스트 케이스에 대해 $N \le 10.$