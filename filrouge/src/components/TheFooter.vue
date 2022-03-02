<template>

    <footer>
            <div id="calc"> 
                <div class="contact">
                    <a href="/html/Contact.html" title="Contact">
                        <span class="iconify" id="logo_contact" data-icon="fluent:contact-card-32-filled" style="color: black;"></span>
                        <p id="contact">Contact</p>
                    </a>
                </div>
                <p id="sommes">Qui sommes nous ?</p>
                <div class="infos">
                    <a href="/html/Infos.html" title="Informations">
                        <span class="iconify" id="logo_infos" data-icon="bi:info-circle-fill" style="color: black;"></span>
                        <p id="infos">Infos</p>
                    </a>
                </div>
            </div>
        </footer>

</template>

<style scoped>
@media screen and (max-width: 427px){
    #sommes{
        display: none;
    }
}
footer{
        height: 87px;
        justify-content: space-between;
    }

#calc{
        justify-content: space-between;
    }

#contact, #infos{
        display: none;
    }

p{
        font-weight: bold;
        font-size:25px
    }

footer{
        background-color: #e5e5e58a;
        padding-top: 10px;
        display: flex;
        flex-direction: row;
        justify-content: center;
    }

#calc{
        display: flex;
        
    }

#logo_contact{
        height: 45px;
        margin-top: 10px;
        padding-right: -10px;
    }

#infos{
        padding-left: 20px;
    }

#logo_infos{
        height: 40px;
        margin-top: 18px;
    }

.iconify{
        width: 79.81px;
        height: 82px;
    }

a:link{ 
    text-decoration:none; 
    } 
</style>