<template>
  <div class="column">
    <div class="title">
      <h1>Vue Simple Chatbot</h1>
    </div>
    <div class="subtitle">
      <p>A simple vue chatbot component</p>
    </div>
    <div class="social-button">
      <img src="/vue-chat img/Faceboock.png" alt="Facebook">
      <img src="/vue-chat img/twitter.png" alt="Tweet">
    </div>
    <div class="button">
      <div class="statistics">
        <a class="statistics__element" href="#">
          <span class="statistics__element_key">
            <img src="" width="50" height="50" alt="Пример">
          </span>
          <span class="statistics__element_value">
            <img src="" width="50" height="50" alt="Пример">
          </span>
        </a>
        <a class="statistics__element" href="#">
          <span class="statistics__element_key">
            <img src="" width="50" height="50" alt="Пример">
          </span>
          <span class="statistics__element_value">
            <img src="" width="50" height="50" alt="Пример">
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
  color: #4a4a4a;
  margin: auto;
}
.subtitle {
  text-align: center;
}
.subtitle p {
  font-size: 23px;
  color: #4a4a4a;
  margin: auto;

}
.social-button {
  align-items: center;
  margin-top: 24px;
}
.social-button img {
}
.button {
  margin: 24px 0 24px 32px;
  text-align: center;
}
.statistics {

}
.statistics__element {

}
.statistics__element_key {

}
.statistics__element_key img {

}
.statistics__element_value {

}
.statistics__element_value img {

}
.documentation {

}
.button__docs {
  border: 2px solid #fff;
  border-radius: 30px;
  padding: 12px 32px;
  color: #fff;
  margin: 16px 0;
  cursor: pointer;
}
</style>