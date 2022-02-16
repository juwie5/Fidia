<template>
  <div class="container">
    <section class="header">
        <nav>
            <div class="nav-sect-1">
                <div class="navimg"><img src="../assets/Logo.svg" alt=""></div>
                <ul class="navlist">
                    <li>Home</li>
                    <li>Dashboard</li>
                    <li>Projects</li>
                    <li>Tasks</li>
                    <li>Reporting</li>
                    <li>Users</li>
                </ul>
            </div>
            <div>
                <ul class="navlist">
                    <li><a href="#" class="navbtn"><img src="../assets/Thunder.svg" alt="">Upgrade now</a></li>
                    <li><a href="#"><img src="../assets/wheel.svg"></a></li>
                    <li><a href="#"><img src="../assets/bell.svg"></a></li>
                    <li><a href="#"><img src="../assets/Avatar.svg"></a></li>
                </ul>
            </div>
        </nav>
        <div class="nav-sect-2">
            <div>
                <ul class="navlist2">
                   <li>Overview</li> 
                   <li>Notifications</li> 
                   <li>Analytics</li> 
                   <li>Saved reports</li> 
                   <li>Trade history</li> 
                   <li>User reports</li> 
                </ul>
            </div>
                <div class="eyecont">
                    <label for="search"></label>
                    <img src="../assets/search.svg" alt="search" id="eyeimg">
                    <input type="text" name="search" placeholder="Search">
                </div>         
        </div>
    </section>
    <section class="hero">
      <div class="hero-main">
        <div>
          <h2>Welcome back, Olivia</h2>
          <p>Track, manage and forecast your customers and orders.</p>
        </div>  
        <div>
            <button><img src="../assets/cloud.svg" alt="">Import</button>
            <button class="btn2"><img src="../assets/add.svg" alt="">Add</button>
        </div>
      </div>
      <div class="hero-sub">
        <div class="hero-card">
          <h3>Total customers <img class="chart" src="../assets/thredots.svg" alt=""></h3>
          <p class="num">2,420</p>
          <p><span class="percent"><img src="../assets/arrowup.svg"> 40%</span> vs last month</p>
          <img class="chart pos" src="../assets/GreenChart.svg" alt="">
      </div>   
        <div class="hero-card">
          <h3>Members <img class="chart" src="../assets/thredots.svg" alt=""></h3>
          <p class="num">1,210</p>
          <p><span id="redp"><img src="../assets/arrowdown.svg"> 10%</span> vs last month</p>
          <img class="chart pos" src="../assets/RedChart.svg" alt="">
      </div> 
        <div class="hero-card">
          <h3>Active now <img class="chart" src="../assets/thredots.svg" alt=""></h3>
          <p class="num">316</p>
          <p><span class="percent"><img src="../assets/arrowup.svg"> 20%</span> vs last month</p>
          <img class="chart pos" src="../assets/GreenChart.svg" alt="">
      </div> 
      </div>
      

    </section>
    <Body/>
  </div>
</template>

<script>
import Body from '../components/Body.vue'
export default {
    name: 'Head',
    data:() => {
        return{

        }
    }
}
</script>

<style lang="scss" scoped>


</style>