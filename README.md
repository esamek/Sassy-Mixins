Sassy-Mixins
============

Very convenient sass mixins

	@mixin size($width,$height){
	  width:$width;
		height:$height;
	}
	
	@mixin position($positionProperty:static,$top:auto,$right:auto,$bottom:auto,$left:auto){
		position:$positionProperty;
		top:$top;
		left:$left;
		right:$right;
		bottom:$bottom;
	}
	
	@mixin fontCond(){
		font-family:$sansCondFontFamily;
	}
	@mixin fontSans(){
		font-family:$sansFontFamily;
	}
	@mixin fontSerif(){
		font-family:$serifFontFamily;
	}


