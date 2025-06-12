<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RailLog Korea 2025 展商資訊</title>
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #003366;
      color: white;
      padding: 1.5em;
      text-align: center;
      font-size: 1.8em;
    }
    main {
      padding: 2em;
    }
    .exhibitor-table {
      width: 100%;
      border-collapse: collapse;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .exhibitor-table th, .exhibitor-table td {
      border: 1px solid #ddd;
      padding: 0.75em;
      text-align: left;
    }
    .exhibitor-table th {
      background: #005288;
      color: white;
    }
    .exhibitor-table tr:nth-child(even) {
      background: #f1f1f1;
    }
    .image-container {
      text-align: center;
      margin-bottom: 2em;
    }
    .image-container img {
      max-width: 100%;
      height: auto;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <header>
    RailLog Korea 2025 展商資訊總覽
  </header>
  <main>
    <div class="image-container">
      <img src="RailLogKorea2025.webp.1024.png" alt="展館配置圖">
    </div>
    <table class="exhibitor-table">
      <thead>
        <tr>
          <th>攤位號</th>
          <th>公司名稱</th>
          <th>國家</th>
          <th>主要產品</th>
          <th>主要客戶</th>
          <th>公司規模</th>
        </tr>
      </thead>
      <tbody>
        <!-- 資料將由 JavaScript 動態載入 -->
      </tbody>
    </table>
  </main>
  <script>
    const data = [
      {
    "攤位號": "A04",
    "公司": "DEMCO CSI",
    "國家": "韓國",
    "主要產品": "戶外高亮度 TFT‑LCD 資訊顯示器",
    "主要客戶": "機場、鐵路及公車站",
    "公司規模": "中型"
  },
  {
    "攤位號": "A05",
    "公司": "YK Construction Equipment Co., Ltd.",
    "國家": "韓國",
    "主要產品": "工程與軌道施工機械租售",
    "主要客戶": "韓國土木、軌道承包商",
    "公司規模": "中型"
  },
  {
    "攤位號": "A06",
    "公司": "SPACEPRO",
    "國家": "韓國",
    "主要產品": "碳纖維車體複材結構",
    "主要客戶": "韓國高鐵與航太供應鏈",
    "公司規模": "小型"
  },
  {
    "攤位號": "A07",
    "公司": "Hyundai Rotem Company",
    "國家": "韓國",
    "主要產品": "高速列車、電聯車、號誌系統",
    "主要客戶": "KORAIL、台灣高鐵、英國 TfL 等",
    "公司規模": "大型"
  },
  {
    "攤位號": "B01",
    "公司": "Electronic & Human Technology",
    "國家": "韓國",
    "主要產品": "車載連接器、感測器整合",
    "主要客戶": "船舶、軌道、自動化設備商",
    "公司規模": "微型"
  }
    ];

    const tbody = document.querySelector(".exhibitor-table tbody");
    data.forEach(row => {
      const tr = document.createElement("tr");
      tr.innerHTML = `
        <td>${row["攤位號"]}</td>
        <td>${row["公司"]}</td>
        <td>${row["國家"]}</td>
        <td>${row["主要產品"]}</td>
        <td>${row["主要客戶"]}</td>
        <td>${row["公司規模"]}</td>
      `;
      tbody.appendChild(tr);
    });
  </script>
</body>
</html>
