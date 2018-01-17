/** ************************************************** **/
 ** on window load or document load call this function **
****** -------------- ********
------	svgGrpah();  ---------
****** -------------- ********

example:: 
<script type="text/javascript">
      window.onload = svgGrpah;
</script>

or if you are calling multiple functions in onload
<script type="text/javascript">
      window.onload = function(){
	svgGrpah();
      };
</script>