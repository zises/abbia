---
layout: pages
permalink: /form/
title: Contact
header_img: img_46.jpg
header_img_mobile: img_46.jpg

---

<h1 class="is-uppercase is-size-1"><span>Contact Us:</span> Give us a call</h1>

We have a supply of cocoa beans available for sample. Please shoot us a note, or give us a call, and we will get you as much as you need to test. We are taking orders for delivery late this year, with shipment expected to be in November 2018. 

{% contentfor section2 %}

<form action="https://formspree.io/zises@jigoro.org" method="POST">
>                    <label>Name</label> <input type="text" name="_name" placeholder="Name" class="form-control"><br>
>                    <label>Email Address</label> <input type="email" name="_replyto" placeholder="email@domain.com" class="form-control"><br>
>                    <label>Phone Number</label>
>                    <input type="tel" name="_telephone" class="form-control" placeholder="xxx-xxx-xxxx"><br>
                    <label>Message</label>
                    <input type="text" name="_message" class="form-control" rows="6" placeholder="Your message here"><br>
                    <input type="hidden" name="save" value="contact">
                    <input type="submit" class="btn btn-default" value="Submit"></button>
                <input type="hidden" name="_subject" value="New submission!">
                <input type="hidden" name="_next" value="{{ site.github.url }}">
                <input type="text" name="_gotcha" style="display:none">
    </form>

{% endcontentfor %}

