---

layout: page
permalink: /contact/
header: no

title: "Contact"
subheadline: 'Get in contact with the team'

---

Leave your message here and we will get in contact as soon as possible.

<form 
	name="ContactFrom" 
	method="POST" 
	id="contact-form" 
	class="contact-form" 
	data-netlify="true" 
	action="/contact/thanks/"
>
	<input type="hidden" name="subject" value="7T contact contact" />
	<p class="form-row">
		<label id="contact-form-name-label" for="contact-form-name" class="form-label">Name *</label>
		<input type="text" name="name" id="contact-form-name" 
			aria-labelledby="contact-form-name-label" class="form-input"/>
	</p>
	<p class="form-row">
		<label id="contact-form-email-label" for="contact-form-email" class="form-label">Email address *</label>
		<input type="email" name="email" id="contact-form-email" 
			aria-labelledby="contact-form-email-label" class="form-input" required/>
	</p>
	<p class="form-row">
		<label id="contact-form-message-label" for="contact-form-message" class="form-label">Message</label>
		<textarea name="message" id="contact-form-message" 
			aria-labelledby="contact-form-message-label" class="form-textarea" rows="2" required></textarea>
	</p>
	<p class="form-row"><div data-netlify-recaptcha="true" class="form-row"></div></p>
	<p class="hidden" style="visibility: hidden; height: 0;">
		<label id="contact-form-bot-label">Don't fill this out if you're human: <input name="" 
			aria-labelledby="contact-form-bot-label" /></label>
	</p>
	<p class="form-row form-submit">
		<button type="submit" class="button">Send</button>
	</p>
</form>