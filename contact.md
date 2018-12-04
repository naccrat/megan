---
title: Contact
date: 2018-12-03 17:24:00 -0700
layout: page
preview: ''
tags: []
permalink: "/contact/"

---
    <div class="contact-form">

    	<form method="post" action="https://formspree.io/megannacc@gmail.com" id="contact-form">

    		<div class="contact-form__item">

			<label class="contact-form__label">Email Address *</label>

			<input type="text" name="email" placeholder="Your email address..." class="contact-form__input">

		</div>

		<div class="contact-form__item">

			<label class="contact-form__label">Name *</label>

			<input type="text" name="name" placeholder="Your name..." class="contact-form__input">

		</div>

		<div class="contact-form__item">

			<label class="contact-form__label">Message *</label>

			<textarea name="message" placeholder="Your message..." class="contact-form__textarea"></textarea>

		</div>

		<input type="hidden" name="_next" value="/thanks">

		<input type="hidden" name="_subject" value="Contact form submission">

		<input type="text" name="_gotcha" style="display: none;" class="contact-form__gotcha" val="">

		<div class="contact-form__item">

			<input type="submit" value="Send your message" class="button button--large">

		</div>

	</form>

</div>