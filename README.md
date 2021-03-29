# deneme2<html>
<head>
<title>Java Script 8</title>
</head>

<body>
<br><br><br><br><br><br><br><br>
<center>
    <script type="text/javascript">
	
        var renk=prompt("Renk","Bir renk giriniz");
            switch(renk)
                {
				
            case "kırmızı":document.bgColor="red";break;
            case "mavi":document.bgColor="blue";break;	
            case "sarı":document.bgColor="yellow";break;	
            case "yeşil":document.bgColor="green";break;
            case "gri":document.bgColor="grey";break;
            case "pembe":document.bgColor="pink";break;	
            case "siyah":document.bgColor="#000000";break;	
            case "kahverengi":document.bgColor="brown";break;	
            case "gümüş":document.bgColor="#f0f0fa";break; 
            case "beyaz":document.bgColor="#ffffff";break;
            default:document.bgColor="white";alert("Bu renk tanımlı değil");
			
                }

        var isim, soyisim;
		
            isim=prompt("Adınız","Adınızı yazınız");
            soyisim=prompt("Soyadınız","Soyadınızı yazınız");
			
                document.write("Merhaba <font color='#ffffff'>",isim," ",soyisim,"</font><br><br><br>");

        var parola="abc123";
        var parolagir=prompt("Parola","Parolayı giriniz")
            if(parola==parolagir)
                {document.write("Tebrikler parola doğru <br><br><br>");}
            else
                {document.write("Maalesef parola yanlış <br><br><br>");}
			 

        var sayi, karesi;
        sayi=prompt("Sayı","Bir sayı giriniz");
        karesi=sayi*sayi;
                document.write(sayi,"'in karesi",karesi,"'tir. <br><br><br>");

        var gun;
        gun=prompt("Gün","Bugün günlerden ne?(Lütfen küçük harf kullanın.)");
            if(gun=="cumartesi" || gun=="pazar")
                {document.write("bugün",gun,"olduğuna göre haftasonundayız.<br>İYİ TATİLLER. <br><br><br>");}
            else
                {document.write("bugün cumartesi da pazar olmadığına göre haftaiçindeyiz.<br><br><br>İYİ ÇALIŞMALAR.<br><br><br>");}


                    function kabul()
                {
            alert("İçeri girebilirsiniz");
                }

                    function ret()
                {
	        alert("İçeri giremezsiniz");
                }


        var yas=prompt("Yaş","Yaşınızı giriniz");
		
            if(yas>=18)
                {
	                kabul();
	
                }
            else
                {
	                ret();
                }

        var gun=prompt("Gün","1-7 arası bir sayı girin");
            switch(gun)
                {
				
	        case "1":
	            document.write("Pazartesi <br><br><br>");
	        break;
	        case "2":
	            document.write("Salı <br><br><br>");
	        break;
	        case "3":
	            document.write("Çarşamba <br><br><br>");
	        break;
	        case "4":
	            document.write("Perşembe <br><br><br>");
	        break;
	        case "5":
	            document.write("Cuma <br><br><br>");
	        break;
	        case "6":
	            document.write("Cumartesi <br><br><br>");
	        break;
	        case "7":
	            document.write("Pazar <br><br><br>");
	        break;
	        default:
	            document.write("Böyle bir gün yok <br><br><br>");
	
                }


                    function carpim(a,b)
                {
                            return a*b;
                }

        var x=prompt("Sayı","1.Sayıyı giriniz");
        var y=prompt("Sayı","2.Sayıyı giriniz");
        var z;
                            z=carpim(x,y);
                document.write(x,"*",y,"=",z);

    </script>
</center>
</body>
</html>
