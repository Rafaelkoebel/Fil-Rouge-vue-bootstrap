<template>
<header>
<a href="#menu">
                <span class="iconify" id="burger"  data-icon="gg:menu" style="color: black;"></span>
            </a>
            <a href="Index.html">
                <span class="iconify" data-icon="openmoji:strawberry" style="color: black;"></span>
            </a>
            <ul id="menu">
                <span class="iconify" id="logo_menu" data-icon="gg:menu" style="color: black;"></span>
                <a href="/html/Compte.html">
                    <li>Mon compte</li>
                </a>
                <a href="/html/Tendances.html">
                    <li>Tendances</li>
                </a>
                <a href="/html/Recette.html">
                    <li>Proposer une recette</li>
                </a>
                <a href="/html/Saisons.html">
                    <li>Saisons</li>
                </a>
                <a href="/html/Minuteur.html">
                    <li>Minuteur</li>
                </a>
            </ul>
<nav class="navbar navbar-light bg-transparent">
  <div class="container-fluid">
    <form class="d-flex">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success" type="submit">Search</button>
    </form>
  </div>
</nav>
</header>

</template>

<style scoped>

header{
        background-image: url(../assets/violet3.jpg);
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

#rouge{
        background-image: url(../assets/rouge.jpg);
    }

#menu:not(:target){
        display: none;
        
    }

#menu:target{
        display: block;
        background-color: #e5e5e58a;
        list-style-type: none;
        width: 300px;
        padding-left: 20px;
        font-size: 40px;
        position: absolute;
        top: -1px;
    }

#logo_menu{
        margin-left: -20px;
    }

li{
        padding-bottom: 10px;
    }

.iconify{
        width: 79.81px;
        height: 82px;
    }

a:link{ 
    text-decoration:none; 
    } 
</style>