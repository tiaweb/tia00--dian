<menu></menu>

<script>
	  
fetch("https://tiaweb.github.io/tiadian/yan")
  .then(response => {
    return response.text()
  })
  .then(data => {
    document.querySelector("menu").innerHTML = data;
  });

</script>
