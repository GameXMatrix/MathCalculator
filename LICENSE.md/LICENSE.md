<script>
function calculate_this() {
  var input = document.getElementById('numbers').value;
  var results = eval(input);
  document.getElementById('results').innerHTML = results;
}
</script>

Calculator: <input type="text" id="numbers" >
<input type=button value="Calculate" onClick="calculate_this()"><br>
Answer: <span id="results"></span>
