<!DOCTYPE html>
<html lang="ko">
<head>

  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5231376252840391"
     crossorigin="anonymous"></script>
  
  <meta charset="UTF-8" />
  <!-- 반응형 + iOS 확대 방지(폰트 16px 이상) -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>꿈 계산기</title>
  <style>
    body {
      font-family: sans-serif;
      /* 중앙 정렬 */
      margin: 20px auto; 
      line-height: 1.6;
      max-width: 600px;  /* 본문 폭 600px 고정, 중앙 배치 */
      
      /* 모바일에서 좌우 여백 확보 */
      padding: 0 20px;
      box-sizing: border-box;
    }
    @media (max-width: 600px) {
      body {
        padding: 0 30px;
        font-size: 14px; /* 화면 작아질 때 폰트 축소 */
      }
    }
    /* h1을 3배 크기로 + 중앙 정렬 */
    h1 {
      margin-bottom: 10px;
      text-align: center;
      font-size: 300%; 
    }
    h2 {
      margin-bottom: 10px;
    }
    .form-group {
      margin-bottom: 15px;
      display: flex;
      align-items: center;
    }
    .form-group label {
      width: 120px; /* 모든 라벨 폭을 동일하게 */
    }
    .form-group input {
      width: 150px;
      padding: 5px;
      text-align: right; /* 숫자 오른쪽 정렬 */
      font-size: 16px;   /* iOS 자동 확대 방지 */
    }
    .form-group span {
      margin-left: 5px;
    }
    .hint {
      color: #666;
      margin-left: 10px;
    }
    .result {
      margin-top: 20px;
      font-weight: bold;
      font-size: 1.2em;
    }
    .detail {
      font-size: 0.8em; 
      color: #333;
      margin-left: 6px;
    }
    .divider {
      margin: 30px 0;
      border-top: 1px solid #ccc;
    }
    button {
      margin-left: 10px;
      cursor: pointer;
      font-size: 16px; /* 버튼 폰트 16px */
    }
    /* 입력 요소 폰트 크기를 16px 이상으로 설정 (자동 확대 방지) */
    input, select, textarea {
      font-size: 16px;
    }

    /* Material-like 버튼 공통 스타일 */
    .material-btn {
      border: none;
      color: #fff;
      border-radius: 4px;
      padding: 8px 16px;
      transition: background-color 0.2s ease;
      cursor: pointer;
    }
    .material-btn:hover {
      opacity: 0.9; /* 간단히 hover 시 약간 투명하게 */
    }
    /* 파란색 버튼 */
    .blue-btn {
      background-color: #2196F3;
    }
    /* 네이버 블로그 초록색 버튼 */
    .naver-btn {
      background-color: #00C73C; /* 네이버 블로그 색상 */
    }
  </style>
</head>
<body>

  <!-- =========================
       (0) "꿈 계산기" 제목
      ========================= -->
  <h1>꿈 계산기</h1>
  <br><br>

  <!-- =========================
       (버튼 2개를 중앙 정렬 + 간격 추가)
      ========================= -->
  <div style="text-align:center; margin: 30px 0;">
    <!-- (0-B) 네이버 블로그 링크 버튼 (초록색) -->
    <button id="blogLinkBtn" class="material-btn naver-btn"
      onclick="window.open('https://m.blog.naver.com/kgh_investment','_blank');">
      네이버 블로그 무료 칼럼 읽기
    </button>
    <br><br><br>
    <!-- (0-A) 열기/접기 버튼 (파란색) -->
    <button id="toggleUsageBtn" class="material-btn blue-btn">
      처음 오셨다면 이 글부터 읽어주세요 → 사용법 (✈️)
    </button>
  </div>

  <!-- =========================
       (0-C) 숨겨진 안내문 (display:none)
         * 노란색 하이라이트: 지정 문구만
      ========================= -->
  <div id="usageBox" style="display:none; margin-top:10px; line-height:1.5;">
    <p>
      <br>
      <span style="background-color:yellow;">당신이 꿈꾸는 미래가 왔습니다. 한 달에 얼마를 사용하고 있나요?</span>
      <br><br><br>
      예를 들어, ‘20년 뒤에 은퇴할 때 3달에 한 번은 해외여행을 다니고 싶다'라고 마음먹었다고 해보겠습니다.
      <br><br>
      그러면 적어도 월 450만원은 필요할 것입니다.
    </p>
      <br>
    <p>
      잠시, <u>'20년 뒤의 450만원'</u>은 현재 물가로는 249만원입니다. 
      <br><br>
      그래서 실제로 20년 뒤가 되면 더 많은 돈이 필요하죠. 
      <br><br><br>
      ❗ 그러니 단순하게, <span style="background-color:yellow;">'현재 물가 기준으로 원하는 월 생활비'</span>를 입력하세요. 나머지는 알아서 계산해드립니다.
    </p>
      <br>
    <p>
      여기서, <u>‘엥? 목돈에서 돈을 그냥 꺼내 써도 되나?’</u>라는 생각이 드실 수도 있습니다. 
      <br><br>
      그런데 만약 월 450만원을 사용해도 자산이 계속 늘어나서 그런 삶을 유지할 수 있다면 어떨까요?
    </p><br>
    <p>
      '원금이 줄어들잖아요'라는 생각이 드실 수도 있습니다.
      <br><br>그런데 만약 20억원이 있고 연평균 수익률이 10%라면 어떨까요? 매년 2억원을 사용해도 될 겁니다.
    </p><br>
    <p>
      ❔ ’하지만 물가가 오르면 어떻게 해? 돈의 가치는 계속 줄어들잖아‘ <br>
      ❔ ’만약 주가가 떨어져서 수익률도 떨어지면 어떻게 해?‘ <br>
      ❔ ‘돈이 다 떨어지면 어떻게 하지?’
      <br><br><br>
      ➡️ <span style="background-color:yellow;">맞습니다. 그래서 수익 전체를 꺼내써선 안 됩니다.</span>
      매년 3% 만큼은 물가가 오르는 것을 대비해서, 인출해선 안 됩니다.
      <br><br>
      그리고 나머지 중 <span style="background-color:yellow;">일부만 인출</span>하고, 또 일부는 자산 자체의 가치가 상승하도록 남겨두세요.
      <br><br>
      이 때, ‘<u>일부만 인출</u>’ 하기로 했는데 그것이 바로 ‘<span style="background-color:yellow;">인출율</span>’입니다. 
      <br><br>
      그럼 인출율은 몇 %로 정하면 좋을까요?
    </p><br>
    <p>
      ⭐ 인출율 정하는 팁 : 
      <br><br>
      1️⃣ 은퇴 시점에 <u>부업이나 근로소득</u>으로 생활비의 일부라도 충당할 수 있을 것으로 보인다면 인출율 <span style="background-color:yellow;">4%</span>도 괜찮습니다.
      <br><br>
      2️⃣ 하지만 <u>'완전한 은퇴’</u>를 꿈꾼다면 보수적으로 인출율 <span style="background-color:yellow;">3.5%</span>로 설정하는 것을 권합니다.
    </p><br>
  </div>

    <!-- 구분선 -->
  <div class="divider"></div>

  <!-- =========================
       (1) 원하는 월 생활비 → 미래에 필요한 목돈
      ========================= -->
  <p>
    현재의 물가로, 얼마의 월 생활비를 원하시나요? 필요한 목돈을 계산해드립니다.
  </p>
  <h2>원하는 월 생활비 → 미래에 필요한 목돈</h2>

  <div class="form-group">
    <label for="C26">원하는 월 생활비</label>
    <input type="text" id="C26" placeholder="예: 4,500,000" />
    <span>원</span>
    <span id="C26_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="C27">인출율</label>
    <input type="number" id="C27" placeholder="예: 3.5" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="C28">연수</label>
    <input type="number" id="C28" placeholder="예: 20" />
    <span>년</span>
  </div>
  <div class="form-group">
    <label for="C29">인플레이션</label>
    <input type="number" id="C29" placeholder="예: 3" step="0.1" />
    <span>%</span>
  </div>

  <!-- 결과 -->
  <div class="result">
    필요한 돈: 
    <span id="C31">0원</span>
    <span id="C31Detail" class="detail">(0원)</span>
  </div>
  <div class="result">
    현재 가치: 
    <span id="C32">0원</span>
    <span id="C32Detail" class="detail">(0원)</span>
  </div>

  <!-- 한 줄 간격 -->
  <div style="height:10px;"></div>

  <!-- tipsText는 사용하지 않으므로 비워둠 -->
  <p id="tipsText" style="line-height:1.5; margin:0;"></p>

  <!-- 구분선 -->
  <div class="divider"></div>

  <!-- =========================
       (2) 낙원 계산기
      ========================= -->
  <h2>낙원 계산기</h2>
  <p>
    현재 보유한 자산과, 
    <span style="color:red; font-weight:bold;">연간</span>으로 얼마를 투자하는지 적어주세요.  
    그럼 은퇴 시점에 얼마의 자산을 가질 수 있는지 계산됩니다.
  </p>

  <div class="form-group">
    <label for="B36">보유 자산</label>
    <input type="text" id="B36" placeholder="예: 100,000,000" />
    <span>원</span>
    <span id="B36_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="B37">
    <span style="color:red; font-weight:bold;">연간</span> 저축 금액
    </label>
    <input type="text" id="B37" placeholder="예: 12,000,000" />
    <span>원</span>
    <span id="B37_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="B38">기간</label>
    <input type="number" id="B38" placeholder="예: 25" />
    <span>년</span>
  </div>
  <div class="form-group">
    <label for="B39">명목 수익률<br>(투자 수익률)</label>
    <input type="number" id="B39" placeholder="예: 10" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="B40">저축 증가율<br>(물가 상승률)</label>
    <input type="number" id="B40" placeholder="예: 3" step="0.1" />
    <span>%</span>
  </div>
  <p class="hint" style="margin-left:20px;">
    물가 상승에 맞춰, 저축 금액도 같은 비율로 매년 상승한다고 가정합니다
  </p>

  <div id="retirementAssetContainer" class="result" style="transition: background-color 0.4s;">
    은퇴 후 자산: 
    <span id="resultValue">0원</span>
    <span id="resultValueDetail" class="detail">(0원)</span>
    <button id="copyResultBtn" class="material-btn blue-btn">결과 복사하기</button>
  </div>
  <div id="retirementAssetMsg" style="margin-top:5px; font-weight:normal;"></div>

  <div class="divider"></div>

  <!-- =========================
       (3) 미래 목돈을 현재로 계산
      ========================= -->
  <p>
    이 돈은 
    <span id="periodYears">0</span>
    년 후의 기준 가치입니다. 현재 기준으로는 얼마의 가치일까요? 환산해보겠습니다.
  </p>
  <h2>미래 목돈을 현재로 계산</h2>

  <div class="form-group">
    <label for="B9">미래 가치</label>
    <input type="text" id="B9" placeholder="0" />
    <span>원</span>
    <span id="B9_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="B10">인플레이션</label>
    <input type="number" id="B10" placeholder="예: 3" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="B11">연수</label>
    <input type="number" id="B11" placeholder="예: 25" />
    <span>년</span>
  </div>

  <div class="result">
    현재 가치: 
    <span id="presentValue">0원</span>
    <span id="presentValueDetail" class="detail">(0원)</span>
  </div>

  <div class="divider"></div>

  <!-- =========================
       (4) 미래 목돈 → 인출 가능한 돈
      ========================= -->
  <p>
    그럼, 위의 돈으로 <span id="withdrawYears">0</span>년 후 매달 얼마를 꺼내서 사용할 수 있을까요?
  </p>
  <h2>미래 목돈 → 인출 가능한 돈</h2>

  <div class="form-group">
    <label for="B16">미래 목돈</label>
    <input type="text" id="B16" placeholder="0" />
    <span>원</span>
    <span id="B16_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="B17">인출율</label>
    <input type="number" id="B17" value="3.5" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="B18">인플레이션</label>
    <input type="number" id="B18" placeholder="예: 3" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="B19">연수</label>
    <input type="number" id="B19" placeholder="예: 25" />
    <span>년</span>
  </div>

  <div class="result">
    가능 월 소득: 
    <span id="possibleIncome">0원</span>
    <span id="possibleIncomeDetail" class="detail">(0원)</span>
  </div>
  <div class="result">
    현재 가치: 
    <span id="withdrawPresentValue">0원</span>
    <span id="withdrawPresentValueDetail" class="detail">(0원)</span>
  </div>

  <div class="divider"></div>

  <!-- =========================
       (5) 현재 가치를 미래 가치로 환산
      ========================= -->
  <h2>현재 가치를 미래 가치로 환산</h2>
  <p style="margin-bottom:10px;">
    예를 들어, 25년 뒤에 자녀에게 4억원을 물려주려면, 인플레이션이 3%일 때 8억 3,751만원이 필요합니다
  </p>

  <div class="form-group">
    <label for="FV_B2">현재 가치</label>
    <input type="text" id="FV_B2" placeholder="예: 400,000,000" />
    <span>원</span>
    <span id="FV_B2_million" class="hint">(0원)</span>
  </div>
  <div class="form-group">
    <label for="FV_B3">인플레이션</label>
    <input type="number" id="FV_B3" placeholder="예: 3" step="0.1" />
    <span>%</span>
  </div>
  <div class="form-group">
    <label for="FV_B4">연수</label>
    <input type="number" id="FV_B4" placeholder="예: 25" />
    <span>년</span>
  </div>

  <div class="result">
    미래 가치: 
    <span id="FV_B5">0원</span>
    <span id="FV_B5Detail" class="detail">(0원)</span>
  </div>

  <!-- ===== JS: DOM 아래에 배치 ===== -->
  <script>
    /* (A) 열기/접기 버튼 JS */
    document.addEventListener("DOMContentLoaded", () => {
      const toggleBtn = document.getElementById("toggleUsageBtn");
      const usageBox = document.getElementById("usageBox");

      // 버튼/토글 기능
      toggleBtn.addEventListener("click", () => {
        if (usageBox.style.display === "none") {
          usageBox.style.display = "block";
        } else {
          usageBox.style.display = "none";
        }
      });
    });

    /* (B) 기존 JS 로직 (수정 금지) */
    let userModifiedFutureMoney = false;

    function formatKoreanUnits(valueInWon) {
      if (valueInWon < 10000) {
        return valueInWon.toLocaleString() + "원";
      }
      const UNIT_1MAN = 1e4;     
      const UNIT_1EOK = 1e8;     
      const UNIT_1JO  = 1e12;    
      const UNIT_1GYEONG = 1e16; 
      const UNIT_1HAE = 1e20;    

      if (valueInWon >= UNIT_1HAE) {
        return valueInWon.toLocaleString() + "원";
      } else if (valueInWon >= UNIT_1GYEONG) {
        const val = valueInWon / UNIT_1GYEONG;
        return val.toLocaleString(undefined, { maximumFractionDigits: 2 }) + "경원";
      } else if (valueInWon >= UNIT_1JO) {
        const val = valueInWon / UNIT_1JO;
        return val.toLocaleString(undefined, { maximumFractionDigits: 2 }) + "조원";
      } else if (valueInWon >= UNIT_1EOK) {
        const val = valueInWon / UNIT_1EOK;
        return val.toLocaleString(undefined, { maximumFractionDigits: 2 }) + "억원";
      } else {
        const val = valueInWon / UNIT_1MAN;
        return val.toLocaleString(undefined, { maximumFractionDigits: 2 }) + "만원";
      }
    }

    function formatInputAndDisplayUnit(id) {
      const inputElement = document.getElementById(id);
      let rawValueString = inputElement.value.replace(/,/g, "");
      let rawValue = parseFloat(rawValueString) || 0;
      let formattedValue = rawValue.toLocaleString();
      inputElement.value = formattedValue;
      const spanElement = document.getElementById(id + "_million");
      if (spanElement) {
        spanElement.textContent = "(" + formatKoreanUnits(rawValue) + ")";
      }
    }

    function calculateNeededMoney() {
      let rawC26 = document.getElementById('C26').value.replace(/,/g, "") || "0";
      let C26 = parseFloat(rawC26);
      let C27 = parseFloat(document.getElementById('C27').value) || 0;
      let C28 = parseInt(document.getElementById('C28').value) || 0;
      let C29 = parseFloat(document.getElementById('C29').value) || 0;

      let neededMoney = 0;
      let presentValue = 0;
      if (C27 > 0) {
        neededMoney = C26 * 12 * Math.pow(1 + C29/100, C28) / (C27/100);
      }
      if (neededMoney > 0) {
        presentValue = neededMoney / Math.pow(1 + C29/100, C28);
      }

      const neededMoneyRounded = isNaN(neededMoney) ? 0 : Math.round(neededMoney);
      const presentValueRounded = isNaN(presentValue) ? 0 : Math.round(presentValue);

      document.getElementById('C31').textContent = formatKoreanUnits(neededMoneyRounded);
      document.getElementById('C31Detail').textContent =
        "(" + neededMoneyRounded.toLocaleString() + "원)";

      document.getElementById('C32').textContent = formatKoreanUnits(presentValueRounded);
      document.getElementById('C32Detail').textContent =
        "(" + presentValueRounded.toLocaleString() + "원)";
    }

    function updateTipsText() {
      document.getElementById('tipsText').innerHTML = "";
    }

    function calculateRetirementAsset() {
      const rawB36 = document.getElementById('B36').value.replace(/,/g, "") || "0";
      const rawB37 = document.getElementById('B37').value.replace(/,/g, "") || "0";
      const B36 = parseFloat(rawB36);
      const B37 = parseFloat(rawB37);
      const B38 = parseInt(document.getElementById('B38').value) || 0;    
      const B39 = parseFloat(document.getElementById('B39').value) || 0; 
      const B40 = parseFloat(document.getElementById('B40').value) || 0; 

      const nominalRate = B39 / 100;
      const savingGrowthRate = B40 / 100;

      let result = 0;
      if (nominalRate === savingGrowthRate) {
        result = B36 * Math.pow(1 + nominalRate, B38)
               + B37 * B38 * Math.pow(1 + nominalRate, B38 - 1);
      } else {
        result = B36 * Math.pow(1 + nominalRate, B38)
               + B37 * (
                   ( Math.pow(1 + nominalRate, B38) - Math.pow(1 + savingGrowthRate, B38) )
                   / (nominalRate - savingGrowthRate)
                 );
      }

      const roundedResult = Math.round(result);
      document.getElementById('resultValue').textContent = formatKoreanUnits(roundedResult);
      document.getElementById('resultValueDetail').textContent =
        "(" + roundedResult.toLocaleString() + "원)";

      document.getElementById('periodYears').textContent = B38.toString();

      const B9Input = document.getElementById('B9');
      B9Input.value = roundedResult.toLocaleString();
      formatInputAndDisplayUnit('B9');

      calculatePresentValue();
      syncWithdrawalInputs();
      compareDreamAndRetirement();
    }

    function copyResultToClipboard() {
      const detailText = document.getElementById('resultValueDetail').textContent;
      const textToCopy = detailText.replace(/\(|\)/g, "");
      navigator.clipboard.writeText(textToCopy)
        .then(() => alert("복사 완료!"))
        .catch(() => alert("복사 실패!"));
    }

    function calculatePresentValue() {
      const rawB9  = document.getElementById('B9').value.replace(/,/g, "") || "0";
      const B9  = parseFloat(rawB9);
      const B10 = parseFloat(document.getElementById('B10').value) || 0; 
      const B11 = parseInt(document.getElementById('B11').value) || 0;

      const present = B9 / Math.pow((1 + B10/100), B11);
      const roundedPresent = Math.round(present);

      document.getElementById('presentValue').textContent = formatKoreanUnits(roundedPresent);
      document.getElementById('presentValueDetail').textContent =
        "(" + roundedPresent.toLocaleString() + "원)";
    }

    function calculateWithdrawal() {
      const rawB16 = document.getElementById('B16').value.replace(/,/g, "") || "0";
      const B16 = parseFloat(rawB16);
      const B17 = parseFloat(document.getElementById('B17').value) || 0;
      const B18 = parseFloat(document.getElementById('B18').value) || 0;
      const B19 = parseInt(document.getElementById('B19').value) || 0;

      document.getElementById('withdrawYears').textContent = B19.toString();

      let monthlyIncome = 0;
      if (B17 !== 0) {
        monthlyIncome = (B16 * (B17 / 100)) / 12;
      }
      const presentVal = monthlyIncome / Math.pow((1 + B18 / 100), B19) || 0;

      const roundedMonthly = Math.round(monthlyIncome);
      const roundedPresentVal = Math.round(presentVal);

      document.getElementById('possibleIncome').textContent = formatKoreanUnits(roundedMonthly);
      document.getElementById('possibleIncomeDetail').textContent =
        "(" + roundedMonthly.toLocaleString() + "원)";
      document.getElementById('withdrawPresentValue').textContent =
        formatKoreanUnits(roundedPresentVal);
      document.getElementById('withdrawPresentValueDetail').textContent =
        "(" + roundedPresentVal.toLocaleString() + "원)";
    }

    function syncWithdrawalInputs() {
      if (!userModifiedFutureMoney) {
        const rawB9 = document.getElementById('B9').value.replace(/,/g, "") || "0";
        document.getElementById('B16').value = parseFloat(rawB9).toLocaleString();
        formatInputAndDisplayUnit('B16');
      }
      calculateWithdrawal();
    }

    function syncFirstSectionToOthers() {
      const c27Val = parseFloat(document.getElementById('C27').value) || 0;
      const c28Val = parseInt(document.getElementById('C28').value) || 0;
      const c29Val = parseFloat(document.getElementById('C29').value) || 0;

      document.getElementById('B17').value = c27Val.toString();
      document.getElementById('B38').value = c28Val.toString();
      document.getElementById('B11').value = c28Val.toString();
      document.getElementById('B19').value = c28Val.toString();

      document.getElementById('B40').value = c29Val.toString();
      document.getElementById('B10').value = c29Val.toString();
      document.getElementById('B18').value = c29Val.toString();

      calculateNeededMoney();
      updateTipsText();         
      calculateRetirementAsset();
      calculatePresentValue();
      calculateWithdrawal();
    }

    function compareDreamAndRetirement() {
      let c31Detail = document.getElementById('C31Detail').textContent || "";
      let dreamMoney = parseInt(c31Detail.replace(/[^0-9]/g, "")) || 0;

      let retDetail = document.getElementById('resultValueDetail').textContent || "";
      let retirementAsset = parseInt(retDetail.replace(/[^0-9]/g, "")) || 0;

      const container = document.getElementById('retirementAssetContainer');
      const msgDiv = document.getElementById('retirementAssetMsg');

      if (dreamMoney === 0 || retirementAsset === 0) {
        container.style.backgroundColor = "transparent";
        msgDiv.innerText = "";
        return;
      }

      let diff = retirementAsset - dreamMoney;
      let absDiff = Math.abs(diff);
      let ratio = diff / dreamMoney;

      const diffReadable = formatKoreanUnits(absDiff);

      let bgColor = "transparent";
      let msg = "";

      if (diff < 0) {
        if (ratio <= -0.2) {
          bgColor = "#ffcccc";
        } else {
          bgColor = "#ffffcc";
        }
        msg = `${diffReadable}(${absDiff.toLocaleString()}원)이 <span style="color:red;">부족합니다</span>`;
      } else {
        if (ratio >= 0.2) {
          bgColor = "#ccffcc";
        } else {
          bgColor = "#ffffcc";
        }
        msg = `${diffReadable}(${absDiff.toLocaleString()}원)이 <span style="color:green;">남습니다</span>`;
      }

      container.style.backgroundColor = bgColor;
      msgDiv.innerHTML = msg;
    }

    // (J) 이벤트 리스너
    document.getElementById('C26').addEventListener('input', () => {
      formatInputAndDisplayUnit('C26');
      calculateNeededMoney();
      updateTipsText();
      compareDreamAndRetirement();
    });
    document.getElementById('C27').addEventListener('input', () => {
      calculateNeededMoney();
      syncFirstSectionToOthers();
    });
    document.getElementById('C28').addEventListener('input', () => {
      calculateNeededMoney();
      syncFirstSectionToOthers();
    });
    document.getElementById('C29').addEventListener('input', () => {
      calculateNeededMoney();
      syncFirstSectionToOthers();
    });

    document.getElementById('B36').addEventListener('input', () => {
      formatInputAndDisplayUnit('B36');
      calculateRetirementAsset();
    });
    document.getElementById('B37').addEventListener('input', () => {
      formatInputAndDisplayUnit('B37');
      calculateRetirementAsset();
    });
    document.getElementById('B38').addEventListener('input', calculateRetirementAsset);
    document.getElementById('B39').addEventListener('input', calculateRetirementAsset);
    document.getElementById('B40').addEventListener('input', calculateRetirementAsset);

    document.getElementById('copyResultBtn').addEventListener('click', copyResultToClipboard);

    document.getElementById('B9').addEventListener('input', () => {
      formatInputAndDisplayUnit('B9');
      calculatePresentValue();
      syncWithdrawalInputs();
    });
    document.getElementById('B10').addEventListener('input', () => {
      calculatePresentValue();
      syncWithdrawalInputs();
    });
    document.getElementById('B11').addEventListener('input', () => {
      calculatePresentValue();
      syncWithdrawalInputs();
    });

    document.getElementById('B16').addEventListener('input', () => {
      userModifiedFutureMoney = true;
      formatInputAndDisplayUnit('B16');
      calculateWithdrawal();
    });
    document.getElementById('B17').addEventListener('input', calculateWithdrawal);
    document.getElementById('B18').addEventListener('input', calculateWithdrawal);
    document.getElementById('B19').addEventListener('input', calculateWithdrawal);

    let userModifiedFV_B3 = false;
    let userModifiedFV_B4 = false;

    function calculateFutureValue() {
      const rawB2 = document.getElementById('FV_B2').value.replace(/,/g, "") || "0";
      const B2 = parseFloat(rawB2);

      const B3 = parseFloat(document.getElementById('FV_B3').value) || 0;
      const B4 = parseInt(document.getElementById('FV_B4').value) || 0;

      let futureVal = 0;
      if (B2 > 0 && B4 > 0) {
        futureVal = B2 * Math.pow(1 + B3/100, B4);
      }

      const roundedVal = Math.round(futureVal);
      document.getElementById('FV_B5').textContent = formatKoreanUnits(roundedVal);
      document.getElementById('FV_B5Detail').textContent =
        "(" + roundedVal.toLocaleString() + "원)";
    }

    document.getElementById('FV_B2').addEventListener('input', () => {
      formatInputAndDisplayUnit('FV_B2');
      calculateFutureValue();
    });
    document.getElementById('FV_B3').addEventListener('input', () => {
      userModifiedFV_B3 = true;
      calculateFutureValue();
    });
    document.getElementById('FV_B4').addEventListener('input', () => {
      userModifiedFV_B4 = true;
      calculateFutureValue();
    });

    document.getElementById('C28').addEventListener('input', syncFutureValueInputs);
    document.getElementById('C29').addEventListener('input', syncFutureValueInputs);

    function syncFutureValueInputs() {
      if (!userModifiedFV_B3) {
        const c29Val = parseFloat(document.getElementById('C29').value) || 0;
        document.getElementById('FV_B3').value = c29Val.toString();
      }
      if (!userModifiedFV_B4) {
        const c28Val = parseInt(document.getElementById('C28').value) || 0;
        document.getElementById('FV_B4').value = c28Val.toString();
      }
      calculateFutureValue();
    }

    // 초기 실행
    calculateNeededMoney();
    updateTipsText(); // 내용은 제거됨
    syncFirstSectionToOthers();
    syncFutureValueInputs();
  </script>
</body>
</html>
