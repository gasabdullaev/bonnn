<html><head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8">
  <title></title>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8">
  <meta name="robots" content="noindex, nofollow">
  <meta name="googlebot" content="noindex, nofollow">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <script type="text/javascript" src="/js/lib/dummy.js"></script>

    <link rel="stylesheet" type="text/css" href="/css/result-light.css">


  <style id="compiled-css" type="text/css">
      
  </style>
</head>
<body>
    <b>Street: </b>
<input type="text" value="2435 W Division St" id="Street">
<button onclick="Street()">Скопировать</button>
<br>

<b>City: </b>
<input type="text" value="Chicago" id="City">
<button onclick="City()">Скопировать</button>
<br>

<b>State: </b>
<input type="text" value="IL" id="State">
<button onclick="City()">Скопировать</button>
<br>

<b>Zip: </b>
<input type="text" value="60622" id="Zip">
<button onclick="City()">Скопировать</button>
<br>

<b>Телефон: </b>
<input type="text" value="2318984455" id="Phone">
<button onclick="City()">Скопировать</button>
<br>


<script type="text/javascript">


function Street() {
  /* Get the text field */
  var copyText = document.getElementById("Street");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
}

function City() {
  /* Get the text field */
  var copyText = document.getElementById("City");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
}

function State() {
  /* Get the text field */
  var copyText = document.getElementById("State");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
}

function Zip() {
  /* Get the text field */
  var copyText = document.getElementById("Zip");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
}

function Phone() {
  /* Get the text field */
  var copyText = document.getElementById("Phone");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
}
</body></html>