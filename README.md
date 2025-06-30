# skuniv_study

<h1>💻 Java 알고리즘 + CS 통합 스터디 (8주)</h1>

<p>Java 입문자를 위한 코딩테스트 준비 + 필수 CS 개념 병행 학습 스터디입니다.</p>

<ul>
  <li>⏰ <strong>기간</strong>: 8주 (주 2회)</li>
  <li>🧠 <strong>목표</strong>: 자바로 알고리즘 문제 풀이 + 자료구조/시간복잡도 등 CS 기반 이해</li>
  <li>🛠 <strong>진행</strong>: 문제 풀이 → 코드 리뷰 → CS 연결 개념 학습</li>
</ul>

<h2>📚 커리큘럼 요약</h2>

<table>
  <thead>
    <tr>
      <th>주차</th>
      <th>알고리즘 주제</th>
      <th>자주 쓰이는 유형</th>
      <th>병행할 CS 지식</th>
      <th>대표 문제 (백준)</th>
      <th>시간/메모리 초과 분석</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1주차</td>
      <td>입출력 & Java 기본</td>
      <td>-</td>
      <td>JVM 구조, main 함수, 컴파일</td>
      <td>2557, 1000, 1008</td>
      <td>Scanner vs BufferedReader 속도 차이</td>
    </tr>
    <tr>
      <td>2주차</td>
      <td>조건문/반복문</td>
      <td>브루트포스(완전탐색)</td>
      <td>제어 흐름, 연산자 우선순위</td>
      <td>1330, 2753, 2438</td>
      <td>이중 for문 사용 시 O(N²) 초과 여부 확인</td>
    </tr>
    <tr>
      <td>3주차</td>
      <td>문자열 처리</td>
      <td>투 포인터, 팰린드롬</td>
      <td>String vs char[], 인코딩</td>
      <td>11720, 1152, 10809, 10988</td>
      <td>substring 반복 → 메모리 사용 증가</td>
    </tr>
    <tr>
      <td>4주차</td>
      <td>배열 & 수학</td>
      <td>슬라이딩 윈도우, 누적합</td>
      <td>배열 메모리, 인덱싱 O(1)</td>
      <td>10818, 2562, 3052, 10986</td>
      <td>매번 합 계산 → 누적합으로 최적화</td>
    </tr>
    <tr>
      <td>5주차</td>
      <td>연결 리스트</td>
      <td>병합 정렬형 리스트, 삽입/삭제 시뮬</td>
      <td>포인터, LinkedList 구조</td>
      <td>1406, 5397, LeetCode 21</td>
      <td>중간 삽입 반복 시 O(N²) → 커서 최적화</td>
    </tr>
    <tr>
      <td>6주차</td>
      <td>스택</td>
      <td>괄호 검사, 후입선출</td>
      <td>Stack 메모리, 콜스택</td>
      <td>10828, 9012, 10773, 1874</td>
      <td>재귀 깊이 초과 시 StackOverflow</td>
    </tr>
    <tr>
      <td>7주차</td>
      <td>큐 & 덱</td>
      <td>요세푸스, 회전 큐</td>
      <td>Deque, 원형 큐 구조</td>
      <td>10845, 18258, 1021</td>
      <td>Deque 사용 시 시간복잡도 O(1) 보장 여부 확인</td>
    </tr>
    <tr>
      <td>8주차</td>
      <td>종합 & 모의 테스트</td>
      <td>스택+큐 조합, 정렬 후 처리</td>
      <td>자료구조 선택, 시간복잡도 분석</td>
      <td>1966, 2164, 10814</td>
      <td>입력 제한 확인, 연산량 계산 → 시간초과 방지</td>
    </tr>
  </tbody>
</table>

<h2>📝 참고</h2>

<ul>
  <li>📌 문제 풀이는 <code>/weekN</code> 폴더에 정리</li>
  <li>📌 각 주차별 코드 리뷰 & CS 요약은 <code>/docs</code> 폴더에 저장</li>
  <li>📌 문제 출처: <a href="https://github.com/encrypted-def/basic-algo-lecture/blob/master/workbook.md" target="_blank">바킹독 문제집</a> + 실전 유형</li>
</ul>

<h2>✅ 코드 작성 팁</h2>

<ul>
  <li>✔ Scanner → 느릴 경우 BufferedReader 사용</li>
  <li>✔ 반복문 중첩 시 O(N²) 이상인지 확인</li>
  <li>✔ 문자열 처리 시 불필요한 객체 생성 방지</li>
  <li>✔ 배열/리스트 삽입 삭제 연산의 시간 복잡도 고려</li>
</ul>
