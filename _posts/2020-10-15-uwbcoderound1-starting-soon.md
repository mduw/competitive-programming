---
layout: post
title: "UWBCode Round 1 is starting soon!"
date: 2020-10-15 12:00:00
background: '/img/uwbcode2020/code_bg.png'
published: true
categories: [UWBCode2020, Announcement, Fall2020, AllenInstitute]

exturl_AllenInstitute: https://alleninstitute.org/what-we-do/brain-science/
exturl_uwb: https://www.uwb.edu
exturl_uwbacm: https://uwbacm.com
exturl_gwc: https://www.instagram.com/girlswhocode__uwb/?igshid=lmenj5wiuyo
exturl_regisform: http://bit.ly/join-uwbcode20
---
<!-- Display the countdown timer in an element -->
<script>
// Set the date we're counting down to
var countDownDate = new Date("Oct 16, 2020 10:00:00 PDT").getTime();

// Update the count down every 1 second
var interval = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="clk"
  document.getElementById("clk").innerHTML = days + " days : " + hours + " hours : "
  + minutes + " minutes : " + seconds + " seconds ";

  // If the count down is finished, write some text 
  if (distance < 0) {
    clearInterval(interval);
    document.getElementById("clk").innerHTML = "ROUND 1 STARTED ON HACKERRANK!";
  }
}, 1000);
</script>
<style>
    .clk-bg {
    background-color: dodgerblue;
    color: white; 
    font-size: 22px; 
    text-align: center;
    padding: 4px 4px;
}
</style>
<div class="container mb-4 col-md-8 clk-bg">
        <div class="d-inline-block">Round 1 starts in</div> <br>
        <b><div class="d-inline-block" id="clk"></div></b>
</div>
<div class="d-flex center">
        <a class="align-self-center col-md-2 d-inline-block zoom" target="blank" href="{{page.exturl_uwb}}">
            <img class="img-fluid" src="/img/uwbcode2020/uwb_logo.png" alt="UWB logo">     
        </a>
        <a class="align-self-center col-md-2 d-inline-block zoom" target="blank" href="{{page.exturl_uwbacm}}">
            <img class="img-fluid" src="/img/uwbcode2020/acm-large-logo.jpg" alt="UWB ACM logo">
        </a>
        <a class="align-self-center col-md-5 col-mt-3 d-inline-block zoom" target="blank" href="{{page.exturl_AllenInstitute}}">
            <img class="img-fluid" src="/img/uwbcode2020/AI_Brain_Science_Logo.png"
                alt="Allen Institute for Brain Science logo">
        </a>
        <a class="align-self-center col-md-2 d-inline-block zoom" target="blank" href="{{page.exturl_gwc}}">
            <img class="img-fluid rounded" src="/img/uwbcode2020/gwc.jpg" alt="Girls Who Code logo">
        </a>
</div>

---

Hello contestants, 
 
UWBCode ROUND 1 is starting in less than 24 hours! We are so excited to “see” everyone on HackerRank tomorrow!<br>
**Contest time**: 10:00 AM PDT, Friday Oct. 16 - 10:00 AM PDT, Saturday Oct. 17<br>
**Contest link**: <a class="ext-link" target="blank" href="https://www.hackerrank.com/uwbcode2020-round1">click here</a>
 
**Please note that**:
<ul>
    <li>Round 1 is only open for submissions in 24 hours. The contest ends at 10:00AM on Saturday, October 17.</li>
    <li>You must solve at least 1 challenge of this round to stay in Group 1. Otherwise, Group 2.</li>
    <li>Contestants in Group 1 and Group 2 still can compete in this round.</li>
</ul>
For new contestants, by the contest rules, you will compete in Group 2, don’t forget to sign up for Round 1 on HackerRank (link above). This is where you will see the questions and submit your code. Contest moderators are available to help with questions via Discord. You can submit your solution anytime within 24 hours; However, we highly recommend early submissions. 
  
Final standings will be announced on our contest website 2 hours after the end of this round on Saturday, October 17 at 10:00 AM.
 
If you have any questions about or during the contest, please contact us:<br>
**Website:** <a class="ext-link" href="https://competitiveprog.uwbacm.com/" target="blank">https://competitiveprog.uwbacm.com/</a><br>
**Email:** <a class="ext-link" href="mailto:uwbacm@uw.edu">uwbacm@uw.edu</a>
 
Good luck and have fun!
 
Cheers, <br>
**UWBCode Team**

---

<code>&ast;&ast;</code>*Group 1: completed the registration form + solved at least 1 challenge*<br>

<code>&ast;&ast;</code>*Group 2: not qualified for Group 1/ registered but did not compete in the Qualification Round/ compete in Qualification Round but did not register.*<br>

##### Schedule

| Open || Round | | Submission accepted for... |
|-----------------||---------------------| |----------|
| Oct. 09 10:00AM || Qualification Round | | 72 hours |
| Oct. 16 10:00AM || Round 1             | | 24 hours |
| Oct. 23 10:00AM || Round 2             | | 24 hours |
| Nov. 20 2 :00PM || Final Round         | | 4 hours  |

*All times in PDT

**Stay tuned on the contest page for updates** [<span style="color: blue">UWBCode 2020</span>]({{ '/blog/uwbcode2020.html' | relative_url}})






