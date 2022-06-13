<script>
</script>

<main>
	<header class='topbar' aria-label="Intro Section">
		<h1>SAVVY TECH, LLC.</h1>
	</header>

	<div class="services">

	<div class="intro div-section">
		<div class="picture">
			<img src="https://static.wixstatic.com/media/2f3f25e96f1643c2b3543396ab016692.jpg/v1/fill/w_556,h_995,fp_0.50_0.50,q_85,usm_0.66_1.00_0.01,enc_auto/2f3f25e96f1643c2b3543396ab016692.jpg" alt="keyboard img"/>
		</div>
		<div class="paragraph">
			<h1>SAVVY TECH</h1>
			<h3>Your Satisfaction is Our Priority</h3>
			<p>Do you have something that needs fixing? Savvy Tech is here for all your repair needs. <br> When possible, we use original parts for repairs, so anything you bring to us will be returned to you in mint condition.<br> Feel free to pick up the phone with any questions you may have, we're invested in customer service and are always happy to help.</p>
		</div>
	</div>




		<h1 id="serve">OUR SERVICES</h1>

		<div class="div-section">
			<div class="paragraph">
				<h2>LAPTOP REPAIR</h2>
				<p>This is one of our most popular services for both new and returning clients, so appointments fill up fast. Feel free to reach out with any questions for our team, and make sure to book your slot today.</p>
			</div>
			<div class="picture">
				<img src="https://static.wixstatic.com/media/936c63273737da67239303dbf2bcd0bf.jpg/v1/fill/w_880,h_460,fp_0.50_0.50,q_85,usm_0.66_1.00_0.01,enc_auto/936c63273737da67239303dbf2bcd0bf.jpg" alt="keyboard img"/>
			</div>
		</div>

		<div class="div-section">
			<div class="picture">
				<img src="https://static.wixstatic.com/media/7ab5b2d2cbfb4c70a0b7be3cd488e0df.jpg/v1/fill/w_880,h_460,fp_0.50_0.50,q_85,usm_0.66_1.00_0.01,enc_auto/7ab5b2d2cbfb4c70a0b7be3cd488e0df.jpg" alt="keyboard img"/>
			</div>
			<div class="paragraph">
				<h2>CUSTOM REPAIR</h2>
				<p>Our expert technicians provide all the services you need with a dedication to quality and efficiency. When you book this service, like all of our others, we guarantee you'll be satisfied with the process and result.</p>
			</div>
		</div>

		<div class="div-section">
			<div class="paragraph">
				<h2>HARDWARE REPAIR</h2>
				<p>Savvy Tech is committed to making your life easier with convenient and comprehensive support when you need it most. Get in touch today to learn more about this service and all that we have to offer.</p>
			</div>
			<div class="picture">
				<img src="https://static.wixstatic.com/media/57d1fed6beee4982a729978553fb8ae2.jpg/v1/fill/w_880,h_460,fp_0.50_0.50,q_85,usm_0.66_1.00_0.01,enc_auto/57d1fed6beee4982a729978553fb8ae2.jpg" alt="keyboard img"/>
			</div>
		</div>

		<div class="div-section">
			<div class="paragraph">
				<h2>CONTACT US</h2>

		</div>
	</div>
</main>

<style>
	.topbar {
  position: relative;
  display: flex;
  justify-content: center;
  width: 100%;
  overflow: hidden;
  padding-top: 0;
	}
	.intro {
		background-color: #eaf5f7;
		width: 100%;
	}
	#serve {
		width: 100%;
	}
	 .services {
		display: flex;
		flex-wrap: wrap;
	}
	.div-section:nth-child(1), .div-section:nth-last-child(3){
		display: flex;
		flex-direction: column-reverse;
	}
	.paragraph {
		padding: 1rem 0;
		margin: 0 1rem;
	}
	.picture {
		height: 400px;
		width: 100%;
	}
	.picture > img {
		width: 100%;
		height: 100%;
	}
	@media (min-width:1000px) {
		.intro {
			display: inherit;
			columns: 2;
		}
		.services > div {
			columns: 2;
		}
		.picture {
			height: 600px;
		}
		.div-section:nth-child(1), .div-section:nth-last-child(3) {
		display: inherit;
		flex-direction: unset;
		columns: 2;
	}
	}
</style>