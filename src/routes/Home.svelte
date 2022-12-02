<main>

  
  <div class="wrapper">
    <!-- Sidebar -->
    <nav id="sidebar">

        <ul class="list-unstyled components" id="content">
            <li class="active fs-3">
                <a href="home" data-toggle="collapse" aria-expanded="false"><i class="fa-solid fa-house"></i> Home</a>
            </li>
            <br>
            <br>
            <li class="fs-3 ">
                <a href="#"><i class="fa-sharp fa-solid fa-chart-simple"></i> Your Statistics</a>
            </li>
            <br>
            <br>
            <li class="fs-3">
                <a href="#" data-toggle="collapse" aria-expanded="false"><i class="fa-solid fa-file"></i> Pages</a>
            </li>
            <br>
            <br>

            <li class="fs-3">
                <a href="#"><i class="fa-sharp fa-solid fa-chart-simple"></i> Graphs</a>
            </li>
            <br>
            <br>
            <li class="fs-3">
                <a href="settings"><i class="fa-solid fa-gear"></i> Settings</a>
            </li>
        </ul>
    </nav>

  </div>


  <div class="welcomecard">
    <div class="box">
        <h5 class="card-title">Welcome $(UserRName)</h5>
        <p class="card-text">Welcome to myPanel! This will be the place where you check your statistics, register for events, and more!</p>
    </div>
  </div>  

</main>


<svelte:head>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
  <script src="https://kit.fontawesome.com/f1706b1936.js" crossorigin="anonymous"></script>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
</svelte:head>

<style>
  .wrapper {
      display: flex;
      align-items: stretch;
      background-color: rgb(36, 36, 36);
      position:absolute;
      left:0;
      top:0;

  }

  #sidebar {
      min-width: 250px;
      max-width: 250px;
      min-height: 65vh;
  }


  #content {
    margin-top: 70px;
  }
  
  a {
    text-decoration:none;
    color:white
  }

  

  .welcomecard {
    display:flex;
    position:relative;
    right: px;
    bottom:400px;
    border-color: rgb(36, 36, 36);
    
    
  }
</style>



