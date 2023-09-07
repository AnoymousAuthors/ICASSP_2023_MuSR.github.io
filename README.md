# MuSR
<html>
	<head>
		<style>
			element.style {
				color: #8899a5;
				font-size: 12px;
			}
			p {
				margin-top: 0;
				margin-bottom: 1rem;
			}
			.col {
				flex-basis: 0;
				flex-grow: 1;
				max-width: 100%;
			}

			.text-center {
				text-align: center !important;
			}
			*, *::before, *::after {
				box-sizing: border-box;
			}
			@media (min-width: 576px)
				.container, .container-sm {
					max-width: 540px;
			}
			.container {
				width: 100%;
				padding-right: 15px;
				padding-left: 15px;
				margin-right: auto;
				margin-left: auto;
			}
			div {
				display: block;
			}
			.row {
				display: flex;
				flex-wrap: wrap;
				margin-right: -15px;
				margin-left: -15px;
			}
			.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col, .col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm, .col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md, .col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg, .col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl, .col-xl-auto {
				position: relative;
				width: 100%;
				padding-right: 15px;
				padding-left: 15px;
			}
			.img-fluid {
				max-width: 100%;
				height: auto;
			}
			img {
				vertical-align: middle;
				border-style: none;
			}
			img[Attributes Style] {
				width: 45%;
			}
			.embed-responsive {
				position: relative;
				display: block;
				width: 100%;
				padding: 0;
				overflow: hidden;
			}
			@media screen and (max-width: 42em)
				.btn {
					display: none;
					width: 100%;
					padding: 0.75rem;
					font-size: 0.9rem;
			}
			@media screen and (max-width: 42em)
				.site-footer {
					display: none;
					font-size: 0.9rem;
			}

		</style>
	</head>


	<body>
 		<br>
		<section>
			<div class="container">
				<div class="row">
					<div class="col-12 text-center">
						<h3>Demo</h3>
						<hr style="margin-top:0px">
						<br>
					</div>
				</div>
			</div> 
		</section>
  		<section>
			<div class="container">
				<div class="row">
					<div class="col-12 text-center">
						<h3>Figure 5-6</h3>
					</div>
				</div>
				<div class="row">
					<div class="col text-center">
						<img class="img-fluid" src="images/5-6/5-11_1.png" width="100%">
					</div>
					<div class="col text-center">
						<img class="img-fluid" src="images/5-6/5-11_2.png" width="100%">
					</div>
					<div class="col text-center">
						<img class="img-fluid" src="images/5-6/5-11_3.png" width="100%">
					</div>
				</div>
    				<div class="row">
					<div class="col text-center">
						<p class="text-justify; text-center"> (a) GT / real scene </p>
					</div>
					<div class="col text-center">
						<p class="text-justify; text-center"> (b) NeuralRecon </p>
					</div>
					<div class="col text-center">
						<p class="text-justify; text-center"> (c) Ours </p>
					</div>
				</div>
			</div>
		</section>
		<section>
			<div class="container">
				<div class="row">
					<div class="col-12 text-center">
						<h3>Figure 5-8</h3>
					</div>
				</div>
				<div class="row">
					<div class="col text-center">
						<img class="img-fluid" src="images/5-12/5-12_1.png" width="100%">
					</div>
					<div class="col text-center">
						<img class="img-fluid" src="images/5-12/5-12_2.png" width="100%">
					</div>
					<div class="col text-center">
						<img class="img-fluid" src="images/5-12/5-12_3.png" width="100%">
					</div>
				</div>
    				<div class="row">
					<div class="col text-center">
						<p class="text-justify; text-center"> (a) GT / real scene </p>
					</div>
					<div class="col text-center">
						<p class="text-justify; text-center"> (b) NeuralRecon </p>
					</div>
					<div class="col text-center">
						<p class="text-justify; text-center"> (c) Ours </p>
					</div>
				</div>
			</div>
		</section>
	</body>
</html>
