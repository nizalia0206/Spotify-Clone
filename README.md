body{
    
    font-family: "Montserrat", serif;
    font-optical-sizing: auto;
    font-weight: weight;
    font-style: normal;
    margin: 0;
    background-color: black;
    color: white;
    /*overflow for scrolling*/
    overflow: hidden;
    /*only main content is scrolling not music player and
    side bar so we will activate it thr*/
  }

  .main{
    display: flex;
    height: 100vh;
    padding: 0.5rem;
  }

  .sidebar{
    background-color:black;
    width: 340px;
    border-radius: 1rem; /*1 rem is 16px*/
    margin-right:0.25rem ;
  }

  .main-content{
        background-color: #121212;
        flex: 1;
        /*for other divs give space according to 
        how much content is thr but rest space give it to
        where flex 1 is thr*/
        border-radius: 1rem;
        overflow: auto;
        /*auto means when needed then only scrollbar appears*/
        padding: 0 1.5rem 0 1.5rem;
  }

  .music-player{
    background-color:black;
    position: fixed;
    bottom: 0;
    width: 100%;
    height: 72px;
  }

  a{
    text-decoration: none;
    color: white;
  }

  .nav{
    background-color: #121212;
    border-radius: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 100px;
    padding: 0.5rem;

  }

  .nav-option{
    line-height:2.5rem;
    opacity: 0.7;
    padding: 0.5rem 0.75rem;
  }

  .nav-option:hover{
    opacity: 1;
  }

  .nav-option i{
    font-size: 1.25rem;
  }

  .nav-option a{
    font-size: 1rem;
    margin-left:1rem;
  }

  .library{
    background-color: #121212;
    border-radius: 1rem;
    height: 100%;
    margin: 0.3rem;
    padding: 0.5rem 0.75rem;

  }

  .options{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .lib-option img{
    height: 1.25rem;
    width: 1.25rem;
  }

  .icons{
    font-size: 1.25rem;
    display: flex;
  }

  .icons i{
    opacity: 0.7;
    margin-right: 1rem;
  }

  .icons i:hover{
    opacity: 1;
  }

  .box{
    background-color: #232323;
    height: 8rem;
    border-radius:0.75rem ;
    margin:0.75rem 0 1.75rem 0;
    padding: 0.75rem 1rem;
  }

  .box-p1{
    font-size: 1rem;
    font-weight: 500;
  }

  .box-p2{
    font-size: 0.85rem;
    opacity: 0.9;
  }

  .badge{
    background-color: white;
    border: none;
    border-radius: 100px;
    padding: 0.25rem 1rem;
    font-weight: 700;
    margin-top: 0.25rem;
    height: 2rem;
    width: fit-content;
  }

  .dark-badge{
    background-color: black;
    color: white;
  }

  .sticky-nav{
    position: sticky;
    top: 0;
    background-color:#121212;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0 1rem 0;
    z-index:10 ;
    /*to prevent overlapping of content with sticky top nav bar*/
  }

  .sticky-nav-icons{
    margin-left: 0.75rem;
  }

  .sticky-nav-options{
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .nav-item button{
          margin-right: 1rem;
  }

 @media(max-width:1000px){
    .hide{
        display: none;
    }
 }

 .card{
    background-color:#232323 ;
    width: 150px;
    border-radius: 0.5rem;
    padding: 1rem;
    margin-left: 1.5rem;
    margin-top: 1rem;
 }

 .cards-container{
    display: flex;
    flex-wrap: wrap;
 }

 .card-img{
    width: 100%;
    border-radius: 0.5rem;
 }

 .card-title{
    font-weight: 600;
 }

 .card-info{
    font-size: 0.85rem;
    opacity: 0.5;
 }

 .footer{
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
 }

 .line{
    width: 90%;
    height: 50%;
    border-top: 1px solid white;
    opacity: 0.4;
 }

 .music-player{
    display: flex;
    justify-content: space-between;
    align-items: center;
 }

 .album{
    width: 25%;
 }

 .player{
    width: 50%;
 }

 .controls{
    width:25%
 }

 .player-controls{
    display: flex;
    justify-content:center;
    align-items: center;
 }

 .player-control-icon{
    height: 1rem;
    margin-right: 1.75rem;
    opacity: 0.7;
 }

 .player-control-icon:hover{
    opacity: 1;
 }

 .playback-bar{
    display: flex;
    justify-content: center;
    align-items: center;
 }

 .progress-bar{
    width:70% ;
    /*appearance to none removes by default properties*/
    appearance: none;
    background-color: transparent;
    cursor: pointer;
}

.progress-bar::-webkit-slider-runnable-track{
    background-color:#dddddd ;
    border-radius: 100px;
    height: 0.2rem;
}
.progress-bar::-webkit-slider-thumb{
    appearance: none;
    height: 1rem;
    width: 1rem;
    background-color: #1bd760;
    border-radius: 50%;
    margin-top: -6px;
}

.album{
    display: flex;
}
.album img{
    height:4rem;
    width: 4rem;
    margin-top: 0.25rem;
}

.plus{
    margin-left: 1rem;
}

.song-name{
    margin-left: 0.5rem; 
    font-weight: 500; 
    font-size: 0.85rem;
    margin-top: 0.55rem;
    align-items: center;
}


.song-singer{
    opacity: 0.7;
    font-size: 0.65rem;
    margin-left: 0.5rem;
    margin-top: -0.5rem;
    font-weight: 300;
}

.controls{
    display: flex;
    margin-right: 1.75rem;
    justify-content: center;
    align-items: center;
}

.control{
 
    display: flex;
    margin-right: 0.75rem;
    justify-content: center;
    align-items: center;
}


.sound{
    width:25% ;
    /*appearance to none removes by default properties*/
    appearance: none;
    background-color: transparent;
    cursor: pointer;
}
.sound::-webkit-slider-runnable-track{
    background-color:#dddddd ;
    border-radius: 100px;
    height: 0.1rem;
}

.sound::-webkit-slider-thumb{
    appearance: none;
    height: 1rem;
    width: 1rem;
    background-color: #1bd760;
    border-radius: 50%;
    margin-top: -6px;
}


