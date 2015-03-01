# algorithm1
<!DOCTYPE html>
<html>
  <head>
    <title>TEST</title>
    <script type="text/javascript" src="jquery-1.11.2.js"></script>
    <script type="text/javascript" src="uf.js"></script>
    <style>
      p {padding: 0px;}
      #howMany {text-align: center;}
      #headers {margin-left: 120px;}
      #pqResult {margin-left: 20px;}
    </style>
  </head>
  <body onload="resetAll()">

    <p> N: 
      <input id="howMany" type="text" size="3" value="10" autocomplete="off">
      <button id="btnReady" onclick="getReady()">Ready</button>
      <button id="btnReset" onclick="location.reload()" disabled>Reset</button>
      <input type=submit id="going" onClick="ok()" value="Go">
    </p>
    <p>  
      <input type='radio' name='choice' value="qf">Quick Find
      <input type='radio' name='choice' value="qu">Quick Union
      <input type='radio' name='choice' value="wqu">W. Quick UF  
    </p>
    <div id="headers"></div>
    <div id="pqResult"></div>

  </body>
</html>
