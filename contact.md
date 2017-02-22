---
layout: page
title: Contact Us
permalink: /contact/
---
<div class="bordered white bg-medium top bottom" id="web">
	<div class="container text-center pt20 pb20">
		<h1 class="m0">Let's Talk!</h1>
	</div>
</div>
<div class="bordered dark top bottom">
	<form action="https://formspree.io/josh@cirkut.net" class="container pt25 pb25" method="POST">
		<div class="col-1-1 text-center">
			<p class="lead pt5 pb20">Give us a bit of information on your project and we'll be in touch!</p>
		</div>
		<div style="clear:both;"></div>
		<!-- Name -->
		<div class="col-1-2">
			<label for="name">Name<span class="required">*</span></label>
			<input type="text" name="name" required aria-required="required">
		</div>
		<!-- Email -->
		<div class="col-1-2">
			<label for="_replyto">Email<span class="required">*</span></label>
			<input type="email" name="_replyto" required aria-required="required">
		</div>
		<div style="clear:both;"></div>
		<!-- Message -->
		<div class="col-1-1">
			<label for="message">Message<span class="required">*</span></label>
			<textarea name="message" id="message" rows="10" required aria-required="required"></textarea>
		</div>
		<div style="clear:both;"></div>
		<!-- Launch Date -->
		<div class="col-1-2">
			<label for="end_date">Ideal Completion Date<span class="required">*</span></label>
			<input type="date" name="launch_date" required aria-required="required" />
		</div>
		<!-- How Did You Hear About Us? -->
        <div class="col-1-2">
			<label for="heard_of_us">How did you hear about us?</label>
			<input type="text" name="heard_of_us">
        </div>
        <div style="clear:both;"></div>
		<input type="hidden" name="_subject" value="Cirkut Media Contact Form Submission">
		<input type="text" name="_gotcha" style="display:none">
        <div class="col-1-1">
			<input type="submit" class="btn large" value="Send">
		</div>
	</form>
</div>
<div style="clear:both;"></div>