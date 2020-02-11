# de
tyske øvelser
Her kommer forskellige øvelser til tysk B
<H3>BISÆTNINGER - øvelse 1</H3>
    <P>Lav nedenstående sætninger om til bisætninger!<BR>Du skal IKKE sætte punktum efter sætningerne!</P>
    <FORM name=Indsaet action=""><BR>EKSEMPEL: <BR>Die Farbe ist zu hässlich. <BR>Ich finde, dass die Farbe zu hässlich ist <BR><BR>Sabine schläft nicht genug. <BR>Ich finde, dass <INPUT type=hidden value="Sabine nicht genug schläft" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=26 name=Tekst0> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Ich soll Salzstangen kaufen. <BR>Ich weiß, dass <INPUT type=hidden value="ich Salzstangen kaufen soll" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=27 name=Tekst1> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Ich muss um 8 Uhr in Kopenhagen sein. <BR>Ich glaube, dass <INPUT type=hidden value="ich um 8 Uhr in Kopenhagen sein muss" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=36 name=Tekst2> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Familie Müller lebt in Koblenz. <BR>Ich weiß nicht, ob <INPUT type=hidden value="Familie Müller in Koblenz lebt" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=30 name=Tekst3> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Sie wollen am Montag in den Zirkus gehen. <BR>Sie haben schon Karten gekauft, weil <INPUT type=hidden value="sie am Montag in den Zirkus gehen wollen" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=40 name=Tekst4> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Kann ich bei euch übernachten? <BR>Ich frage, ob <INPUT type=hidden value="ich bei euch übernachten kann" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=29 name=Tekst5> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Du musst viele Stunden warten. <BR>Es ist ganz sicher, dass <INPUT type=hidden value="du viele Stunden warten musst" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=29 name=Tekst6> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Karl ruft immer sehr laut. <BR>Ich finde, dass <INPUT type=hidden value="Karl immer sehr laut ruft" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=25 name=Tekst7> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Sie hat die Stelle bekommen. <BR>Ich bin froh, weil <INPUT type=hidden value="sie die Stelle bekommen hat" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=27 name=Tekst8> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR>Es regnete den ganzen Tag. <BR>Der Ausflug war schön, obwohl <INPUT type=hidden value="es den ganzen Tag regnete" name=RigtigtSvar> <INPUT style="BORDER-RIGHT: 1px solid; BORDER-TOP: 1px solid; BORDER-LEFT: 1px solid; BORDER-BOTTOM: 1px solid" size=25 name=Tekst9> <SPAN>&nbsp;&nbsp;&nbsp;</SPAN>
    <BR><BR></FORM>
    <FORM name=resultat action="">
    <P><INPUT style="FONT: 20px Wingdings; COLOR: green" onclick=Rettelse() type=button value=" ü " name=check> <SPAN id=smiley style="BORDER-RIGHT: 1px solid; PADDING-RIGHT: 3px; BORDER-TOP: 1px solid; PADDING-LEFT: 3px; BACKGROUND: #fffff0; VISIBILITY: hidden; PADDING-BOTTOM: 3px; BORDER-LEFT: 1px solid; PADDING-TOP: 3px; BORDER-BOTTOM: 1px solid; HEIGHT: 28px"></SPAN></P></FORM></TD></TR></TBODY></TABLE>
<BR><BR></FORM>
    <FORM name=resultat action="">
    <P><INPUT style="FONT: 20px Wingdings; COLOR: green" onclick=Rettelse() type=button value=" ü " name=check> <SPAN id=smiley style="BORDER-RIGHT: 1px solid; PADDING-RIGHT: 3px; BORDER-TOP: 1px solid; PADDING-LEFT: 3px; BACKGROUND: #fffff0; VISIBILITY: hidden; PADDING-BOTTOM: 3px; BORDER-LEFT: 1px solid; PADDING-TOP: 3px; BORDER-BOTTOM: 1px solid; HEIGHT: 28px"></SPAN></P></FORM></TD></TR></TBODY></TABLE>
    <SCRIPT type=text/javascript>
    var PPoint=0;
    var total="10"
    function Rettelse() {
    var e=0;
    PPoint=0;
    var tegn = document.getElementsByTagName("span");
    var inputs = document.getElementsByTagName("input");
       for (var i=0;i<inputs.length;i++)
            if ( inputs.item(i).type=="text")
            {
                      if (trim(inputs.item(i).value)==inputs.item(i-1).value)
                    {
                    (tegn.item(e)).style.fontFamily="Wingdings";
                    (tegn.item(e)).style.fontSize="20";
                    (tegn.item(e)).style.color="#008000";
                    (tegn.item(e)).innerHTML="\u00FC";
                    PPoint++;
                    }
                else if (inputs.item(i).value != "")
                    {
                    (tegn.item(e)).style.fontFamily="Wingdings";
                    (tegn.item(e)).style.fontSize="20";
                    (tegn.item(e)).style.color="#FF0000";
                    inputs.item(i).value="";(tegn.item(e)).innerHTML="\u00FB";
                    };
    e++;
     }
    PPoint=Math.round(100*PPoint/total)
    if (PPoint==100)	    	
     sml = "J"
    else  sml = "L"
    document.getElementById("smiley").style.visibility="visible";
    document.getElementById("smiley").innerHTML=  "<font face='Wingdings' size='5'>" + sml + "<\/font>";
    }
</BODY>
