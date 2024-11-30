# ISHTAR2.ORG
ISHTAR2 is Self employed platforms use Such As Intelligence Bot
<!DOCTYPE html>
<html>

<body onload="startTime()">

<h2>JavaScript Clock</h2>

<div id="txt"></div>

<script>
function startTime() {
  const today = new Date();
  let h = today.getHours();
  let m = today.getMinutes();
  let s = today.getSeconds();
  m = checkTime(m);
  s = checkTime(s);
  document.getElementById('txt').innerHTML =  h + ":" + m + ":" + s;
  setTimeout(startTime, 1000);
}

function checkTime(i) {
  if (i < 10) {i = "0" + i};  // add zero in front of numbers < 10
  return i;
}![Ishtar~3](https://github.com/user-attachments/assets/d02d92ef-86ef-4662-8fec-46b95b85bfba)
