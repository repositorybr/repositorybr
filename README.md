# Eu sou Marcelo! :D
[![Github Badge](https://img.shields.io/badge/-Telegram-000?style=flat-square&logo=Telegram&logoColor=white&link=https://t.me/botsnewsbr)](https://t.me/botsnewsbr)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://youtube.com/channel/UCeQmH_pju8ze7PVRRP3lx6w)](https://youtube.com/channel/UCeQmH_pju8ze7PVRRP3lx6w)


#### About me
Siga meus Projetos Nas redes sociais.

- [botNews](https://t.me/botsnewsbr) 👨🏼‍🏫 - Um canal onde você pode encontrar diversos bots 
- [YouTube](https://youtube.com/channel/UCeQmH_pju8ze7PVRRP3lx6w) ✍🏼 - Meu canal no YouTube onde eu posto dicas e tutoriais.

@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400&display=swap');

*,
*::before,
*::after {
    padding: 0;
    margin: 0;
    box-sizing: inherit;
}

html{
    box-sizing: border-box;
    font-size: 62.5%; // 10px
}

ul{
    list-style-type: none;
}

a{
    text-decoration: none;
}

body{
    width: 100%;
    min-height: 100vh;
    font-family: 'Source Sans Pro', sans-serif;
    background-color: #f0fafb;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container{
    position: relative;
    width: 35rem;
    height: 11.5rem;
    background-color: #fff;
    padding: 2rem;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    overflow: hidden;
    transition: height .4s ease-in;
}
.container.active{
    height: 35rem;
    
}

.card{
    position: relative;
    display: flex;
    align-items: center;
}

.card-img img{
    width: 80px;

}

.card h2{
    font-size: 2.2rem;
    margin-left: 1.5rem;
    color: #222;
    letter-spacing: 2px;
}
.card h2 span{
    font-size: 1.6rem;
    font-weight: 400;
    color: #777;
    letter-spacing: 0px;
}

.container ul {
    position: relative;
    border-top: 1px solid rgba(0,0,0,0.1);
    margin-top: 1.5rem;
    padding: 2rem 0;

    display: flex;
    flex-direction: column;
    gap: 2rem;
}
.container ul a{
    font-size: 1.8rem;
    color: #444;
    transition: 0.2s;
}
.fa{
    font-size: 2rem;
    margin-right: 1rem;

}
.container ul a:hover{
    color: #3EDBF0;
}

.toggle{
    position: absolute;
    bottom: 0;
    right: 0;
    width: 4rem;
    height: 4rem;
    background-color: #3EDBF0;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}

.toggle > .fa{
    margin: auto;
    color: #fff;
    text-align: center;
    cursor: pointer;
    transition: 0.25s;
   font-size: 1.8rem;
}

.container.active .toggle > .fa{
    transform: rotate(-540deg);
}
