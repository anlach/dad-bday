<template>
  <div class="cake">
    <h2>Make a wish!</h2>
    <div id="outer-container">
      <div id="frosting"></div>
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
      <img src="../assets/candle.png" id="candle">
    </div>
    <div id="bottom-text">
      <h4>Candles are for viewing purposes only. Please do not attempt to extinguish the flames</h4>
      <h4>Confidentiality Note:  the information transmitted is intended for the person, persons, or entity to whom it is addressed, and may contain confidential, private and/or privileged material.  Any review, retransmission, or other use of this information by persons or entities other than the intended recipient is prohibited.  If you received this in error, please notify the original sender immediately by return e-mail and delete this message and any attachments from your computer.  This message is and effort to protect the confidentiality of this transmission and does not constitute a guarantee.  Thank you.</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: 'cake',
  props: {
    msg: String
  }
}
</script>

<style >
#outer-container {
  width: 300px;
  height: 350px;
  margin-left: auto; 
  margin-right: auto;
}
#frosting {
  border-radius: 50px;
  width: 310px;
  height: 310px;
  margin-left: auto; 
  margin-right: auto;
  position: relative;
  top: 50px;
  z-index: -1;
  background: rgba(36, 22, 9, 0.959);
}
#candle {
  position: relative;
  bottom: 300px;
  left: 5px;
}
#bottom-text {
  width: 600px;
  margin-left: auto; 
  margin-right: auto;
}
h4 {
  text-align: left;
}
</style>
