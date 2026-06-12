---
title: UEL Academic Super Search
author: markbeachill@gmail.com
type: post
date: 2017-01-06T13:45:32+00:00
url: /uel-academic-super-search/
CODE1:
  - |
    <script language="JavaScript">
    		
    		
    function stopRKey(evt) { 
      var evt = (evt) ? evt : ((event) ? event : null); 
      var node = (evt.target) ? evt.target : ((evt.srcElement) ? evt.srcElement : null); 
      if ((evt.keyCode == 13) && (node.type=="text"))  
      {
      showInput();
      return false;
      } 
    } 
    
    document.onkeypress = stopRKey; 		
    		
    		
    function showInput() {
        var message_entered =  document.getElementById("user_input").value;
    	var m2 = "<a href='https://scholar.google.co.uk/scholar?hl=en&q=" + message_entered + "' target=_blank>Google Scholar search</a>";
        document.getElementById('display').innerHTML = m2;
    	m2 = "<a href='https://www.google.co.uk/search?q=.ac.uk+" + message_entered + "' target=_blank>UK Academic search</a>";
        document.getElementById('display2').innerHTML = m2;
    	m2 = "<a href='https://www.google.co.uk/search?q=.ac.uk+pdf+" + message_entered + "' target=_blank>UK Academic PDF search</a>";
        document.getElementById('display3').innerHTML = m2;
    	
    		m2 = "<a href='https://www.google.co.uk/search?q=" + message_entered + "' target=_blank>Google search</a>";
        document.getElementById('display-google').innerHTML = m2;
    	
    	
    
    		m2 = "<a href='https://www.google.co.uk/search?q=site:academia.edu " + message_entered + "' target=_blank>Academia.edu</a>";
        document.getElementById('display-academia').innerHTML = m2;
    
    
    
    
    
    
    
    	m2 = "<a href='https://www.google.com/search?tbm=bks&q=" + message_entered + "' target=_blank>Google Books search</a>";
        document.getElementById('display-googlebooks').innerHTML = m2;
    	
    	m2 = "<a href='https://www.google.co.uk/search?q=site:theguardian.com+" + message_entered + "' target=_blank>Guardian site search</a>";
        document.getElementById('display-guardian').innerHTML = m2;
    	
    	m2 = "<a href='https://www.google.co.uk/search?q=site:economist.com+" + message_entered + "' target=_blank>Economist site search</a>";
        document.getElementById('display-economist').innerHTML = m2;	
    	
    	m2 = "<a href='http://encore.lsbu.ac.uk/iii/encore/search?formids=target&lang=eng&suite=def&reservedids=lang%2Csuite&submitmode=&submitname=&submit2=GO%21&target=" + message_entered + "' target=_blank>LSBU Library search</a>";
        document.getElementById('display-lsbulibrary').innerHTML = m2;	
    	
    	m2 = "<a href='http://encore.lsbu.ac.uk/iii/encore/search?lang=eng&target=" + message_entered + "' target=_blank>LSBU library search</a>";
        document.getElementById('display-lsbulibrary').innerHTML = m2;	
    	
    	m2 = "<a href='http://lsbu.summon.serialssolutions.com/search?ho=t&l=en&q=" + message_entered + "' target=_blank>LSBU library journals search</a>";
        document.getElementById('display-lsbulibraryjournals').innerHTML = m2;	
    
    	
    		
    	
    	
    	
    		m2 = "<a href='https://uel.primo.exlibrisgroup.com/discovery/search?query=any,contains," + message_entered + "&tab=LibraryCatalog&search_scope=MyInstitution&vid=44UEL_INST:UEL_VU1&lang=en&offset=0" + "' target=_blank>UEL Library search</a>";
        document.getElementById('display-lsbulibrary').innerHTML = m2;	
    
    
    
    
    
    	
    	m2 = "<a href='https://uel.primo.exlibrisgroup.com/discovery/search?query=any,contains,"+ message_entered + "&tab=CentralIndex&search_scope=CentralIndex&vid=44UEL_INST:UEL_VU1&offset=0" + "' target=_blank>UEL Library journal search</a>";
        document.getElementById('display-lsbulibraryjournals').innerHTML = m2;
    	
    
    	
    
    	m2 = "<a href='http://bobnational.net/site/search?yt0=Search&query=" + message_entered + "' target=_blank>Box of Broadcasts search</a>";
        document.getElementById('display-bob').innerHTML = m2;	
    
    
    	
    	
    	m2 = "<a href='https://www.google.co.uk/search?q=site:telegraph.co.uk+" + message_entered + "' target=_blank>Telegraph site search</a>";
        document.getElementById('display-telegraph').innerHTML = m2;
    	
    	m2 = "<a href='https://www.google.co.uk/search?q=site:independent.co.uk+" + message_entered + "' target=_blank>Independent site search</a>";
        document.getElementById('display-independent').innerHTML = m2;
    
    
    	m2 = "<a href='https://www.google.co.uk/search?q=site:bbc.co.uk+" + message_entered + "' target=_blank>BBC site search</a>";
        document.getElementById('display-bbc').innerHTML = m2;	
    
    	m2 = "<a href='https://www.google.co.uk/search?q=site:dailymail.co.uk+" + message_entered + "' target=_blank>Daily Mail site search</a>";
        document.getElementById('display-dailymail').innerHTML = m2;
    
    	m2 = "<a href='https://www.google.co.uk/search?q=site:thesun.co.uk+" + message_entered + "' target=_blank>Sun site search</a>";
        document.getElementById('display-sun').innerHTML = m2;
    	
    	
    		m2 = "<a href='https://www.google.co.uk/search?q=site:mirror.co.uk+" + message_entered + "' target=_blank>Mirror site search</a>";
        document.getElementById('display-mirror').innerHTML = m2;
    
    	m2 = "<a href='https://www.google.co.uk/search?q=site:nytimes.com+" + message_entered + "' target=_blank>New York Times site search</a>";
        document.getElementById('display-nyt').innerHTML = m2;
    	
    	m2 = "<a href='https://www.google.co.uk/search?q=site:newstatesman.com+" + message_entered + "' target=_blank>New Statesman site search</a>";
        document.getElementById('display-newstatesman').innerHTML = m2;
    
    	m2 = "<a href='https://www.google.co.uk/search?q=site:spectator.co.uk+" + message_entered + "' target=_blank>Spectator site search</a>";
        document.getElementById('display-spectator').innerHTML = m2;	
    	
    		m2 = "<a href='https://www.google.co.uk/search?q=site:order-order.com+" + message_entered + "' target=_blank>Order Order site search</a>";
        document.getElementById('display-orderorder').innerHTML = m2;
    	
    		m2 = "<a href='https://www.google.co.uk/search?q=site:spiked-online.com+" + message_entered + "' target=_blank>Spiked Online site search</a>";
        document.getElementById('display-spiked').innerHTML = m2;
    	
    	
    	
    	m2 = "<a href='http://ethos.bl.uk/ProcessSearch.do?sedDownload.chk1=on&query=" + message_entered + "' target=_blank>British Library thesis search</a>";
        document.getElementById('display-blthesis').innerHTML = m2;
    	
    	
    
    	m2 = "<a href='https://www.youtube.com/results?search_query=" + message_entered + "' target=_blank>YouTube search</a>";
        document.getElementById('display-youtube').innerHTML = m2;
    	
    	
    		m2 = "<a href='https://twitter.com/search?q=" + message_entered + "' target=_blank>Twitter search</a>";
        document.getElementById('display-twitter').innerHTML = m2;
    	
    	m2 = "<a href='https://en.wikipedia.org/wiki/Special:Search?search=" + message_entered + "' target=_blank>Wikipedia search</a>";
        document.getElementById('display-wikipedia').innerHTML = m2;
    	
    
    	m2 = "<a href='http://www.newsnow.co.uk/h/?lang=en&search=" + message_entered + "' target=_blank>News Now aggregation</a>";
        document.getElementById('display-newsnow').innerHTML = m2;
    
    
    	
    	
    	
    	var yr = "&tbs=cdr%3A1%2Ccd_min%3A01%2F01%2F2011%2Ccd_max%3A";
    	
    	yr = "&tbs=cdr:1,cd_min:01/01/2011,sbd:1";
    	
    	
    	document.getElementById('SearchList').style.display = 'block';
    	
    	
    	document.getElementById('searchterms').innerHTML = message_entered;
    	
    	
    	
    	
    }
    
    
    
    
    
    
    
    
    
    
    
      </script>
    	<style>
    
    	body
    {
    	margin: 0;
    	padding: 0;
    	color: #333;
    	background-color: #eee;
    	font: 1em/1.2 "Helvetica Neue", Helvetica, Arial, Geneva, sans-serif;
    }
    
    h1,h2,h3,h4,h5,h6
    {
    	margin: 0 0 .5em;
    	font-weight: 500;
    	line-height: 1.1;
    }
    
    h1 { font-size: 2.25em; } /* 36px */
    h2 { font-size: 1.75em; } /* 28px */
    h3 { font-size: 1.375em; } /* 22px */
    h4 { font-size: 1.125em; } /* 18px */
    h5 { font-size: 1em; } /* 16px */
    h6 { font-size: .875em; } /* 14px */
    
    p
    {
    	margin: 0 0 1.5em;
    	line-height: 1.5;
    }
    
    blockquote
    {
    	padding: 1em 2em;
    	margin: 0 0 2em;
    	border-left: 5px solid #eee;
    }
    
    hr
    {
    	height: 0;
    	margin-top: 1em;
    	margin-bottom: 2em;
    	border: 0;
    	border-top: 1px solid #ddd;
    }
    
    table
    {
    	background-color: transparent;
    	border-spacing: 0;
    	border-collapse: collapse;
    	border-top: 1px solid #ddd;
    }
    
    th, td
    {
    	padding: .5em 1em;
    	vertical-align: top;
    	text-align: left;
    	border-bottom: 1px solid #ddd;
    }
    
    a:link { color: royalblue; }
    a:visited { color: purple; }
    a:focus { color: black; }
    a:hover { color: green; }
    a:active { color: red; }
    
    /* -----------------------
    Layout styles
    ------------------------*/
    
    .container
    {
    	max-width: 70em;
    	margin: 0 auto;
    }
    
    .header
    {
    	color: #fff;
    	background: #555;
    	padding: 1em 1.25em;
    }
    
    .header-heading { margin: 0; }
    
    .nav-bar
    {
    	background: #000;
    	padding: 0;
    }
    
    .content
    {
    	overflow: hidden;
    	padding: 1em 1.25em;
    	background-color: #fff;
    }
    
    .main, .aside
    {
    	margin-bottom: 1em;
    }
    
    .footer
    {
    	color: #fff;
    	background: #000;
    	padding: 1em 1.25em;
    }
    
    /* -----------------------
    Nav
    ------------------------*/
    
    .nav
    {
    	margin: 0;
    	padding: 0;
    	list-style: none;
    }
    
    .nav li
    {
    	display: inline;
    	margin: 0;
    }
    
    .nav a
    {
    	display: block;
    	padding: .7em 1.25em;
    	color: #fff;
    	text-decoration: none;
    	border-bottom: 1px solid gray;
    }
    
    .nav a:link { color: white; }
    .nav a:visited { color: white; }
    
    .nav a:focus
    {
    	color: black;
    	background-color: white;
    }
    
    .nav a:hover
    {
    	color: white;
    	background-color: green;
    }
    
    .nav a:active
    {
    	color: white;
    	background-color: red;
    }
    
    /* -----------------------
    Single styles
    ------------------------*/
    
    .img-responsive { max-width: 100%; }
    
    .btn
    {
    	color: #fff !important;
    	background-color: royalblue;
    	border-color: #222;
    	display: inline-block;
    	padding: .5em 1em;
    	margin-bottom: 0;
    	font-weight: 400;
    	line-height: 1.2;
    	text-align: center;
    	white-space: nowrap;
    	vertical-align: middle;
    	cursor: pointer;
    	border: 1px solid transparent;
    	border-radius: .2em;
    	text-decoration: none;
    }
    
    .btn:hover
    {
    	color: #fff !important;
    	background-color: green;
    }
    
    .btn:focus
    {
    	color: #fff !important;
    	background-color: black;
    }
    
    .btn:active
    {
    	color: #fff !important;
    	background-color: red;
    }
    
    .table
    {
    	width: 100%;
    	max-width: 100%;
    	margin-bottom: 20px;
    }
    
    .list-unstyled
    {
    	padding-left: 0;
    	list-style: none;
    }
    
    .list-inline
    {
    	padding-left: 0;
    	margin-left: -5px;
    	list-style: none;
    }
    
    .list-inline > li
    {
    	display: inline-block;
    	padding-right: 5px;
    	padding-left: 5px;
    }
    
    /* -----------------------
    Wide styles
    ------------------------*/
    
    @media (min-width: 55em)
    {
    	.header { padding: 1.5em 3em; }
    	.nav-bar { padding: 1em 3em; }
    	.content { padding: 2em 3em; }
    
    	.main
    	{
    		float: left;
    		width: 65%;
    		margin-right: 5%;
    		margin-bottom: 1em;
    	}
    
    	.aside
    	{
    		float: left;
    		width: 30%;
    		margin-bottom: 1em;
    	}
    
    	.footer { padding: 2em 3em; }
    	
    	.nav li
    	{
    		display: inline;
    		margin: 0 1em 0 0;
    	}
    	
    	.nav a
    	{
    		display: inline;
    		padding: 0;
    		border-bottom: 0;
    	}
    }
    
    .enjoy-css {
      display: inline-block;
      -webkit-box-sizing: content-box;
      -moz-box-sizing: content-box;
      box-sizing: content-box;
      width: 90%;
      height: 25px;
      padding: 10px 20px;
      border: 1px solid #b7b7b7;
      -webkit-border-radius: 10px;
      border-radius: 10px;
      font: normal 18px/normal Tahoma, Geneva, sans-serif;
      color: rgba(0,0,0,1);
      -o-text-overflow: clip;
      text-overflow: clip;
      letter-spacing: 2px;
      word-spacing: 5px;
      background: rgba(255,255,255,1);
      -webkit-box-shadow: 2px 2px 2px 0 rgba(0,0,0,0.2) inset;
      box-shadow: 2px 2px 2px 0 rgba(0,0,0,0.2) inset;
      text-shadow: 1px 1px 0 rgba(255,255,255,0.66) ;
      -webkit-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);
      -moz-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);
      -o-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);
      transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);
    }
    
    .enjoy-css-button {
      display: inline-block;
      -webkit-box-sizing: content-box;
      -moz-box-sizing: content-box;
      box-sizing: content-box;
      cursor: pointer;
      padding: 10px 20px;
      border: 1px solid #018dc4;
      -webkit-border-radius: 3px;
      border-radius: 3px;
      font: normal normal bold 16px/normal Arial, Helvetica, sans-serif;
      color: rgba(255,255,255,0.9);
      -o-text-overflow: clip;
      text-overflow: clip;
      background: #0199d9;
      -webkit-box-shadow: 2px 2px 2px 0 rgba(0,0,0,0.2) ;
      box-shadow: 2px 2px 2px 0 rgba(0,0,0,0.2) ;
      text-shadow: -1px -1px 0 rgba(15,73,168,0.66) ;
      -webkit-transition: all 300ms cubic-bezier(0.42, 0, 0.58, 1);
      -moz-transition: all 300ms cubic-bezier(0.42, 0, 0.58, 1);
      -o-transition: all 300ms cubic-bezier(0.42, 0, 0.58, 1);
      transition: all 300ms cubic-bezier(0.42, 0, 0.58, 1);
    }
    
    /* --------------------------
    base styles 
    -------------------------- */
    
    body
    {
    	margin: 0;
    	padding: 0;
    	color: #000;
    	background: #fff;
    	font: 1em/1.2 helvetica, arial, sans-serif;
    }
    
    h1
    {
    	margin: 0;
    	font-size: 1.5em;
    	font-weight: 500;
    }
    
    h2,h3
    {
    	margin: 0 0 1em;
    	font-size: 1.3em;
    	font-weight: 500;
    }
    
    p
    {
    	margin: 0 0 1.5em;
    	line-height: 1.5;
    }
    
    /* --------------------------
    layout 
    -------------------------- */
    
    .header
    {
    	background-color: #ccc;
    	padding: 1em;
    }
    
    .nav-bar
    {
    	color: #fff;
    	background-color: #000;
    }
    
    .content { padding: 1em; }
    .main { margin-bottom: 1em; }
    .aside { margin-bottom: 1em; }
    
    .footer
    {
    	clear: both;
    	padding: 1em;
    	background-color: #ccc;
    }
    
    /* --------------------------
    nav 
    -------------------------- */
    
    .nav
    {
    	margin: 0;
    	padding: 0;
    	list-style: none;
    }
    
    .nav li
    {
    	display: inline;
    	margin: 0;
    }
    
    .nav a
    {
    	display: block;
    	padding: .7em 1.25em;
    	color: #fff;
    	text-decoration: none;
    	border-bottom: 1px solid gray;
    }
    
    .nav a:link { color: white; }
    .nav a:visited { color: white; }
    
    .nav a:focus
    {
    	color: black;
    	background-color: white;
    }
    
    .nav a:hover
    {
    	color: white;
    	background-color: green;
    }
    
    .nav a:active
    {
    	color: white;
    	background-color: red;
    }
    
    /* --------------------------
    wide screen 
    -------------------------- */
    
    @media (min-width:700px)
    {
    	.header { padding: 1em 5%; }
    	.nav-bar { padding: 1em 5%; }
    	
    	.nav li
    	{
    		display: inline;
    		margin: 0 1em 0 0;
    	}
    	
    	.nav a
    	{
    		display: inline;
    		padding: 0;
    		border-bottom: 0;
    	}
    	
    	.content
    	{
    		overflow: hidden;
    		padding: 2em 0 1em;
    	}
    	
    	.main
    	{
    		float: left;
    		width: 60%;
    		margin-left: 5%;
    	}
    	
    	.aside
    	{
    		float: left;
    		width: 25%;
    		margin-left: 5%;
    	}
    	
    	.footer { padding: 1em 5%; }
    }
    
    	
    </style>
    	</head>
    	<body>
    	
    		<div class="content">
    			<div class="container">
    				<div class="main">
    
    					<!-- Heading levels -->
    <p>Type in search terms &amp; click "Search"
    <form>
    <input type="text" class="enjoy-css" width="100%" name="message" id="user_input" autofocus="autofocus"  onkeydown="if (event.keyCode == 13) document.getElementById('btnSearch').click()">
    </form>
    </p>
    <p>
    <input id="btnSearch" type="submit" onclick="showInput();" value="Search" class="enjoy-css-button"><br />
    </p>
    <p> </p>
    
    					<hr>
    <div id="SearchList" style="display:none">
    </div>
    
    <div>
    <h2>Searches for <br /><span id='searchterms' style="color:red;">UNSPECIFIED</span></h2>
    <p> </p>
    
    
    <table>
    		
    						
    						
    						
    						
    							<tr>
    								<td colspan=2><b>UEL Library</td>
    							</tr>
    						
    						
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-lsbulibrary'>UEL Library</span></td>
    							</tr>
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-lsbulibraryjournals'>UEL Library Journals</span></td>
    								
    							</tr>
    
    							<tr>
    								<td colspan=2><b>Scholar/academic</td>
    							</tr>
    
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display'>Google Scholar</span></td>
    							</tr>
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-googlebooks'>Google Books</span></td>
    							</tr>							
    							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td colspan=2><span id='display2'>UK academic</span></td>
    							</tr>
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display3'>UK academic PDF</span></td>
    							</tr>
    
    
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-academia'>Academia.edu</span></td>
    							</tr>
    
    
    							
    							<tr>
    								<td colspan=2><b>Video and Wikipedia</td>
    							</tr>
    							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-bob'>Box of Broadcasts</span><br>requires login</td>
    							</tr>
    
    							
    			<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-youtube'>YouTube</span></td>
    							</tr>
    			
    
    
    <tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-wikipedia'>Wikipedia</span><br>*Use for a quick overview - do not cite in your work*</td>
    							</tr>
    			
    
    			
    							<tr>
    								<td colspan=2><b>Newspapers (&amp;BBC)</td>
    							</tr>
    							
    							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-newsnow'>News Now aggregation</span></td>
    							</tr>							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-guardian'>Guardian site search</span></td>
    							</tr>
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-telegraph'>Telegraph site search</span></td>
    							</tr>
    							
    							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-independent'>Independent site search</span></td>
    							</tr>
    
    
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-dailymail'>Daily Mail site search</span></td>
    							</tr>
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-sun'>Sun site search</span></td>
    							</tr>
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-mirror'>Mirror site search</span></td>
    							</tr>
    							
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-bbc'>BBC site search</span></td>
    							</tr>				
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-nyt'>New York Times site search</span></td>
    							</tr>							
    							
    							
    							<tr>
    								<td colspan=2><b>Magazines</td>
    							</tr>
    							
    							
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-economist'>Economist site search</span></td>
    							</tr>
    
    
    							<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-spectator'>Spectator site search</span></td>
    							</tr>
    
    													<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-newstatesman'>New Statesman site search</span></td>
    							</tr>
    
    
    							
    
    							
    							<tr>
    								<td colspan=2><b>Online</b></td>
    							</tr>							
    														<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-spiked'>Spiked-Online site search</span></td>
    							</tr>	
    							
    							<tr><td>&nbsp;&nbsp;</td>
    
    								<td><span id='display-orderorder'>Order Order site search</span></td>
    							</tr>							
    							
    							
    							<tr>
    								<td colspan=2><b>Other</b></td>
    							</tr>
    							
    							
    													<tr><td>&nbsp;&nbsp;</td>
    
    								<td><span id='display-google'>Google search</span></td>
    							</tr>
    
    							
    														<tr><td>&nbsp;&nbsp;</td>
    								<td><span id='display-twitter'>Twitter search</span></td>
    							</tr>							
    							
    														<tr><td>&nbsp;&nbsp;</td>
    
    								<td><span id='display-blthesis'>British Library Thesis search</span></td>
    							</tr>							
    							
    	
    					</table>
    
    </div>
    
    
    
    
    
    
    
    
    	<!-- Paragraphs 
    					<h3>Paragraphs</h3>
    					<p>Ut wisi enim ad minim veniam, <a href="#">quis nostrud exerci tation ullamcorper</a> suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
    					<p>Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>
    					<hr>
    -->
    			
    
    	<!-- 				<h3>Buttons</h3>
    					<p>You can apply the <code>btn</code> class to any element that requires a button style.</p>
    					<p><a href="#" class="btn">Submit</a></p>
    					<hr>-->
    
    				</div>
    
    			</div>
    				<div class="aside">
    					<h3>Sidebar</h3>
    					<p>This search page will help you search for terms from a wide range of sources</p>
    					<p>It is configued for UEL students in media and journalism</p>
    					
    					<p>
    					
    					<a href="https://scholar.google.co.uk/scholar_setprefs?instq=East+London" target="_blank">Set Scholar to Show East London Links</a>
    					
    					
    				</div>
    		</div>
categories:
  - Research

---
%CODE1%