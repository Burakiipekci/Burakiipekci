
## Hi there, I'm Burak  
<head>
    <title>JavaScript Dijital Saat</title>
    <link href="https://fonts.googleapis.com/css?family=Orbitron" rel="stylesheet" type="text/css"/>
 
    <style>
        .tabBlok
        {
            background-color:#57574f;
            border:solid 0px #FFA54F;
            border-radius:5px; -moz-border-radius:5px; -webkit-border-radius:5px;
            max-width:200px;
            width:100%;
            overflow:hidden;
            display:block;
        }
        .dijitalSaat
        {
            vertical-align:middle;
            font-family:Orbitron;
            font-size:40px;
            font-weight:normal;
            color:#FFF;
            padding:0 10px;
        }
        .saat
        {
            vertical-align:middle; 
            font-family:Orbitron;
            font-size:20px;
            font-weight:normal;
            color:#FFF;
        }
        .zemin{
            background-color:#F3F3F3;
            max-width:220px;
            width:100%;
            margin:0 auto;
            padding:20px;
        }
    </style>
</head>
 
<body onload="dijitalSaat();">
    <div class="zemin">
 
        <table class="tabBlok" align="center" cellspacing="0" cellpadding="0" border="0">
            <tr><td class="dijitalSaat" id="dt"></td> 
                <td>
                    <table cellpadding="0" cellspacing="0" border="0">
 
                        <tr><td class="saat" id="dt_saat">😴</td></tr>
 
                        <!-- SHOWING SECONDS. -->
                        <tr><td class="saat" id="dt_saniye"></td></tr>
                    </table>
                </td>
            </tr>
        </table>
    </div>
</body>
 
<script>
    // tarih oluşturma fonksiyonu
    function dijitalSaat() {
        var dt = new Date();    // DATE() ile yeni bir tarih nesnesi oluşturuldu.
        var saat = dt.getHours();
        var dakika = dt.getMinutes();
        var saniye = dt.getSeconds();
 
        dakika = Tik(dakika);
        saniye = Tik(saniye);
 
        document.getElementById('dt').innerHTML = saat + ":" + dakika;
        document.getElementById('dt_saniye').innerHTML = saniye;
 
        if (saat > 12) { 
            document.getElementById('dt_saat').innerHTML = '😊'; 
        }
        else { 
            document.getElementById('dc_hour').innerHTML = '😴'; 
        }
 
        // her 1 saniyede bir yenileme yapılıyor.
        var time
        time = setInterval('dijitalSaat()', 1000);
    }
 
    function Tik(tikDegeri) {
        if (tikDegeri < 10) {
            tikDegeri = "0" + tikDegeri;
        }
        return tikDegeri;
    }
</script>
</html>
 

- 🌱 I’m currently learning everything 🤣
- 👯 I’m looking to collaborate with other content creators
- 🥅 I like teamwork
- ⚡ I'm improving myself


### Connect with me:

[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

### Languages and Tools:


<img align="left" alt="Visual Studio " width="26px" src="https://image.flaticon.com/icons/png/512/74/74906.png" />
<img align="left" alt="Visual Studio " width="26px" src="https://image.flaticon.com/icons/png/512/906/906324.png" />
<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="26px" src="https://image.flaticon.com/icons/png/512/732/732190.png" />
<img align="left" alt="Java" width="26px" src="https://image.flaticon.com/icons/png/512/226/226777.png" />
<img align="left" alt="JavaScript" width="26px" src="https://image.flaticon.com/icons/png/512/29/29105.png" />
<img align="left" alt="React" width="26px" src="https://image.flaticon.com/icons/png/512/1126/1126012.png" />

<img align="left" alt="SQL" width="26px" src="https://image.flaticon.com/icons/png/512/2772/2772128.png" />
<img align="left" alt="MySQL" width="26px" src="https://image.flaticon.com/icons/png/512/1199/1199128.png" />
<br />
<br />

[twitter]: https://twitter.com/Burakiipekci
[instagram]: https://instagram.com/Burakiipekci
[linkedin]: https://linkedin.com/in/Burakiipekci
