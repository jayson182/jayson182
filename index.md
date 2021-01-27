<script>
let url = 'https://api.sheety.co/d453d8dc73dbbd69a3e9fcfa5a115e10/copyOfSsDeviantsGroupGames/sheet1';
fetch(url)
.then((response) => response.json())
.then(json => {
  // Do something with the data
  console.log(json.sheet1S);
});
  </script>
