<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Restaurant Analytics Dashboard</title>

  <style>
    body{
      font-family: Arial, sans-serif;
      background:#f4f6f9;
      margin:0;
      padding:0;
      color:#333;
    }

    .container{
      width:90%;
      max-width:1100px;
      margin:40px auto;
      background:#fff;
      padding:40px;
      border-radius:12px;
      box-shadow:0 4px 12px rgba(0,0,0,0.1);
    }

    h1{
      text-align:center;
      color:#1f4e79;
      margin-bottom:10px;
    }

    .subtitle{
      text-align:center;
      color:#666;
      margin-bottom:40px;
    }

    h2{
      color:#1f4e79;
      border-bottom:2px solid #e5e5e5;
      padding-bottom:8px;
      margin-top:35px;
    }

    p{
      line-height:1.7;
    }

    table{
      width:100%;
      border-collapse:collapse;
      margin-top:20px;
    }

    table th{
      background:#1f4e79;
      color:white;
      padding:12px;
      text-align:left;
    }

    table td{
      padding:12px;
      border-bottom:1px solid #ddd;
    }

    ul{
      line-height:1.8;
    }

    .footer{
      text-align:center;
      margin-top:40px;
      color:#777;
      font-size:14px;
    }

    .badge{
      display:inline-block;
      background:#1f4e79;
      color:white;
      padding:8px 14px;
      border-radius:20px;
      margin:5px;
      font-size:14px;
    }

  </style>
</head>
<body>

  <div class="container">

    <h1>Restaurant Analytics Dashboard</h1>

    <p class="subtitle">
      Interactive Excel Dashboard for Restaurant Business Analysis
    </p>

    <h2>Project Overview</h2>

    <p>
      This project is an interactive Restaurant Analytics Dashboard created using Microsoft Excel.
      The dashboard helps analyze restaurant business performance, customer engagement,
      online ordering trends, ratings, voting patterns, and dining costs through
      dynamic visualizations and interactive filters.
    </p>

    <h2>Dataset Columns Used</h2>

    <table>
      <tr>
        <th>Column Name</th>
        <th>Description</th>
      </tr>

      <tr>
        <td>name</td>
        <td>Restaurant name</td>
      </tr>

      <tr>
        <td>online_order</td>
        <td>Availability of online ordering</td>
      </tr>

      <tr>
        <td>book_table</td>
        <td>Table booking availability</td>
      </tr>

      <tr>
        <td>rate</td>
        <td>Restaurant rating</td>
      </tr>

      <tr>
        <td>votes</td>
        <td>Customer votes received</td>
      </tr>

      <tr>
        <td>approx_cost(for two people)</td>
        <td>Approximate dining cost for two people</td>
      </tr>

      <tr>
        <td>listed_in(type)</td>
        <td>Restaurant category/type</td>
      </tr>
    </table>

    <h2>Dashboard Features</h2>

    <ul>
      <li>Interactive slicers for restaurant category filtering</li>
      <li>Customer vote analysis</li>
      <li>Average rating comparison</li>
      <li>Average cost analysis</li>
      <li>Online order analysis</li>
      <li>Table booking analysis</li>
      <li>Dynamic charts and visual reports</li>
    </ul>

    <h2>Key Insights</h2>

    <ul>
      <li>Identified the most popular restaurant categories</li>
      <li>Compared customer engagement across restaurant types</li>
      <li>Analyzed online ordering trends</li>
      <li>Studied table booking availability patterns</li>
      <li>Evaluated restaurant pricing and rating relationships</li>
    </ul>

    <h2>Tools & Technologies Used</h2>

    <div>
      <span class="badge">Microsoft Excel</span>
      <span class="badge">Pivot Tables</span>
      <span class="badge">Pivot Charts</span>
      <span class="badge">Slicers</span>
      <span class="badge">Data Analysis</span>
      <span class="badge">Dashboard Design</span>
    </div>

    <h2>Project Objectives</h2>

    <ul>
      <li>To analyze restaurant business trends</li>
      <li>To visualize customer engagement data</li>
      <li>To create an interactive dashboard experience</li>
      <li>To generate business insights from restaurant data</li>
    </ul>

    <h2>Conclusion</h2>

    <p>
      This dashboard demonstrates how Microsoft Excel can be used effectively
      for business intelligence and restaurant data analysis. The project converts
      raw restaurant data into meaningful visual insights that help understand
      customer behavior and restaurant performance.
    </p>

    <div class="footer">
      Created for Data Analytics & Dashboard Portfolio Project
    </div>

  </div>

</body>
</html>
