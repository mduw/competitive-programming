---
layout: post
title: "Rankings for the UWBCode Qualification Round"
date: 2020-10-12 13:00:00
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

Thanks to all contestants who participated in the Qualification Round. You can submit your solution after the end of the contest; However, no score will be added to the Leaderboard. We are excited to announce that 68/206 contestants are eligible to compete in Group 1. If you are not in Group 1, you still can compete in Group 2 for upcoming rounds. 
#### Top 3 of Group 1 :
1. victoreis1 
2. mshang_
3. qiujames
…<br>
#### Top 3 of group 2: 
1. yipcubed
2. austin_arlitt
3. mahimajeslani26
…<br>

The first successful solution of the contest was submitted at minute 5 by leonli3three for EZ-DNA (#18). victoreis1 had the first solution for A-EndingDigits, C-CovidFlights, and D-Compensation and became the first contestant to get aperfect score at minute 1937 (#1). The first accepted solution for B-Minima belongs to quijames (#3).

UWBCode Round 1 will be hosted on HackerRank on Friday, Oct. 16 at 10:00AM PDT. The contest link will be updated on our contest website by Wednesday.
Congrats! 

Cheers, 

---

**UWBCode Team**

&ast;&ast;*Group 1: completed the registration form + solved at least 1 challenge*<br>
&ast;&ast;*Group 2: not qualified for Group 1/ registered but did not compete in the Qualification Round/ compete in Qualification Round but did not register.*<br>

##### Schedule

| Open || Round | | Submission accepted for... |
|-----------------||---------------------| |----------|
| Oct. 09 10:00AM || Qualification Round | | 72 hours |
| Oct. 16 10:00AM || Round 1             | | 24 hours |
| Oct. 23 10:00AM || Round 2             | | 24 hours |
| Nov. 20 2 :00PM || Final Round         | | 4 hours  |

*All times in PDT

**Stay tuned on the contest page for updates** [<span style="color: blue">UWBCode 2020</span>]({{ '/blog/uwbcode2020.html' | relative_url}})






