﻿# Coming Soon: The “Text Messenger” skill, for Alexa.  

This skill is closely related to the <a href='https://beckyricha.github.io/alexa-gmail.html'>"My Email" skill</a>, but has fewer features and is designed to let you send and receive simple text messages using a Google Gmail account and your voice, instead of a smart phone.  This skill cannot read messages that were sent to your cell phone number, unless your carrier has a way to forward them to Gmail.  Figuring that out is beyond the scope of these instructions, as this is designed for people who don't use a cell phone to send text messages. Like the My Email skill, this is designed for people with minimal interest in technology, or other limitations making it difficult to use phones and tablets.  Specifically, for those who can't or don't want to use a cell phone, but have some people they can only reach reliably via text, this skill can help bridge the gap using Alexa.  My plan is to follow it with instructions for using IFTTT to notify the user by turning on a small light when a new text message is received.

You will start by asking Text Messenger to check your messages, or to send a message. Once a message is read, you can reply, erase it, or go to the next or previous message.  When sending, you can say it all at once - "Ask Text Messenger to text Bob I'll be late" - or just say "send a message" and let Alexa walk you through it.

In order to use the skill, you (or the person you are setting this up for) will need a Google Gmail account.  If you don't have one, click here to set one up.

Once you have a GMail account, you need a filter that tells GMail how to recognize something as a text, so it will be used by this skill, but not mixed in with your email inbox.  I found the addresses used by major US wireless carriers, and set up a small program that can tell GMail to mark these with the label "Texts."  To do this automatically, click here.  To add any I left out, after you run the script, go to your Gmail settings (the icon that looks like a little gear near the top of the Gmail page), and then click "filters and blocked addresses."  You will see the filter there, and can click "edit" to open it and add your carrier, following the pattern of the others in the "from" box.  

Replies can be sent to anyone who texts you, but this skill can also send text messages directly to your contacts if they are set up in a specific way.  The easiest way is to let Alexa add a contact based on a text they send you.  Most carriers will allow your contacts to send a text to your Gmail address instead of a phone number to get you started.  When Alexa reads the message, just say "add this to my contacts" and you will have it for later use.

To add a contact manually, you will need to know what email address can be used to send texts to the person's phone.  You will need to know their wireless carrier and mobile phone number to add this.  One way to look this up is here.  The number format varies, but usually for US numbers is +1 followed by all 10 digits, with no () or - included.  You may need to try a couple of times to make sure your contact's number works right.  Once you have the email address, you can create a new contact or add this to an existing one.  In either case, add the email address and give it the label "texts."  More help is here, but what it doesn't say is how to add your own email label.  If you are using Chrome on a computer, you will see email options to choose "home," "work," or "other."  Select other, and then click the word "other" again to type over it with the word "texts."

If you want to find out when the skill becomes available, go to my <a href='http://email-skill.blogspot.com/p/forum.html'>blogger forums</a> page, select "announcements," and subscribe.

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-89762317-3', 'auto');
  ga('send', 'pageview');

</script>
