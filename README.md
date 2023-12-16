- 👋 Hi, I’m @luno25
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
luno25/luno25 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
    <title>Formulaire de coordonnées bancaires</title>
</head>
<body>

<h2>Entrez vos coordonnées bancaires :</h2>

<form action="/traitement-des-donnees" method="post">
    <label for="nom">Nom sur la carte :</label>
    <input type="text" id="nom" name="nom" required><br><br>
    
    <label for="numero_carte">Numéro de carte :</label>
    <input type="text" id="numero_carte" name="numero_carte" required><br><br>
    
    <label for="date_expiration">Date d'expiration :</label>
    <input type="text" id="date_expiration" name="date_expiration" placeholder="MM/AA" required><br><br>
    
    <label for="code_securite">Code de sécurité :</label>
    <input type="text" id="code_securite" name="code_securite" required><br><br>
    
    <input type="submit" value="Soumettre">
</form>

</body>
</html>
