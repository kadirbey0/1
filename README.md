# Merhaba Hoşgeldiniz
<html>
<head>
<style>
body {
    -webkit-animation: colorchange 60s infinite; 
    animation: colorchange 60s infinite;
}
@-webkit-keyframes colorchange {
     0%  {background: #33FFF3;}
    25%  {background: #78281F;}
    50%  {background: #117A65;}
    75%  {background: #DC7633;}
    100% {background: #9B59B6;}
}
@keyframes colorchange {
     0%  {background: #33FFF3;}
    25%  {background: #78281F;}
    50%  {background: #117A65;}
    75%  {background: #DC7633;}
    100% {background: #9B59B6;}
}   
</style>
</head>
<body>
</body>
</html>

<body>
  <h1>Bir 1 Haftalık Bakımdayız</h1>
  <nav>
    <ul>
      <li><a href="/">AnaSayfa</a></li>
      <li><a href="/events">Etkinlikler</a></li>
     </ul>
  </nav>
  <article>
    <header>
    </header>
    <nav>
      <ul>
        <li><a href="#genel">Genel Bilgi</a></li>
        <li><a href="#diger">Diğer Bilgiler</a></li>
      </ul>
    </nav>
    <div>
      <section id="genel">
        <h2>Genel Bilgi</h2>
        <p>...daha...</p>
      </section>
      <section id="diger">
        <h2>Diğer Bilgiler</h2>
        <p>...daha...</p>
      </section>
    </div>
    <footer>
      <p><a href="?duzen">Düzenle</a> | <a href="?sil">Sil</a> | <a href="?incele">İncele</a></p>
    </footer>
  <footer>
<a href="http://www.ipadresi.net" title="ip adresi"><img src="http://in3.sitekodlari.com/ipadresi2.php" border="0" alt="ip adresi"></a> 
     
   
   <script language="JavaScript1.2">
function setcountup(theyear,themonth,theday){
yr=theyear;mo=themonth;da=theday
}
//////////CONFIGURE THE countup SCRIPT HERE//////////////////
//STEP 1: Configure the date to count up from, in the format year, month, day:
//This date should be less than today
setcountup(2009,04,25)
//STEP 2: Configure text to be attached to count up
var displaymessage="(her saniye büyüyoruz)"
//STEP 3: Configure the below 5 variables to set the width, height, background color, and text style of the countup area
var countupwidth='95%'
var countupheight='20px' //applicable only in NS4
var countupbgcolor='alt1'
var opentags='<span class="smallfont">'
var closetags='</span>'
//////////DO NOT EDIT PASS THIS LINE//////////////////
var montharray=new Array("Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec")
var crosscount=''
function start_countup(){
if (document.layers)
document.countupnsmain.visibility="show"
else if (document.all||document.getElementById)
crosscount=document.getElementById&&!document.all?document.getElementById("countupie") : countupie
countup()
}
if (document.all||document.getElementById)
document.write('<span id="countupie" style="width:'+countupwidth+'; background-color:'+countupbgcolor+'"></span>')
window.onload=start_countup
function countup(){
var today=new Date()
var todayy=today.getYear()
if (todayy < 1000)
todayy+=1900
var todaym=today.getMonth()
var todayd=today.getDate()
var todayh=today.getHours()
var todaymin=today.getMinutes()
var todaysec=today.getSeconds()
var todaystring=montharray[todaym]+" "+todayd+", "+todayy+" "+todayh+":"+todaymin+":"+todaysec
paststring=montharray[mo-1]+" "+da+", "+yr
dd=Date.parse(todaystring)-Date.parse(paststring)
dday=Math.floor(dd/(60*60*1000*24)*1)
dhour=Math.floor((dd%(60*60*1000*24))/(60*60*1000)*1)
dmin=Math.floor(((dd%(60*60*1000*24))%(60*60*1000))/(60*1000)*1)
dsec=Math.floor((((dd%(60*60*1000*24))%(60*60*1000))%(60*1000))/1000*1)
if (document.layers){
document.countupnsmain.document.countupnssub.document.write(opentags+dday+ " gün, "+dhour+" saat, "+dmin+" dakika ve "+dsec+" saniyedir sizlerleyiz... "+displaymessage+closetags)
document.countupnsmain.document.countupnssub.document.close()
}
else if (document.all||document.getElementById)
crosscount.innerHTML=opentags+dday+ " gün, "+dhour+" saat, "+dmin+" dakika ve "+dsec+" saniye "+displaymessage+closetags
setTimeout("countup()",1000)
}
</script> 
   
    <p><small>@2020Copyright</small></p>
  </footer>

