//不定宽高水平垂直居中
  //第一种方案
  .wrapper{
  			position:absolute;
  			top:50%;
  			left:50%;
  			z-index:3;
  			-webkit-transform:translate(-50%,50%);
  			border-radius:6px;
  			background:red;
  }
  <div class="wrapper">	</div>
  //第二种方案
  justify-content:center;//子元素水平
	box-pack:center;//子元素垂直居中
  display:-webkit-flex;
//固定宽高水平垂直居中
  .wrapper{
		width:500px;
		height:500px;
		position:absolute;
		left:50%;
		top:50%;
		margin-top:-250px;
		margin-left:-250px;
		background:red;
	}
	<div class="wrapper">	</div>
