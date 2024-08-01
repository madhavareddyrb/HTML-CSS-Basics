here are html file and css file i will mention some gap to better understand

#class for doing styles to that particular passage
#<br> for hrizental space

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>buttonsprac</title> 
    <link rel="stylesheet" href="styles.css">    #relation to css file combination href refers to file name and rel means relation 
</head>
<body>
    <button class="Requestnow" >
        
       Request now
    </button>
    <br>

    <button class="add">
        Add to Cart
    </button>
         

    <button class="sign">

        Sign up
    </button>

    <button class="get">
        Get Started
    </button>
    
    <button class="download">
        Download
    </button>
    <br>
    <a class="back" href="https://www.amazon.com/">Back to amazon <br></a>
     <p>
        <br> #space
        <b>Nike Black Running Shoes</b>
     </p>
      
        <p class="stock"> #class for doing styles to that particular passage
            $39-in stock
        </p>
        <p class="free">
            Free Delivary Tomorrow
        </p>
        
        <button class="add">
            ADD to cart  
        </button>
                
            <button class="buy">
            Buy Now
        </button>
</body>
</html>


##CSS file code

.Requestnow {
     color:white;
     background-color: hsl(0, 0%, 0%);
     margin: 25px;
     padding: 10px;
     font-size: 20px;
     cursor: pointer;
     transition:opacity 1s ;
     -webkit-transition:opacity 1s ;
     -moz-transition:opacity 1s ;
     -ms-transition:opacity 1s ;
     -o-transition:opacity 0.15s ;
}
.Requestnow:hover{
    opacity:0.8;
}
.add{
    background-color: rgb(255,216,20);
    border:none;
    font-size: 20px;
    height: 50px;
    width:200px;
    border-radius:30px;
    font-weight: solid;
    -webkit-border-radius:30px;
    -moz-border-radius:30px;
    -ms-border-radius:30px;
    -o-border-radius:30px;
    margin-right: 20px;
    cursor: pointer;
}

.add:hover{
    background-color: rgb(213, 176, 26) ;
}
.sign{
    background-color:rgb(46,164,79);
    color: white;
    font-size:20px;
    height: 50px;
    width: 150px;
    font-weight: solid;
    border:none;
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -ms-border-radius: 5px;
    -o-border-radius: 5px;
    cursor: pointer;
    transition: box-shadow 0.15s ;
    margin-right: 20px;
    }
.sign:hover{
     box-shadow:0px 5px 8px ogba 0,0,0,0.15s;
}
.get{
    background-color: rgb(121, 82, 179) ;
    height:40px;
    width: 100px;
    border-radius:5px;
    -webkit-border-radius:5px;
    -moz-border-radius:5px;
    -ms-border-radius:5px;
    -o-border-radius:5px;
    border:none;
    color:white;
    margin-right:10px;
    cursor: pointer;

}

.get:hover{
    background-color: blueviolet;
}
.download{
    background-color: rgb(245, 245, 245);
    border:1px black solid;
    height: 40px;
    width:150px;
    cursor: pointer;
    margin-bottom: 40px;
}
.download:hover{
    background-color: rgba(0, 0, 0, 0.595);
    color:white;
}

.n{
    font-weight: soild;
    font-size: 20px;
    margin-top: 40px;
}

.back{
    cursor: pointer;
    color:aqua;
    font-size: 30px;
    margin-bottom: 50px;
}
.back:hover{
    color:red;
}

.stock{
    color:green;
    cursor:pointer;
    font-size: 20px;

}

.buy{
    background-color: orange;
    height: 50px;
    width: 150px;
    color:solid;
    border:none;
    border-radius: 20px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    -ms-border-radius: 20px;
    -o-border-radius: 20px;

}

.buy:hover{
    background-color: rgb(245, 190, 120);
    
}
.buy:active{
    opacity: 0.5;
}




