meo
===

DU for Thomson/Technicolor
Firmware 10.2.1.D

===

1 - Abrir a consola de javascript no browser.

===

2 - Na ‘Console’ inserir o seguinte:

2.0- TG784n:

var user = "Debug";
var hash2 = "91cd28f3d8d3a503e9839caaa2929123";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();

===

2.1- TG799:

var user = "microuser";
var hash2 = "bd739b58aea3a4278d11bff06496a38f";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();

===

2.2- TG799vn:

var user = "Debug";
var hash2 = "082d7ff2a82ff89c3f9c5b2356144357";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();

===

2.3- TG787:

var user = "Debug";
var hash2 = "1019a97d050c3ef42997740ee54731bf";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();

===

2.4- TG784n v3:

var user = "Debug";
var hash2 = "276da5030a939d29642637f279629770";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();

===

2.5- Para outras versões:

var user = "Debug";
var hash2 = "f2bb79a855558478357aa3ef778ffa1a";

var HA2 = MD5("GET" + ":" + uri);
document.getElementById("user").value = user;
document.getElementById("hidepw").value = MD5(hash2 + ":" + nonce +":" + "00000001" + ":" + "xyz" + ":" + qop + ":" + HA2);
document.authform.submit();
