<template>

	<div>

	<div class="container-fluid bg-1 text-center" id="home">

		<h3 class="margin animated fadeInDown" id="h1">

			<b v-text="nm"></b>

		</h3>
		<a href="mailto:satishpal456@gmail.com" >

		<button type="button" class="btn btn-success btn-lg" id="bt1">

			<i class="fa fa-envelope" style="font-size: 25px;color:black"></i>&nbsp;<label style="color: white">E-mail</label>

		</button>
	</a>

		<a href="https://github.com/satishpal456">

			<button type="button" class="btn btn-success btn-lg " id="bt2">

				<i class="fa fa-github" style="font-size: 25px;color:black"></i>&nbsp;<label style="color: white;">Github</label>

			</button>

		</a>
		
		<h3 class="margin text-center" id="h2">

			<b>MY BLOG</b>

		</h3>

</div>

<div class="container-fluid" id="bioche">

	<div class="row" style="padding-bottom: 70px;">

	<div class="text-center">

		<h1 style="padding-top: 40px;text-shadow: 2px 2px black;font-size: 50px;padding-bottom: 50px;color: tomato;font-family:times new roman ">

			<b>BIO</b>

		</h1>
	</div>

	<div class="col-sm-12 text-center" id="lop" >
				
				<div class=" text-center">
					
					<h3 class=" margin text-center"  style="text-transform: capitalize;text-align:center;"  v-html="bio()"></h3>
				
				</div>
	</div>

	</div>

</div>

	<div class="container-fluid text-center" id="friendche" style="padding-bottom: 30px">

		<div class="text-center">

			<h1 id="kak">

				<strong v-text="frnd" style="color: white;"></strong>
			</h1>
		</div>
		<div class="col-sm-6">

			<h2 class="text-center" id="pika">

				<strong>{{College()}}</strong>

			</h2>
			
			<h3 id="pop" class="text-center" style="color: black; text-transform: capitalize;text-align: center;" v-html="College23()"> </h3>
			
			<img src="./assets/IMG-20180409-WA0039.jpg" class="img-responsive  margin" style="display:inline" alt="Bird" width="350" height="350">
		
		</div>
		
		<div class="col-sm-6">
			
			<h2 class="text-center" id="pika">

				<strong>{{Nadiad()}}</strong>

			</h2>
			
			<h3 class="text-center" style="text-transform: capitalize;color: black;text-align: center;" v-html="nadiad22()"> </h3>
			
			<img src="./assets/IMG-20170325-WA0016.jpg" class="img-responsive margin" style="display:inline" alt="Bird" width="350" height="350">
		
		</div>
	
	</div>

<div class="container-fluid text-center" id="sl">
	
	<h1 class=" text-center" id="skl">

		<strong>Skills</strong>

	</h1>
	
	<h3 class="margin text-center" >

		<label id="js" v-text="skill1"></label>
	</h3>

		<h3 class="margin text-center">

			<label id="js">{{skill2}}</label>

		</h3>
			
			<h3 class="margin text-center">

				<label id="js" v-text="skill3"></label>

			</h3>
				
				<h3 class="margin text-center">

					<label id="js">{{skill4}}</label>

				</h3>
					
					<h3 class="margin text-center">

						<label id="js" v-text="skill5"></label>

					</h3>

						<h3 class="margin text-center">

							<label id="js">{{skill6}}</label>

						</h3>
</div>

<div class="container-fluid text-center" style="height: 300px;background-color: lightgrey;">

	<h3 class="margin" style="text-transform: capitalize; color: black;padding-top: 90px;">

		<b>if you fall me in any situation,i'm ready to fight with any type of situation</b>

	</h3>

	<h4 class="margin" style="color: black;font-size: 20px;" v-html="name"></h4>

</div>

<div class="container-fluid" style="background-color: black">

	<div class="col-sm-4 text-center responsive">

		 <a href="https://www.instagram.com/__satish_pal__/" data-toggle="tooltip" title="Contact through Instagram" style="color: purple;">

		 	<i class="fa fa-instagram" id="pl"></i>
		 
		 	<br><label style="font-size: 30px;color: white">Instagram</label>

		 </a>

	</div>
	
	<div class="col-sm-4 text-center">

		 <a href="https://www.facebook.com/satish.pal.925" data-toggle="tooltip" title="Contact through Fb" style="color: darkblue;">

		 	<i class="fa fa-facebook" id="pl"></i>

		 	<br><label style="font-size: 30px;color: white">Facebook</label>

		 </a>

	</div>

	<div class="col-sm-4 text-center">
		 
		 <a href="tel:+919824028173" data-toggle="tooltip" title="Contact Me" style="color: green;"><i class="fa fa-phone" id="pl"></i><br><label style="font-size: 30px;color: white">Call </label></a>
	
	</div>

</div>

<div class="container-fluid text-center" style="background-color:black;border-top: 2px solid white;border-top-width: thick;">

	<div class="col-sm-12" style="color: white">

		<h1>

			<strong>&copy;</strong>{{end()}}</h1>

	</div>

</div>
	<a id="top" href="" class="to-top"><i class="glyphicon glyphicon-chevron-up"></i> </a>

	</div>

</template>


<script>
	export default{data(){return{skill1:"Javascript",skill2:"Java",skill3:"HTML",skill4:"CSS",skill5:"Firebase",skill6:"Bootstrap",
name:'<strong>--Satish Pal</strong>',frnd:'Friends Life',nm:"Satish Pal"}},
	 methods: {end : function() {return "All Rights Reserved";},College:function(){return "College"},Nadiad:function(){return "Nadiad"
      },bio:function(){
      	return "<strong>Hello Guys You alredy know my name,Reading title of the page.<br>\
      	I am current study in KJIT,Savli in 3rd Year BE IT('Information Technology').<br>\
      	i want to convert my passion into profit for human's better life.<br>\
      	i don't believe in future because future never comes if, it is come so come into the present situation.<br>My Dream is not big, i want to build my own small software company.<br><br> \
      	<label style='color:red;'>'Support hardley open source'</label></strong>"
      },
      College23:function(){
      	return "<strong>College is Heaven of the earth after school,i am not only got Friends or squad but i got family more than family.<br>\
      	my some Friends are topper of a class or some of second to last topper of the class\
      	or some friends are creative.<br><br><label style='color:red;'>'sorry but it's true no one can beat me comedy in my group'<label> </strong>"
      },
      nadiad22:function(){
      	return "<strong>Here i saw quality of friends not quantity of friend.<br>here my friends motivates me god gifted me friends cum brother like you buddies.<br>\
      	here we spent every evening with each other,telling jokes,some meaning less words that's the memory i can't forget.<br><br>\
      	<label style='color:red'> 'no more words for you brothers.'</label></strong><br><br>"
      }
   }
}
</script>

<style scoped>
	#home
	{
		 background-color: black;
		height: 300px;
		-webkit-animation:mymove 3s infinite;
animation:mymove 3s infinite; 
font-style: bold;
	}
	 @keyframes mymove 
	 {
    from {background-color:  black;}
    to {background-color: rebeccapurple;}
		}
		@-webkit-keyframes mymove {
    	from {background-color:  black;}
    to {background-color: rebeccapurple;}
}

#bioche
	{
	background-color: darkseagreen;
		color: black;
		-webkit-animation:myfun 3s infinite;
animation:myfun 3s infinite; 
	}
@keyframes myfun 
	{
    from {background-color:  darkseagreen;}
    to {background-color:goldenrod;}
	}
	@-webkit-keyframes myfun {
    	from {background-color:  darkseagreen;}
    to {background-color:goldenrod;}
}
#friendche
	{
	background-color:rgb(122,152,149);
		-webkit-animation:myx 3s infinite;
animation:myx 3s infinite; 
	}
@keyframes myx
	{
	from {background-color:rgb(122,152,149)}
    to {background-color:cornflowerblue;}
	}
	@-webkit-keyframes myx {
    from {background-color:rgb(122,152,149)}
    to {background-color:cornflowerblue;}	
}
	#h1
	{
		padding-top: 10px;
		text-shadow: 2px 2px  black;
		color: tomato;

	}
	#bt1
	{
		margin-top: 50px;
		border:4px solid goldenrod;
	}
	#bt2
	{
			margin-top: 50px;
		margin-left: 0px;
		border:4px solid goldenrod;
	}
	#h2
	{
		margin-top: 40px;
		font-family: comicsansms;
		font-size: 36px;
		text-shadow: 2px 2px  black;
		color: white;
	}
	#bt1:hover 
	{
    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
    background-color: skyblue;
    border: 4px solid hotpink;
}
#bt2:hover 
{
    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
    background-color: skyblue;
     border: 4px solid hotpink;
}
#h1
{
	font-family: comic sans ms;
	font-size: 40px;
}
#skl
{
	color: tomato;
	text-shadow: 2px 2px black;
	font-size: 50px;
	padding-bottom: 30px;
}
#sl
{
	background-color: black;
	color: white;
}
#js
{
	font-size: 30px;
	padding-bottom: 30px;
}
#js:hover
{
	color: deepskyblue;
}
#kak
{
	color: rebeccapurple;
	font-size: 50px;
	text-shadow: 2px 2px black;
}
#pika
{
	color:indianred;
	text-shadow: 2px 2px black;
	font-size: 40px;
}
#pl
{
	font-size: 100px;
	padding-top: 30px;
	padding-bottom: 15px;
}
#ooo:hover
{
	background: linear-gradient(to left,rebeccapurple,hotpink)
}
.to-top
{
	position: fixed;
	bottom: 20px;
	right: 20px;
	background: white;
	color: black;
	padding: 9px 12px;
	border-radius: 50%;
	cursor: pointer;
	box-shadow: 2px 2px 16px rgba(0,0,0,0.3);
	transition: all 0.5s ease;
}
.to-top:hover
{
	background:blue;
	color: white;
	transform: scale(1.4,1.4);
	transition: all 0.5s ease;
}

</style>