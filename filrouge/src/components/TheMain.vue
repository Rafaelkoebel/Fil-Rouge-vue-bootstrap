<template>
<div id="rouge">
    <main>
        <div id="pc">
            <ul class="nav nav-pills nav-fill">
            <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Mon compte</a>
            </li>
            <li class="nav-item">
            <a class="nav-link" href="#">Proposer une recette</a>
            </li>
            <li class="nav-item">
            <a class="nav-link" href="#">Saisons</a>
            </li>
            <li class="nav-item">
            <a class="nav-link">Minuteur</a>
            </li>
            </ul>
                </div>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/cA02sRHo9-8" title="YouTube video player" id="video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                <div class="bloc">
                </div>
    </main>
</div>
</template>

<style scoped>
@media screen and (max-width: 427px){
    

    #pc{
        display: none;
    }

    #confiture, #glace, #gateau, #yaourt{
        max-height: 80px;
    }

    #rouge{
        max-height: 948px;
    }

    
}

@media screen and (max-width: 833px){
    #pc{
        display: none;
    }

    main #video{
        display: none;
    }
}
.nav-item{
        border: solid black 1px;
    }
    
#confiture, #glace, #gateau, #yaourt{
        height: 150px;
    }


#pc ul{
        color: white;
        list-style-type: none;
        justify-content: space-around;
        display: flex;
        -webkit-text-stroke: 0.2px black;
    }

#pc ul li{
        background-color: rgba(255, 255, 255, 0.438);
        border-radius: 10px;
        padding-top: 10px;
    }


#rouge{
        background-image: url(../assets/rouge.jpg);
    }


li{
        padding-bottom: 10px;
    }


main{
        justify-content: space-around;
        
    }

h1{
        text-align: center;
        color: white;
    }

img{
        position: relative;
    }

#video{
        margin: auto;
        display: flex;
        width: 400px;
    }

#confiture{
        background-image: url(../assets/confiture.jpg);
        background-size: cover;
        background-position: center;
        margin: 22px;
        padding: 40px;
        -webkit-text-stroke: 0.1px black;
        font-size: 3em;
        border: solid 2px black;
    }

#glace{
        background-image: url(../assets/glace3.jpg);
        background-size: cover;
        background-position: center;
        margin: 22px;
        padding: 40px;
        border-radius: 5px;
        -webkit-text-stroke: 0.1px black;
        font-size: 3em;
        border: solid 2px black;
    }

#gateau{
        background-image: url(../assets/gateau2.jpg);
        background-size: cover;
        background-position: center;
        margin: 22px;
        padding: 40px;
        border-radius: 5px;
        -webkit-text-stroke: 0.1px black;
        font-size: 3em;
        border: solid 2px black;
    }

#yaourt{
        background-image: url(../assets/yaourt2.jpg);
        background-size: cover;
        background-position: center;
        margin: 22px;
        padding: 40px;
        border-radius: 5px;
        -webkit-text-stroke: 0.1px black;
        font-size: 3em;
        border: solid 2px black;
    }

</style>