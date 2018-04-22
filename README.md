.nome {
	margin: 5px 0;
	padding: 10px 10px;
	background-color: #444444;
	font-size: 15px;
	color: #fff
}
.quem {	
	margin: 10px 0;
	padding: 30px 30px;
	color: #fff;
	font-size: 20px;
	text-align: center;
	background-color: #2283c9
}
  .nav {
  	text-align: center;
    display: flex;
    justify-content: flex-end;
    padding: 2em;    
    ul {
      list-style: none;
      margin: 20;
      padding: 0;
      display: flex;           
      a {
        position: relative;
        display: inline-block;
        padding: 1em;
        text-decoration: none;
        color: #fff;
        &:hover {
          color: rgba(255,255,255,0.7);
        }
      }
    }
  }
}
.blocos {
  display: block;
  width: 90%;
  margin: 20 auto;
  text-align: center;
}
  .blocos .bloco {
  	text-align: center;
    width: 40%;
    display: inline-table;
    background: #069;
    color: #fff;
    padding: 10px;
    margin: 5px;
  }  
  .blocos strong {
    font-family: Arial, Helvetica, Montserrat, sans-serif;
    text-align: center;
    color: 000;
    padding-bottom: 5px;
    font-weight: bold;
    font-size: 25px;
  }
  .blocos p {
    font-family: Arial, Helvetica, Montserrat, sans-serif;
    text-align: left;
  }
*{
	margin: 0;
	padding: 0;
}
.menu {
	width: 100%;
	height: 50px;
	background-color: #222;
	font-family: 'Arial';
}
.menu ul{
	list-style: none;
	position: relative;
}
.menu ul li {
	width: 150px;
	float: left;
}
.menu a {
	padding: 15px;
	display: block;
	text-decoration: none;
	text-align: center;
	background-color: #222;
	color: #fff;
}
.menu ul ul {
	position: absolute;
	visibility: hidden;
}
.menu ul li:hover ul {
	visibility: visible;
}
.menu a:hover {
	background-color: #f4f4f4;
	color: #555;
}
.menu ul ul li {
	float: none;
	border-bottom: solid 1px #ccc;
}
.menu ul ul li a {
	background-color: #069;
}
label[for="bt_menu"]{
	padding: 5px;
	background-color: #222;
	color: #fff;
	font-family: 'Arial';
	text-align: center;
	font-size: 30px;
	cursor: pointer;
	width: 50px;
	height: 50px;
}
#bt_menu {
		display: none;
	}
	label[for="bt_menu"]{
		display: none;
	}
@media (max-width: 600px){
	label[for="bt_menu"]{
		display: block;
	}
	#bt_menu: checked ~ .menu{
		margin-left: 0;
	}
	.menu {
		margin-top: 5px;
		margin-left: -100%;
		transition: all .4s;
	}
	.menu ul li {
		width: 100%;
		float: none;
	}
	.menu ul ul {
		position: static;
		overflow: hidden;
		max-height: 0;
		transition: all .4s;
	}
	.menu ul li:hover ul{
		height: auto;
		max-height: 200px;
	}				
}
@media (min-width: 600px) {
  .nome{
  	margin: 10px 0;	
  	padding: 20px 30px;
  	font-size: 30px;
  }
  .quem {
  	margin: 10px 0;
	padding: 30px 30px;
  	font-size: 54px;
  }
  strong {
  	font-size: 40px;
  }
}
