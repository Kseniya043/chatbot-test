<template>
  <div class="column">
    <div class="rsc">
      <div class="rsc-greetings">
        <img src="../assets/svg/robot.svg" alt="robot">
        <p>Welcome to chatbot!</p>
      </div>
      <div class="rsc-documentation">
        <p>Check out the documentation!</p>
      </div>
      <div class="rsc-start">
        <p>Go it!</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ChatBot"
}
</script>

<style>
.rsc {
  background: rgb(245, 248, 251);
  border-radius: 10px;
  font-family: monospace;
  margin-top: 2px;
  padding-top: 6px;
}
.rsc-greetings {
  display: flex;
}
.rsc-greetings img {
  padding: 6px;
  width: 46px;
  height: 46px;
}
.rsc-greetings p {
  animation: 0.3s ease 0s 1 normal forwards running Lmuha;
  background: rgb(110, 72, 170);
  border-radius: 18px 18px 18px 0px;
  color: rgb(255, 255, 255);
  font-size: 14px;
  margin: 0px 0px 10px;
  padding: 12px;
}
.rsc-documentation {
  align-items: flex-end;
  display: flex;

}
.rsc-documentation p {
  animation: 0.3s ease 0s 1 normal forwards running Lmuha;
  background: rgb(110, 72, 170);
  border-radius: 0px 18px 18px;
  color: rgb(255, 255, 255);
  font-size: 14px;
  max-width: 50%;
  margin: -8px 0px 10px 46px;
  padding: 12px;
}
.rsc-start {
  align-items: flex-end;
  display: flex;
}
.rsc-start p {
  animation: 0.3s ease 0s 1 normal forwards running Lmuha;
  background: rgb(110, 72, 170);
  border-radius: 0px 18px 18px;
  color: rgb(255, 255, 255);
  font-size: 14px;
  margin: -5px 0px 10px 20px;
  padding: 10px;
}
</style>