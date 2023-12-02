<!-- Tunji Adetunji
<!-- CSC235.01
<!-- HomeWork:#2
<!-- Git-Hub: https://github.com/yourName/ypurHomeWork-->
-->

<!DOCTYPE html>
<html language>
<head>
<body>

<Script language="JavaScript">
<!--
var v = new Array(0,0,0,0);
var h = new Array(false,false,false,false,false); // false means not clickable.
var f = new Array(0,0,0,0,0,0,0);

function roll()
{
 f[1]=f[2]=f[3]=f[4]=f[5]=f[6]=0;
 for(var i=0;i<5;i++)
{
  if(!h[i]){
  d=document.getElementById("d"+1);
  v[i]=math.floor(6*math.random())+1;
  d.sc"pix/dice"+v[i]+" .gif";
  }
  f[v[i]]++;
}
    
}
function hold(i)
{
  d=document.getElementById("d"+i);
  h[i]=!h[i];
  if(h[i]) { d.src="pix/diceX"+v[i]+" .gif"; }
  else     { d.src="pix/diceX"+v[i]+" .gif"; }
}
function roll()
{
  d=document.getElementById("s"+1);
  d.innerHTML=f[i]*i;
}
//-->
</script>

<h1>Yahtzee </h1>
<div Class="a">
      <img id="d0" src="pix/dice0.gif">
      <img id="d1" src="pix/dice0.gif">
      <img id="d2" src="pix/dice0.gif">
      <img id="d3" src="pix/dice0.gif">
      <img id="d4" src="pix/dice0.gif"> </div>
<br><br>
<table class="t" >
<tr> <td class="a"> 1's </td>
<td id="s1" onMouseOver="scr(1);" onMouseOut="clr(1)" class="b" >  </td>
       <td class="c" rowspan="5"> <button class="b" onClick="roll()">Roll</button> </td> </tr>
<tr> <td class="a"> 2's </td> <td> <td class="b"> </td> </tr>
<tr> <td class="a"> 3's </td> <td> <td class="b"> </td> </tr>
<tr> <td class="a"> 4's </td> <td> <td class="b"> </td> </tr>
<tr> <td class="a"> 5's </td> <td> <td class="b"> </td> </tr>
<tr> <td class="a"> 6's </td> <td> <td class="b"> </td> </tr>
       <td class="c" rowspan="5" > <button class="c"> New game </button> </td> </tr>
<tr> <td class="a"> 3 of a kind </td> <td class="b"> </td> </tr>
<tr> <td class="a"> 4 of a kind </td> <td class="b"> </td> </tr>
<tr> <td class="a"> Yahtzee </td> <td class="b"> </td> </tr>
<tr> <td class="a"> Total </td> <td class="b"> </td> </tr>

</table>
</head>
</body>


 
    
        
