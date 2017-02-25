<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>三栏式布局</title>
	<style>
		.clearfix:after {
			content: ".";
			display: block;
			height: 0;
			clear: both;
			visibility: hidden;
			}
		.container{
			padding: 20px; 
			border:1px solid #999;
			background-color: #eee;
		}
		.column1{
			float: left;
			max-width:160px;
			min-width: 160px; 
			padding: 20px;
			border:1px solid #999;
			background-color: blue;
		}
		.team-logo{
			float: left;
		}
		.team p{
			float: right;
			margin: 0px;
			font-family: 18px;
			line-height: 18px;
		}
		.column2{
			float: right;
			max-width: 80px;
			min-width: 80px;
			padding: 20px;
			border:1px solid #999;
			background-color: green;
		}
		.column2 ul{
			padding:0px;
			margin: 0px;
			list-style-type: none;
		}
		.column2 li{
			margin-bottom: 20px;
		}
		.column3{
			margin: 0 140px 0 220px;
		}
		.column3-main{
			padding: 20px;
			border:1px solid #999;
			background-color: pink;
		}
		
	</style>
</head>
<body>
	<div class="container  clearfix">

		<!-- 团队名称 开始-->
		<section class="column1">
			<div class="team">
				<img src="logo.jpg" alt="team-logo" width="80px" height="80px" class="team-logo"/>
				<p>团队名称</p>
			</div>
		</section>
		<!-- 团队名称 结束 -->

		<!-- 团队成员 开始-->
		<section class="column2">
			<ul>
				<li><img src="logo.jpg" alt="member1" width="80px" height="80px"></li>
				<li><img src="logo.jpg" alt="member2" width="80px" height="80px"></li>
				<li><img src="logo.jpg" alt="member3" width="80px" height="80px"></li>
				<li><img src="logo.jpg" alt="member4" width="80px" height="80px"></li>
			</ul>
		</section>
		<!-- 团队成员 结束 -->

		<!-- 团队介绍 开始-->
		<section class="column3">
		    <div class="column3-main">
				<h3>团队介绍</h3>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi, libero, ab. Quae voluptatum ea voluptas! Culpa ea fugit, sint aliquam magnam numquam fugiat obcaecati earum. Quis inventore, dolorum eos ullam.
				</br>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo, eaque molestiae. Tenetur, maxime et cumque numquam nobis dolor, dolorem veniam nam aut eligendi perspiciatis exercitationem enim deserunt perferendis, dolore aperiam.
				</p>
			</div>
		</section>
		<!-- 团队介绍 结束 -->
	</div>
</body>
</html>
