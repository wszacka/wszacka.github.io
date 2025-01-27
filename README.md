<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My super page</title>
  <style>
    body {
      background-color: pink;
      text-align: center;
    }
    h1 {
      font-weight: bold;
      color:red
    }
    .last {
        font-weight: bold;
        font-size: large;
        color:orange
    }
    a {
        text-decoration: none;
        padding: 10px;
        color:blueviolet
    }
    table {
        margin: auto;
        border-collapse: collapse;
    }
    tr,td,th {
        border:1px solid black
    }
    tr:first-child{
        background-color: blueviolet;
    }
    tr {
        background-color: wheat;
    }
  </style>
</head>
<body>
    <h1>Witaj na mojej stronie!</h1>
    <p>Zastanawiales sie kiedys</p>
    <p>gdzie kupić gry w niskich cenach?</p>
    <p>Polecam te strony:</p>
    <a href='https://www.eneba.com/pl'>Eneba</a>
    <a href="https://www.g2a.com/pl">G2A</a>
    <a href="https://isthereanydeal.com">IsThereAnyDeal</a>
    <p>W tabeli znajdziesz moje opinie na temat niektórych gier</p>
    <table>
        <tr>
            <th>Nazwa</th>
            <td>Cena</td>
            <th>Grafika</th>
            <th>Lore</th>
            <th>Community</th>
            <th>Moja Ocena</th>
            <th>Czy polecam?</th>
        </tr>
        <tr>
            <td>Wiedźmin</td>
            <td>99,99zł</td>
            <td>9/10</td>
            <td>10/10</td>
            <td>7/10 (W4 incydent)</td>
            <td>10/10</td>
            <td>Tak</td>
        </tr>
        <tr>
            <td>The forest</td>
            <td>71,99zł</td>
            <td>7/10</td>
            <td>8/10</td>
            <td>8/10</td>
            <td>8/10</td>
            <td>Tak</td>
        </tr>
        <tr>
            <td>Valorant</td>
            <td>FREE</td>
            <td>6/10</td>
            <td>4/10 (almost nothing)</td>
            <td>2/10</td>
            <td>3/10</td>
            <td>Nie</td>
        </tr>
    </table>
    <p class="last">Dziekuje za uwage</p>
    <img src="https://ih1.redbubble.net/image.5005159817.8337/bg,f8f8f8-flat,750x,075,f-pad,750x1000,f8f8f8.u4.jpg" alt="like">
</body>
</html>
