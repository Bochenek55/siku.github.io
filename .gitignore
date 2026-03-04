}
@keyframes migaj{
  0%{opacity:1}
  50%{opacity:0.2}
  100%{opacity:1}
}
</style>
</head>
<body>

<div id="okno">
<h1>Analiza systemu...</h1>
<p id="status">Trwa skanowanie</p>
<button onclick="start()">Uruchom test</button>
</div>

<script>
function start(){
  document.getElementById("status").textContent = "Błąd krytyczny...";
  document.body.classList.add("blink");

  setTimeout(()=>{
    document.getElementById("status").textContent =
      "Spokojnie 😄 To tylko żart. Naciśnij dowolny klawisz.";
  },3000);
}

document.addEventListener("keydown", ()=>{
  document.body.classList.remove("blink");
  document.getElementById("status").textContent = "System działa normalnie.";
});
</script>

</body>
</html>
