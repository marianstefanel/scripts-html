# scripts-html
script-uri html

SCRIPT 1 - ANTI F12
------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
 
<script language="JavaScript">

//////////F12 disable code////////////////////////
    document.onkeypress = function (event) {
        event = (event || window.event);
        if (event.keyCode == 123) {
           //alert('No F-12');
            return false;
        }
    }
    document.onmousedown = function (event) {
        event = (event || window.event);
        if (event.keyCode == 123) {
            //alert('No F-keys');
            return false;
        }
    }
document.onkeydown = function (event) {
        event = (event || window.event);
        if (event.keyCode == 123) {
            //alert('No F-keys');
            return false;
        }
    }
/////////////////////end///////////////////////
</script>

-------------------------------------------------------------------------------------
----------------------------------------------------------------------------

Script #2 - ANTI ALT+C
 <script>
    /*function check(e)
    {
    alert(e.keyCode);
    }*/
    document.onkeydown = function(e) {
            if (e.ctrlKey && (e.keyCode === 67 || e.keyCode === 86 || e.keyCode === 85 || e.keyCode === 117)) {//Alt+c, Alt+v will also be disabled sadly.
            }
            return false;
    };
    </script>
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------


SCRIPT 3# ANTI CLICK DREAPTA
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
<!-- START SCRIPT ANTI CLICK DREAPTA -->
<script language=Javascript1.2>
    function ejs_nodroit() { ; 
    return(false); } document.oncontextmenu = ejs_nodroit; 
</script> 
<!-- END SCRIPT ANTI CLICK DREAPTA -->
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

Script Audio #4 
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
 <!--audio script-->
 <audio autoplay="" loop="" id="player">
		 <source src="music.mp3">
		 <script>
		var audio = document.currentScript.parentElement;
		audio.volume = 0.17;
		</script>
		 </audio>
 <!--audio script-->

-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

<!-- script-uri -->
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/feather-icons/4.7.3/feather.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
<script src="js/scripts.js"></script>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
