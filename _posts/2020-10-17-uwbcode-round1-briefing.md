---
layout: post
title: "Ranking for UWBCode Round 1"
date: 2020-10-17 12:00:00
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
var countDownDate = new Date("Oct 23, 2020 10:00:00 PDT").getTime();

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
    document.getElementById("clk").innerHTML = "ROUND 2 STARTED ON HACKERRANK!";
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
        <div class="d-inline-block">UWBCode Round 2 starts in</div> <br>
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

The UWBCode Round 1 ended at 10:00AM this morning, October 17, 2020. UWBCode Round 2 will be hosted on HackerRank on Friday, Oct. 23 at 10:00AM PDT. **Register for UWBCode Round 2** <a href="https://www.hackerrank.com/uwbcode2020-round2" class="ext-link">here</a>.<br>
Thanks to all contestants who participated in this round. You still can still submit your solution after the end of the contest; However, no score will be added to the Leaderboard. 

Our top participants for this round:

1. ashwinkbanwari
2. mshang_
3. Twangybeast
4. benhunter
5. syaniv
6. qiujames
7. 2018UCP1472
8. mansisinha1609
9. mrjohnfishcher
10. jkuang7


The first successful solution of the contest was submitted at minute 14 by **mahimajeslani26** (#30) for A-HIndex. **mshang_** (#2) had the first solution for B-ServiceCuts, C-SynapticSignals, and D-AsteroidX and became the first contestant who got at perfect score at minute 602. The first accepted solution for E-ValidParentheses belongs to **sanikapol** (#3). 

The winner of this round is ashwinkbanwari who got a perfect score with the least amount of time, with a time of 4:20:38!


Congrats! 

Cheers, 
UWBCode Team

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






