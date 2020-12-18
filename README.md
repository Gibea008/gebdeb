<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="css/cs.css">
    <title>Final Exam</title>
</head>

<body>
    <h1><strong>Our Menu</strong></h1>
    <div id="pagewrap">
        <section id="content">
            <div id="second">HOKKAIDO</div>
              lorem ipsum dolor sit amet, consectetur adipisicing elit,sed do eiusmod tempor incididunt 
              ut labore et dolor magna aliqua.ut enim ad minim veniam ,quis nostrud 
              exercitation ullamaco laboris nisi ut aliquip ex ea commondo consequat.   
        </section>

        <section id="middle">
            <div id="second">OKINAWA</div>
            lorem ipsum dolor sit amet, consectetur adipisicing elit,sed do eiusmod tempor incididunt 
            ut labore et dolor magna aliqua.ut enim ad minim veniam ,quis nostrud 
            exercitation ullamaco laboris nisi ut aliquip ex ea commondo consequat.  
        </section>

        <aside id="sidebar">
            <div id="second">MELON</div>
            lorem ipsum dolor sit amet, consectetur adipisicing elit,sed do eiusmod tempor incididunt 
            ut labore et dolor magna aliqua.ut enim ad minim veniam ,quis nostrud 
            exercitation ullamaco laboris nisi ut aliquip ex ea commondo consequat.  
        </aside>
        <style>
          body{
    padding: 0px;
    font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:antialiased;

}
.center
{
    margin: 0px auto;
}

h1{
    color: black;
    text-align: center;
}

/* STRUCTURE */

#pagewrap {
	padding: 5px;
	width: 100%;
	margin: 5px auto;
}

#content {
	width: 28%;
	float: left;
    padding: 5px 15px;
    border: 1px solid black;
    background-color: aqua;
}

#middle {
	width: 28%;
	float: left;
	padding: 5px 15px;
    margin: 0px 5px 5px 5px;
    border: 1px solid black;
    background-color: pink;
}

#sidebar {
	width: 28%;
	padding: 5px 15px;
    float: left;
    border: 1px solid black;
    background-color: blue;
}
#content #second{
    border: 2px solid black;
    width: 20%;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: rgb(47, 180, 7);
    text-align: center;
}
#middle #second{
    color: whitesmoke;
    border: 2px solid black;
    width: 20%;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: orange;
    text-align: center;
}
#sidebar #second{
    border: 2px solid black;
    width: 20%;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: yellow;
    text-align: center;
}

@media screen and (max-width: 1000px) {
	
	#pagewrap {
		width: 100%;
	}
	#content {
		width: 41%;
		padding: 1% 4%;
	}
	#middle {
		width: 41%;
		padding: 1% 4%;
		margin: 0px 0px 5px 5px;
		float: right;
	}
	
	#sidebar {
		clear: both;
		padding: 1% 4%;
		width: auto;
		float: none;
	}

	
}

@media screen and (max-width: 767px) {

	#content {
		width: auto;
        float: none;
        
	}
	
	#middle {
		width: auto;
		float: none;
		margin-top: 4px;
	}
	
	#sidebar {
		width: auto;
		float: none;
	}
  * {
    box-sizing: border-box;
}
.row{
    position: relative;
    width: 100%;
}
.title{
    position: relative;
    float: right;
    border: 1px solid black;
    color: white;
    font-size: 20px;
    padding: 5px 20px 5px 20px;
}
p{
    position: relative;
    margin: 35px 0 0 0;
    padding: 5px;
}
.bg-red{
    background-color: rgb(0, 255, 34);
}
.bg-green{
    background-color:rgb(58, 128, 0);
}
.bg-yellow{
    background-color: rgb(102, 255, 0);    
    color: black;
}
h1{
    text-align: center;
}
/*large devices*/
@media(min-width: 992px){
   .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12{
       float: left;
   }
   .col-lg-1{
       width: 8.33%;
   }
   .col-lg-2{
       width: 16.66%;
   }
   .col-lg-3{
       width: 25%;
   }
   .col-lg-4{
        width:33.33%;
   }
   .col-lg-5{
       width:41.66%;
   }
   .col-lg-6{
       width:50%;
   }
   .col-lg-7{
       width:58.33%
   }
   .col-lg-8{
       width:66.66%
   }
   .col-lg-9{
       width:75%;
   }
   .col-lg-10{
       width:83.33%;
   }
   .col-lg-11{
       width:91.66%;
   }
   .col-lg-12{
       width:100%;
   }
   .container{
        border: 2px solid rgb(0, 140, 255);
        margin:15px;
        box-sizing: border-box;
        color: white;
   }
   .lg-bg-purple{
        background-color: rgb(9, 131, 29);
        color: white;
    }
    .lg-bg-pink{
        background-color:rgb(192, 204, 255);
        color:black;
    }
    .lg-bg-orange{
        background-color: rgb(0, 255, 170);    
        color: black;
    }
    .lg-bg-grey{
        background-color: rgb(128, 128, 128);
    }
}
/*Medium devices*/
@media(min-width: 768px) and (max-width: 991px){
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12{
        float: left;
    }
    .col-md-1{
        width: 8.33%;
    }
    .col-md-2{
        width: 16.66%;
    }
    .col-md-3{
        width: 25%;
    }
    .col-md-4{
         width:33.33%;
    }
    .col-md-5{
        width:41.66%;
    }
    .col-md-6{
        width:50%;
    }
    .col-md-7{
        width:58.33%
    }
    .col-md-8{
        width:66.66%
    }
    .col-md-9{
        width:75%;
    }
    .col-md-10{
        width:83.33%;
    }
    .col-md-11{
        width:91.66%;
    }
    .col-md-12{
        width:100%;
    }
    .container{
        border: 2px solid green;
        box-sizing: border-box;
        background-color: grey;
        margin: 15px;
   }
   .md-bg-red{
        background-color: rgb(0, 255, 157);
        color: white;
    }
    .md-bg-green{
        background-color:rgb(0, 66, 128);
        color:white;
    }
    .md-bg-yellow{
        background-color: rgb(162, 0, 255);    
        color: black;
    }
   .md-bg-brown{
        background-color: brown;
    }
}
/*Small devices*/
@media(max-width: 767px){
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12{
        float: left;
    }
    .col-sm-1{
        width: 8.33%;
    }
    .col-sm-2{
        width: 16.66%;
    }
    .col-sm-3{
        width: 25%;
    }
    .col-sm-4{
         width:33.33%;
    }
    .col-sm-5{
        width:41.66%;
    }
    .col-sm-6{
        width:50%;
    }
    .col-sm-7{
        width:58.33%
    }
    .col-sm-8{
        width:66.66%
    }
    .col-sm-9{
        width:75%;
    }
    .col-sm-10{
        width:83.33%;
    }
    .col-sm-11{
        width:91.66%;
    }
    .col-sm-12{
        width:100%;
    }
    .container{
        border: 2px solid rgb(0, 174, 255);
        margin:15px;
        box-sizing: border-box;
   }
   .sm-bg-red{
        background-color: rgb(0, 255, 13);
        color: white;
    }
    .sm-bg-green{
        background-color:rgb(58, 128, 0);
        color: white;
    }
    .sm-bg-yellow{
        background-color: rgb(102, 255, 0);    
        color: black;
    }
    .title{
        position: relative;
        float: right;
        border: 1px solid black;
        color: white;
        font-size: 20px;
        padding: 5px 20px 5px 20px;
    }
    .sm-bg-brown{
        background-color: brown;
    }
}
        </style>


    </div>

</body>

</html>