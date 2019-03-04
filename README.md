# guardian
A discord bot meant to help you moderate your server.

<a href="https://discordbots.org/bot/549302771510280203" >
  <img src="https://discordbots.org/api/widget/549302771510280203.svg" alt="Guardian" />
</a>

<div class="longdescription">
						<div class="content">
							
							<style>
  @import url('https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');
    p{
    	color: white;
  		font-size: 16px;
    }
    body{ 
    	background: #171717; 
    	font-family: 'Poppins', arial-black !important; 
    }
    .item {
    	color: white;
    	font-size: 14px;
    }
    #menu { 
    	background: #171717 !important; 
    	position: fixed; 
    }
    #menu ul li a:not(.btn) {
    	color: white !important;
    	background-color: none !important;
    	border-bottom: 1px solid #171717 !important;
    	transition: all .2s;
  		padding: 0.400rem 1rem !important;
    }
    #menu ul li a:not(.btn):hover{
    	color: white !important;
    	background-color: #171717 !important;
    	border-bottom: 1px solid gold !important;
    	transition: all .2s;
  		padding: 0.400rem 1rem !important;
    }
    code{ 
    	background-color: transparent;
    	font-size: .975em;
    	font-weight: 400;
    	padding: .25em .5em;
    	color: gold;
    	transition: all .5s;
    }
    code:hover{
    	color: white;
  		transition: all .5s;
    }
    .btn-orange {
  		border-radius: 100em;
    	background-color: gold;
  		transition: all .5s !important;
    	color: #171717;
    	border: 1px solid #171717 !important;
  		padding: 10px !important;
  	}
    .btn-orange:hover {
  		border-radius: 100em;
    	background-color: #171717;
    	color: gold;
    	transition: all .5s ease-in-out;
    	border: 1px solid gold !important;
  		padding: 10px !important;
    }
    .botpagebutton {
  		border-radius: 100em;
    	background-color: #252525;
  		padding: 0.400rem 1rem;
    	color: gold;
    	transition: all .4s ease-in-out;
  		height: auto;
  		line-height: 1.5 !important;
  		font-size: 14px !important;
    }
    .botpagebutton:hover {
  		border-radius: 100em;
    	background-color: #252525;
  		padding: 0.400rem 1rem;
    	color: white;
    	transition: all .4s ease-in-out;
  		height: auto;
  		line-height: 1.5 !important;
  		font-size: 14px !important;
    }
    #cdm-zone-01 { 
  		display: none !important; 
  	}
  	.color-blue{
  		background-color: #252525 !important;
  		border-radius: 10px;
    }
    .lib a { 
    	color: gold !important;
    	transition: all .8s
    }
    .lib a:hover { 
    	color: white !important;
    	transition: all .8s
    }
    .container.is-widescreen{ 
  		border: 0px !important; 
  	} 
    span.bot-name{ 
    	color: gold; 
    	border-bottom: 1px solid gold; 
    	margin-bottom: 20px;
   	}
    p.bot-description { color: white; }
    #bot-details-page .btn-like:after {
    	background-color: none;
    	color: gold;
    	padding-right: 5px;
    	content: " VOTES (CLICK TO VOTE)";
    	transition: all .8s;
    	white-space: pre;
    	border-radius: 5px;
    }
    .btn-like {
    	background-color: #00000030;
    	color: gold;
    	border: none;
    	border-radius: 5px;
    	transition: all .8s
    }
    .btn-like:hover {
    	background-color: #000;
    	color: gold;
    	padding-right: 5px;
    	transition: all .8s;
    	border-radius: 5px;
    }
    #upvotebutton img { 
    	filter: invert(100%) 
    }
    .atag {
    	background-color: #252525;
    	color: gold;
    	border-bottom: 1px solid #171717 !important;
    	transition: all .5s
    }
    .atag:hover {
    	background-color: #252525;
    	color: white;
    	transition: all .2s ease-in-out;
    }
  	.atag:after {
    	border-bottom: 13px solid transparent;
    	border-left: 10px solid #252525;
    	border-top: 13px solid transparent;
    	content: '';
    	position: absolute;
    	right: -10px;
    	transition: all .4s;
    	top: 0
	}
	.atag:hover:after {
    	background: 0 0 !important;
    	border-bottom: 13px solid transparent;
    	border-left: 10px solid gold;
    	border-top: 13px solid transparent;
    	content: '';
    	position: absolute;
    	right: -10px;
    	transition: all .4s;
    	top: 0
	}
    .bot-tags-title {
    	color: white;
    }
    .owners a{
    	color: gold;
    }
    #createdby b {
    	background-color: #252525 !important;
    	color: gold;
    	border-bottom: 1px solid #171717 !important;
    	transition: all .5s;
    }
    #createdby b:hover {
    	background-color: #252525 !important;
    	color: white;
    	transition: all.2s ease-in-out;
    	border-bottom: 1px solid gold !important;
    }
    .blog_card.blog_card_is_actually-server {
    	background: #252525 !important;
    }
    .blog_card.blog_card_is_actually_server:hover {
    	background: #171717 !important;
    }
    b {
    	color: white;
    }
    .longdescription { 
    	background: transparent !important;
    }
    .content { 
    	background: #171717 !important;
    }
    .no:hover:hover { 
    	background: #171717 !important;
    }
  	tr:hover {
  		background: #171717 !important;
  		border: none !important;
  	}
  	tr, td, th {
  		border: none !important;
  	}
  	th.title {
  		font-size: 16pt;
  		color: white !important;
  	}
  	th.sub-title {
  		font-size: 12pt;
  		color: white !important;
  	}
  	.note{
  		color: #fa6060 !important;
  		transition: all .5s;
  	}
  	.note:hover{
  		color: white !important;
    	transition: all .5s;
  	}
  	td{
  		font-weight: 300;
  		font-size: 10pt;
  	}
    html{
    	background: #171717 !important;
    }
  	.JoinServer {
  		border-radius: 100em;
    	background-color: gold;
    	color: #171717;
  		transition: all .4s ease-in-out;
    	border: 1px solid #171717 !important;
  		font-size: 14pt !important;
  		padding: 10px !important;
  		font: 600 18px "Karla", sans-serif !important;
  		margin-bottom: 20px !important;
  	}
    .JoinServer:hover {
  		border-radius: 100em;
    	background-color: #171717;
    	color: gold;
    	transition: all .4s ease-in-out;
    	border: 1px solid gold !important;
  		font-size: 14pt !important;
  		padding: 10px !important;
		font: 600 18px "Karla", sans-serif !important;
  		margin-bottom: 20px !important;
    }	
    .columns .bot-img { 
    	border-radius: 4px !important;
    	overflow: visible !important;
    	box-shadow: none !important;
    	background: 0 0 !important;
    	box-shadow: none !important;
    }
    .bot-img img {
    	-webkit-border-radius: 10px;
    	-moz-border-radius: 10px;
    	border-radius: 10px;
    	-webkit-box-shadow: 0 0 5px 1px gold;
    	box-shadow: 0 0 5px 1px gold;
    	-webkit-animation: mover 1.5s infinite alternate;
    	animation: mover 1.5s infinite alternate;
    	-webkit-animation-timing-function: ease-in-out;
   		animation-timing-function: ease-in-out;
    	-webkit-animation-iteration-count: infinite;
    	animation-iteration-count: infinite;
    	border-radius: 10%
  	}
  	@-webkit-keyframes mover {
  		0% { 
  			transform: translateY(0); 
  		}
  		100% { 
  			transform: translateY(-20px); 
  		}
  	}
  	@keyframes mover {
  		0% { 
  			transform: translateY(0); 
  		}
  		100% { 
  			transform: translateY(-20px); 
  		}
    }
    .bot-img img {
    	-webkit-animation: mover 1.5 infinite alternate;
    	animation: mover 1.5s infinite alternate;
    	-webkit-animation-timing-function: ease-in-out;
    	animation-timing-function: ease-in-out;
    	-webkit-animation-iteration-count: infinite;
    	animation-iteration-count: infinite;
  	}
  	.columns .bot-img { 
    	border-radius: 4px !important;
    	overflow: visible !important;
    	box-shadow: none !important;
    	background: 0 0 !important;
    	box-shadow: none !important;
    }
  	.centerr {
  		display: block;
  		margin-left: auto;
  		margin-right: auto;
 		width: 50%;
    	border-radius: 10px;
    	box-shadow: 0 0 5px 1px gold;
  		transition: all .5s ease-in-out;
	}
  	.centerr:hover {
  		display: block;
  		margin-left: auto;
  		margin-right: auto;
 		width: 50%;
    	border-radius: 10px;
    	box-shadow: 0 0 5px 1px #fa6060;
  		transition: all .5s;
	}
  	.medals-ex {
  		font-size: 16pt;
  		color: #fa6060 !important;
  		text-align: center !important;
  		padding-top: 20px !important;
  		padding-bottom: 20px !important;
  	}
    ::-moz-selection {
    	background: gold;
    	border-radius: 15px;
    }
    ::selection {
  		color: black;
    	background: gold;
    }
    ::webkit-scrollbar {
    	width: 9px;
    }
    ::-webkit-scrollbar-thumb {
    	background-color: gold;
    	border-radius: 8px;  
    }
    ::-webkit-scrollbar-track {
    	background-color: #252525;
    }
</style>

<p>A guardian that protects your discord server.</p>
<table style="border:0;color:white;">
  <tbody>
    <tr class="no-hover">
      <th class="title">GENERAL COMMANDS</th>
  	</tr>
  	<tr>
      	<td><code>g!help</code> Bot Info</td>
      	<td><code>g!setup</code> Bot Commands</td>
      	<td><code>g!upvote</code> Sends bot link</td>
    </tr>
    <tr class="no-hover">
      <th class="title">PLAYER'S COMMANDS</th>
    </tr>
    <tr>
      	<td><code>g!checkme</code> Show your warnings</td>
      	<td><code>g!getname [userid]</code> Show name of userid</td>
    </tr>
    <tr>
       <th class="title">STAFF COMMANDS</th>
    </tr>
    <tr>
      	<td><code>g!ban</code> Bans a user</td>
      	<td><code>g!kick</code> Kicks a user</td>
      <td><code>For more commands</code>Issue g!help</td>
    </tr>
    <tr class="no-hover">
      <th class="title">Features &amp; Specials</th>
    </tr>
    <tr>
      	<td><code class="note">Advanced Logging</code> We've designed an advanced logging</td>
      	<td><code class="note">Moderation</code> We've got lots of useful Moderation commands</td>
      	<td><code class="note">Updates</code> We're constantly putting out new updates</td>
    </tr>
</tbody></table>
<table style="border:0;color:white;">
  <tbody>
    <tr class="no-hover">
      <th class="title">UPDATES</th>
  	</tr>
    <tr>
      <td><code class="note">01-03-2019</code> Changes in logging, removed some logging for errortesting</td>
    </tr>
    <tr>
      <td><code class="note">01-03-2019</code> Updated more logging and moderation commands</td>
    </tr>
</tbody></table>
<br>
<br>
<br>
<div style="text-align:center">
  <a target="_blank" onclick="trackCampaignWebClick('', 'description');" rel="nofollow" href="https://discord.gg/WYNpfbc">
    <button class="JoinServer">Join Support Server</button>
  </a></div>
							
						</div>
					</div>

To run the bot use g!setup

For commands do g!help

For support, join our support server.

Made by leny32#0001
