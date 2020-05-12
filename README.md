!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Assignment  Module 2</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <h1>Top YouTubers</h1>
    <div class="container-fluid">
    <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12">
            <section id="Pewdiepie">
                <h2>Felix Arvid Ulf Kjellberg</h2>
                  <p>
                   Pewdiepie is a Swedish YouTuber who focuses on a little phenomenon referred to as “Let’s Play.” The remarkably clear method has sling many to immense success on YouTube and is so silly, you wouldn’t imagine it was entertaining till you saw it with your own eyes: it’s merely a person’s face floating in a small display in the corner, whereas they play a video game. The games he plays are usually scary and action-related games, most prominently Amnesia, a game so was a talk of the (online) town and regarded by many to be a terrifying game ever. 
                  </p>
            </section>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-12">
            <section class="JennaMarbles">
                <h2>Jenna Nicole Mourey</h2>
                <p>
                    JennaMarbles, in any other name known as Jenna Mourey, is undoubtedly one of few feminine channel-owners into that Top 20. Mourey earns identification in 2010 unitedly with her hilarious video “ trick individuals into thinking you’re good looking.” After before Jenna becomes continue updating her channel as shortly as a week with a new video bomb.Marbles’ videos principally characteristic her sitting in front of a white wall in her bedroom having a random conversation with herself either her dogs
                </p>
            </section>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <section class="PointlessBlog">
                <h2>Alfred Sidney Deyes</h2>
                <p>
                    Did you see The Pointless Book on the bestseller cabinets over Christmas? Meet the person behind it, Sunday Times bestselling writer Mr. Alfie Deyes. You may additionally refer to him as Mr. Zoella, for he’s the other half of Zoe Sugg also conclude the YouTube power couple known as Zalfie.
                    Deyes found fame all by himself before dating Zoe although. His assortment of unique and comedic videos gained him millions of subscribers throughout three channels, together with PointlessBlogTV and AlfieGames: 1,979,169 people signed up to watch his video diaries while 1,252,637 like nothing more than watching him play video games. 
                </p>
            </section>
        </div>
    </div>
    </div>
</body>

</html>
* {
    box-sizing: border-box;
    font-family: Helvetica;
}

body {
    background-color: #f7f7fa;
}

h1 {
    text-align: center;
    color: #666699;
}

section {
    border: 1px solid rgb(24, 22, 22);
    background-color: #b5c4d2;
    margin: 15px;
}

section>h2 {
    float: right;
    overflow: auto;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    margin: 0px;
}

section#Pewdiepie>h2 {
    background-color: #3b7da7;
    color:whitesmoke;
}
section.JennaMarbles>h2 {
    background-color: #5988e6;
    color:whitesmoke;
}

section.PointlessBlog>h2 {
   
    background-color: #5b7ac9;
    color:whitesmoke;
}

section>p {
    padding: 40px ;
    color : #397093;
    margin-top: 10%;
}

.row {
    width: 100%;
}


/* Desktop view options */

@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
    }
    .col-lg-1 {
        width: 8.33%;
    }
    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25%;
    }
    .col-lg-4 {
        width: 33.33%;
    }
    .col-lg-5 {
        width: 41.66%;
    }
    .col-lg-6 {
        width: 50%;
    }
    .col-lg-7 {
        width: 58.33%;
    }
    .col-lg-8 {
        width: 66.66%;
    }
    .col-lg-9 {
        width: 74.99%;
    }
    .col-lg-10 {
        width: 83.33%;
    }
    .col-lg-11 {
        width: 91.66%;
    }
    .col-lg-12 {
        width: 100%;
    }
}


/* Tablet view options */

@media (min-width: 768px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
        float: left;
    }
    .col-md-1 {
        width: 8.33%;
    }
    .col-md-2 {
        width: 16.66%;
    }
    .col-md-3 {
        width: 25%;
    }
    .col-md-4 {
        width: 33.33%;
    }
    .col-md-5 {
        width: 41.66%;
    }
    .col-md-6 {
        width: 50%;
    }
    .col-md-7 {
        width: 58.33%;
    }
    .col-md-8 {
        width: 66.66%;
    }
    .col-md-9 {
        width: 74.99%;
    }
    .col-md-10 {
        width: 83.33%;
    }
    .col-md-11 {
        width: 91.66%;
    }
    .col-md-12 {
        width: 100%;
    }
}


/* Mobile view options */

@media (max-width: 767px) {
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
        float: left;
    }
    .col-sm-1 {
        width: 8.33%;
    }
    .col-sm-2 {
        width: 16.66%;
    }
    .col-sm-3 {
        width: 25%;
    }
    .col-sm-4 {
        width: 33.33%;
    }
    .col-sm-5 {
        width: 41.66%;
    }
    .col-sm-6 {
        width: 50%;
    }
    .col-sm-7 {
        width: 58.33%;
    }
    .col-sm-8 {
        width: 66.66%;
    }
    .col-sm-9 {
        width: 74.99%;
    }
    .col-sm-10 {
        width: 83.33%;
    }
    .col-sm-11 {
        width: 91.66%;
    }
    .col-sm-12 {
        width: 100%;
    }
}
