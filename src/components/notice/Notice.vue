<template>
  <div class="gridWrap">
    <h2>공지사항</h2>
    <table class="table">
      <thead>
      <tr>
        <th>번호</th>
        <th>제목</th>
        <th>글쓴이</th>
        <th>등록날짜</th>
        <th>조회수</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <td>1</td>
        <td>한국언론진흥재단-인천항만공사, 빅카인즈 뉴스빅데이터 활용</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>2</td>
        <td>IPA, 인천항에 뉴스 빅데이터 분석기술 도입</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>3</td>
        <td>국감 덮어버린 언론보도 키워드 윤석열·게임·막말</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>4</td>
        <td>조정래 발언 왜곡 논란, '진중권 저널리즘'이 키웠다</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>5</td>
        <td>한국언론진흥재단-인천항만공사, 빅카인즈 뉴스빅데이터 활용</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>6</td>
        <td>IPA, 인천항에 뉴스 빅데이터 분석기술 도입</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>7</td>
        <td>국감 덮어버린 언론보도 키워드 윤석열·게임·막말</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>8</td>
        <td>조정래 발언 왜곡 논란, '진중권 저널리즘'이 키웠다</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>9</td>
        <td>한국언론진흥재단-인천항만공사, 빅카인즈 뉴스빅데이터 활용</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      <tr>
        <td>10</td>
        <td>언론은 왜 '방역 훼방꾼' 됐나? "정권 비판에 재난 이용"</td>
        <td>서울신문</td>
        <td>2020-11-27</td>
        <td>30</td>
      </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'Notice',
};
</script>

<style scoped>
.gridWrap {padding:20px;}
.gridWrap h2 {padding:20px 0;}
table {width:100%;border-top:2px solid #888;border-collapse: collapse;}
table th,table td {padding:10px;border-right:1px solid #ccc;border-bottom:1px solid #ccc;font-size:14px;background:#fff;text-align:center;}
table th {background:#888;color:#fff;font-weight:bold;}
table td:nth-child(2) {text-align:left;}
table th:last-child,table td:last-child {border-right:none;}
</style>