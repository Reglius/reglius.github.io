<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: "Times New Roman", serif;
      margin: 0;
      background: #ECE6D6; /* soft cream to evoke oak interiors */
      color: #3B3B2B;       /* dark olive for readable text */
    }
    .wrapper {
      width: 800px;
      margin: 0 auto;
      background: #FFFFFF;
      border-left: 1px solid #8B4513; /* saddle brown borders */
      border-right: 1px solid #8B4513;
    }
    .header {
      background: #4F7942; /* forest green header */
      color: #FFFFFF;
      padding: 20px;
      border-bottom: 4px solid #8B4513; /* saddle brown accent */
    }
    .frontpage {
      padding: 20px;
      background-color: #F7F3EA; /* very light cream */
    }
    .content {
      padding: 20px;
    }
    .performance-table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
      table-layout: fixed;
    }
    .performance-table th,
    .performance-table td {
      border: 1px solid #4F7942; /* forest green lines */
      padding: 8px;
      text-align: center;
      width: 33%;
      color: #3B3B2B;
    }
    .performance-table th {
      background: #4F7942;
      color: #FFFFFF;
    }
    .performance-table tr:nth-child(even) {
      background: #F7F3EA;
    }
    .button {
      background: #8B4513; /* saddle brown buttons */
      color: #FFFFFF;
      padding: 8px 20px;
      border: 2px outset #8B4513;
      font-weight: bold;
      cursor: pointer;
      font-size: 1rem;
    }
    .button:hover {
      background: #6E2F0B; /* darker brown on hover */
    }
    .footer {
      background: #4F7942;
      color: #FFFFFF;
      padding: 10px;
      text-align: center;
      font-size: 12px;
    }

    @media (max-width: 820px) {
      .wrapper {
        width: 100%;
        max-width: 600px;
      }
      .header {
        text-align: center;
        padding: 15px;
      }
      .header table {
        width: 100%;
      }
      .header td {
        display: block;
        text-align: center;
        padding: 5px 0;
      }
      .button {
        width: 80%;
        max-width: 300px;
        padding: 10px 20px;
        margin: 10px auto;
        display: block;
      }
      .performance-table th,
      .performance-table td {
        display: block;
        width: auto;
      }
      .performance-table tr {
        margin-bottom: 10px;
        display: block;
      }
      h1 {
        font-size: 1.8rem;
        margin: 10px 0;
      }
      .content {
        padding: 15px;
      }
      ol {
        padding-left: 25px;
      }
      li {
        margin-bottom: 15px;
      }
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <div class="header">
      <table width="100%">
        <tr>
          <td>
            <font size="6">LEAWOOD OAKS</font>
          </td>
          <td align="right">
            <button class="button" onclick="window.location.href='https://forms.gle/KQMTeY1NNEveNAmJ9';">
              CONNECT WITH US
            </button>
          </td>
        </tr>
      </table>
    </div>

    <div class="content">
      <div class="frontpage">
        <center>
          <h1><font color="#4F7942">ALGORITHMIC</font></h1>
          <h1><font color="#4F7942">-- & --</font></h1>
          <h1><font color="#4F7942">MACHINE LEARNING</font></h1>
          <h1><font color="#4F7942">TRADING</font></h1>
        </center>
      </div>

      <table class="performance-table">
        <tr>
          <th>Annual Return*</th>
          <th>Minimum Investment</th>
          <th>Assets Under Management</th>
        </tr>
        <tr>
          <td><b>---%</b></td>
          <td><b>$---,---</b></td>
          <td><b>$---,---,---</b></td>
        </tr>
      </table>

      <hr>
      <h2><font color="#4F7942">READY TO GET STARTED?</font></h2>
      <ol>
        <li><b>CONTACT US</b><br>
            Reach out and let us understand your investment goals.</li>
        <li><b>INVEST FUNDS</b><br>
            Determine how much you’d like to allocate.</li>
        <li><b>WATCH IT GROW</b><br>
            Sit back and let our strategies at Leawood Oaks work for you.</li>
      </ol>

      <hr>
      <center>
        <table width="80%" cellpadding="10">
          <tr>
            <td align="center" bgcolor="#F7F3EA">
              <b>EAGER TO BEGIN?</b><br>
              <button class="button" onclick="window.location.href='https://forms.gle/KQMTeY1NNEveNAmJ9';">
                CONTACT US
              </button>
            </td>
          </tr>
        </table>
      </center>
    </div>

    <div class="footer">
      <font size="2">
        *Past Performance Does Not Guarantee Future Results
      </font>
    </div>
  </div>
</body>
</html>
