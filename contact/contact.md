---
layout: page
title: Contact
permalink: /contact/
comments: false
---

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
<script src="/js/validator.js"></script>

You have suggestions about improvements that could be made or just want to talk about something?
Then contact us! We are always happy to receive constructive criticism.

<div class="container-fluid">
  <form role="form"  data-toggle="validator" action="//formspree.io/copykatt@yandex.com" method="post">
    <div class="form-group has-feedback">
      <label for="inputName" class="control-label">Name</label>
      <input type="text" pattern="^([_A-z0-9 ]){3,20}" class="form-control" name="name" id="inputName" placeholder="Enter your name here"
      data-error="Please enter a name with 3-20 characters consiting only of letters, numbers, underscores or spaces." required>
      <span class="help-block">Between 3 and 20 characters. Letters, numbers, underscores or spaces.</span>
    </div>
    <div class="form-group has-feedback">
      <label for="inputSubject" class="control-label">Subject</label>
      <input type="text" data-minlength="6" class="form-control" name="subject" id="inputSubject" placeholder="What you want to discuss about"
      data-error="Please enter a subject with at least 6 characters" required>
      <span class="help-block with-errors">Minimum 6 characters.</span>
    </div>
    <div class="form-group has-feedback">
      <label for="inputEmail" class="control-label">Email</label>
      <input type="email" class="form-control" name="_replyto" id="inputEmail" placeholder="Your email" data-error="Please enter a valid email address." required>
      <div class="help-block with-errors"></div>
    </div>
    <div class="form-group">
      <label for="inputComment">Comment:</label>
      <textarea class="form-control" rows="5" maxlength="1000" name="comment" id="inputComment" placeholder="What exactly you want to tell us." required></textarea>
    </div>
    <div class="form-group">
    <button type="submit" class="btn btn-primary">Submit</button>
    </div>
    <input type="hidden" name="_subject" value="New submission!" />
    <input type="text" name="_gotcha" style="display:none" />
    <!-- <input type="hidden" name="_next" value="//tanukilabs.github.io/thanks/" /> -->
  </form>
</div>
