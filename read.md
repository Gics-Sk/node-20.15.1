Pour reproduire le style de tableau utilisé par Bootstrap avec les classes `table` et `table Thead` en CSS pur, voici un exemple de code :

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tableau avec CSS pur</title>
<style>
/* Styles pour le tableau */
.table {
  width: 100%;
  border-collapse: collapse;
  border: 1px solid #ccc;
}

.table th, .table td {
  border: 1px solid #ccc;
  padding: 8px;
  text-align: left;
}

.table th {
  background-color: #f2f2f2;
}

.table Thead th {
  background-color: #e6e6e6;
  font-weight: bold;
}
</style>
</head>
<body>

<table class="table">
  <thead>
    <tr>
      <th>Heading 1</th>
      <th>Heading 2</th>
      <th>Heading 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Row 1 Data 1</td>
      <td>Row 1 Data 2</td>
      <td>Row 1 Data 3</td>
    </tr>
    <tr>
      <td>Row 2 Data 1</td>
      <td>Row 2 Data 2</td>
      <td>Row 2 Data 3</td>
    </tr>
    <tr>
      <td>Row 3 Data 1</td>
      <td>Row 3 Data 2</td>
      <td>Row 3 Data 3</td>
    </tr>
  </tbody>
</table>

</body>
</html>
```

Ce code définit un style de tableau simple avec des bordures, un fond de couleur pour l'en-tête (`thead`), et des cellules bien alignées et espacées. Vous pouvez ajuster les couleurs, les espacements et d'autres propriétés CSS selon vos besoins spécifiques.