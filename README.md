# The-beginnig-of-Javascript-Adventure-Story
Get whole boxex in same class name under same roof with set a height as widths of boxes

<html>
.........
  <body>
    <div class="container-fluid">
      <div class="row">
         <div class="col-lg-2 bg-success" id="cate_left">
		       <div class="cate_box"></div>
		       <div class="cate_box"></div>
		       <div class="cate_box"></div>
	      </div>
        
        <!-- ......................  -->
        
        <div class="col-lg-2 bg-success" id="cate_right">
		       <div class="cate_box"></div>
		       <div class="cate_box"></div>
		       <div class="cate_box"></div>
	      </div>
        
      </div>
    </div>
  </body>  
.........
  
  <script type="text/javascript">
    
     var cate_box = document.querySelectorAll(".cate_box"); //get each div which called  "cate_box" as class name
   
     for(var i=0;i<cate_box.length;i++){
	      cate_box[i].style.height = cate_box[0].offsetWidth+"px"; 
     }
                                         
     //get number of div called "cate_box" : cate_box.length
     //get width of once div called "cate_box" : cate_box[0].offsetWidth+"px";
     //set height to any div called "cate_box" : cate_box[0].style.height = "200px(randomly)";                                      
  </script>
  
</html>
