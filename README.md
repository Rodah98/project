<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Admin Dashboard</title>
        <!--montserrat-->
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;1,500&display=swap" rel="stylesheet">

        <!---material icons-->
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Outlined"
      rel="stylesheet">

        <!--custom css-->
        <link rel="stylesheet" href="css/styles.css">
    </head>
    <body>
        <div class="grid-container">

      <!-- Header -->
      <header class="header">
        <div class="menu-icon" onclick="openSidebar()">
          <span class="material-icons-outlined">menu</span>
        </div>
        <div class="header-left">
          <span class="material-icons-outlined">search</span>
        </div>
        <div class="header-right">
          <span class="material-icons-outlined">notifications</span>
          <span class="material-icons-outlined">email</span>
          <span class="material-icons-outlined">account_circle</span>
        </div>
      </header>
      <!-- End Header -->

      <!-- Sidebar -->
      <aside id="sidebar">
        <div class="sidebar-title">
          <div class="sidebar-brand">
            <span class="material-icons-outlined">shopping_cart</span> STORE
          </div>
          <span class="material-icons-outlined" onclick="closeSidebar()">close</span>
        </div>

        <ul class="sidebar-list">
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">dashboard</span> Dashboard
          </li>
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">inventory_2</span> Products
          </li>
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">category</span> Categories
          </li>
          <li class="sidebar-list-item"> 
            <span class="material-icons-outlined">groups</span> Customers
          </li>
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">fact_check</span> Inventory
          </li>
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">poll</span> Reports
          </li>
          <li class="sidebar-list-item">
            <span class="material-icons-outlined">settings</span> Settings
          </li>
        </ul>
      </aside>
      <!-- End Sidebar -->

      <!-- Main -->
      <main class="main-container">
        <div class="main-title">
          <h2>DASHBOARD</h2>
        </div>

        <div class="main-cards">

          <div class="card">
            <div class="card-inner">
              <h3>PRODUCTS</h3>
              <span class="material-icons-outlined">inventory_2</span>
            </div>
            <h1>249</h1>
          </div>

          <div class="card">
            <div class="card-inner">
              <h3>CATEGORIES</h3>
              <span class="material-icons-outlined">category</span>
            </div>
            <h1>25</h1>
          </div>

          <div class="card">
            <div class="card-inner">
              <h3>CUSTOMERS</h3>
              <span class="material-icons-outlined">groups</span>
            </div>
            <h1>1500</h1>
          </div>

          <div class="card">
            <div class="card-inner">
              <h3>ALERTS</h3>
              <span class="material-icons-outlined">notification_important</span>
            </div>
            <h1>56</h1>
          </div>

        </div>

        <div class="charts">

          <div class="charts-card">
            <h2 class="chart-title">Top 5 Products</h2>
            <div id="bar-chart"></div>
          </div>

          <div class="charts-card">
            <h2 class="chart-title">Purchase and Sales Orders</h2>
            <div id="area-chart"></div>
          </div>

        </div>
      </main>
      <!-- End Main -->

    </div>
    <!--scripts-->
<!--apexcharts-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/apexcharts/3.36.0/apexcharts.min.js"></script>
        <!--custom js-->
        <script src="js/scripts.js"></script>
    </body>
</html>
![Screenshot (7)](https://user-images.githubusercontent.com/112557749/195865861-3f5a619e-ddb5-4539-ac66-bfb7325af29f.png)

