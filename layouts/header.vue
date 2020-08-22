<template> 
    <header class="header_main d-flex px-3 align-center" >
        <div class="brand__logo">
            <div class="d-flex">
              <v-icon color="white">home</v-icon>
              <h3 style="color: white">Logo</h3>
            </div> 
        </div>
        <div class="nav__bar_left ml-2">
            <ul class="nab__bar">
              <li>
                  <a href="#" class="active"><v-icon color="white">format_list_bulleted</v-icon> Reports</a>
              </li>
              <li>
                  <a href="#"><v-icon color="white">map</v-icon> Map</a>
              </li>
              <li>
                  <a href="#"><v-icon color="white">addchart</v-icon> Gallery</a>
              </li>
              <li>
                  <a href="#"><v-icon color="white">directions_off</v-icon> Statistics</a>
              </li>
            </ul>
        </div>
        <div class="nav__bar_left ml-auto">
            <ul class="nab__bar">
              <li>
                  <a href="#"><v-icon color="white">info</v-icon> Tutorials</a>
              </li>
              <li>
                  <a href="#"><v-icon color="white">settings</v-icon> Settings</a>
              </li>
              <li>
                  <a href="#"><v-icon color="white">power_settings_new</v-icon> Log Out</a>
              </li> 
            </ul>
        </div>
    </header>  
</template>
 

<style lang="scss"> 
  .header_main{
      background: #102c42;
  }
  .nab__bar{
    list-style-type: none;
    display: flex;
    margin: 0;
    padding: 0;
    li{
   
      a {
        text-decoration: none;
        padding: 8px 15px;
        display: inline-block; 
        color: white; 
         border-bottom: 4px solid #102c42;  
        }
        .active{
          border-bottom: 4px solid #fff;    
        }
    }
 
  
  }
   .nab__bar li a:not(.active):hover {
      background: #535353;
      border-bottom: 4px solid #535353;
  }
  
</style>