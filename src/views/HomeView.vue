<template>
    <div class="container-fluid">
      <div class="row">
        
  <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block bg-light sidebar">
  <div class="position-sticky">
    <img src="@/assets/PKL.svg" alt="Home" class="me-3"  height="50" width="150"/>
  </div>

  <div class="dashboard">
    <ul class="menu list-unstyled" style="gap: 15px; display: flex; flex-direction: column;"> 
      <li class="menu-item active d-flex align-items-center mb-2">
        <img src="@/assets/uu.svg" alt="Home" class="me-3 n" />
        <img src="@/assets/home.svg" alt="Home" class="me-3 n" />
        <span><i class="fas fa-home"></i> Home</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/con.svg" alt="Orders" class="me-3 n" />
        <span><i class="fas fa-shopping-cart"></i> Orders</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/no.svg" alt="Reviews" class="me-3 n" />
        <span><i class="fas fa-star"></i> Reviews</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/cl.svg" alt="Clients" class="me-3 n" />
        <span><i class="fas fa-users"></i> Clients</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/com.svg" alt="Companies" class="me-3 n" />
        <span><i class="fas fa-building"></i> Companies</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/kk.svg" alt="Trucks" class="me-3 n" />
        <span><i class="fas fa-truck"></i> Trucks</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/Br.svg" alt="Brands" class="me-3 n" />
        <span><i class="fas fa-tags"></i> Brands</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/ci.svg" alt="Cities" class="me-3 n" />
        <span><i class="fas fa-city"></i> Cities</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/con.svg" alt="Content Management" class="me-3 n" />
        <span><i class="fas fa-cog"></i> Content Management</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/per.svg" alt="Permissions" class="me-3 n" />
        <span class="me-auto"><i class="fas fa-lock"></i> Permissions</span>
        <button class="btn btn">
          <img src="@/assets/zf.svg" alt="Permissions" class="me-3 n" />
        </button>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/sy.svg" alt="System Management" class="me-3 n" />
        <span><i class="fas fa-server"></i> System Management</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/tran.svg" alt="Translation" class="me-3 n" />
        <span><i class="fas fa-language"></i> Translation</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/cont.svg" alt="Contact" class="me-3 n" />
        <span><i class="fas fa-phone"></i> Contact</span>
      </li>

      <li class="menu-item d-flex align-items-center mb-2">
        <img src="@/assets/ntr.svg" alt="Client Review" class="me-3 n" />
        <span><i class="fas fa-comments"></i> Client Review</span>
      </li>
    </ul>
  </div>
</nav>

  
      <main class="col-md-9 ms-sm-auto col-lg-10 px-4">
         <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3">
        <div>
    <div>
  <h1 class="h2">Dashboard Overview</h1>
  <span class="d-block text-start">26 Sep 2023</span> 
</div>
  </div>
  <div class="btn-toolbar mb-2 mb-md-0">
    <div class="btn-group me-2">
      <i class="fas fa-bell text-warning"></i>
      <img src="@/assets/gy.svg" alt="Notification" class="me-3 n" />
      <img src="@/assets/mm.svg" alt="Settings" class="me-3 n" />
    </div>
  </div>
</div>
          
<div class="d-flex justify-content-start mb-4">
  <div class="d-flex align-items-center ms-3">
    <div class="form-check form-check-inline">
      <input class="form-check-input" type="radio" id="all" name="filter" checked />
      <label class="form-check-label" for="all">All</label>
    </div>
    <div class="form-check form-check-inline">
      <input class="form-check-input" type="radio" id="some" name="filter" />
      <label class="form-check-label" for="some"></label> 
    </div>
    
    <div class="input-group mx-2">
    <span class="input-group-text" style="font-size: 12px;">From</span>
      <input class="form-control" type="date" value="2023-09-26" aria-label="From date" />
    </div>

    <div class="input-group mx-2">
      <span class="input-group-text" style="font-size: 12px;">To</span>
      <input class="form-control" type="date" value="2023-09-26" aria-label="To date" />
    </div>

    <button class="btn btn-warning ms-2">Find</button>
  </div>
</div>
  


   <div class="row mb-4">
  <div class="col-md-3">
    <div class="card text-start">
      <div class="card-body d-flex flex-column align-items-start">
        <h5 class="card-title text-seconday" style="color: #7E7E7E; font-size: 13px;">
          <img src="@/assets/sal.svg" alt="Order Number" class="mb-3" />  Order Number</h5>
        <div class="d-flex justify-content-center align-items-baseline">
          <p class="card-text display-6 mb-0" style="font-weight: 500;">1000</p>
          <p class="card-text ms-2 mb-0" style="font-size: 12px;">Orders</p>
        </div>
      </div>
    </div>
  </div>

  

  <div class="col-md-3">
    <div class="card text-start">
      <div class="card-body d-flex flex-column align-items-start">
        <h5 class="card-title text-seconday" style="color: #7E7E7E; font-size: 13px;">
          <img src="@/assets/mb.svg" alt="Company Number" class="mb-3" />  Company Number</h5>
        <div class="d-flex justify-content-center align-items-baseline">
          <p class="card-text display-6 mb-0" style="font-weight: 500">1000000</p>
          <p class="card-text ms-2 mb-0" style="font-size: 12px;">SR</p>
        </div>
      </div>
    </div>
  </div> 

  
  

  <div class="col-md-3">
    <div class="card text-start">
      <div class="card-body d-flex flex-column align-items-start">
        <h5 class="card-title text-seconday" style="color: #7E7E7E; font-size: 13px;">
           <img src="@/assets/di.svg" alt="Drivers Number" class="mb-3" />  Drivers Number</h5>
        <div class="d-flex justify-content-center align-items-baseline">
          <p class="card-text display-6 mb-0" style="font-weight: 500;">500</p>
          <p class="card-text ms-2 mb-0" style="font-size: 12px;">Drivers</p>
        </div>
      </div>
    </div>
  </div>


  <div class="col-md-3">
    <div class="card text-start">
      <div class="card-body d-flex flex-column align-items-start">
        <h5 class="card-title text-seconday" style="color: #7E7E7E; font-size: 13px;">
          <img src="@/assets/fa.svg" alt="Total Sales" class="mb-3"  />  Total Sales</h5>
        <div class="d-flex justify-content-center align-items-baseline">
          <p class="card-text display-6 mb-0" style="font-weight:500 ;" >500</p>
          <p class="card-text ms-2 mb-0" style="font-size: 12px;">Sales</p>
        </div>
      </div>
    </div>
  </div>
</div>
      





          <div class="row mb-4">
            <div class="col-md-3">
              <div class="card text-center">
                <div class="card-body">
                  <h5 class="card-title">Waiting For Loading</h5>
                  <div class="d-flex justify-content-center align-items-center">
                    <div class="position-relative">
                      <img src="@/assets/r.svg" alt="old mt-4" class="me-3 n" />
                      <div class="position-absolute top-50 start-50 translate-middle">
                        <span class="display-6">80</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>


            <div class="col-md-3">
              <div class="card text-center">
                <div class="card-body">
                  <h5 class="card-title">Waiting For Arrive</h5>
                  <div class="d-flex justify-content-center align-items-center">
                    <div class="position-relative">
                      <img src="@/assets/r.svg" alt="old mt-4" class="me-3 n" />    <div class="position-absolute top-50 start-50 translate-middle">
                        <span class="display-6">80</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>


            <div class="col-md-3">
              <div class="card text-center">
                <div class="card-body">
                  <h5 class="card-title">Completed</h5>
                  <div class="d-flex justify-content-center align-items-center">
                    <div class="position-relative">
                      <img src="@/assets/r.svg" alt="old mt-4" class="me-3 n" />
                      <div class="position-absolute top-50 start-50 translate-middle">
                        <span class="display-6">80</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            
            <div class="col-md-3">
              <div class="card text-center">
                <div class="card-body">
                  <h5 class="card-title">Canceled</h5>
                  <div class="d-flex justify-content-center align-items-center">
                    <div class="position-relative">
                      <img src="@/assets/r.svg" alt="old mt-4" class="me-3 n" />
                      <div class="position-absolute top-50 start-50 translate-middle">
                        <span class="display-6">80</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
  
          
  <div class="row">
  <div class="col-md-6"> 
    <div class="card">
      <div class="card-body">
<table class="table table-borderless"> 
  <thead>
    <h5 class="card-title text-start" style="font-size: 14px; margin-bottom: 15px;">TOP 5 Companies</h5>  
    <tr>
      <td class="text-start" style="color: #7E7E7E;">Company Name</td>
      <td class="text-start" style="color:#7E7E7E;">Order Qty</td>
      <td class="text-start" style="color: #7E7E7E;">Amount</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="text-start">Gillette</td>
      <td class="text-start">5000</td>
      <td class="text-start">50000 SR</td>
    </tr>
    <tr>
      <td class="text-start">Louis Vuitton</td>
      <td class="text-start">3000</td>
      <td class="text-start">50000 SR</td>
    </tr>
    <tr>
      <td class="text-start">Johnson & Johnson</td>
      <td class="text-start">2000</td>
      <td class="text-start">50000 SR</td>
    </tr>
    <tr>
      <td class="text-start">Nintendo</td>
      <td class="text-start">1000</td>
      <td class="text-start">50000 SR</td>
    </tr>
  </tbody>
</table> 
      </div>
    </div>
  </div>
  <div class="col-md-6"> 
  <div class="row"> 
    <div class="col-md-6 mb-3"> 
      <div class="card">
        <div class="card-body text-center">
          <h5 class="card-title">Order Repeated</h5>
          <div class="d-flex justify-content-center align-items-center">
            <div class="position-relative">
              <img src="@/assets/r.svg" alt="old mt-4" class="me-3 n" />
              <div class="position-absolute top-50 start-50 translate-middle">
                <span class="display-6">80%</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col-md-6 "> 
      <div class="card">
        <div class="card-body text-center">
          <h5 class="card-title">Commission</h5>
          <div class="d-flex justify-content-center align-items-center">
            <div class="position-relative">
              <img src="@/assets/g.svg" alt="old mt-4" class="me-3 n" />
              <div class="position-absolute top-50 start-50 translate-middle">
                <span style="font-size: 30px;">127K</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div> 
</div> 
</div> 
        </main>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomeView',
  };
  </script>
  
  <style scoped>
  body {
    background-color: #f8f9fa;
  }
  .sidebar {
    position: fixed;
    top: 0;
    bottom: 0;
    z-index: 100;
    height: 100%;
    overflow-y: auto;
  }
  .card {
    border: 1px solid #dee2e6;
  }
  .rounded-circle {
    border-width: 8px;
  }


  .form-check-input:checked {
    background-color: #FBA81A; 
    border-color: #FBA81A; 
  }


  .form-check-input:checked {
    border: 2px solid #FBA81A; 
    outline: none;}






    
  
  </style>

















































