<!DOCTYPE html>
<html lang="eu">
<head>
  <meta charset="UTF-8">
  <title>Ordutegia</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #fafafa;
    }

    table {
      margin: 20px auto;
      border-collapse: collapse;
      font-size: 16px;
    }

    th, td {
      border: 1px solid #888;
      padding: 10px 15px;
      min-width: 90px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    td:hover {
      transform: scale(1.1);
    }

    th {
      background-color: #00aaff;
      color: white;
    }

    .matematika { background-color: #00ccff; }
    .eus { background-color: #66cc99; }
    .fisikimi { background-color: #b0e0e6; }
    .biziki { background-color: #f5e050; }
    .gh { background-color: #8dc63f; }
    .gizarte { background-color: #e68cbf; }
    .ingles { background-color: #ff9999; }
    .bazkadu { background-color: #f3e5f5; font-weight: bold; }
    .gazte { background-color: #f39c12; }
    .digit { background-image: linear-gradient(to right, #00ffff, violet); color: black; }
    .tekno { background-color: #66ccff; }

  </style>
</head>
<body>

  <h1>Ordutegia</h1>

  <table>
    <tr>
      <th>Ordua</th>
      <th>Astelehena</th>
      <th>Asteartea</th>
      <th>Asteazkena</th>
      <th>Osteguna</th>
      <th>Ostirala</th>
    </tr>
    <tr>
      <td>08:30</td>
      <td class="matematika">Matematika</td>
      <td class="matematika">Matematika</td>
      <td class="eus">Euskera</td>
      <td class="gh">GH</td>
      <td class="matematika">Matematika</td>
    </tr>
    <tr>
      <td>09:30</td>
      <td class="eus">Euskera</td>
      <td class="fisikimi">Fisikimi</td>
      <td class="biziki">Biziki</td>
      <td class="gh">GH</td>
      <td class="eus">Euskera</td>
    </tr>
    <tr>
      <td>10:30</td>
      <td colspan="5">Patio</td>
    </tr>
    <tr>
      <td>11:00</td>
      <td class="fisikimi">Fisikimi</td>
      <td class="gizarte">Gizarte</td>
      <td class="gizarte">Gizarte</td>
      <td class="digit">Digit</td>
      <td class="gizarte">Gizarte</td>
    </tr>
    <tr>
      <td>12:00</td>
      <td class="ingles">Ingles</td>
      <td class="ingles">Ingles</td>
      <td class="digit">Digit</td>
      <td class="ingles">Ingles</td>
      <td class="fisikimi">Fisikimi</td>
    </tr>
    <tr>
      <td>13:00</td>
      <td colspan="5" class="bazkadu">Bazkaldu</td>
    </tr>
    <tr>
      <td>14:30</td>
      <td class="gazte">Gazte</td>
      <td class="gazte">Gazte</td>
      <td class="gazte">Gazte</td>
      <td class="matematika">Matematika</td>
      <td class="tekno">Tekno</td>
    </tr>
    <tr>
      <td>15:30</td>
      <td class="digit">Digit</td>
      <td class="tekno">Tekno</td>
      <td class="tekno">Tekno</td>
      <td class="eus">Euskera</td>
      <td class="gazte">Gazte</td>
    </tr>
  </table>

</body>
</html>
