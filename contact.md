---
title: Order Form
layout: page
permalink: "/contact/"

---
<form method="post" id="contact-form" action="/success" netlify>

<div class="form-group">

<label>Name *</label>
<input type="text" name="name" class="form-control">

</div>

<div class="form-group">
<label>Email Address *</label>
<input type="text" name="email" class="form-control">
</div>

<div class="form-group">
<label>Phone/Texting Number *</label>
<input type="text" name="phone" class="form-control">
</div>

<div class="form-group">
<label>I want to order… *</label>
<textarea name="message" class="form-control"></textarea>
</div>

<input type="submit" value="Place order" class="btn btn-primary">

</form>