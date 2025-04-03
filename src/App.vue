<template>
  <div id="app" class="container">
    <header>
      <h1>個人簡歷</h1>
    </header>
    
    <section class="info">
      <h2>個人資訊</h2>
      <img src="/CAI_YU_FENG.jpg" alt="個人照片" class="profile-photo">
      <p><strong>姓名:</strong> 蔡育灃</p>
      <p><strong>聯絡方式:</strong> <a href="mailto:a0985541606@gmail.com">a0985541606@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/as985643" target="_blank">github.com/as985643</a></p>
    </section>
    
    <section class="education">
      <h2>教育背景</h2>
      <ul>
        <li>2019/1 - 2022/6, 國立虎尾科技大學, 機械設計工程系</li>
        <li>2022/9 - 2025/1, 國立虎尾科技大學, 機械設計工程系碩士班</li>
      </ul>
    </section>
    
    <section class="projects">
      <h2>專案經驗</h2>
      <ul>
        <li>
          <strong>自主移動機器人開發與應用</strong> - 在碩士期間專注於自主移動機器人的開發與應用，具備機器人控制、感測技術與路徑規劃等相關經驗，熟悉 ROS 與 SLAM 技術，對機器人技術及其應用充滿熱情。
        </li>
        <li>
          <strong>個人簡歷網站開發</strong> - 使用 Vue.js 搭建響應式個人簡歷網站，優化 UI/UX 設計。
        </li>
      </ul>
    </section>
    
    <section class="skills">
      <h2>擅長的程式</h2>
      <ul>
        <li>Python、ROS、影像辨識</li>
      </ul>
      <h2>目前學習中</h2>
      <ul>
        <li>HTML, CSS, JavaScript、c++</li>
        <li>Vue.js, React</li>
      </ul>
    </section>
    
    <section class="design">
      <h2>繪圖</h2>
      <ul>
        <li>SolidWorks、AutoCAD</li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style scoped>
#app {
  background-color: #000000; /* 全黑背景 */
  color: #DDDDDD; /* 文字改成淡灰，避免對比過強 */
  max-width: 800px; /* 限制最大寬度 */
  margin: 40px auto; /* 讓內容置中 */
  padding: 20px;
  border-radius: 10px; /* 圓角邊框 */
  box-shadow: 0px 0px 15px rgba(255, 255, 255, 0.1); /* 加點陰影讓它更有層次感 */
}

body {
  font-family: 'Roboto', Arial, sans-serif;
  background-color: #000000; /* 背景全黑 */
  color: #DDDDDD;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh; /* 讓內容在畫面中央 */
}

header {
  background-color: #181818; /* 標題區塊深灰色，區分內容 */
  color: #FFFFFF; /* 標題純白 */
  padding: 20px;
}

h2 {
  border-bottom: 2px solid #42b983;
  padding-bottom: 5px;
  margin-bottom: 15px;
}

section {
  background-color: #181818; /* 區塊區分 */
  padding: 15px;
  margin: 10px;
  border-radius: 10px;
}

ul {
  list-style-type: none;
  padding: 0;
}

ul li {
  background: #1e3d32; /* 改為較柔和的深綠 */
  color: #ffffff;
  padding: 12px;
  margin: 6px 0;
  border-radius: 8px;
  transition: background 0.3s ease-in-out;
}

ul li:hover {
  background: #2a5d44; /* 滑鼠懸停時變亮 */
}


a {
  color: #42b983;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.profile-photo {
  width: 150px; /* 照片寬度 */
  height: 150px; /* 照片高度 */
  border-radius: 50%; /* 讓圖片變成圓形 */
  object-fit: cover; /* 確保圖片不變形 */
  display: block;
  margin: 0 auto 15px; /* 讓圖片置中，並加點間距 */
  border: 3px solid #42b983; /* 加上外框 */
}

</style>
