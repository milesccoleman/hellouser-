<template>
  <body>
    <h1>{{ msg }}</h1>
  </body>
</template>

<script>
var msg = prompt('What is your name?')
document.write('Oh my gosh, ' + msg + ', we just made a unique web experience together!')
</script>

<style>
body {
background-color: #f0db4f;
font-family: sans-serif;
text-align: center;
color: #323330;
font-size:  100px;
}
h1 {
margin-top: -150px;
}
</style>
