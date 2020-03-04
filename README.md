<!--
    |_
    (O)
    |#|
    '-'
   
Main ingredient : DOM (no jQuery, no Bootstrap)

Coders & © : JD & KING👑

This is a mobile with some basic apps in it.
from a bot to video player😁, 
20+1 apps crafted on a basic theme.💝

Name : Android OS
version : 2.0
Published : 10 Mar 2019

If you find bugs please report it in comments.
Also drop your suggestions & feedback in comments.
Thanks for checking😎👍
-->

<!--
    by default connection type will be WiFi
    iOS devices don't support battery type, so default is 100%
    
    +-*/= shortcut to close calculator😁 
    🥚command 'connect' in terminal is necessary, get a code, write that in phone & call🥚
-->
<!DOCTYPE html>
<html id="html">
<head>
    <title>Mobile</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://fonts.googleapis.com/css?family=Barlow|Baloo+Bhaijaan|Caveat|Indie+Flower|Monoton|Pattaya|Satisfy|Shadows+Into+Light|Spicy+Rice|VT323" rel="stylesheet">
</head>
<body id="body" onload="if(navigator.onLine==true){document.getElementById('mobload').style.display='none';}else{alert('Connect to network')}">
<!-- try reloading the code, if the loader is slow -->
<div class="mobileloader" id="mobload"><i class="fa fa-circle-o-notch fa-spin"></i></div>
<div id="notific" class="notific" align="right"><span id="usericon"></span> <span id="musicnotico"></span> <span id="wifiico"></span> <b><span id="batt"></span> &nbsp; <span id="times"></span></b></div><br/><br/>
<div class="content" id="content">
       <div class="mapp" id="mapp1" onclick="openassistant()" align="center" title="Assistant">
           <img src="https://3.bp.blogspot.com/-_vSOM2NjQUs/W4ztNZgzVYI/AAAAAAAAEqk/Am3o5MESpPgXaxpHDLLkFICGRD5CBi4GwCLcBGAs/s320/assi.jpg" width="70" height="70" id="ap1"/><br/>
           <span class="apname" align="center" id="aptxt1">Assistant</span>
       </div>
       <div class="mapp" id="mapp2" onclick="obrowser()" align="center" title="Browser">
        <img src="https://2.bp.blogspot.com/--kHORty-sZI/XERw7zeB4jI/AAAAAAAAJuc/2gKNWmTWdDAH1EPn00Z9qDk6370pBmu5wCLcBGAs/s1600/PicsArt_01-20-06.44.21.png" width="70" height="70" id="ap4"  /><br/>
        <span class="apname" align="center" id="aptxt2">Browser</span> 
    </div>
    <div class="mapp" id="mapp3" onclick="showcalc()" align="center" title="Calculator">
        <img src="https://1.bp.blogspot.com/-cW_hfIWmSHQ/XG7gzh0RSMI/AAAAAAAAKrs/ATbYZE0vCtsPRfynp68tr6J39I0siXrYwCPcBGAYYCw/s1600/PicsArt_02-21-11.11.32.png?fbclid=IwAR0Ha7B6QTAcUDIkmKGupQ2a04hr8EA9S-Kl5vl-n0-wxVugysJsVKHq-pI" width="70" height="70" id="ap2" /><br/>
        <span class="apname" align="center" id="aptxt3">Calculator</span>
    </div>
    <div class="mapp" id="mapp4" onclick="cal()" align="center" title="Calendar">
        <img src="https://2.bp.blogspot.com/-FlZ4r2MkScU/W3KkiwZIn4I/AAAAAAAADzM/HkCkeqNt1WInjM1YAd6ZS4JOtJ1eA8oWQCLcBGAs/s200/calendar.jpg" width="70" height="70" id="ap3" /><br/>
        <span class="apname" align="center" id="aptxt4">Calendar</span>
    </div>
    <div class="mapp" id="mapp5" onclick="showclock()" align="center" title="Clock">
        <img src="https://3.bp.blogspot.com/-Oho9jBzmuTY/W4zsTSAWcyI/AAAAAAAAEqE/0Y2-hyamH7YKq47a5aPIt7Wdj3KYKmWYACLcBGAs/s320/clock.jpg" width="70" height="70" id="ap5" /><br/>
        <span class="apname" align="center" id="aptxt5">Clock</span>
    </div>
    <div class="mapp" id="mapp6" onclick="odevmode()" align="center" title="Developer Mode">
        <img src="https://2.bp.blogspot.com/-X3Do6HiExgU/XIJnn214PVI/AAAAAAAALQs/Z1DeTmDqGH4yJfM6dxONM2jhujnYsvrGQCLcBGAs/s1600/PicsArt_03-08-06.43.31.png" width="70" height="70" id="ap6" /><br/>
        <span class="apname" align="center" id="aptxt6">Developer</span>
    </div>
    <div class="mapp" id="mapp7" onclick="showdevs()" align="center" title="Devs☺">
        <img src="https://3.bp.blogspot.com/--I8y0L5sInI/W4zsbBqvnYI/AAAAAAAAEqI/1TMS_gPGbF4EqmGZrqnURs8qs99q-ldwQCLcBGAs/s320/dev.jpg" width="70" height="70" id="ap7" /><br/>
        <span class="apname" align="center" id="aptxt7">Devs</span>
    </div>
    <div class="mapp" id="mapp21" align="center" style="display: none" onclick="omeme()" title="Easter Egg">
        <img src="https://4.bp.blogspot.com/-GTkeEP8yrA0/XIJpguYziFI/AAAAAAAALQ4/anTozHwiZTAx5zx6bev1zw2fyJj0D_tDwCLcBGAs/s1600/PicsArt_03-08-06.51.16.png" width="70" height="70" id="ap21" /><br/>
        <span class="apname" align="center" id="aptxt21">Easter Egg</span>
    </div>
    <div class="mapp" id="mapp8" align="center" onclick="openmaila()" title="E-mail">
        <img src="https://3.bp.blogspot.com/-02Uy6CDhxSY/W3KkkHKf2II/AAAAAAAADzQ/GdALKATh7NUWFV_cZ3ClZ_nvpWwWuKZAwCLcBGAs/s200/email.jpg" width="70" height="70" id="ap8" /><br/> 
        <span class="apname" align="center" id="aptxt8">E-mail</span>
    </div>
    <div class="mapp" id="mapp9" onclick="maps()" align="center" title="Maps">
        <img src="https://2.bp.blogspot.com/-h7l3UsgWNwk/XG7g2KzqEDI/AAAAAAAAKr4/G6GLcMQTFD8sLXQy2YUpjT1ot036XfKBACPcBGAYYCw/s1600/PicsArt_02-21-11.13.57.png" width="70" height="70" id="ap9" /><br/>
        <span class="apname" align="center" id="aptxt9">Maps</span>
    </div>
    <div class="mapp" id="mapp10" onclick="musicplayer()" align="center" title="Music">
        <img src="https://4.bp.blogspot.com/-K3ERktIEtUc/W3KporvaujI/AAAAAAAAD0A/UjaGfe7wjy8wz3ApFj82Wc0D9KvbnE0WQCLcBGAs/s200/music.jpg" width="70" height="70" id="ap10" /><br/>
        <span class="apname" align="center" id="aptxt10">Music</span>
    </div>
    <div class="mapp" id="mapp11" onclick="phone()" align="center" title="Phone">
        <img src="https://4.bp.blogspot.com/-GDCDaAXKDmM/W4z7VPIB9sI/AAAAAAAAEq0/rETlH77WjCkiT2LYKUS1A0yXc3syxHq-gCLcBGAs/s200/contact.jpg" width="70" height="70" id="ap11" /><br/>
        <span class="apname" align="center" id="aptxt11">Phone</span>
    </div>
    <div class="mapp" id="mapp12" onclick="ophotoeditor()" align="center" title="Photo Editor">
        <img src="https://1.bp.blogspot.com/-ICEkNDT7n38/XG7g1aCPXQI/AAAAAAAAKr0/5c_ytrTO28AD5cNrpCX67s9gT1gQHJqxgCPcBGAYYCw/s1600/PicsArt_02-21-11.12.59.png" width="70" height="70" id="ap12" /><br/>
        <span class="apname" align="center" id="aptxt12">Photo Editor</span>
    </div>
    <div class="mapp" id="mapp13" onclick="settings()" align="center" title="Settings">
        <img src="https://1.bp.blogspot.com/-kty_OnX3F68/W3Kkn4m6FRI/AAAAAAAADzY/ps3ydaz2mtQqWSNtjR6kzP2Mcl3_fYJwQCLcBGAs/s200/setting.jpg" width="70" height="70" id="ap13" /><br/>
        <span class="apname" align="center" id="aptxt13">Settings</span>
    </div>
    <div class="mapp" id="mapp14" align="center" onclick="sololearnf()" title="SoloLearn❤">
        <img src="https://1.bp.blogspot.com/-O6iKW1vxmWw/W4zroSP3XMI/AAAAAAAAEp4/9FBtAEDCZN0RFM4NwoPWp4H5FwNjGJ5TgCLcBGAs/s320/sololearn.jpg" width="70" height="70" id="ap14" /><br/>
        <span class="apname" align="center" id="aptxt14">SoloLearn</span>
    </div>
    <div class="mapp" id="mapp15" onclick="stopwatchz()" align="center" title="Stopwatch">
        <img src="https://4.bp.blogspot.com/-SY74N0-5Hfg/W4zsj49I7JI/AAAAAAAAEqQ/xjC6cAdsvSszKHWbU1CfIiMibYMIuNv1wCLcBGAs/s320/stop_watch.jpg" width="70" height="70" id="ap15" /><br/>
        <span id="aptxt15" class="apname" align="center">Stopwatch</span>
    </div>
    <div class="mapp" id="mapp16" onclick="oterminal()" align="center" title="Terminal">
        <img src="https://4.bp.blogspot.com/-CKwuylBjW7M/XDspVA-ECzI/AAAAAAAAJsQ/49EfJ9rbYaIeOnjiSV32tkMXPnA9GlimgCLcBGAs/s1600/PicsArt_01-13-05.48.26.png" width="70" height="70" id="ap16"/><br/>
        <span class="apname" align="center" id="aptxt16">Terminal</span>
    </div>
    <div class="mapp" id="mapp17" onclick="texteditor()" align="center" title="TextEditor">
        <img src="https://2.bp.blogspot.com/-hBduXd8cXJQ/XG7gzHsmC4I/AAAAAAAAKrQ/8nou6nYVDyAAPuz286lNfJs3a47twfhFQCLcBGAs/s1600/PicsArt_02-21-11.10.37.png" width="70" height="70" id="ap17" /><br/>
        <span class="apname" align="center" id="aptxt17">Text Editor</span>
    </div>
    <div class="mapp" id="mapp18" onclick="themesz()" align="center" title="Themes">
        <img src="https://4.bp.blogspot.com/-e0NY_w6XjVs/XG7gyuXwz7I/AAAAAAAAKro/4x_KWgWckV48w9FWtJf5rZyyLR80KBTBwCPcBGAYYCw/s1600/PicsArt_02-21-11.11.05.png" width="70" height="70" id="ap18" /><br/>
        <span class="apname" align="center" id="aptxt18">Themes</span>
    </div>
    <div class="mapp" id="mapp19" onclick="unitconverter()" align="center" title="Unit Converter">
        <img src="https://3.bp.blogspot.com/-MlzUPm72Agw/XG7g1ZVfrWI/AAAAAAAAKr4/hkxUh577rEILNRD3ssQ03GpUUN6V8Q2LwCPcBGAYYCw/s1600/PicsArt_02-21-11.13.30.png" width="70" height="70" id="ap19" /><br/>
        <span class="apname" align="center" id="aptxt19">Unit Converter</span>
    </div>
    <div class="mapp" id="mapp20" onclick="videos()" align="center" title="Videos">
        <img src="https://2.bp.blogspot.com/-T593dY1AZ-w/W3Kpy3jSYWI/AAAAAAAAD0I/AT386V5s080EI9qsiyO_PtXl2bzyC4snACLcBGAs/s200/youtube.jpg" width="70" height="70" id="ap20" /><br/> 
        <span class="apname" align="center" id="aptxt20">Videos</span>
    </div>
</div>




<!--APPS-->
<!--Assistant-->
<div id="botcontent" class="apbtheme">
    <div id="botplayground" class="botplayground">
        <br/>
        <div class='message'>About<hr/><span>1. Informal chat<br/>2. Roll A Die<br/>3. Random Card<br/>4. Flip a coin<br/>5. Clear -> Clear Screen<br/>6. Table( _ Reuires a number)<br/>7. Date, Time<br/>8. Close</span></div>
    </div>
    <div id="banthis" class="banthis">
        <div class="banthisz" align="center">
            <span href="#"><i class="fa fa-ban" style="color:#ff6666"></i> <b>BLOCKED</b> <i class="fa fa-ban" style="color:#ff6666"></i></span><hr style="color:#ddd;" size="4"/>
            <span style="font-color:#fff;font-size:20px;">Run the Code again 😛</span>
        </div>
    </div>
    <div class="backbtnz">
    <button onclick="closebot()" class="closeasstbtn" id="closeasstbtn">Close &times;</button>
    <form onsubmit="return false;" class="botinputform">
        <input type="text" id="uinput" class="textbotmessage" oninput="checkasinp()" placeholder="Type a message" autocomplete="off" autofocus  /><button class="sendbotbutton" id="botmessagesend" disabled="true" onclick="assistantwork()"><i class="fa fa-paper-plane"></i></button>
    </form>
</div>
</div>

<!--Browser-->
<div class="mainhomescr apbtheme" id="browser">
    <div class="inputxzz">
        <h2 class="browselogo">Bing!</h2><br/>
        <form onsubmit="return false">
            <input type="text" class="browinp" id="browinp" autocomplete="off" /><br/><br/>
            <button onclick="searchthis()" class="browsearchbtn">Bing Search</button><br/>&nbsp;
        </form>
    </div>
    <br/>
    <div class="mainscr" id="mainscr">
        <iframe id="ibrowser" width="100%" height="100%"></iframe>
    </div>
    <div class="browserap" id="browbtns">
        <span class="browbbtns" onclick="cbrowser()"><i class="fa fa-times fa-fw"></i></span>
        <span class="browbbtns" onclick="history.back();"><i class="fa fa-arrow-left fa-fw"></i></span>
        <span class="browbbtns" onclick="closeifmbr()"><i class="fa fa-home fa-fw fa-fw"></i></span>
        <span class="browbbtns" onclick="history.forward();"><i class="fa fa-arrow-right"></i></span>
        <span class="browbbtns" id="browinco" onclick="refreshsear()"><i class="fa fa-refresh fa-fw"></i></span>
    </div>
</div>



<!--Calculator-->
<div id="calculator" class="apbtheme">
<input type="text" id="calcinput" placeholder="0" disabled="true" /><br/>
<input type="text" id="calcoutput" placeholder="0" disabled="true" />
<table width="100%" border="0" class="calctable">
    <tr align="center">
        
        <td onclick="addnum('(')" class="calcbut"><span class="calcnum">(</span></td>
        <td onclick="addnum(')')" class="calcbut"><span class="calcnum">)</span></td>
        <td onclick="rvcalc()" class="calcbut"><span class="calcnum"><i class="fa fa-arrow-left"></i></span></td>
        <td onclick="addnum('+')" width="25%" id="calcnum1"><span class="calcnum">+</span></td>
    </tr>
    <tr align="center">
        <td onclick="addnum('7')" width="25%" class="calcbut"><span class="calcnum">7</span></td>
        <td onclick="addnum('8')" width="25%" class="calcbut"><span class="calcnum">8</span></td>
        <td onclick="addnum('9')" width="25%" class="calcbut"><span class="calcnum">9</span></td>
        <td onclick="addnum('-')" id="calcnum2"><span class="calcnum">-</span></td>

    </tr>
    <tr align="center">
        <td onclick="addnum('4')" class="calcbut"><span class="calcnum">4</span></td>
        <td onclick="addnum('5')" class="calcbut"><span class="calcnum">5</span></td>
        <td onclick="addnum('6')" class="calcbut"><span class="calcnum">6</span></td>
        <td onclick="addnum('*')" id="calcnum3"><span class="calcnum">*</span></td>
    </tr>
    <tr align="center">
        <td onclick="addnum('1')" class="calcbut"><span class="calcnum">1</span></td>
        <td onclick="addnum('2')" class="calcbut"><span class="calcnum">2</span></td>
        <td onclick="addnum('3')" class="calcbut"><span class="calcnum">3</span></td>
        <td onclick="addnum('/')" id="calcnum4"><span class="calcnum">/</span></td>
    </tr>
    <tr align="center">
        <td onclick="ravcalc()" ondblclick="ccalc()" class="calcbut"><span class="calcnum">C</span></td>
        <td onclick="addnum('0')"  class="calcbut"><span class="calcnum">0</span></td>
        <td onclick="addnum('.')" class="calcbut"><span class="calcnum">.</span></td>
        <td onclick="outputit()"  class="calcbut" id="calcnum5"><span class="calcnum"><b>=</b></span></td>
    </tr>
</table>
</div>


<!--Calendar-->
<div class="apbtheme" id="cal">
    <br/>
    <div style="padding:5px;height:calc(100vh - 32px);overflow:scroll;"><br/>
        <span align="center" class="calbtns"><button onclick="prevcal()" class="calbtn"><i class="fa fa-angle-left"></i></button></span><b><span align="center" class="calmonths" id="caption"></span></b><span  align="center" class="calbtns"><button onclick="nextcal()" class="calbtn"><i class="fa fa-angle-right"></i></button></span>
        <br/><br/>
        <table width="90%" align="center" border="0" id="caltable" class="caltable"></table>
        <br/><br/>&nbsp;
        <div class="backbtnz" align="center"><button onclick="calhide()" style="justify-content:center" class="closeappbtn">Close &times;</button></div>
    </div>
</div>



<!--
Seems like someone is scrolling here;
-->



<!--Clock-->
<div id="clock" class="apbtheme" align="center">
    <div class="mainclock">
        <br/><br/><br/>
    <div class="clocktime">
        <span id="clockhour"></span> : <span id="clockminute"></span> <span id="clocksecond" class="clocksecond"></span>
    </div>
    <span id="yearnow"></span> <span id="monthnow"></span> <span id="daynow"></span>, <span id="weekday"></span>
    <br/><br/>
    <table border="1" width="80%" style="border-collapse: collapse;">
        <tr align="center">
            <td width="50%">🇺🇸 California <span style="opacity:0.7;">(-8:00)</span></td>
            <td width="50%" id="timezone1"></td>
        </tr>
        <tr align="center">
            <td>🇲🇽 Mexico <span style="opacity:0.7;">(-6:00)</span></td>
            <td id="timezone13"></td>
        </tr>
        <tr align="center">
            <td>🇨🇦 Montreal <span style="opacity:0.7;">(-5:00)</span></td>
            <td id="timezone2"></td>
        </tr>
        <tr align="center">
            <td>🇦🇷 Buenos Aires <span style="opacity:0.7;">(-3:00)</span></td>
            <td id="timezone12"></td>
        </tr>
        <tr align="center">
            <td>🇧🇷 Rio de Janerio <span style="opacity:0.7;">(-2:00)</span></td>
            <td id="timezone8"></td>
        </tr>
        <tr align="center">
            <td>🇬🇧 London <span style="opacity:0.7;">(0:00)</span></td>
            <td id="timezone3"></td>
        </tr>
        <tr align="center">
            <td>🇮🇹 Rome <span style="opacity:0.7;">(+1:00)</span></td>
            <td id="timezone9"></td>
        </tr>
        <tr align="center">
            <td>🇷🇺 Moscow <span style="opacity:0.7;">(+3:00)</span></td>
            <td id="timezone7"></td>
        </tr>
        <tr align="center">
            <td>🇦🇪 Dubai <span style="opacity:0.7;">(+4:00)</span></td>
            <td id="timezone4"></td>
        </tr>
        <tr align="center">
            <td>🇮🇳 New Delhi <span style="opacity:0.7;">(+5:30)</span></td>
            <td id="timezone10"></td>
        </tr>
        <tr align="center">
            <td>🇳🇵 Kathmandu <span style="opacity:0.7;">(+5:45)</span></td>
            <td id="timezone11"></td>
        </tr>
        <tr align="center">
            <td>🇨🇳 Beijing <span style="opacity:0.7;">(+8:00)</span></td>
            <td id="timezone5"></td>
        </tr>
        <tr align="center">
            <td>🇯🇵 Tokyo <span style="opacity:0.7;">(+9:00)</span></td>
            <td id="timezone6"></td>
        </tr>
    </table>
    <br/>&nbsp;
</div>
    <div class="backbtnz" align="center"><button onclick="hideclock()" class="closeappbtn">Close &times;</button></div>
</div>



<!--Developer Mode-->
<div class="apbtheme" id="devmode">
    <br/>
    <div style="height:calc(100vh - 32px);overflow:scroll;" align="center">
        <br/>
        <textarea class="textarearep" id="devappinp" rows="7" placeholder="console.log('Developer Mode -beta');" maxlength="150"></textarea>
        <button class="cldevbtn" onclick="document.getElementById('userwcdev').style.width = '100%';">User Scripts</button>
        <button class="cldevbtn" onclick="document.getElementById('helpdev').style.width = '100%';">Help</button> <button onclick="devfunc()" class="cldevbtn"> RUN <i class="fa fa-caret-right fa-fw"></i></button>
        <br/>&nbsp;
        <div id="devfunc" class="devfunc" align="left">JavaScript error exceptions:<br/></div>
    </div>
    <div class="backbtnz" align="center"><button onclick="cdevmode()" class="closeappbtn">Close &times;</button>
    </div>
</div>
<div class="apbtheme" id="helpdev">
    <br/>
    <div class="userwcdevz">
        <h2 align="center">Help - Developer Mode</h2>
        <h3>Example</h3>
        <ul class="helpdevul">
            <li><code>console.log("Hello World!");</code></li>
            <li><code>alert('Hey');</code></li>
            <li><code>5/2<br/><span style="color:#0b0">//Simple Maths Calculations</span></code></li>
            <li><code>var a = 1<br/>var b = 3;<br/>console.log(a+b);</code></li>
        </ul>
        <h3>In Code</h3>
        <ul class="helpdevul">
            <li><code class="devlcodefun">worldclockshouldwork(hour, minute);<br/><span style="color:#0b0;">//hour & minute in parameter</span></code></li>
            <li><code class="devlcodefun">seticosize('size')<br/><span style="color:#0b0;">//size = small or medium or large</span></code></li>
            <li><code class="devlcodefun">themcolo('#abc');<br/> <span style="color:#0b0;">//write color name instead #abc</span></code></li>
        </ul>
        <h3>Open Apps</h3>
        <ul class="helpdevul">
            <li>Assistant - <code class="devlcodefun">openassistant()</code></li>
            <li>Browser - <code class="devlcodefun">obrowser()</code></li>
            <li>Calculator - <code class="devlcodefun">showcalc()</code></li>
            <li>Calendar - <code class="devlcodefun">cal()</code></li>
            <li>Clock - <code class="devlcodefun">showclock()</code></li>
            <li>Developer - <code class="devlcodefun">odevmode()</code></li>
            <li>Devs - <code class="devlcodefun">showdevs()</code></li>
            <li>E-mail - <code class="devlcodefun">openmaila()</code></li>
            <li>Maps - <code class="devlcodefun">maps()</code></li>
            <li>Music - <code class="devlcodefun">musicplayer()</code></li>
            <li>Phone - <code class="devlcodefun">phone()</code></li>
            <li>Settings - <code class="devlcodefun">settings()</code></li>
            <li>Sololearn - <code class="devlcodefun">sololearnf()</code></li>
            <li>Stopwatch - <code class="devlcodefun">stopwatchz()</code></li>
            <li>Terminal - <code class="devlcodefun">oterminal()</code></li>
            <li>Text Editor - <code class="devlcodefun">texteditor()</code></li>
            <li>Themes - <code class="devlcodefun">themesz()</code></li>
            <li>Unit Converter - <code class="devlcodefun">unitconverter()</code></li>
            <li>Videos - <code class="devlcodefun">videos()</code></li>
        </ul>
    </div>

    <div class="backbtnz" align="center"><button onclick="document.getElementById('helpdev').style.width = '0';" class="closeappbtn">Back <i class="fa fa-mail-reply fa-fw"></i></button></div>
</div>
<div class="apbtheme" id="userwcdev">
    <br/>
    <div class="userwcdevz" id="userwcdevz">
        <h2 align="center">User Scripts</h2><hr/></div>
    <div class="backbtnz" align="center"><button onclick="document.getElementById('userwcdev').style.width = '0';" class="closeappbtn">Back <i class="fa fa-mail-reply fa-fw"></i></button></div>
</div>



<!--Devs-->
<div id="devs" class="apbtheme">
    <br/>
    <div style="height:calc(100vh - 32px);overflow:scroll;">
    <table width="100%" border="0">
        <tr align="center">
            <td width="50%"><span style="float:left; opacity:0.9;border-radius:4px;padding:4px;" id="setbadge2">Devs</span><br/><br/><a href="https://www.sololearn.com/Profile/487380" class="devs"><img src="https://api.sololearn.com/Uploads/Avatars/487380.jpg" width="60px" class="setava" /><br/>Jaydeep Khatri</a></td>
            <td width="50%"><br/><br/><a href="https://www.sololearn.com/Profile/4714357" class="devs"><img src="https://api.sololearn.com/Uploads/Avatars/4714357.jpg" width="60px" class="setava" /><br/>Shudarshan Rai👑</a></td>
        </tr>
        <tr>
            <td><span style="float:left; opacity:0.9;border-radius:4px;padding:4px;" id="setbadge5">Credits</span>
            <br/>
            <ul>
                <li>SoloLearn Q&amp;A Discussions</li>
                <li>W3schools</li>
                <li>StackOverFlow</li>
            </ul>
            </td>
        </tr>
    </table><br/>
</div>
    <div class="backbtnz" align="center"><button onclick="cdevs()" class="closeappbtn">Close &times;</button></div>
</div>



<!--Easter //Meme-->
<div class="banthis" style="z-index: 3; background-color:#111;" id="memeap">
    <div style="height:calc(100vh - 32px); overflow:scroll;" align="center">
        <img id="memewallp" width="80%" height="80%" style="border-radius:0; margin-top:20px; border:2px solid #fff;"/><br/>
        <button onclick="changememe()" class="cldevbtn">Next</button>
    </div>
    <div class="backbtnz" align="center">
        <button class="closeappbtn" onclick="cmeme()">Close &times;</button>
    </div>
</div>
<!-- Memes are taken from Google search (images) result & fb/i am programmar, i have no life (group) -->


<!--Email-->
<div class="apbtheme" id="email">
    <br/>
    <div style="padding:20px;">
        <span id="by">12:50&#32;By Dev's<span id="dev">&#32;<i class="fa fa-user-circle"></i></span></span><br>
        <div class="emailmsg">
            - Hello there, We are few step away from new update.(V2.0)<br/>
            New Update Includes<br/>
            - Photo Editor<br/>
            - Unit Converter<br/>
            - Maps<br/>
            - Developer Mode<br/>
            - Bug fix<br/>
            - Optimized system performance<br/>
            - Leave your suggestions in the comment
        <pre align="right">
                        - Devs
         </pre>
        </div><br/><br/><br/>
        <span id="by">11:05&#32;By Dev's<span id="dev">&#32;<i class="fa fa-user-circle"></i></span></span><br>
        <div class="emailmsg">
            - That was a overwhelming response to the update-1, so we are here with the second update🔥<br/>
            - Thanks to SoloLearn for selecting this code as <a href="https://www.sololearn.com/post/63757/">Code of the Month</a>🙏😍🔥<br/>
            - supports iOS<br/>
            - user color in themes (terminal -&gt; connect)<br/>
            - incognito mode in browser<br/>
            - email reply<br/>
            - Secret Easter Egg, for MeMes💻<br/>
            - Leave your suggestions in the comment
        <pre align="right">
                        - Devs
         </pre>
        </div>
       </div>
        <button onclick="closeemail()" class="closeemailappbtn" id="closeembtn">Close &times;</button><button onclick="replymail()" class="replyemailbtn" id="repmaibtn">Reply <i class="fa fa-mail-reply"></i></button>
</div>
<div class="apbtheme" id="mailreppal">
    <br/><br/>
    <input type="email" class="inputmaad" placeholder="From :" />
    <input type="email" class="inputmaad" placeholder="To :" />
    <input type="email" class="inputmaad" placeholder="Cc/Bcc :" />
    <textarea rows="8" class="textarearep" placeholder="Compose..."></textarea><br/><br/>
    <button onclick="creplymail()" class="closeemailappbtn" id="closeembtnc">Close &times;</button>
    <button class="replyemailbtn" id="repmaibtnc"><i class="fa fa-paperclip"></i> Attach</button>
</div>



<!--Maps-->
<div class="apbtheme mapmainscr" id="map">
    <br/>
    <div class="mapforinp">
        <h2>Maps</h2>
        <form onsubmit="return false;">
            <input type="text" id="mapval" class="videoinputuser" placeholder="City" /><br/>
            <button onclick="mapfin()" class="cldevbtn" style="margin-top:3px;">Search</button>
        </form>
    </div>
    <div class="mainmap" id="mainmap">
        <br/>
        <iframe id="mappp" width="100%" height="100%"></iframe>
    </div>
    <div class="backbtnz" align="center">
        <button onclick="cmaps()" class="closeappbtn" id="closemapbtn">Close &times;</button>
        <button onclick="bmmaps()" class="closeappbtn" id="closemapbtn1" style="display: none">Back <i class="fa fa-mail-reply"></i></button>
    </div>
</div>



<!--Music-->
<div id="musicplayer" class="apbtheme">
    <div class="mainmusicb">
    <div id="dancebars" class="dancebars" align="center">
        <ul class="musicbars">
        <li id="dnd1" class="musicstic"></li>
        <li id="dnd2" class="musicstic"></li>
        <li id="dnd3" class="musicstic"></li>
        <li id="dnd4" class="musicstic"></li>
        <li id="dnd5" class="musicstic"></li>
        <li id="dnd6" class="musicstic"></li>
        <li id="dnd7" class="musicstic"></li>
        <li id="dnd8" class="musicstic"></li>
        <li id="dnd9" class="musicstic"></li>
        <li id="dnd10" class="musicstic"></li>
        </ul>
    </div>
    <div class="namedur">
        <hr/>
        <span class="songname" style="font-size:20px;" align="center" id="titlesong">Name of song</span>
        <span class="songdur" id="ctime" align="center">Duration</span>
        <span class="songrandom" id="songrandom" align="center" onclick="hitrandommusic()">Random</span>
    </div>
    <hr/>
    <div class="seek" align="center"><progress value="" min="0" max="100" id="seekvalue"></progress></div>
    <br/>
    <div style="width:100%">
        <table style="padding:0;">
            <tr>
                <td class="tabmusic"><button class="mbutton" onclick="repeatthis()" id="musicbu1"><i class="fa fa-refresh fa-fw"></i></button></td>
                <td class="tabmusic"><button class="mbutton" onclick="mbackward()" id="musicbu2"><i class="fa fa-backward fa-fw"></i></button></td>
                <td class="tabmusic"><button class="mbutton" onclick="playmusic()" id="playbutton"><i class="fa fa-play fa-fw"></i></button><button class="mbutton" onclick="pausemusic()" id="pausebutton"><i class="fa fa-pause fa-fw"></i></button></td>
                <td class="tabmusic"><button class="mbutton" onclick="mforward()" id="musicbu3"><i class="fa fa-forward fa-fw"></i></button></td>
                <td class="tabmusic"><input type="range" min="0" max="1" value="0.7" step="0.01" class="volumeslider" oninput="volumecontrol(this.value)" /></td>
                <td class="tabmusic"><button onclick="cmusicplayer()" class="closeappbtn">&times;</button></td>
            </tr>
        </table>
    </div>
    <div id="mloading" class="mloading" align="center"><span id="mstatus">&nbsp;</span></div>
    </div>
</div>



<!--Phone-->
<div id="phone" class="apbtheme">
    <input id="inputnumber" type="text" class="inputnumber" maxlength="15" align="center" disabled />
<table width="100%" border="0" class="keymtable">
    <tr align="center">
        <td width="33%" class="phonekeypad" onclick="phonenumin('1')"><span class="keyntable">1</span><br/><span class="keyatable">&alpha;</span></td>
        <td width="33%" class="phonekeypad" onclick="phonenumin('2')"><span class="keyntable">2</span><br/><span class="keyatable">ABC</span></td>
        <td width="33%" class="phonekeypad" onclick="phonenumin('3')"><span class="keyntable">3</span><br/><span class="keyatable">DEF</span></td>
    </tr>
    <tr align="center">
        <td class="phonekeypad" onclick="phonenumin('4')"><span class="keyntable">4</span><br/><span class="keyatable">GHI</span></td>
        <td class="phonekeypad" onclick="phonenumin('5')"><span class="keyntable">5</span><br/><span class="keyatable">JKL</span></td>
        <td class="phonekeypad" onclick="phonenumin('6')"><span class="keyntable">6</span><br/><span class="keyatable">MNO</span></td>
    </tr>
    <tr align="center">
        <td class="phonekeypad" onclick="phonenumin('7')"><span class="keyntable">7</span><br/><span class="keyatable">PQRS</span></td>
        <td class="phonekeypad" onclick="phonenumin('8')"><span class="keyntable">8</span><br/><span class="keyatable">TUV</span></td>
        <td class="phonekeypad" onclick="phonenumin('9')"><span class="keyntable">9</span><br/><span class="keyatable">WXYZ</span></td>
    </tr>
    <tr align="center">
        <td class="phonekeypad" onclick="phonenumin('*')"><span class="keyntable">*</span></td>
        <td class="phonekeypad" onclick="phonenumin('0')"><span class="keyntable">0</span><br/><span class="keyatable">+</span></td>
        <td class="phonekeypad" onclick="phonenumin('#')"><span class="keyntable">#</span></td>
    </tr>
    <tr align="center">
        <td class="phonekeypad" onclick="closephone()"><button class="closeappbtn">Close &times;</button></td>
        <td onclick="phonecallit()"><span class="keyntable"><i class="fa fa-phone phoneico fa-fw"  id="phonecallbtn"></i></span><br/></td>
        <td onclick="clearnum()"><span class="keyntable" ><i class="fa fa-long-arrow-left phoneico fa-fw" id="phonebackbtn"></i></span><br/></td>
    </tr>
</table>
</div>



<!--do you have any specific reasons for roaming in source code-->



<div class="apbtheme" id="photoeditor"><br/>
<div style="height:calc(100vh - 32px); overflow:scroll;">
    <div class="imgHere"><br/>
          <center> <img src="https://picsum.photos/250/250/?random" class="iemimg" id="imagefil" /></center>
        <div class="container">
            <p contenteditable="true" id="name">Edit Image name <span id="blink">✎</span></p>
        </div>
    </div>
    <br/><br/>   
    <div class="styleControl">
    <div class="iedefslidecontainer" id="ieslidecontainer">
        Effects:<input type="range" min="0" max="100" id="inputrange" value="0" class="slider" oninput="mainimgedi(this.value)"/>
    </div>
    <div class="iedefslidecontainer" id="bRadius">
        Border Radius:<input type="range" min="0" max="50" oninput="bradius(this.value);" id="baRadius" value="0" class="slider" />
    </div>
    <div class="iedefslidecontainer" id="ieborder">
        Border:<input type="range" min="0" max="15" id="borderplus" value="0" class="slider" oninput="ieeborder(this.value)" />
    <ul class="ietabs">
        Border color:
        <li class="iebortab ier" onclick="peborder = 'F44336';ieeborder(document.getElementById('borderplus').value);">red</li>
        <li class="iebortab ieg" onclick="peborder = '4CAF50';ieeborder(document.getElementById('borderplus').value);">green</li>
        <li class="iebortab ieb" onclick="peborder = '0f97f9';ieeborder(document.getElementById('borderplus').value);">blue</li>
        <li class="iebortab iey" onclick="peborder = 'FF9800';ieeborder(document.getElementById('borderplus').value);">yellow</li>
    </ul>
    <ul class="ietabs">
        Border style:
        <li class="ieborstab solid" onclick="peborderstyle = 'solid';ieeborder(document.getElementById('borderplus').value);">Solid</li>
        <li class="ieborstab dot" onclick="peborderstyle = 'dotted';ieeborder(document.getElementById('borderplus').value);">Dooted</li>
        <li class="ieborstab dash" onclick="peborderstyle = 'dashed';ieeborder(document.getElementById('borderplus').value);">Dashed</li>
        <li class="ieborstab double" onclick="peborderstyle = 'double';ieeborder(document.getElementById('borderplus').value);">Double</li>
        <li class="ieborstab inset" onclick="peborderstyle = 'inset';ieeborder(document.getElementById('borderplus').value);">Inset</li>
    </ul>
    </div>
    <div class="iedefslidecontainer" id="ierotate">
        Rotate:<input type="range" min="0" max="180" id="imgrotate" oninput="ieroate(this.value);" value="0" class="slider" />
    </div><br/>
    <select oninput="changefil(this.value)" id="iebtn0" class="iebtns" onclick="ieimeff()">
        <option selected disabled>Effects</option>
        <option>Grayscale</option>
        <option>Sepia</option>
        <option>Saturate</option>
        <option>Hue rotate</option>
        <option>Invert</option>
        <option>Opacity</option>
        <option>Brightness</option>
        <option>Contrast</option>
        <option>Blur</option>
    </select>
    <button class="cldevbtn" id="iebtn1" onclick="borradcli()">Border Radius</button>
    <button class="cldevbtn" id="iebtn2" onclick="boriecli()">Border</button>
    <button class="cldevbtn" id="iebtn3" onclick="borroti()">Rotate</button>
    <button class="cldevbtn" id="iebtn4" onclick="iechagim()">Change Image</button>
    <button class="cldevbtn" id="iebtn5" onclick="reset()">Reset</button><br/><br/>
    <div class="iewrapper">
        <div class="iegrid">Grayscale - <span id="iefiltex1"></span></div>
        <div class="iegrid">Sepia - <span id="iefiltex2"></span></div>
        <div class="iegrid">Saturate - <span id="iefiltex3"></span></div>
        <div class="iegrid">Hue Rotate - <span id="iefiltex4"></span></div>
        <div class="iegrid">Invert - <span id="iefiltex5"></span></div>
        <div class="iegrid">Opacity - <span id="iefiltex6"></span></div>
        <div class="iegrid">Brightness - <span id="iefiltex7"></span></div>
        <div class="iegrid">Contrast - <span id="iefiltex8"></span></div>
        <div class="iegrid">Blur - <span id="iefiltex9"></span></div>
    </div><br/><br/>
    </div>
</div>
<div class="backbtnz" align="center"><button class="closeappbtn" onclick="cphotoeditor()">Close &times;</button></div>
</div>



<!--Settings-->
<div id="settings" class="apbtheme">
    <br/><br/>
    <span style=" opacity:0.9;border-radius:4px;padding:4px;" id="setbadge1">Icon - Size</span><br/><br/>  
    <table border="0" width="80%" align="center" style="border-collapse:collapse; box-shadow:0 0 2px #000;">
        <tr align="center">
            <td class="seticosiz" width="33%" id="seticobtn1" onclick="seticosize('small')">Small</td>
            <td class="seticosiz" width="34%" id="seticobtn2" onclick="seticosize('medium')">Medium</td>
            <td class="seticosiz" width="33%" id="seticobtn3" onclick="seticosize('large')">Large</td>
        </tr>
    </table><hr/><br/>
    <div align="center">
        <span style=" opacity:0.9;border-radius:4px;padding:4px;" id="setbadge4">Power</span> ------>
        <button onclick="mobileoff()" class="powerbutton">Power Off!</button>
    </div>
    <br/>
    <div class="backbtnz" align="center"><button onclick="closesettings()" class="closeappbtn">Close &times;</button></div>
</div>



<!--Sololearn-->
<div id="sololearn" class="apbtheme">
    <iframe src="https://www.sololearn.com" class="ifsololearn">Your Browser does not support iframes</iframe>
    <div class="backbtnz" align="center"><button onclick="csololearnf()" class="closeappbtn">Close &times;</button></div>
</div>



<!--beware, you are in watch...
    also a kind request, don't scroll in the source code
-->



<!--Stopwatch-->
<div id="stopwatch" class="apbtheme">
    <br/>
    <div style="font-size:40px; height:calc(100vh - 32px);overflow:scroll;" align="center">
        <br/>&nbsp;
        <span id="stophour">00</span> : <span id="stopminute">00</span> : <span id="stopsecond">00</span> <span style="font-size:20px;" id="stopmsecond">00</span>
        <br/>
        <button class="cldevbtn" id="swstart" onclick="clockinterval = setInterval(countstopwatch, 10); this.disabled=true;">Start</button>
        <button class="cldevbtn" onclick="clearInterval(clockinterval); document.getElementById('swstart').disabled = false;" >Pause</button>
        <button class="cldevbtn" onclick="swlap()">Lap</button>
        <button class="cldevbtn" onclick="resetsw()">Reset</button>
        <br/>&nbsp;
        <table style="border-collapse:collapse; font-size:16px;" border="1" width="90%" align="center" id="tabforlap"></table>
        <br/>
    </div>
    <div class="backbtnz" align="center"><button class="closeappbtn" onclick="closestopwatch()">Close &times;</button></div>
 </div>



<!--Terminal-->
<div class="apbtheme" style="background-color:#000;" id="materminal">
    <div id="mterminal" style="height:calc(100vh - 34px); overflow:scroll;" class="terminal">
        <br/>Hello World!<br/>Type in 'help'
    </div>
    <button onclick="closeterminal()" class="closetermbtn" id="closetermbtn">Close &times;</button>
    <form onsubmit="return false">
        <input type="text" class="terminaltext" id="terminalinput" autofocus="on" autocomplete="off" />
        <button onclick="workterminal()" class="sendtermmsg" id="sendtermmsg"><i class="fa fa-angle-right"></i>_</button>
    </form>
</div>



<!--TextEditor-->
<div id="texteditor" class="apbtheme" style="border-bottom:1px solid #ddd;">
    <button onclick="showtebar()" id="teshowbtn" class="texteditbutton" style="padding:8px; position:fixed; bottom:0; right:0; display:none;">Show tab</button><br/>
    <div style="padding:10px; height:75%; overflow:scroll;" contenteditable="true" id="texteditorcontent">Hello World!</div><br/>
    <div style="position:fixed; z-index:2; bottom:0;padding:10px; width:95%; background-color:#a0a0a0;" id="tetab">
        <button onclick="boldthis()" class="texteditbutton" id="textedit1"><i class="fa fa-bold fa-fw"></i></button>
        <button onclick="italicthis()" class="texteditbutton" id="textedit2"><i class="fa fa-italic fa-fw"></i></button>
        <button onclick="underlinethis()" class="texteditbutton" id="textedit3"><i class="fa fa-underline fa-fw"></i></button>
        <button onclick="alignthis('left')" class="texteditbutton" id="textedit4"><i class="fa fa-align-left fa-fw"></i></button>
        <button onclick="alignthis('center')" class="texteditbutton" id="textedit5"><i class="fa fa-align-center fa-fw"></i></button>
        <button onclick="alignthis('right')" class="texteditbutton" id="textedit6"><i class="fa fa-align-right fa-fw"></i></button>
        <button onclick="alignthis('justify')" class="texteditbutton" id="textedit7"><i class="fa fa-align-justify fa-fw"></i></button>
        <button onclick="shadowthis()" class="texteditbutton" id="textedit8">Shadow</button>
        <button class="texteditbutton"><i class="fa fa-text-height fa-fw"></i></button>
        <input type="range" min="12" max="50" class="volumeslider" id="fontsize" oninput="fontsizethis(this.value)" value="16" />
        <select id="tefont" style="font-size:18px" onchange="tefont()">
            <option class="tebarlow">Barlow</option>
            <option class="tebaloobhaijaan">Baloo Bhaijaan</option>
            <option class="tecaveat">Caveat</option>
            <option class="teindieflower">Indie Flower</option>
            <option class="temonoton">Monoton</option>
            <option class="tepattaya">Pattaya</option>
            <option class="tesatisfy">Satisfy</option>
            <option class="teshadowsintolight">Shadows into Light</option>
            <option class="tespicyrice">Spicy Rice</option>
        </select>
        <input type="color" id="tecolpal" onchange="techangecol()" />
        <button onclick="document.getElementById('texteditorcontent').innerHTML = '';" class="texteditbutton">Clear</button>
        <button onclick="hidetebar()" class="texteditbutton">Hide tab</button> &nbsp;<button class="closeappbtn"  onclick="ctexteditor()">Close &times;</button> &nbsp;
    </div>
</div>



<!--Themes-->
<div id="themesz" class="apbtheme" align="center">
    <br/><br/>
    <span style="float:left; opacity:0.9;border-radius:4px;padding:4px;" id="setbadge3">Select a Theme</span><br/><br/>
    <div onclick="themcolo('ff691f');navigator.vibrate(50);" class="themcolo themcolo1">&nbsp;</div>
    <div onclick="themcolo('fab81e');navigator.vibrate(50);" class="themcolo themcolo2">&nbsp;</div>
    <div onclick="themcolo('7fdbb6');navigator.vibrate(50);" class="themcolo themcolo3">&nbsp;</div>
    <div onclick="themcolo('19cf86');navigator.vibrate(50);" class="themcolo themcolo4">&nbsp;</div>
    <div onclick="themcolo('91d2fa');navigator.vibrate(50);" class="themcolo themcolo5">&nbsp;</div>
    <div onclick="themcolo('1b95e0');navigator.vibrate(50);" class="themcolo themcolo6">&nbsp;</div>
    <div onclick="themcolo('abb8c2');navigator.vibrate(50);" class="themcolo themcolo7">&nbsp;</div>
    <div onclick="themcolo('e81c4f');navigator.vibrate(50);" class="themcolo themcolo8">&nbsp;</div>
    <div onclick="themcolo('f58ea8');navigator.vibrate(50);" class="themcolo themcolo9">&nbsp;</div>
    <div onclick="themcolo('981ceb');navigator.vibrate(50);" class="themcolo themcolo10">&nbsp;</div><br/><br/>
    <div id="themedef" style="display: none;">
        <span style="float:left; opacity:0.9;border-radius:4px;padding:4px;" id="setbadge6">Define</span><br/><br/>
        <input type="color" id="inpcol" onchange="themcolo((this.value).substring(1))" />
    </div>
    <div class="backbtnz" align="center"><button onclick="cthemes()" class="closeappbtn" id="clbtn">Close &times;</button></div>
</div>



<!--Unit Converter-->
<div class="apbtheme" id="unitconveter">
    <br/>
    <div class="unitccon" align="center">
        <br/>
        <div class="unitconlist" onclick="document.getElementById('uclength').style.width='100%'"><i class="fa fa-arrows-v fa-fw"></i> Length</div>
        <div class="unitconlist" onclick="document.getElementById('ucweight').style.width='100%'"><i class="fa fa-thermometer fa-fw"></i> Temperature</div>
        <div class="unitconlist" onclick="document.getElementById('ucbinary').style.width='100%';"><i class="fa fa-file-code-o fa-fw"></i> ASCII Converter</div>
    </div>
    <div class="backbtnz" align="center"><button onclick="cunitconverter()" class="closeappbtn" id="clbtn">Close &times;</button></div>
</div>
<div class="apbtheme" id="uclength">
    <div class="unitccon">
    <br/><br/>
    <h2 align="center">Length <i class="fa fa-arrows-v fa-fw"></i></h2>
Centimeter
    <input type="number" class="inputmaad" id="inpcentimeter" oninput="uccentimeter(this.value)"/><br/>
    Meter
    <input type="number" class="inputmaad" id="inpmeter"  oninput="ucmeter(this.value)" /><br/>
    Kilometer
    <input type="number" class="inputmaad" id="inpkilometer" oninput="uckilometer(this.value)" /><br/>
    Inch
    <input type="number" class="inputmaad" id="inpinch" oninput="ucinch(this.value)" /><br/>
    Foot
    <input type="number" class="inputmaad" id="inpfoot" oninput="ucfoot(this.value)" /><br/>
    Yard
    <input type="number" class="inputmaad" id="inpyard" oninput="ucyard(this.value)" /><br/>
    Mile
    <input type="number" class="inputmaad" id="inpmile" oninput="ucmile(this.value)" /><br/>&nbsp;
</div>
    <div class="backbtnz" align="center"><button onclick="document.getElementById('uclength').style.width = '0';" class="closeappbtn">Back <i class="fa fa-arrow-left"></i></button></div>
</div>
<!--Temperature-->
<div class="apbtheme" id="ucweight">
    <div class="unitccon">
    <br/><br/>
    <h2 align="center">Temperature <i class="fa fa-thermometer fa-fw"></i></h2>
Fahrenheit
<input type="number" class="inputmaad" id="ufahrenheit" oninput="ucfahrenheit(this.value)" /><br/>
Celsuis
<input type="number" class="inputmaad" id="ucelsius" oninput="uccelsius(this.value)" /><br/>
Kelvin
<input type="number" class="inputmaad" id="ukelvin" oninput="uckelvin(this.value)" />
</div>
<div class="backbtnz" align="center"><button onclick="document.getElementById('ucweight').style.width = '0';" class="closeappbtn">Back <i class="fa fa-arrow-left"></i></button></div>
</div>
<!--Binary Converter -->
<div class="apbtheme" id="ucbinary">
    <div class="unitccon">
<br/><br/>
<h2 align="center">ASCII Converter <i class="fa fa-file-code-o fa-fw"></i></h2>
Text
<textarea class="textarearep" id="binctext" rows="6" oninput="convtetb(this.value);" onchange="convtetb(this.value);" row="5"></textarea><br/><br/>
ASCII
<textarea class="textarearep" id="bincbin" rows="6" disabled></textarea><br/>&nbsp;
</div>
<div class="backbtnz" align="center"><button onclick="document.getElementById('ucbinary').style.width = '0';" class="closeappbtn">Back <i class="fa fa-arrow-left"></i></button></div>
</div>



<!--Video-->
<div id="vidplayer" class="apbtheme"><br/><br/>
<center><iframe  id="youtubeid" class="vidiframe" allowfullscreen="allowfullscreen" mozallowfullscreen="mozallowfullscreen" msallowfullscreen="msallowfullscreen" oallowfullscreen="oallowfullscreen" webkitallowfullscreen="webkitallowfullscreen"></iframe></center><br/>
<center><button onclick="playytv(0); this.style.display='none';" id="videoplbtn" class="cldevbtn">Play</button> <button onclick="prevvid()" class="cldevbtn">Prev</button> <button onclick="nextvid()" class="cldevbtn">Next</button> <button class="closeappbtn" onclick="cvideos()">Close &times;</button><br/>
<input type="text" class="videoinputuser" id="videouserinput" placeholder="Enter YouTube video link" /> <button onclick="adduservideo()" class="cldevbtn" style="margin-top:3px;">ADD +</button></center>
<h3 id="videoexp"></h3>
<div class="videolist" id="videolistj">
    <div class="videoitem" id="videoitem0" onclick="playytv(0)">SoloLearn Introduction</div>
    <div class="videoitem" id="videoitem1" onclick="playytv(1)">SoloLearn: Anything Coding</div>
    <div class="videoitem" id="videoitem2" onclick="playytv(2)">Ping Pong Trick Shots</div>
    <div class="videoitem" id="videoitem3" onclick="playytv(3)">The art of writing software</div>
    <div class="videoitem" id="videoitem4" onclick="playytv(4)">GOOD STUDENTS vs BAD STUDENTS</div>
    <div class="videoitem" id="videoitem5" onclick="playytv(5)">Titu Talks- Episode 1</div>
    <div class="videoitem" id="videoitem6" onclick="playytv(6)">Types Of Fake People</div>
    <div class="videoitem" id="videoitem7" onclick="playytv(7)">250,000 Dominoes</div>
    <div class="videoitem" id="videoitem8" onclick="playytv(8)">A Robot shoots, when get hit in Fortnite</div>
    <div class="videoitem" id="videoitem9" onclick="playytv(9)">Tom & Jerry</div>
    <div class="videoitem" id="videoitem10" onclick="playytv(10)">Charlie Chaplin - The Dentist</div>
    <div class="videoitem" id="videoitem11" onclick="playytv(11)">How to Learn to Code</div>
    <div class="videoitem" id="videoitem12" onclick="playytv(12)">Coding is not difficult</div>
    <div class="videoitem" id="videoitem13" onclick="playytv(13)">Apna Mahi Ayega</div>
</div>
</div>
<script>
var mainloadingz = setInterval(bodyonloadingz, 1000);
var baticon = document.getElementById('batt');
var wifiicon = 0;
//Supports 🍎;
//will not work in Internet Explorer, intentionally
var devplatform = !!navigator.platform && /iPad|iPhone|iPod|MacIntel|MacPPC|Mac68K/.test(navigator.platform);
if(devplatform == true){
    devzplatform = 'ios';
}
else{
    devzplatform = 'idkwhatever';
}
function androidmobbat(){
    navigator.getBattery().then(function (battery) {
        var  level = battery.level;
        levelz= level*100;
        level = Math.round(levelz);
        if(level > 0 && level <= 10){
            baticon.innerHTML = level + "% <i class='fa fa-battery-0'></i>"
        }
        else if(level>=11 && level <= 25){
            baticon.innerHTML = level + "% <i class='fa fa-battery-1'></i>";
        }
        else if(level>=26 && level <= 50){
            baticon.innerHTML = level + "% <i class='fa fa-battery-2'></i>";
        }
        else if(level>=51 && level <= 75){
            baticon.innerHTML = level + "% <i class='fa fa-battery-3'></i>";
        }
        else{
            baticon.innerHTML = level + "% <i class='fa fa-battery-4'></i>";
        }
    });
    return;
}
function bodyonloadingz(){
    if(devzplatform == 'ios'){
        baticon.innerHTML = "100% <i class='fa fa-battery-4'></i>";
    }
    else{
        androidmobbat();
    }
    var time=document.getElementById('times');
    var date = new Date();
    var hour = date.getHours();
    var minutes = date.getMinutes();
    var seconds = date.getSeconds();
    if(minutes>=0 && minutes <=9){
        minutes = "0"+minutes;
    }
    if(hour>=0 && hour <=9){
        hour = "0"+hour;
    }
    if(seconds>=0 && seconds<=9){
        seconds = "0"+seconds;
    }
    time.innerHTML=hour +":"+minutes+"&nbsp;";
    document.getElementById('clockhour').innerHTML = hour;
    document.getElementById('clockminute').innerHTML = minutes;
    document.getElementById('clocksecond').innerHTML = seconds;
    var weekdayz = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
    var weekday = weekdayz[date.getDay()];
    document.getElementById("weekday").innerHTML = weekday;
    document.getElementById("yearnow").innerHTML = date.getFullYear();
    var monthz = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];
    var month = monthz[date.getMonth()];
    document.getElementById("monthnow").innerHTML = month;
    document.getElementById("daynow").innerHTML = date.getDate();
    if(navigator.onLine == true){
        if(wifiicon%2 == 0){ document.getElementById('wifiico').style.color = "#333";}
        else{ document.getElementById('wifiico').style.color = "#0b0";}
        document.getElementById('wifiico').innerHTML = "<i class='fa fa-wifi' class='wifiico'></i>";
        wifiicon++;
    }
    else{
        document.getElementById('wifiico').innerHTML = "<i class='fa fa-warning' class='wifiico'></i>";
        if(wifiicon%2 == 0){ document.getElementById('wifiico').style.color = "#333";}
        else{ document.getElementById('wifiico').style.color = "#ff0066";}
        wifiicon++;
    }
    document.getElementById('timezone1').innerHTML = worldclockshouldwork(-8, 0);
    document.getElementById('timezone2').innerHTML = worldclockshouldwork(-5, 0);
    document.getElementById('timezone3').innerHTML = worldclockshouldwork(0, 0);
    document.getElementById('timezone4').innerHTML = worldclockshouldwork(4, 0);
    document.getElementById('timezone5').innerHTML = worldclockshouldwork(8, 0);
    document.getElementById('timezone6').innerHTML = worldclockshouldwork(9, 0);
    document.getElementById('timezone7').innerHTML = worldclockshouldwork(3, 0);
    document.getElementById('timezone8').innerHTML = worldclockshouldwork(-2, 0);
    document.getElementById('timezone9').innerHTML = worldclockshouldwork(1, 0);
    document.getElementById('timezone10').innerHTML = worldclockshouldwork(5, 30);
    document.getElementById('timezone11').innerHTML = worldclockshouldwork(5, 45);
    document.getElementById('timezone12').innerHTML = worldclockshouldwork(-3, 0);
    document.getElementById('timezone13').innerHTML = worldclockshouldwork(-6, 0);
}

function openassistant(){
    document.getElementById('botcontent').style.width = "100%";
    var scrollelement = document.getElementById('botplayground');
    scrollelement.scrollTop = scrollelement.scrollHeight;
}
function checkasinp(){
    if(document.getElementById('uinput').length == 0)
        document.getElementById('botmessagesend').disabled = true;
    else
        document.getElementById('botmessagesend').disabled = false;
}
function assistantwork(){
    var inputz = document.getElementById('uinput').value;
    var input = inputz.toLowerCase();
    if(input == "")
        input = " ";

    document.getElementById('uinput').value = "";
    var hey =["hello","hi", "hey","hey there", "hi dude", "hii", "hiii"];
    var heyrep = ["fine", "i'm fine", "i am fine", "great", "awesome", "good"];
    var thank = ["thanks","thank you"];
    var gmwish = ["gm", "good morning"];
    var gnwish = ["gn", "good night"];
    var yups =["lol","yes","yups","yeah", "nice"];
    var nope = ["no", "nope"];
    var fac = ["flip a coin", "fac", "f a c"];
    var rad = ["roll a die", "rad", "r a d"];
    var rc = ["random card", "rc", "r c"];
    var asdate = ["date", "what is date", "what is date?"];
    var astime = ["time", "what is time", "what is time?"];
    var wru=["who r u?","w r u??", "who are you?", "wru?","wru", "who r u","w r u", "who are you","what is your name?","what is your name?"];
    var ok=["hmm","hmmm","hmmmm","okay","kk","okk","ok","yeah"];
    var about= ["what can you do?", "what do you do", "about"];
    var asopenap = ["open", "openapp", "open app"];
    var plsong = ["play song", "play a song", "play music", "play a music"];
    var abuse = ["mc", "bc", "fuck", "fuck you",  "bitch", "shit", "shut up"];
    var clear = ["clear"];
    var jd = ["jd", "jaydeep"];
    var king = ["king", "shudarshan"];
    var blkmsg = [" ", "  "];
    var closethis = ["close"];
    (hey.indexOf(input) > -1)?botoutput = "Hello, how are you? 😊":
    (heyrep.indexOf(input) > -1)?botoutput = "Nice to hear it!":
    (thank.indexOf(input) > -1)?botoutput = "You're Welcome! 😇":
    (gmwish.indexOf(input) > -1)?botoutput = "Good Morning! 😇":
    (gnwish.indexOf(input) > -1)?botoutput = "Good Night! 😪":
    (yups.indexOf(input) > -1)?botoutput = "Okay 👍":
    (nope.indexOf(input) > -1)?botoutput = "Ok":
    (fac.indexOf(input)> -1)?botoutput = flipacoin():
    (rad.indexOf(input)> -1)?botoutput = rolladie():
    (rc.indexOf(input)> -1)?botoutput = randomcard():
    (asdate.indexOf(input)> -1)?botoutput = showdate():
    (astime.indexOf(input)> -1)?botoutput = showtime():
    (abuse.indexOf(input)> -1)?(botoutput = banthis(inputz), closebot()):
    (wru.indexOf(input)> -1)?botoutput = "I don't know, maybe a bot or something! 😁":
    (ok.indexOf(input)> -1)?botoutput = "hmm 🙃":
    (about.indexOf(input)> -1)?botoutput = aboutmsg():
    (blkmsg.indexOf(input)> -1)?botoutput = "Blank Message🙄":
    (asopenap.indexOf(input)> -1)?botoutput = asopenapp():
    (plsong.indexOf(input) > -1)?botoutput = asplaysong():
    (jd.indexOf(input) > -1)?(botoutput = "Jaydeep's SoloLearn Profile", window.location.href = "https://www.sololearn.com/Profile/487380"):
    (king.indexOf(input) > -1)?(botoutput = "Shudarshan's SoloLearn Profile", window.location.href = "https://www.sololearn.com/Profile/4714357"):
    (clear.indexOf(input)> -1)?(botoutput="Done",setTimeout(clearbotscreen, 250)):
    (closethis.indexOf(input)> -1)?(botoutput = "closed!", closebot()):
    input.substring(0, 6)=="table "?(inputzz = input.slice(6), botoutput = inputzz+" * 1 = "+(inputzz*1)+"<br/>"+inputzz+" * 2 = "+(inputzz*2)+"<br/>"+inputzz+" * 3 = "+(inputzz * 3)+"<br/>"+inputzz+" * 4 = "+(inputzz * 4)+"<br/>"+inputzz+" * 5 = "+(inputzz * 5)+"<br/>"+inputzz+" * 6 = "+(inputzz * 6)+"<br/>"+inputzz+" * 7 = "+(inputzz * 7)+"<br/>"+inputzz+" * 8 = "+(inputzz * 8)+"<br/>"+inputzz+" * 9 = "+(inputzz * 9)+"<br/>"+inputzz+" * 10 = "+(inputzz * 10)):
    input.substring(0,3)=="rep"?(inputzz=input.slice(3), botoutput = inputzz):
    input.substring(0,7)=="are you"?(inputzz=input.slice(8), botoutput=aareyou()):
    input.substring(0,7)=="you are"?(inputzz=input.slice(8), botoutput=ayouare()):
    input.substring(0,5)=="was i"?(inputzz=input.slice(6), botoutput=awasi()):
    input.substring(0,5)=="i was"?(inputzz=input.slice(6), botoutput=aiwas()):
    input.substring(0,4)=="i am"?(inputzz=input.slice(5), botoutput=aiam()):
    input.substring(0,9)=="i can not"?(inputzz=input.slice(10), botoutput=aicannot()):
    input.substring(0,8)=="i do not"?(inputzz=input.slice(9), botoutput=aidonot()):
    input.substring(0,6)=="i feel"?(inputzz=input.slice(7), botoutput=aifeel()):
    input.substring(0,6)=="no one"?(inputzz=input.slice(6), botoutput=anoone()):
    input.substring(0,7)=="can you"?(inputzz=input.slice(8), botoutput=acanyou()):
    input.substring(0,4)=="am i"?(inputzz=input.slice(5), botoutput=aami()):

    botoutput =  inputdidntmatch();
    document.getElementById('botplayground').innerHTML += "<div class='message user'>"+inputz+"</div>";
    document.getElementById('uinput').focus();
    setTimeout(replybotmessage, 250);
    var scrollelement = document.getElementById('botplayground');
    scrollelement.scrollTop = scrollelement.scrollHeight;
}
//no voice for bot, as SpeechSynthesisUtterance is not supported in Mobile devices.
function replybotmessage(){
    document.getElementById('botplayground').innerHTML += "<div class='message' style='background-color:#"+themecolorname+"'>"+botoutput+"</div>";
    document.getElementById('botmessagesend').disabled = true;
    var scrollelement = document.getElementById('botplayground');
    scrollelement.scrollTop = scrollelement.scrollHeight;
}
function flipacoin(){
    var flipacoina = ["Heads", "Tails"];
    var flipacoinb = flipacoina[Math.floor(Math.random() * flipacoina.length)];
    return flipacoinb;
}
function rolladie(){
    var rolladiez = ["1", "2", "3", "4", "5", "6"];
    var rolladie = rolladiez[Math.floor(Math.random() * rolladiez.length)];
    return rolladie;
}
function randomcard(){
    var cardco = ["Spades", "Hearts", "Diamonds", "Clubs"];
    var randomcarda = ["2", "3", "4", "5", "6", "7", "8", "9", "10", "Jack", "Queen", "King", "Ace"];
    var cardnum = cardco[Math.floor(Math.random() * cardco.length)];
    var cardnuma = randomcarda[Math.floor(Math.random() * randomcarda.length)];
    var cardans = cardnuma+ " of "+cardnum;
    return cardans;
}
function asplaysong(){
    if(navigator.onLine == true){
        closebot();
        musicplayer();
        hitrandommusic();
        return "Playing 🎵"
    }
    else{
        return "please check your connectivity";
    }
}
function inputdidntmatch(){
    var inputio = ["I am not sure, I understand you fully", "Please go on", "That is interesting. Please continue", "Tell me more about that", "Does talking about this bother you?", "I see"];
    var inputioa = inputio[Math.floor(Math.random() * inputio.length)];
    return inputioa;
}
function clearbotscreen(){
    document.getElementById('botplayground').innerHTML = "<br/>";
    return true;
}
function showdate(){
    var date = new Date();
    var weekdayz = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
    var weekday = weekdayz[date.getDay()];
    var monthz = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];
    var month = monthz[date.getMonth()];
    var year = date.getFullYear();
    var day = date.getDate();
    var statement = year+" "+month+" "+day+", "+weekday;
    return statement;
}
function showtime(){
    var date = new Date();
    var hour = date.getHours();
    var minutes = date.getMinutes();
    if(hour>=0 && hour <= 9){
        hour = "0"+hour;
    }
    if(minutes>=0 && minutes <= 9){
        minutes = "0"+minutes;
    }    
    var statement = hour+" : "+minutes;
    return statement;
}
function asopenapp(){
    var myapps = ["Assistant", "Browser", "Calculator", "Calendar", "Clock", "Developer", "Devs", "E-mail", "Maps", "Music", "Phone", "Photo Editor", "Settings", "Sololearn", "Stopwatch", "Terminal", "Text Editor", "Themes", "Unit Converter", "Videos"];
    var apptbopen = prompt("Enter the name of app, CaseSensitive", myapps[Math.floor(Math.random() * myapps.length)]);
    if(myapps.indexOf(apptbopen) > -1){
        closebot();
        switch(apptbopen){
            case myapps[0]:
                openassistant();
                break;
            case myapps[1]:
                obrowser()
                break;
            case myapps[2]:
                showcalc();
                break;
            case myapps[3]:
                cal();
                break;
            case myapps[4]:
                showclock();
                break;
            case myapps[5]:
                odevmode()
                break;
            case myapps[6]:
                showdevs();
                break;
            case myapps[7]:
                openmaila()
                break;
            case myapps[8]:
                maps()
                break;
            case myapps[9]:
                musicplayer();
                break;
            case myapps[10]:
                phone()
                break;
            case myapps[11]:
                ophotoeditor();
                break;
            case myapps[12]:
                settings();
                break;
            case myapps[13]:
                sololearnf();
                break;
            case myapps[14]:
                stopwatchz();
                break;
            case myapps[15]:
                oterminal();
                break;
            case myapps[16]:
                texteditor();
                break;
            case myapps[17]:
                themesz();
                break;
            case myapps[18]:
                unitconverter()
                break;
            case myapps[19]:
                videos();
                break;
            default:
                alert("Something went wrong...");
                break;
        } 
         return "Here you go, "+apptbopen+"!";
    }
    else{
        var retrnsen = "";
        for(app =0; app<myapps.length; app++){
            retrnsen +="<br/>- "+myapps[app];
        }
        retrnsen +="<br/>&gt; It is Case Sensitive";
        return retrnsen;
    }
}


//Replies Credits : https://www.rivescript.com/try
//RiveScript-JS version 2.0.0-beta.1 - rs-standard.rive
function aami(){
    var amia = ["Do you believe you are "+inputzz+"?", "Would you want to be "+inputzz+"?", "Do you wish I would tell you are "+inputzz+"?", "What would it mean if your were "+inputzz];
    var amiaa = amia[Math.floor(Math.random() * amia.length)];
    return amiaa;
}
function aareyou(){
    var areyoua = ["Are you interested in whether i am "+inputzz+" or not", "Would it matter to you", "Would you prefer if I weren't "+inputzz+"?", "Perhaps I am "+inputzz+" in your fantasies", "Do you sometimes think I am "+inputzz+"?", "What if I were "+inputzz+"?"];
    var areyouaa = areyoua[Math.floor(Math.random() * areyoua.length)];
    return areyouaa;
}
function ayouare(){
    var youarea = ["What makes you think I am "+inputzz+"?", "Does it please you to believe I am "+inputzz+"?", "Do you sometimes wish you were "+inputzz+"?", "Perhaps you would like to be "+inputzz+"."];
    var youareaa = youarea[Math.floor(Math.random() * youarea.length)];
    return youareaa;
}
function awasi(){
    var wasia = ["What if you were "+inputzz+"?", "Do you think you were "+inputzz+"?", "Were you "+inputzz+"?", "What would it mean if you were "+inputzz+"?", "What does "+inputzz+" suggest to you?"];
    var wasiaa = wasia[Math.floor(Math.random() * wasia.length)];
    return wasiaa;
}
function aiwas(){
    var iwasa = ["Were you really?", "Why do you tell me you were "+inputzz+" now?", "Perhaps I already know you were "+inputzz+"."]; 
    var iwasaa = iwasa[Math.floor(Math.random() * iwasa.length)];
    return iwasaa;
}
function aiam(){
    var iama = ["Is it because you are "+inputzz+" that you came to me?", "How long you have been "+inputzz+"?", "Do you believe it is normal to be "+inputzz+"?", "Do you enjoy being "+inputzz+"?", "Do you know anyone else who is "+inputzz+"?"];
    var iamaa = iama[Math.floor(Math.random() * iama.length)];
    return iamaa;
}
function aicannot(){
    var icannota = ["How do you know that you can&quot;t "+inputzz+"?", "Have you tried?", "Perhaps you could "+inputzz+" now", "Do you really want to be able to "+inputzz+"?", "What if I could "+inputzz+"?"];
    var icannotaa = icannota[Math.floor(Math.random() * icannota.length)];
    return icannotaa;
}
function aidonot(){
    var idonota = ["Do you really "+inputzz+"?", "Why dont you "+inputzz+"?", "Do you wish to be able to "+inputzz+"?", "Does that trouble you?"];
    var idonotaa = idonota[Math.floor(Math.random() * idonota.length)];
    return idonotaa;
}
function anoone(){
    var noonea = ["Are you sure no one "+inputzz+"?", "Surely someone "+inputzz+".", "Can you think of anyone at all?", "Are you thinking of a very special person", "who, may I ask?", "You have a particular person in mind, dont you?", "Who do you think you are talking about?"];
    var nooneaa = noonea[Math.floor(Math.random() * noonea.length)];
    return nooneaa;
}
function acanyou(){
    var canyoua = ["You believe I can "+inputzz+" dont you", "You want me to be able to "+inputzz+"?", "Perhaps you would like to be able to "+inputzz+" yourself."];
    var canyouaa = canyoua[Math.floor(Math.random() * canyoua.length)];
    return canyouaa;
}
function aboutmsg(){
    return "About<hr/><span>1. Informal Chat<br/>2. Roll A Die<br/>3. Random Card<br/>4. Flip a coin<br/>5. Clear -> Clear Screen<br/>6. Table<br/>7. Date, Time<br/>8. Close</span>";
}

function banthis(inputz) {
    document.getElementById("banthis").style.height = "100%";
    var overlaynav = "Banned!";
    return overlaynav;
}
function closebot(){
    document.getElementById('botcontent').style.width = "0";
}


//a dangerous/stupid lies benath the code..



//Browser
function obrowser(){
    document.getElementById('browser').style.width = "100%";
}
var browhist = [];
function searchthis(){
    var searchitem = document.getElementById('browinp').value;

    if(searchitem.length == 0){
        alert("Write Something in Search bar!");
    }
    else{
        document.getElementById('mainscr').style.display="block";
        document.getElementById('ibrowser').setAttribute('src', 'https://www.bing.com/search?q='+searchitem);
        
        if(tconnect >= txtz.length){
               browhist.push("");
        }
        else{
            browhist.push(searchitem);
        }
    }
}
function closeifmbr(){
    document.getElementById('mainscr').style.display="none";
    document.getElementById('browinp').value ="";
}
function refreshsear(){
    var searchitem = document.getElementById('browinp').value;
    if(searchitem.length == 0){
        alert("Write something in Search bar!");
    }
    else{
        document.getElementById('ibrowser').setAttribute('src', 'https://www.bing.com/search?q='+searchitem);
    }
}
function cbrowser(){
    document.getElementById('browser').style.width = "0";
    document.getElementById('browinp').value ="";
    document.getElementById('mainscr').style.display = "none"
}


//Calculator
function showcalc(){
    document.getElementById('calculator').style.width = "100%";
    alert("Double Click 'C' to Close!");
}
calcinput = document.getElementById('calcinput');
function calcfontsize(){
    if(calcinput.value.length >= 0){
        calcinput.style.fontSize = "36px";
    }
    if(calcinput.value.length >= 10){
        calcinput.style.fontSize = "32px";
    }
    if(calcinput.value.length >= 15){
        calcinput.style.fontSize = "28px";
    }
    if(calcinput.value.length >= 20){
        calcinput.style.fontSize = "24px";
    }
}
function addnum(cnum){
    calcinput.value += cnum;
    calcfontsize();
}
function ravcalc(){
    document.getElementById("calcinput").value = "";
    document.getElementById("calcoutput").value = "";
    calcfontsize();
}
function rvcalc(){
    var calcinputz = calcinput.value;
    calcinputzz = calcinputz.slice(0, -1);
    calcinput.value = calcinputzz;
    calcfontsize();
}
function outputit(){
    if(calcinput.value == null || calcinput.value == ""){
        calcinput.value = "";
        document.getElementById('calcoutput').value = "";
    }
    else{
        try{
            if(calcinput.value == "+-*/"){
                ravcalc();
                ccalc();
            }
            else{document.getElementById('calcoutput').value = eval(calcinput.value);}
        }
        catch(err){
            calcinput.value = "";
            alert("Invalid Input");
        }
    }
}
function ccalc(){
    document.getElementById('calculator').style.width = "0";
}




//I repeat, don't scroll;


//Calendar
function cal(){
    document.getElementById("cal").style.width ="100%";
    writecal();
}
var d = new Date;
var year = d.getFullYear();
var monthz = d.getMonth();
function writecal(){
    var calheader = document.getElementById('caltable').insertRow(-1);
    var calweekday = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
    for(weekdayforcal = 0; weekdayforcal<7;weekdayforcal++){
        insertingcell = calheader.insertCell(-1);
        insertingcell.innerHTML = "<b>"+calweekday[weekdayforcal]+"</b>";
    }
    switch(monthz){
        case 0: month = "January"; month_length=31;break;
        case 1: month = "Feburary";
            if(((year % 4 == 0) && (year % 100 != 0)) || (year % 400 == 0)){
                month_length=29;
            }
            else{
                month_length = 28;
                }
        break;
        case 2: month = "March"; month_length=31;break;
        case 3: month = "April"; month_length=30;break;
        case 4: month = "May"; month_length=31;break;
        case 5: month = "June"; month_length=30;break;
        case 6: month = "July"; month_length=31;break;
        case 7: month = "August"; month_length=31;break;
        case 8: month = "September"; month_length=30;break;
        case 9: month = "October"; month_length=31;break;
        case 10: month = "November"; month_length=30;break;
        case 11: month = "December"; month_length=31;break;
    }
    start_monthz = new Date(month+"1, "+year);
    start_month = start_monthz.getDay() +1;
    document.getElementById('caption').innerHTML = month+" "+year;
    var a = 0;
    var row1 = document.getElementById('caltable').insertRow(-1);
    for(var i=1;i<start_month;i++){
        cell = row1.insertCell(-1);
    }
    day = 1;
    for (var i=start_month;i<8;i++){
        cell = row1.insertCell(-1);
        if(d.getDate() == day  && d.getMonth() == monthz && d.getFullYear() == year){
            cell.classList.add("caltoday");
        }
        cell.innerHTML = day;
        day++
    }
    var a = document.getElementById('caltable').insertRow(-1);
    var row = [a];
    var rowing = 0;
    while (day <= month_length) {
        for (var i=1;i<=7 && day<=month_length;i++){
            cell = row[rowing].insertCell(-1);
            if(d.getDate() == day && d.getMonth() == monthz && d.getFullYear() == year){
                cell.classList.add("caltoday");
            }
            cell.innerHTML = day;
            day++
        }
        rowing++;
        row[rowing] = document.getElementById('caltable').insertRow(-1);
    }
}
function nextcal(){
    document.getElementById('caltable').innerHTML = "";
    monthz++;
    if(monthz > 11){
        monthz= 0;
        year++;
    }
    writecal();
}
function prevcal(){
    document.getElementById('caltable').innerHTML = "";
    monthz--;
    if(monthz < 0){
        monthz= 11;
        year--;
    }
    writecal();
}
function calhide(){
    document.getElementById("cal").style.width ="0";
    document.getElementById('caltable').innerHTML = "";
}


function showclock(){
    document.getElementById('clock').style.width = "100%";
}
function worldclockshouldwork(adahour, adamin){
    if(adahour <= -13 || adahour >= 13 || adamin < 0 || adamin > 60){
        return "See the time difference";
    }
    var d = new Date();
    var ofset = d.getTimezoneOffset();
    var timmin = ofset%60;
    var hourz = ofset-timmin;
    var timhour = hourz/60;
    var seconds = d.getSeconds();
    var crntlhour = d.getHours();
    var crntlmin = d.getMinutes();
    var t1crntlhour1 = crntlhour + timhour;
    var t1crntlmin1 = crntlmin + timmin;
    var t1crntlhour = t1crntlhour1 + adahour;
    var t1crntlmin = t1crntlmin1 + adamin;
    if(t1crntlmin < 0){
        t1crntlmin = t1crntlmin + 60;
        t1crntlhour--;
    }
    if(t1crntlmin > 60){
        t1crntlmin = t1crntlmin - 60;
        t1crntlhour++;
    }
    if(t1crntlhour < 0){
        t1crntlhour = t1crntlhour + 24;
    }
    
    if(t1crntlhour >= 24){
        t1crntlhour -= 24;
    }
    if(t1crntlhour >= 0 && t1crntlhour <= 9){
        t1crntlhour = "0"+t1crntlhour;
    }
    if(t1crntlmin >= 0 && t1crntlmin <= 9){
        t1crntlmin = "0"+t1crntlmin;
    }
    if(seconds >= 0 && seconds <=9){
        seconds = "0"+seconds;
    }
    return t1crntlhour+" : "+t1crntlmin+" : "+seconds;
}

function hideclock(){
    document.getElementById('clock').style.width = "0";
}


//Developer Mode
function odevmode(){
    document.getElementById('devmode').style.width = "100%";
}
function devfunc(){
    var jsstr = document.getElementById('devappinp').value;
    if(jsstr.length == 0)
         document.getElementById('devfunc').innerHTML += "- need some javascript input<br/>";
    else
           document.getElementById('userwcdevz').innerHTML += jsstr+"<hr/>";
    var notallowedjs = ["notallowedjs","assistantwork", "clearinterval", "replybotmessage", "write", "devfunc", "tconnect", "abxxsasswsasa", "mapp21", "memeap"];
    var notoffen = true;
    for(i=0; i<notallowedjs.length;i++){
        if(jsstr.search(notallowedjs[i]) > -1){
            notoffen = false;
            document.getElementById('devfunc').innerHTML += "Not allowed<br/>";
            return true;
        }
    }
    if(notoffen == true){
        try{
            document.getElementById('devappinp').value = "";
            var abxxsasswsasa = eval(jsstr);
            if((typeof abxxsasswsasa) == 'number'){
                console.log(abxxsasswsasa);
            }
        }
        catch(err){
            document.getElementById('devfunc').innerHTML += "- "+err+"<br/>";
        }
    }
}
function cdevmode(){
    document.getElementById('devmode').style.width = "0";
}


//Devs
function showdevs(){
    document.getElementById('devs').style.width = "100%";
}
function cdevs(){
    document.getElementById('devs').style.width = "0";
}


//Easter
function omeme(){
    document.getElementById('memeap').style.height = "100%";
    changememe();
}
function changememe(){
    var num = Math.ceil(Math.random() * 108);
    document.getElementById('memewallp').src = "https://jaydeepkhatri.000webhostapp.com/MeMe/me ("+num+").jpg";
}
function cmeme(){
    document.getElementById('memeap').style.height = '0';
}





//Email
function openmaila(){
    document.getElementById('email').style.width = "100%";
    document.getElementById('closeembtn').style.display = "block";
    document.getElementById('repmaibtn').style.display="block";
}
function replymail(){
    document.getElementById('mailreppal').style.width="100%";
    document.getElementById('closeembtnc').style.display = "block";
    document.getElementById('repmaibtnc').style.display = "block";
}
function creplymail(){
    closeemail();
    document.getElementById('mailreppal').style.width="0";
    document.getElementById('closeembtnc').style.display = "none";
    document.getElementById('repmaibtnc').style.display = "none";
}
function closeemail(){
    document.getElementById('email').style.width = "0";
    document.getElementById('closeembtn').style.display = "none";
    document.getElementById('repmaibtn').style.display="none";
}


//Maps
function maps(){
    document.getElementById('map').style.width="100%";
}
function mapfin(){
    var mapval = document.getElementById('mapval').value;
    if(mapval.length == 0){
        alert("Write in search bar");
    }
    else{
        document.getElementById('mainmap').style.display="block";
        document.getElementById('closemapbtn').style.display = "none";
        document.getElementById('closemapbtn1').style.display = "block";
        document.getElementById('mappp').setAttribute('src', "https://maps.google.com/maps?q="+mapval+"&output=embed");
    }
}
function bmmaps(){
    document.getElementById('mainmap').style.display="none";
    document.getElementById('closemapbtn').style.display = "block";
    document.getElementById('closemapbtn1').style.display = "none";

}
function cmaps(){
    document.getElementById('map').style.width="0";
    document.getElementById('mapval').value = "";
}


/*
Caught you, Danger Ahead💀
*/


//Music Player
function musicplayer(){
    document.getElementById('musicplayer').style.width="100%";
}
var song = ["Afreen Afreen.mp3", "Attention.mp3", "Bolna.mp3", "Daru Badnaam.mp3", "Despacito.mp3", "Faded.mp3", "Girls Like You.mp3", "Havana.mp3", "Let Me Love You(remix).mp3", "Maahi Ve.mp3", "Magenta Riddim.mp3", "Mehram.mp3", "Qaafirana.mp3", "Shape of You.mp3", "Taki Taki.mp3", "Tera Yaar Hoon Main.mp3", "Zaalima.mp3"];
var songlen = [398,233,212,185,228,212,235,218,209,240,194,278,342,233, 231,264,299];
var songnum = 0;
var seekprogress = document.getElementById('seekvalue');
var audioElement = document.createElement('audio');
audioElement.setAttribute('ontimeupdate', 'currentti()');
audioElement.setAttribute('onloadstart', 'thisonloadstart()');
audioElement.setAttribute('onloadeddata', 'thisonloadeddataz()');
audioElement.setAttribute('onended', 'mforward()');
function thisonloadstart(){
    document.getElementById('mloading').style.display = "block";
    document.getElementById('mstatus').innerHTML = "Loading.. <i class='fa fa-circle-o-notch fa-spin'></i> ";
}
function thisonloadeddataz(){
    setTimeout(alertthisonloadeddata, 500);
    document.getElementById('mstatus').innerHTML = "Done 👍";
}
function alertthisonloadeddata(){
    document.getElementById('mloading').style.display = "none";
}
document.getElementById("pausebutton").style.display = "none";
volumecontrol(0.7);
function dancethis1(){
    for(i=1;i<11;i++){
        if(i%3 == 0)
            document.getElementById('dnd'+i).style.height = Math.floor((Math.random()*220))+"px";
    }
}
function dancethis2(){
    for(j=1;j<11;j++){
        if(j%3 == 1)
        document.getElementById('dnd'+j).style.height = Math.floor((Math.random()*220))+"px";
    }
}
function dancethis3(){
    for(k=1;k<11;k++){
        if(k%3 == 2)
        document.getElementById('dnd'+k).style.height = Math.floor((Math.random()*220))+"px";
    }
}
var currentz = 0;
var bardance1;
var bardance2;
var bardance3;
function playmusic(){

    seekprogress.setAttribute('max', songlen[songnum]);
    
    audioElement.setAttribute('src', "https://jaydeepkhatri.000webhostapp.com/music/SL/"+song[songnum]);
    audioElement.currentTime = currentz;
    var playPromise = audioElement.play();
    if (playPromise !== undefined) {
    playPromise.then(_ => {
        document.getElementById('musicnotico').innerHTML = "<i class='fa fa-headphones'></i>";
        bardance1 = setInterval(dancethis1, 400);
        bardance2 = setInterval(dancethis2, 500),
        bardance3 = setInterval(dancethis3, 600),
        tobemus = song[songnum].substring(0, song[songnum].length-4)
        document.getElementById("titlesong").innerHTML = tobemus;
        document.getElementById("pausebutton").style.display = "block";
        document.getElementById("playbutton").style.display = "none";
    })
    .catch(error => {
        alert("Have Patience!\nLet the song load ☺🎵🎶");
    });
    }
    //help from Google, try & catch.
}
function pausemusic(){
    audioElement.pause();
    document.getElementById('musicnotico').innerHTML = "";
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
    document.getElementById("playbutton").style.display = "block";
    document.getElementById("pausebutton").style.display = "none";
}
function currentti(){
    document.getElementById('seekvalue').value = audioElement.currentTime;
    currentz = audioElement.currentTime;
    current = currentz.toFixed(1);
    mmin = Math.floor(current/60);
    currents = (current - (60*mmin)).toFixed(1);
    if(currents >= 0 && currents <= 10){
        currents = "0"+currents;
    }
    document.getElementById('ctime').innerHTML = "0"+mmin +" : "+currents;
}
function mforward(){
    songnum++;
    currentz = 0;
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
    if(songnum>=song.length){
        songnum = 0;
    }
    playmusic();
}
function mbackward(){
    songnum--;
    currentz = 0;
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
    if(songnum<0){
        songnum = song.length;
        return;
    }

    playmusic();
}
function hitrandommusic(){
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
    currentz = 0;
    songnum = Math.floor(Math.random() * song.length);
    playmusic();
}
function repeatthis(){
    audioElement.currentTime = 0;
    currentz = 0;
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
    playmusic();
}
function volumecontrol(volume){
    audioElement.volume = volume;
}
function cmusicplayer(){
    document.getElementById('musicplayer').style.width="0";
    document.getElementById('mloading').style.display = "none";
    pausemusic();
    clearInterval(bardance1);
    clearInterval(bardance2);
    clearInterval(bardance3);
}



//Phone
function phone(){
    document.getElementById('phone').style.width = "100%";
}
function phonenumin(val){
    var phonenumber = "";
    phonenumber += val;
    document.getElementById('inputnumber').value += phonenumber;
}
function clearnum(){
    phonenumber = document.getElementById('inputnumber').value;
    phonenumber = phonenumber.slice(0, -1);
    document.getElementById('inputnumber').value = phonenumber;
}
var tbeaster = Math.floor(Math.random()*9999);
if(tbeaster>=1 && tbeaster <=9)
    tbeaster = "000"+tbeaster;
else if(tbeaster>=10 && tbeaster <=99)
    tbeaster = "00"+tbeaster;
else if(tbeaster>=100 && tbeaster <=999)
    tbeaster = "0"+tbeaster;
function phonecallit(){
    var num = document.getElementById('inputnumber').value;
    if(num.length > 0){
        if(num == tbeaster){
            closephone();
            document.getElementById('mapp21').style.display = "inline-block";
            document.getElementById('inputnumber').value = "";
            alert("Activated");
        }
        else{
            window.open("tel:"+num);
        }
    }
}
function closephone(){
    document.getElementById('phone').style.width = "0";
}



/*
warning, warning, warning, warning!!!!!!!!
some people already had a serious attack while moving benath the code

so simply, don't scroll ⚡
*/



//Photo Editor
function ophotoeditor(){
    document.getElementById('photoeditor').style.width = "100%";
}
var ieinprange = document.getElementById('inputrange');
var iemainimg = document.getElementById('imagefil').style;
var ieimgbr = document.getElementById('bRadius').style;
var ieimgb = document.getElementById('ieborder').style;
var ieimgsld = document.getElementById('ieslidecontainer').style;
var ieimgrot = document.getElementById('ierotate').style;
function ieimeff(){
    ieimgsld.display = "block";
    ieimgbr.display = "none";
    ieimgb.display = "none";
    ieimgrot.display = "none";
}
var ieimgval = ["0", "0", "100", "0", "0", "100", "100", "100", "0"];
var iedefval = ["0", "0", "100", "0", "0", "100", "100", "100", "0"];
function mainimgedi(value){
    switch (iefilter){
    case 0:
        ieimgval[0] = value;
        document.getElementById('iefiltex1').innerHTML = ieimgval[0];
    break;
    case 1:
        ieimgval[1] = value;
        document.getElementById('iefiltex2').innerHTML = ieimgval[1];
    break;
    case 2:
        ieimgval[2] = value;
        document.getElementById('iefiltex3').innerHTML = ieimgval[2];
    break;
    case 3:
        ieimgval[3] = value;
        document.getElementById('iefiltex4').innerHTML = ieimgval[3];
    break;
    case 4:
        ieimgval[4] = value;
        document.getElementById('iefiltex5').innerHTML = ieimgval[4];
    break;
    case 5:
        ieimgval[5] = value;
        document.getElementById('iefiltex6').innerHTML = ieimgval[5];
    break;
    case 6:
        ieimgval[6] = value;
        document.getElementById('iefiltex7').innerHTML = ieimgval[6];
    break;
    case 7:
        ieimgval[7] = value;
        document.getElementById('iefiltex8').innerHTML = ieimgval[7];
    break;
    case 8:
        ieimgval[8] = value;
        document.getElementById('iefiltex9').innerHTML = ieimgval[8];
    break;
    }
    iemainimg.filter = "grayscale("+ieimgval[0]+"%) sepia("+ieimgval[1]+"%) saturate("+ieimgval[2]+"%) hue-rotate("+ieimgval[3]+"deg) invert("+ieimgval[4]+"%) opacity("+ieimgval[5]+"%) brightness("+ieimgval[6]+"%) contrast("+ieimgval[7]+"%) blur("+ieimgval[8]+"px)";
}
var iefilter ="";
function changefil(value){
    switch(value){
    case 'Grayscale':
        ifsetminatt(0);
        ifsetmaxatt(100);
        iefilter = 0;
        ieinprange.value = ieimgval[0];
    break;
    case 'Sepia':
        ifsetminatt(0);
        ifsetmaxatt(100);
        iefilter = 1;
        ieinprange.value = ieimgval[1];
    break;
    case 'Saturate':
        ifsetminatt(0);
        ifsetmaxatt(200);
        iefilter = 2;
        ieinprange.value = ieimgval[2];
    break;
    case 'Hue rotate':
        ifsetminatt(0);
        ifsetmaxatt(360);
        iefilter = 3;
        ieinprange.value = ieimgval[3];
    break;
    case 'Invert':
        ifsetminatt(0);
        ifsetmaxatt(100);
        iefilter = 4;
        ieinprange.value = ieimgval[4];
        break;
    case 'Opacity':
        ifsetminatt(0);
        ifsetmaxatt(100);
        iefilter = 5;
        ieinprange.value = ieimgval[5];
    break;
    case 'Brightness':
        ifsetminatt(0);
        ifsetmaxatt(300);
        iefilter = 6;
        ieinprange.value = ieimgval[6];
    break;
    case 'Contrast':
        ifsetminatt(50);
        ifsetmaxatt(200);
        iefilter = 7;
        ieinprange.value = ieimgval[7];
    break;
    case 'Blur':
        ifsetminatt(0);
        ifsetmaxatt(10);
        iefilter = 8;
        ieinprange.value = ieimgval[8];
    break;
    }
}
function ifsetminatt(min){
    return ieinprange.setAttribute('min', min);
}
function ifsetmaxatt(max){
    return ieinprange.setAttribute('max', max);
}
function borradcli(){
    ieimgbr.display = "block";
    ieimgb.display = "none";
    ieimgsld.display = "none";
    ieimgrot.display = "none";
}
function bradius(bvalue){
    iemainimg.borderRadius = bvalue+"%";
}


function boriecli(){
    ieimgbr.display = "none";
    ieimgb.display = "block";
    ieimgsld.display = "none";
    ieimgrot.display = "none";
}
var peborder = '000';
var peborderstyle = 'solid';
function ieeborder(value){
    iemainimg.border = value+"px solid #"+peborder;
    iemainimg.borderStyle = peborderstyle;
}
function borroti(){
    ieimgbr.display = "none";
    ieimgb.display = "none";
    ieimgsld.display = "none";
    ieimgrot.display = "block";
}
function ieroate(value){
    iemainimg.transform = "rotate("+value+"deg)";
}
function reset(){
    iemainimg.filter = "grayscale("+iedefval[0]+"%) sepia("+iedefval[1]+"%) saturate("+iedefval[2]+"%) hue-rotate("+iedefval[3]+"deg) invert("+iedefval[4]+"%) opacity("+iedefval[5]+"%) brightness("+iedefval[6]+"%) contrast("+iedefval[7]+"%) blur("+iedefval[8]+"px)";
    for(i=0;i<9;i++){ 
        ieimgval[i] = iedefval[i];
        document.getElementById('iefiltex'+(i+1)).innerHTML = ieimgval[i];
        document.getElementById('baRadius').value = 0;
        iemainimg.border = "0";
        iemainimg.borderRadius = 0;
        iemainimg.transform = 'rotate(0deg)';
        document.getElementById('borderplus').value = 0;
        document.getElementById('imgrotate').value = 0;
    }
}
var idkcef = 0;
function iechagim(){
    document.getElementById('imagefil').src = "https://picsum.photos/250/250/?random&randomm="+idkcef;
    idkcef++;
    reset();
}
function cphotoeditor(){
    document.getElementById('photoeditor').style.width = "0";
}





//Settings
function settings(){
    document.getElementById('settings').style.width = "100%";
}
var seticobt1 = document.getElementById('seticobtn1');
var seticobt2 = document.getElementById('seticobtn2');
var seticobt3 = document.getElementById('seticobtn3');
seticosize('medium');
function seticosize(appsize){
    var size = appsize;
    if(size == 'small'){
        seticobt1.style.backgroundColor = "#"+themecolorname;
        seticobt2.style.backgroundColor = "#ddd";
        seticobt3.style.backgroundColor = "#ddd";
        for(i=1;i<=21;i++){
            document.getElementById("mapp"+i).style.width = "20%";
            document.getElementById("mapp"+i).style.cssFloat = "left";
            document.getElementById('ap'+i).style.width = '55px';
            document.getElementById('ap'+i).style.height = '55px';
            document.getElementById('aptxt'+i).style.fontSize = "12px";
        }
    }
    else if(size == 'medium'){
        seticobt1.style.backgroundColor = "#ddd"
        seticobt2.style.backgroundColor = "#"+themecolorname;
        seticobt3.style.backgroundColor = "#ddd";
        for(i=1;i<=21;i++){
            document.getElementById("mapp"+i).style.width = "25%";
            document.getElementById("mapp"+i).style.cssFloat = "left";
            document.getElementById('ap'+i).style.width = '70px';
            document.getElementById('ap'+i).style.height = '70px';
            document.getElementById('aptxt'+i).style.fontSize = "16px";
        }
    }
    else if(size == 'large'){
        seticobt1.style.backgroundColor = "#ddd";
        seticobt2.style.backgroundColor = "#ddd";
        seticobt3.style.backgroundColor = "#"+themecolorname;
        for(i=1;i<=21;i++){
            document.getElementById("mapp"+i).style.width = "33%";
            document.getElementById("mapp"+i).style.cssFloat = "left";
            document.getElementById('ap'+i).style.width = '80px';
            document.getElementById('ap'+i).style.height = '80px';
            document.getElementById('aptxt'+i).style.fontSize = "20px";
        }
    }
    else{
        alert("Something went wrong");
    }
}
function mobileoff(){
    var conf = confirm("Are you Sure?");
    var closemusic = document.createElement('audio');
    closemusic.setAttribute('src', 'http://jaydeepkhatri.000webhostapp.com/music/SL/windowsc.mp3');
    if(conf==true){
        closemusic.volume = 1;
        closemusic.play();
        setTimeout(function()
        {
            var body = document.getElementById('body');
            body.innerHTML = "";
            body.innerHTML = "<img src='http://jaydeepkhatri.000webhostapp.com/music/SL/a144.jpg' style='width:100%; height:100%; border-radius:0;'/>";
            clearInterval(mainloadingz);
        }, 500);
    }
}
function closesettings(){
    document.getElementById('settings').style.width = "0";
}


/*
Seems like you are taking this lightly
or didn't you read the warning above in the code
there is danger ahead⚠

DONT SCROLL;
*/




//SoloLearn
function sololearnf() {
    document.getElementById('sololearn').style.width="100%";
}
function csololearnf() {
    document.getElementById('sololearn').style.width="0";
}


//Stopwatch
function stopwatchz(){
    document.getElementById('stopwatch').style.width="100%";
}
clockinterval = null;
swmsec = swmsecp = swsec = swsecp = swmin = swminp = swhour = swhourp = 0;
function countstopwatch(){
    swmsec++;
    swmsecp = swmsec;
    swsecp = swsec;
    swminp = swmin;
    swhourp = swhour;
    if(swmsec>=0 && swmsec<=9){
        swmsecp = "0"+swmsec;
    }
    if(swsec>=0 && swsec <= 9){
        swsecp = "0"+swsec;
    }
    if(swmin>=0 && swmin <= 9){
        swminp = "0"+swmin;
    }
    if(swhour>=0 && swhour <= 9){
        swhourp = "0"+swhour;
    }
    if(swmsec>=99){
        swsec++;
        swmsec = 0;
    }
    if(swsec > 59){
        swmin++;
        swsec = 0;
    }
    if(swmin > 59){
        swhour++;
        swmin = 0;
        swsec = 0;
    }
    printswvalues(swmsecp, swsecp, swminp, swhourp);
}
function printswvalues(swmsec, swsec, swmin, swhour){
    document.getElementById('stophour').innerHTML = swhour;
    document.getElementById('stopminute').innerHTML = swmin;
    document.getElementById('stopsecond').innerHTML = swsec;
    document.getElementById('stopmsecond').innerHTML = swmsec;
}
function resetsw(){
    clearInterval(clockinterval);
    document.getElementById('swstart').disabled = false;
    swmsec = swmsecp = swsec = swsecp = swmin = swminp = swhour = swhourp = 0;
    printswvalues(swmsec, swsec, swmin, swhour);
    swtable.innerHTML = "";
}
var swtable = document.getElementById('tabforlap');
function swlap(){
    var swtrow = swtable.insertRow(-1);
    var cell = swtrow.insertCell(-1);
    cell.style.textAlign = "center";
    cell.innerHTML = swhourp+" : "+swminp+" : "+swsecp+" : "+swmsecp;
}
function closestopwatch(){
    document.getElementById('stopwatch').style.width="0";
}




//Terminal
function oterminal(){
    document.getElementById('materminal').style.width = "100%";
}
var mainterminal = document.getElementById('mterminal');
var tinput = document.getElementById('terminalinput');
var tscrollelement = document.getElementById('mterminal');
var txtz = '██████████████';
function workterminal(){
    var ttextz = tinput.value;
    var ttext = ttextz.toLowerCase();
    mainterminal.innerHTML += "<br/>~//root/"+ttextz;
    tinput.value = "";
    var posinput = ["connect", "disconnect", "delete", "close", "browser", "help", ""];
    switch(ttext){
        case posinput[0]:
            tinput.disabled = true;
            mainterminal.innerHTML += "<br/> <i class='fa fa-caret-right'></i> Finding server...<br/>";
            setTimeout(tprogressitz, 2000);
            break;
        case posinput[1]:
            tconnect = 0;
            mainterminal.innerHTML +="<br/> <i class='fa fa-caret-right'></i> You are disconnected!";
            document.getElementById('mapp21').style.display = "none";
            document.getElementById('usericon').innerHTML = "";
            document.getElementById('themedef').style.display = "none";
            document.getElementById('browinco').innerHTML = "<i class='fa fa-refresh fa-fw'></i>";
            document.getElementById('browinco').setAttribute('onclick', 'refreshsear()');
            break;
        case posinput[2]:
            if(tconnect >= txtz.length){
                var apptbdelete = prompt("Enter the name of app", "Name");
                tdeleteapp(apptbdelete);
            }
            else{
                mainterminal.innerHTML += "<br/><i class='fa fa-caret-right'></i>Please connect to server";
            }
            break;
        case posinput[3]:
            document.getElementById('materminal').style.width = "0";
            break;
        case posinput[4]:
            mainterminal.innerHTML += "<br/> <i class='fa fa-caret-right'></i> History ("+browhist.length+")";
            for(a = 0; a<browhist.length;a++){
                mainterminal.innerHTML += "<br/> - "+browhist[a];
            }
            break;
        case posinput[6]:
            break;
        default:
            mainterminal.innerHTML +="<br/><i class='fa fa-caret-right'></i> List of commands is";
            for(commands = 0; commands<posinput.length;commands++){
                mainterminal.innerHTML +="<br/>- "+posinput[commands];
            }
    }
    tscrollelement.scrollTop = tscrollelement.scrollHeight;
}
function tprogressitz(){
    document.getElementById('mterminal').innerHTML += "<i class='fa fa-caret-right'></i> Connecting...<br/>";
    tscrollelement.scrollTop = tscrollelement.scrollHeight;
    setTimeout(tprogressit, 500);
}
var tconnect = 0;
function tprogressit(){
    tconnect++;
    if(tconnect > txtz.length){
        document.getElementById('mterminal').innerHTML += "<i class='fa fa-caret-right'></i> Already connected to server<br/><i class='fa fa-caret-right'></i> "+tbeaster;
        tinput.disabled = false;
        tscrollelement.scrollTop = tscrollelement.scrollHeight;
    }
    if(tconnect < txtz.length){
        document.getElementById("mterminal").innerHTML += txtz.charAt(tconnect);
        tscrollelement.scrollTop = tscrollelement.scrollHeight;
        setTimeout(tprogressit, 500);
    }
    if(tconnect == txtz.length){
        document.getElementById('mterminal').innerHTML += "<br/><i class='fa fa-caret-right'></i> Connection established to server!<br/><i class='fa fa-caret-right'></i> "+tbeaster;
        tinput.disabled = false;
        document.getElementById('usericon').innerHTML = "<i class='fa fa-user fa-fw'></i>";
        document.getElementById('browinco').innerHTML = "<i class='fa fa-coffee fa-fw'></i>";
        document.getElementById('browinco').setAttribute('onclick', "alert('You are in Incognito Mode!')");
        document.getElementById('themedef').style.display = "block";
        tscrollelement.scrollTop = tscrollelement.scrollHeight;
    }
}
function tdeleteapp(apptbdelete){
    var myapps = ["Assistant", "Browser", "Calculator", "Calendar", "Clock", "Developer", "Devs", "E-mail", "Maps", "Music", "Phone", "Photo Editor", "Settings", "Sololearn", "Stopwatch", "Terminal", "Text Editor", "Themes", "Unit Converter", "Videos"];
    if(myapps.indexOf(apptbdelete) > -1){
        document.getElementById("mapp"+(myapps.indexOf(apptbdelete)+1)).style.display = "none";
        mainterminal.innerHTML +="<br/>&gt; deleted "+apptbdelete+"!";
    }
    else{
        mainterminal.innerHTML +="<br/><i class='fa fa-caret-right'></i> "+apptbdelete+"<br/><i class='fa fa-caret-right'></i> Please check the name";
        for(app =0; app<myapps.length; app++){
            mainterminal.innerHTML +="<br/>- "+myapps[app];
        }
        mainterminal.innerHTML +="<br/><i class='fa fa-caret-right'></i> It is Case Sensitive";
    }
}
function closeterminal(){
    document.getElementById('materminal').style.width = "0";
   }


/*
So you have decided to move benath the code😑
*/



//TextEditor
function texteditor(){
    document.getElementById('texteditor').style.width = "100%";
}
var defbor = "2px solid #ddd";
var texteditorelement = document.getElementById('texteditorcontent').style;
var bolding = 1;
function boldthis(){
    if(bolding%2 == 1){
        texteditorelement.fontWeight = "bold";
        document.getElementById('textedit1').style.border = "2px solid #"+themecolorname;
        bolding++;
    }
    else{
        texteditorelement.fontWeight = "normal";
        document.getElementById('textedit1').style.border = defbor;
        bolding++;
    }
}
var italicing = 1;
function italicthis(){
    if(italicing%2 ==1){
        texteditorelement.fontStyle = "italic";
        document.getElementById('textedit2').style.border = "2px solid #"+themecolorname;
        italicing++;
    }
    else{
         texteditorelement.fontStyle = "normal";
         document.getElementById('textedit2').style.border = defbor;
         italicing++;
    }
}
var underlining = 1;
function underlinethis(){
    if(underlining%2 == 1){
        texteditorelement.textDecoration = "underline";
        document.getElementById('textedit3').style.border = "2px solid #"+themecolorname;
        underlining++;
    }
    else{
         texteditorelement.textDecoration = "none";
         document.getElementById('textedit3').style.border = defbor;
         underlining++;
    }
}
function fontsizethis(size){
    texteditorelement.fontSize = size+"px";
}
function alignthis(alignname){
    texteditorelement.textAlign = alignname;
    if(alignname == "left"){
        document.getElementById('textedit4').style.border = "2px solid #"+themecolorname;
        for(textalignbutton = 5; textalignbutton <=7; textalignbutton++){
            document.getElementById('textedit'+textalignbutton).style.border = defbor;
        }
    }
    else if(alignname == "center"){
        document.getElementById('textedit5').style.border = "2px solid #"+themecolorname;
        for(textalignbutton = 4; textalignbutton <=7; textalignbutton++){
            if(textalignbutton == 5){
                continue;
            }
            else{
            document.getElementById('textedit'+textalignbutton).style.border = defbor;
            }
        }
    }
    else if(alignname == "right"){
        document.getElementById('textedit6').style.border = "2px solid #"+themecolorname;
        for(textalignbutton = 4; textalignbutton <=7; textalignbutton++){
            if(textalignbutton == 6){
                continue;
            }
            else{
            document.getElementById('textedit'+textalignbutton).style.border = defbor;
            }
        }
    }
    else if(alignname == "justify"){
        document.getElementById('textedit7').style.border = "2px solid #"+themecolorname;
        for(textalignbutton = 4; textalignbutton <=6; textalignbutton++){
            document.getElementById('textedit'+textalignbutton).style.border = defbor;
        }
    }
}
var shadowing = 1;
function shadowthis(){
    if(shadowing%2==1){
        texteditorelement.textShadow = "0px 0px 8px #"+themecolorname;
    
    document.getElementById('textedit8').style.border = "2px solid #"+themecolorname;
    shadowing++;
    }
    else{
        texteditorelement.textShadow = "none";
         document.getElementById('textedit8').style.border = defbor;
        shadowing++;
    }
}
function tefont(){
    var fontstyle=document.getElementById('tefont').value;
    switch(fontstyle){
        case 'Barlow':
            texteditorelement.fontFamily = 'Barlow, sans-serif';
            break;
        case 'Pattaya':
            texteditorelement.fontFamily = 'Pattaya, sans-serif';
            break;
        case 'Spicy Rice':
            texteditorelement.fontFamily = 'Spicy Flower, cursive';
            break;
        case 'Indie Flower':
            texteditorelement.fontFamily = 'Indie Flower, cursive';
            break;
        case 'Shadows into Light':
            texteditorelement.fontFamily = 'Shadows Into Light, cursive';
            break;
        case 'Satisfy':
            texteditorelement.fontFamily = 'Satisfy, cursive';
            break;
        case 'Baloo Bhaijaan':
            texteditorelement.fontFamily = 'Baloo Bhaijaan, cursive';
            break;
        case 'Caveat':
            texteditorelement.fontFamily = 'Caveat, cursive';
            break;
        case 'Monoton':
            texteditorelement.fontFamily = 'Monoton, cursive';
            break;
    }
}
function techangecol(){
    var val = document.getElementById('tecolpal').value;
    texteditorelement.color = val;
}
function showtebar(){
    document.getElementById('tetab').style.display="block";
    texteditorelement.height = "70%";
    document.getElementById('teshowbtn').style.display="none";
}
function hidetebar(){
    document.getElementById('tetab').style.display="none";
    texteditorelement.height = "100%";
    document.getElementById('teshowbtn').style.display="block";
}
function ctexteditor(){
    document.getElementById('texteditor').style.width = "0";
}



var ytembed = "https://www.youtube.com/embed/";
var youtubevideos = ["Ii3c3mEAuA4", "Q6_5InVJZ88", "UeG1ftTmLAg", "QdVFvsCWXrA", "1KofiHFsBQk", "zsjK04TqQq0", "fTvelC4ZZds", "Q0jeohWnmAQ", "D75ZuaSR8nQ", "cqyziA30whE", "HZrsuEWw9m8", "WKuNWrxuJ9g", "F9GujgK0y2M", "OmeFGPnT3Qs"];
var playingnow = 0;
//Themes
function themesz(){
    document.getElementById('themesz').style.width = "100%";
}
themcolo('aabac2');
var themecolorname;
function themcolo(themecolornamez){
    themecolorname = themecolornamez;
    document.getElementById('notific').style.backgroundColor = "#"+themecolorname;
    document.getElementById('phonecallbtn').style.backgroundColor = "#"+themecolorname;
    document.getElementById('phonebackbtn').style.backgroundColor = "#"+themecolorname;
    document.getElementById('playbutton').style.border = "2px solid #"+themecolorname;
    document.getElementById('pausebutton').style.border = "2px solid #"+themecolorname;
    document.getElementById('repmaibtn').style.backgroundColor = "#"+themecolorname;
    document.getElementById('closeembtn').style.backgroundColor = "#"+themecolorname;
    document.getElementById('repmaibtnc').style.backgroundColor = "#"+themecolorname;
    document.getElementById('closeembtnc').style.backgroundColor = "#"+themecolorname;
    for(i=1;i<=6;i++){
        document.getElementById('setbadge'+i).style.backgroundColor = "#"+themecolorname;
    }
    for(i=1; i<=5;i++){
        document.getElementById('calcnum'+i).style.backgroundColor = "#"+themecolorname;
    }
    for(i=1;i<=8;i++){
        document.getElementById('textedit'+i).style.border = "2px solid #ddd";
    }
    for(l=1;l<=10;l++){
        document.getElementById('dnd'+l).style.backgroundColor = "#"+themecolorname;
    }
    for(m=1;m<=3;m++){
        document.getElementById('musicbu'+m).style.border = "2px solid #"+themecolorname;
    }
    for(ie=0;ie<=5;ie++){
        document.getElementById('iebtn'+ie).style.backgroundColor = "#"+themecolorname;
    }
    for(vid=0;vid<=youtubevideos.length-1;vid++){
        document.getElementById('videoitem'+vid).style.backgroundColor = "#"+themecolorname
    }
}
function cthemes(){
    document.getElementById('themesz').style.width = "0";
}


/*
⚠⚠⚠⚠⚠⚠⚠⚠⚠⚠

Are this warning signs a joke???🙄😑
*/



//Unit Converter
function unitconverter(){
    document.getElementById('unitconveter').style.width = "100%";
}
var ucentimeter = document.getElementById('inpcentimeter');
    var umeter = document.getElementById('inpmeter');
    var ukilometer = document.getElementById('inpkilometer');
    var uinch = document.getElementById('inpinch');
    var ufoot = document.getElementById('inpfoot');
    var uyard = document.getElementById('inpyard');
    var umile = document.getElementById('inpmile');
function uccentimeter(cm){
    umeter.value = cm/100;
    ukilometer.value = cm/100000;
    uinch.value = cm*0.39370;
    ufoot.value = cm*0.032808;
    uyard.value = cm*0.010936;
    umile.value = cm*0.0000062137;
}
function ucmeter(m){
    ucentimeter.value = m/0.01;
    ukilometer.value = m/1000;
    uinch.value = m*39.370;
    ufoot.value = m*3.2808;
    uyard.value = m*1.0936;
    umile.value = m*0.00062137;
}
function uckilometer(km){
    ucentimeter.value = km*100000;
    umeter.value = km*1000;
    uinch.value = km*39370;
    ufoot.value = km*3280.8;
    uyard.value = km*1093.6;
    umile.value = km*0.62137;
}
function ucinch(inch){
    ucentimeter.value = inch/0.39370;
    umeter.value = inch/39.370;
    ukilometer.value = inch/39370;
    ufoot.value = inch*0.83333;
    uyard.value = inch*0.027778;
    umile.value = inch*0.000015783;
}
function ucfoot(foot){
    ucentimeter.value = foot/0.032808;
    umeter.value = foot/3.2808;
    ukilometer.value = ft/3280.8;
    uinch.value = foot*12;
    uyard.value = foot*0.33333;
    umile.value = foot*0.00018939;
}
function ucyard(yard){
    ucentimeter.value = yard/0.010936;;
    umeter.value = yard/1.0936;
    ukilometer.value = yard/1093.6;
    uinch.value = yard*36;
    ufoot.value = yard*3;
    umile.value = yard*0.00056818;
}
function ucmile(mile){
    ucentimeter.value = mile/0.0000062137;
    umeter.value = mile/0.00062137;
    ukilometer.value = mile/0.62137;
    uinch.value = mile*63360;
    ufoot.value = mile*5280;
    uyard.value = mile*1760;
}



//Temperature
var fah = document.getElementById('ufahrenheit');
var cel = document.getElementById('ucelsius');
var kel = document.getElementById('ukelvin');
function ucfahrenheit(tempf){
    cel.value = ((tempf-32)/1.8).toFixed(2);
    kel.value = (((tempf-32)/1.8)+273.15).toFixed(2);
}
function uccelsius(tempc){
    fah.value = ((tempc*1.8)+32).toFixed(2);
    kel.value = ((tempc*1) + 273.15).toFixed(2);
}
function uckelvin(tempk){
    fah.value = (((tempk-273.15)*1.8)+32).toFixed(2);
    cel.value = (tempk-273.15).toFixed(2);
}

//Text to Binary
function convtetb(binctinp){
    document.getElementById('bincbin').value = "";
    for(i = 0; i < binctinp.length; i++){
        document.getElementById('bincbin').value +=binctinp[i].charCodeAt(0).toString(2) + " ";
    }
}

function cunitconverter(){
    document.getElementById('unitconveter').style.width = "0";
}


/*
You are almost benath the code
    *The End is near*
    *haha*
*/


//Videos
function videos(){
    document.getElementById('vidplayer').style.width = "100%";
}

function playytv(playingno){
    if(navigator.onLine == true){
        playingnow = playingno;
        document.getElementById('youtubeid').setAttribute("src", ytembed+youtubevideos[playingno]+"?controls=1");
        document.getElementById('videoplbtn').style.display = "none"
        document.getElementById('vidplayer').scrollTo(0,0);
    }
    else{
        alert("check your connectivity");
    }
}
function nextvid(){
    playingnow++;
    if(playingnow>=youtubevideos.length)
        playingnow = 0;
    playytv(playingnow);
}
function prevvid(){
    playingnow--;
    if(playingnow<0)
        playingnow = youtubevideos.length-1;
    playytv(playingnow);
}
function adduservideo(){
    var ytvideol = youtubevideos.length-1;
    var youtubevlink = document.getElementById('videouserinput').value;
    if(youtubevlink.indexOf('youtube.com') > -1){
        var youtubevlin = youtubevlink.split("/");
        var youtubevli = youtubevlin[youtubevlin.length-1];
        var youtubevl = youtubevli.split("?");
        var youtub = youtubevl[1];
        var youtu = youtub.split("&");
        var yout = youtu[0].split("=");
        var tyou = yout[1];
        youtubevideos.push(tyou);
        ytvideol++;
        playytv(ytvideol);
        document.getElementById('videolistj').innerHTML += "<div class='videoitem' style=background-color:"+themecolorname+" onclick=playytv("+ytvideol+")>Video "+ytvideol+"</div>";
        document.getElementById('videouserinput').value = "";
    }
    else{
        alert('check the link\n ex : https://www.youtube.com/watch?v=YbJOTdZBX1g');
    }
}
function cvideos(){
    document.getElementById('vidplayer').style.width = "0";
    document.getElementById('youtubeid').setAttribute("src", ytembed+youtubevideos[playingnow]+"?controls=1");
    document.getElementById('videoplbtn').style.display = "inline-block";
}
</script>
<script>
/*
This is last & final warning, Dont Scroll
  _        _
_| |      | |_
|_ \      / _|
  \ \____/ /
   \/_  _\/
    \*  */
/*   |/\|
     /__\
    /\__/\
  _/ /  \ \_
 |_ /    \ _|
  |_|    |_|


Something danger 😨🔥 or foolish
*/
</script>
</body>
</html>







































































<!--
Although you are here, Can you say what is the OUTPUT of this code
<script>
    var a = "I fooled that guy".slice(2, 8);
    var aa = "you look sick".search("you");
    document.write("i "+a+" "+aa.charAt(2));
</script>



JK😂😛
I appreciate the patience for scrolling this long😂😂🤣
Run the code & Enjoy
Happy Coding💻😊
-->



*{
    outline:none;
}
body{
    font-family: "Barlow", sans-serif;
    background-color:#ddd;
    margin:0;
    padding:0;
}
::-webkit-scrollbar { 
    display: none; 
}
.notific{
    position:fixed;
    top:0;
    z-index:2;
    width:100%;
    display: inline-block;
    border-bottom:1px solid #999;
}
.mobileloader{
    position:fixed;
    width:100%;
    height:100vh;
    background-color:#333;
    color:#ddd;
    z-index:3;
    display:flex;
    justify-content: center;
    align-items: center;
    font-size:40px;
}
img{
    box-shadow:1px 1px 7px #000;
    border-radius:50%;
}
.mapp{
    display:inline-block;
    padding-bottom:10px;
}
.mapp:active{
    transform: translateY(4px);
}
.apname{
    width:70px;
    opacity:0.8;
    cursor:default;
    font-size:15px;
}
.apbtheme{
    height: 100%;
    width: 0;
    position: fixed;
    top: 0;
    right: 0;
    background-color: #eee;
    overflow: scroll;
    transition:0.25s; /*set the speed here.....*/
}
.backbtnz{
    width:100%;
    background-color:#000;
    bottom:0;
    position: absolute;
    left:0;
}
.backbtnz .closeappbtn{
    border:2px solid #aa0000;
    opacity:0.9;
    font-size:16px;
    background-color:#000;
    color:#fff;
}
.closeappbtn{
    padding:8px;
    border-radius:4px;
    border:1px solid #4d0000;
    opacity:0.9;
    font-size:16px;
    background-color:#ff6666;
}
.closeappbtn:active{
    transform: translateY(2px);
    box-shadow:0 0 #ff4040;
}




/*Assistant*/
.botplayground{
    padding:5px;
    height:calc(100vh - 32px);
    overflow:scroll;
    width:100%;
    box-sizing: border-box;
}
.closeasstbtn{
    position:absolute;
    bottom:2px; 
    width: 20%;
    left:0;
    padding:5px;
    text-align:center;
    box-sizing: border-box;
    border: 1px solid grey;
    border-right:0;
    border-left:none;
    border-radius:5px 0 0 5px;
}
.textbotmessage{
    left:20%;
    position:absolute;
    padding:5px;
    box-sizing: border-box;
    bottom:2px;
    border: 1px solid grey;
    width: 70%;
    background: #f1f1f1;
    border-right:none;
    border-left:none;
    border-radius:0;
}
.textbotmessage:focus{
    outline:none;
}
.sendbotbutton{
    position:absolute;
    bottom:2px; 
    width: 10%;
    padding:5px;
    box-sizing: border-box;
    right:0;
    text-align:center;
    border: 1px solid grey;
    border-left:none;
    border-radius:0 5px 5px 0;
}
.botinputform{
    margin-bottom:0;
}
.botinputform::after{
  content: "";
  clear: both;
  display: table;
  margin:0;
}
#botcontent::after {
    content: "";
    clear: both;
    display: table;
}
.message {
    border: 2px solid #dedede;
    border-radius: 5px;
    padding: 5px;
    margin: 4px;
    width:50%;
    float:left;
    font-size:16px;
    background-color:#abb8c2;
}
.user {
    border-color: #ccc;
    float:right;
    background-color:#fff;
}
.banthis {
    height: 0;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0, 0.9);
    overflow-y: hidden;
    transition: 0.5s;
}
.banthisz {
    position: relative;
    top: 25%;
    width: 100%;
    text-align: center;
    margin-top: 30px;
    font-size:36px;
    color:#ff3333;
}



/*Browser*/
.mainhomescr{
    background-image:url("http://jaydeepkhatri.000webhostapp.com/music/strbkg.jpg");
    background-size:100% 100%;
    background-repeat: no-repeat;
    display:flex;
    justify-content: center;
    align-items: center;
    background-color:#aaa;
    font-family: 'Roboto', sans-serif;
}
.browserap{
    position:absolute;
    bottom:0;
    width:100%;
    left:0;
    right:0;
    z-index:2;
    background-color:#ddd;
}
.inputxzz{
    margin: auto;
    text-align:center;
    padding:10px;
    /*border:2px solid #ff0;*/
}
.browinp{
    padding:8px;
    font-size:18px;
    width:300px;
    border-radius:8px;
    border:0;
    z-index:3;
}
.browinp:active, .browinp:hover, .browinp:focus{
    outline:none;
}
.browsearchbtn{
    padding:5px;
    background-color:#aec;
}
.browselogo{
    letter-spacing:3px;
    color:#fff;
    font-weight:lighter;
}
.browsearchbtn{
    height:35px;
    border:1px solid transparent;
    border-radius:3px;
    font-size:0.8em;
    font-weight:800;
    color:#555;
    background-color:#EEE;
    transition-duration:0.2s;
}
.browsearchbtn:hover, .browsearchbtn:active{
    border:1px solid #333;
    color:#333;
    box-shadow:0 0 5px #000;
}
.mainscr{
    height:calc(100vh - 48px);
    width:100%;
    overflow:hidden;
    display:none;
    position:fixed;
    left:0;
    top:16px;
    background-color:#fff;
    z-index:2;
}
.browbbtns{
    width:20%;
    float:left;
    text-align:center;
    padding:10px;
    box-sizing: border-box;
}




/*Calculator*/
.calctable{
    position:fixed;
    bottom:0;
    height:60%;
    border-collapse:collapse;
    border-top:1px solid #aaa;
}
.calcnum{
    height: 25%;
    font-size: 30px;
}
.calcbut{
    transition:0.05s;
}
.calcbut:hover, .calcbut:focus, .calcbut:active{
    background-color:#ddd;
}
#calcinput{
    position: fixed;
    bottom:70%;
    width:98%;
    font-size: 36px;
    padding:4px;
    background-color:#eee;
    border:0;
    text-align:right;
    color:#000;
}
#calcoutput{
    position: fixed;
    bottom:60%;
    width:98%;
    font-size: 36px;
    padding:4px;
    background-color:#eee;
    border:0;
    color:#000;
    text-align:right;
}




/*Calendar*/
.caltable{
    border-collapse:collapse;
    text-align:center;
}
.caltoday{
    background-color:#333;
    color:#ccc;
}
.calbtns{
    width:25%;
    display:inline-block;
}
.calbtn{
    background-color:#ddd;
    padding:5px;
    border:1px solid #999;
    border-radius:3px;
    box-shadow:0 4px 8px 0 rgba(0,0,0,0.2);
}
.calmonths{
    width:50%;
    display:inline-block;
}



/*Clock*/
.clocktime{
    font-size:40px;
}
.mainclock{
    height:calc(100vh - 32px);
    overflow:scroll;
}
.clocksecond{
    font-size:20px;
}


/*Developer*/
.devfunc{
    border:1px solid #ddd; 
    color:#ff4c4c;
    font-weight:900;    
    padding:10px;
    box-sizing: border-box;
}
.helpdevul{
    list-style-type: circle;
}
.userwcdevz{
    padding:20px;
    box-sizing: border-box;
    height:calc(100vh - 32px);
    overflow:scroll;
}
.devlcodefun{
    color:#00f;
}


/*Devs*/
td{
    padding:5px;
    cursor:default;
    transition:0.25s;
}
.devs{
    text-decoration: none;
    color:black;
}
.setava{
    border:2px solid #aaa;
    border-radius:50%;
    width:50%;
    cursor:default;
    box-shadow: 0 5px 15px 0 rgba(0,0,0,0.6);
    -webkit-transform: translatey(0px);
    -webkit-animation: float 6s ease-in-out infinite; 
}
@keyframes float {
    0% {
        box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
        transform: translatey(0px);
    }
    50% {
        box-shadow: 0 25px 15px 0px rgba(0,0,0,0.2);
        transform: translatey(-20px);
    }
    100% {
        box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
        transform: translatey(0px);
    }
}



/*E-mail*/
#by{
    background-color:#f2f2f2;
    color:#aaa;
    padding:5px;
    border-radius:5px;
}
#dev{
    color:black;
}
.closeemailappbtn{
    width:50%;
    position:fixed;
    border:0;
    bottom:0;
    padding:8px;
    box-sizing: border-box;
    left:0;
    float:left;
    display:none;
}
.replyemailbtn{
    width:50%;
    position:fixed;
    border:0;
    padding:8px;
    box-sizing: border-box;
    bottom:0;
    right:0;
    float:right;
    display:none;
}
.inputmaad{
    width:100%;
    border:0;
    padding:10px;
    margin-bottom:5px;
    box-sizing: border-box;
    /*border-bottom:1px solid #000;*/
}
.textarearep{
    width:100%;
    border:0;
    padding:10px;
    font-size:18p;
    box-sizing:border-box;
    background-color: #fff;
}
.emailmsg {
    background: #e91e63;
    color: #FFF;
    padding: 10px;
    display: inline-block;
    border-radius: 5px;
    word-wrap: break-word;

}
.emailmsg:before {
    background: #e91e63;
    width: 12pt;
    height: 12pt;
    display: inline-block;
    content: ' ';
    transform: rotate(45deg);
    position: relative;
    left: -10pt;
    top: 50%;
    margin: 0;
    padding:0;
}



/*Map*/
.mapmainscr{
    background-image:url("http://jaydeepkhatri.000webhostapp.com/music/SL/gmap.jpg");
    background-size:100% 100%;
    background-repeat: no-repeat;
    display:flex;
    justify-content: center;
    align-items: center;
}
.mapforinp{
    margin:auto;
    text-align:center;
    padding:10px;
}
.mainmap{
    height:calc(100vh - 36px);
    width:100%;
    border:0;
    overflow:hidden;
    display:none;
    position:absolute;
    left:0;
    top:0;
    background-color:#fff;
    z-index:3;
}
.mapinp{
    padding:8px;
    font-size:18px;
    border:1px solid #aaa;
    border-radius:2px;
    width:300px;
}
.closemapbtn{
    width:100%;
    position:absolute;
    padding:5px;
    bottom:0;
    font-size:18px;
    left:0;
    border:0;
    background-color:#ff6666;
}



/*Music*/
.mainmusicb{
    bottom:0;

    position:fixed;
    width:100%;
}
.songname{
    width:50%;
    display:inline-block;
}
.songdur, .songrandom{
    width:20%;
    display:inline-block;
}
.songrandom{
    width:25%;
    display:inline-block;
    border:1px solid #000;
    padding:3px 0 3px 0;
    border-radius:5px;
    background-color:#ddd;
    box-shadow:0 3px 10px 0 rgba(0,0,0,0.6)
}
.songrandom:active{
    transform:translateY(4px);
}
progress[value] {
    -webkit-appearance: none;
    appearance: none;
    width: 95%;
    height: 7px;
}
progress[value]::-webkit-progress-value {
    background-color:#000;
    border-radius: 0;
    float:left;
}
progress::-webkit-progress-bar {
    background-color: #DDD;
}
.seekprogress{
    padding:8px;
}
.mbutton{
    padding:6px;
    border-radius:40%;
    border:1px solid #aaa;
    font-size:18px;
    display:inline-block;
}
.mbutton:focus{
    outline:none;
}
.tabmusic{
    padding:2px;
}
.mloading{
    position: fixed;
    top:25%;
    left:12.5%;
    width:70%;
    height:20%;
    border:2px solid black;
    align-items: center;
    padding-top:35px;
    font-size: 35px;
    border-radius:5px;
    box-shadow: 5px 5px black;
    background-color: #ddd;
    display:none;
}
.volumeslider {
    -webkit-appearance: none;
    width: 100px;
    height: 5px;
    background: #d3d3d3;
    outline: none;
    opacity: 0.7;
    border-radius:15px;
    top:5px;
}
.volumeslider::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 15px;
    height: 15px;
    background: #4CAF50;
    cursor: pointer;
    border-radius:50%;
}
.musicstic{
    display: inline-block;
    list-style-type: none;
    background-color: #00ffbf;
    padding: 12px;
    border-radius:9px;
    box-shadow:0 0 4px #000;
}
.musicbars{
    padding:5px;
    bottom:0;
    position:relative;
}



/*Phone*/
.keymtable{
    position: fixed;
    bottom:0;
    height: 65%;
    border-top:1px solid #aaa;
}
.keyntable{
    font-size: 32px;
    vertical-align: middle;
}
.keyatable{
    font-size:12px;
    opacity:0.8;
}
.inputnumber{
    font-size:40px;
    font-family: "Barlow", sans-serif;
    position: fixed;
    bottom:67%;
    width:100%;
    border:none;
    background-color:#eee;
    text-align:center;
}
.phonecall{
    border-radius: 50%;
    height:20px;
    width:20px;
    border:2px solid #ddd;
}
.phonekeypad{
    transition:0.1s;
}
.phonekeypad:hover, .phonekeypad:focus, .phonekeypad:active{
    background-color:#ddd;
}
.phoneico{
    display: inline-block;
    border-radius: 50%;
    box-shadow: 0px 0px 2px #888;
    padding: 0.35em 0.25em;
}




/*Photo Editor*/
.iemimg{
    border-radius: 0;
}
.iemimg:hover {
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
}
div.imgHere{
    width: 95%;
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    margin-bottom: 25px;
    margin:0 auto;
    padding:10px;
    box-sizing: border-box;
}
div.container {
    text-align: center;
    padding:-5px;
}
#name{
    color:#aaa;
    text-transform:uppercase ;
}
#blink{
    color:#000;
    animation: blink 0.9s  1s infinite forwards;
    display: inline-block;
    transform: rotateZ(90deg);
}
@keyframes blink{
    0%{opacity: 0;}
    50%{opacity: 1;}
    100%{opacity: 0;}
}
.styleControl{
    padding:0;
    text-align:center;
    transform:translateY(-20px);
}
.iedefslidecontainer{
  display:none;
}
select{
    padding:8px;
    border-radius:4px;
    border:1px solid #ddd;
    opacity:0.9;
    font-size:18px;
    background-color:#f2f2f2;
}
.slider {
    -webkit-appearance: none;
    width: 80%;
    height: 12px;
    background: #d3d3d3;
    outline: none;
    opacity: 0.7;
    -webkit-transition: .2s;
    transition: opacity .2s;
}
.slider:hover {
    opacity: 1;
}
.slider::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 20px;
    height: 20px;
    border-radius: 35%;
    background: #0f97f9;
}
.slider::-moz-range-thumb {
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: #0f97f9;
}
.ietabs li{
    display:inline ;
}
.iebortab{
    padding:5px;
    color:#fff;
    border-radius:5px;
    cursor:default;
    display: inline-block;
    margin-bottom: 5px;
}
.ier{
    background:#F44336;
}
.ieb{
    background:#0f97f9;
}
.ieg{
    background:#4CAF50;    
}
.iey{
    background:#FF9800;    
}
.ieborstab{
    background:#F2f2f2;
    padding:5px;
    color:#aaa;
    cursor: default;
    border-radius:5px;
    display: inline-block;
    margin-bottom: 5px;
}
.dot{
    border-style:dotted;        
}
.dash{
    border-style:dashed;      
}
.double{
    border-style:double; 
}
.solid{
    border-style:solid;
}
.inset{
    border-style:inset;
}
.iewrapper{
    display: grid;
    grid-template-columns: auto auto auto;

}
.iegrid{
    padding:10px;
    font-size:20px;
    border:1px solid #ddd;
    text-align: center;
}




/*Settings*/
.seticosiz{
    border:2px solid #ddd;
    border-radius:5px;
    background-color:#ddd;
}
#seticobtn2{
    background-color:#aabac2;
}
.powerbutton{
    padding:10px;
    border:0;
    background: linear-gradient(30deg, #000, #555);
    box-shadow: 0 0 10px #f00;
    color:#f33;
    border-radius:13px;
}
.powerbutton:active{
    transform: translateY(4px);
}


/*SoloLearn*/
.ifsololearn{
    width:100%;
    height:calc(100vh - 44px);
}


/*Stop Watch*/
.cldevbtn{
    padding:8px;
    border-radius:4px;
    border:1px solid #ddd;
    opacity:0.9;
    font-size:18px;
    margin-bottom: 8px;
    background-color:#f2f2f2;
}
.cldevbtn:active{
    transform: translateY(5px);
    box-shadow:0 0 #737373;
}



/*Terminal*/
#materminal{
    overflow:scroll;
    /*height:200px;*/
}
.terminal{
    background-color:#000;
    color:#0c0;
    font-size:20px;
    padding:5px 5px 28px 5px;
    font-family: 'VT323', monospace;
}
.terminaltext{
    bottom:0;
    width:65%;
    left:20%;
    border:0;
    position:absolute;
    padding:5px;
    font-size:18px;
    background-color:#393; 
    border-radius:0;
    color:#ddd;
    box-sizing: border-box;
}
.sendtermmsg{
    bottom:0;
    width:15%;
    right:0;
    border:0;
    position:absolute;
    padding:5px;
    font-size:18px;
    background-color:#363; 
    border-radius:0 3px 3px 0;
    color:#ddd;
    box-sizing: border-box;
}
.closetermbtn{
    bottom:0;
    width:20%;
    left:0;
    border:0;
    position:absolute;
    padding:5px;
    font-size:18px;
    background-color:#363; 
    border-radius:3px 0 0 3px;
    color:#ddd;
    box-sizing: border-box;
}



/*TextEditor*/
.texteditbutton{
    border-radius:10%;
    padding:6px 6px;
    margin-bottom:3px;
    border:2px solid #ddd;
}
.tebarlow{
    font-family:'Barlow', sans-serif;
}
.tebaloobhaijaan{
    font-family:'Baloo Bhaijaan', cursive;
}
.tecaveat{
    font-family:'Caveat', cursive;
}
.teindieflower{
    font-family:'Indie Flower', cursive;
}
.temonoton{
    font-family:'Monoton', cursive;
}
.tepattaya{
    font-family:'Pattaya', sans-serif;
}
.tesatisfy{
    font-family:'Satisfy', cursive;
}
.teshadowsintolight{
    font-family:'Shadows Into Light', cursive;
}
.tespicyrice{
    font-family:'Spicy Rice', cursive;
}



/*Themes*/
.themcolo{
    width:20px;
    padding:20px;
    margin-top:5px;
    display: inline-block;
    border-radius:50%;
    cursor:default;
    transition:0.1s;
}
.themcolo:hover{
    box-shadow:0 0 5px #000;
}
.themcolo1{
    background-color: #ff691f;
}
.themcolo2{
    background-color: #fab81e;
}
.themcolo3{
    background-color: #7fdbb6;
}
.themcolo4{
    background-color: #19cf86;
}
.themcolo5{
    background-color: #91d2fa;
}
.themcolo6{
    background-color: #1b95e0;
}
.themcolo7{
    background-color: #abb8c2;
}
.themcolo8{
    background-color: #e81c4f;
}
.themcolo9{
    background-color: #f58ea8;
}
.themcolo10{
    background-color: #981ceb;
}


/*Unit Converter*/
.unitccon{
    height: calc(100vh - 32px);
    overflow:scroll;
}
.unitconlist{
    width:90%;
    border-radius:3px;
    background-color: #211;
    color:#ddd;
    padding:8px;
    text-align: center;
    font-size: 24px;
    margin-bottom: 5px;
    cursor:default;
}

/*Videos*/
.vidiframe{
    width:95%;
    height:270px;
    border:1px solid #333;
}
.videolist{
    padding:10px;
}
.videoinputuser{
    padding:8px;
    font-size:18px;
    border:1px solid #aaa;
    border-radius:2px;
}
.videoitem{
    background-color:#ddf;
    padding:10px;
    margin-top:10px;
    cursor:default;
}


/*So you scrolled in CSS section also😂😂*/
