# 2A1_1004
Website for Class Routine table
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>2A1 Class Routine</title>
 <link rel="stylesheet" href="style.css">
</head>
<body>
<table>
  <thead>
    <tr>
      <th>2A</th>
      <th>08:00-09:00</th>
      <th>09:00-10:00</th>
      <th>10:00-11:00</th>
      <th>11:00-12:00</th>
      <th>12:00-01:00</th>
      <th>01:00-02:00</th>
      <th>02:00-03:00</th>
      <th>03:00-04:00</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sunday</td>
      <td class="pink">MATH0541121-2A-ST-413</td>
      <td class="yellow" colspan="2">CSE0613121-2A-EMSH-602</td>
      <td class="lightpink" colspan="3">CSE0613124-2A-FTTE,SAU-411</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
        <td rowspan="2">Monday</td>
        <td class="pink" rowspan="2">GED02 22121-2A-ZS-B203</td>
        <td class="lightyellow" rowspan="2" colspan="2">EEE0713121-2A-MUH-603</td>
        <td rowspan="2"></td>
        <td class="lightyellow" colspan="2">EEE0713122-2A1-ABH-502</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td class="purple"  colspan="2">ME0715122-2A2-SSCE-210</td>
        <td></td> 
    </tr>
      <td>Tuesday</td>
      <td class="gray" colspan="8"></td>
    </tr>
    <tr>
      <td>Wednesday</td>
      <td class="pink" colspan="3">CSE0541123-2A-DMK-B203</td>
      <td class="pink" colspan="2">MATH0541121-2A-ST-203</td>
      <td></td>
      <td></td>
      <td class="yellow">CSE0613121-2A-EMSH-602</td>
    </tr>
<tr>
        <td rowspan="2">Thursday</td>
        <td class="pink"rowspan="2">GED0222121-2A-ZS-B203</td>
        <td colspan="2" class="purple">ME0715122-2A1-MTS-210</td>
        <td class="lightyellow"rowspan="2">EEE0713121-2A-MUH-509</td>
        <td class="yellow" rowspan="2" colspan="3">CSE0613121-2A-EMSH,KNA-411</td>
        <td rowspan="2"></td>
    </tr>
    <tr>
    <td class="lightyellow" colspan="2">EEE0713122-2A2--504</td>
    </tr>
  </tbody>
</table>
</body>
</html>

  body 
  {
    font-family: Arial, sans-serif;
    margin: 20px;
    background-color: #f9f9f9;
  }
  table 
  {
    border-collapse: collapse;
    width: 100%;
    max-width: 100%;
    table-layout: fixed;
    font-size: 14px;
    box-shadow: 0 0 10px rgb(0 0 0 / 0.1);
    background: #fff;
  }
  th, td {
    border: 1px solid #999;
    padding: 6px 8px;
    text-align: center;
    vertical-align: middle;
    word-wrap: break-word;
    overflow-wrap: break-word;
  }
  th {
    background-color: #31c7d9;
    color: black;
    font-weight: 600;
    letter-spacing: 0.03em;
  }
  td:first-child {
    background-color: #f4f4f4;
    text-align: center;
    padding-left: 12px;
    white-space: nowrap;
  }
  .pink {
    background-color: #f2c7c7;
  }
  .yellow {
    background-color: #ffe48d;
  }
  .lightyellow {
    background-color: #fff4ccf1;
  }
  td.lightyellow {
    background-color: #fff4cc !important;
  }
  .gray  {
    background-color: 	#636363;
  }
  .lightpink {
    background-color: rgb(249,195,178);
  }
.purple {
  background-color: #f8bae9;
}
