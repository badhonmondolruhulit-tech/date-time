# date-time
  &lt;script src="./js/bootstrap.bundle.min.js">&lt;/script>   &lt;script> setInterval(() => {     let d = new Date();     document.getElementById("clock").innerHTML =         d.toLocaleTimeString() + " | " + d.toDateString(); }, 1000); &lt;/script>
