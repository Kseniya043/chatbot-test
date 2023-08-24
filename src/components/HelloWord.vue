<template>
  <div class="column">
    <div class="title">
      <h1>Vue Simple Chatbot</h1>
    </div>
    <div class="subtitle">
      <p>A simple vue chatbot component</p>
    </div>
    <div class="social-button">
      <a class="social-button__facebook" href="#" >
      <img src="../assets/img/Facebook.png" alt="Facebook">
      </a>
      <a class="social-button__twitter" href="#">
        <img src="../assets/img/twitter.png" alt="Tweet">
      </a>
    </div>
    <div class="button">
      <div class="statistics">
        <a class="statistics__element" href="#">
          <span class="statistics__element_key">
            <img src="../assets/img/git.png" width="50" height="50" alt="Пример">
            <p>Star</p>
          </span>
          <div class="triangle-left"></div>
          <span class="statistics__element_value">
            <p>1,623</p>
          </span>
        </a>
        <a class="statistics__element" href="#">
          <span class="statistics__element_key">
            <img src="../assets/img/git.png" width="50" height="50" alt="Пример">
            <p>Fork</p>
          </span>
          <div class="triangle-right"></div>
          <span class="statistics__element_value">
            <p>576</p>
          </span>
        </a>
      </div>
    </div>
    <div class="documentation">
      <a class="button__docs">Documentation</a>
    </div>
  </div>
</template>

<script>
</script>
<style>

.column {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.title {
  text-align: center;
}
.title h1 {
  font-size: 39px;
  color: #fff;
  margin: auto;
}
.subtitle {
  text-align: center;
}
.subtitle p {
  font-size: 23px;
  color: #fff;
  margin: auto;

}
.social-button {
  display: flex;
  justify-content: center;
  margin-top: 24px;
  gap: 20px;
  align-items: center;
}
.social-button__facebook {
  width: 120px;
}
.social-button__twitter {
  width: 35px;
}
.social-button__facebook img {
  border-radius: 3px;
  width: 90%;
  background: white;
  padding: 4px;
}
.social-button__twitter img {
  width: 80%;
  border-radius: 3px;
}
.button {
  margin: 24px 0 0 32px;
  text-align: center;
}
.statistics {
  display: flex;
  justify-content: space-between;
}
.statistics__element {
  display: flex;
  text-decoration: none;
  position: relative;

}
.statistics__element_key {
  display: flex;
  align-items: center;
  background: #eee;
  padding: 3px 10px 3px 8px;
  line-height: 22px;
  border-radius: 4px;
}
.statistics__element_key img {
  width: 20px;
  height: 20px;
  margin: 0 4px 0 0;

}
.statistics__element_key p {
  font-size: 16px;
  color: black;
  margin: 0;
  padding: 0;
}
.statistics__element_value {
  background: #eee;
  padding: 3px 10px 3px 8px;
  line-height: 22px;
  border-radius: 4px;
  margin: 0 0 0 6px;
}

.statistics__element_value p {
  font-size: 16px;
  color: black;
  margin: 0;
  padding: 0;

}
.documentation {
  margin: 36px 0 0;
}
.button__docs {
  border: 2px solid #fff;
  border-radius: 30px;
  padding: 12px 32px;
  color: #fff;
  margin: 16px 0;
  cursor: pointer;
}
.triangle-right::after {
  content: '';
  position: absolute;
  top:10px;
  right: 42px;
  border: 4px solid transparent; /* Прозрачные границы */
  border-right: 4px solid white; /* Добавляем треугольник */
  color: #fff;
}
.triangle-left::after {
  content: '';
  position: absolute;
  top:10px;
  right: 54px;
  border: 4px solid transparent; /* Прозрачные границы */
  border-right: 4px solid white; /* Добавляем треугольник */
  color: #fff;
}
</style>