<template>
    <div id="Contact">
    <h2>&#8659; Pour toute collaboration 	&#8659;</h2>
    
<form action="#">
  <p><i>Complétez le formulaire. Les champs marqué par </i><em>*</em> sont <em>obligatoires</em></p>
  <fieldset>
    <legend>Contact</legend>
      <label for="nom">Nom <em>*</em></label>
      <input id="nom" placeholder="Entrez votre nom ici" autofocus="" required=""><br>

      <label for="telephone">Portable</label>
      <input id="telephone" type="tel" placeholder="06xxxxxxxx" pattern="06[0-9]{8}"><br>

      <label for="email">Email <em>*</em></label>
      <input  id="email" type="email" placeholder="Entrez votre email ici" required="">
      </fieldset>

      <fieldset>
    <legend>Message</legend>
      
      <label for="comments">Ecrivez votre message</label>
      <textarea id="comments"></textarea> <br>

      <input id="submit" type="submit" value="Valider">
  </fieldset>
      </form>
    
    </div>
</template>

<style scoped>
#Contact {
    display: flex;
    align-items: center;
    flex-direction: column;
    border-radius: 25px;
    color: antiquewhite;
    background-color: black;
    padding: 20px;
    margin: 20px;
    opacity: 0.8;
}
#Contact:hover {
    opacity: 1;
}



 
fieldset {
  margin-bottom: 15px;
  padding: 10px;
}
 
legend {
  padding: 0px 3px;
  font-weight: bold;
  font-variant: small-caps;
}
 
label {
  width: 110px;
  display: inline-block;
  vertical-align: top;
  margin: 6px;
}
 
em {
  font-weight: bold;
  font-style: normal;
  color: #f00;
}
 #submit {
    border-radius: 25px;
    cursor: pointer;
    margin-top: 10px;
 }
 #submit:focus {
    background-color: green;
 }
input:focus {
  background: #eaeaea;
  border-radius: 30px;
}
 
input, textarea {
  width: 249px;
}
 
textarea {
  height: 100px;
  resize: none;
}
 
input[type=submit] {
  width: 150px;
  padding: 10px;
}
#output {
  text-align: center;
}



</style>

<script setup>

  </script>