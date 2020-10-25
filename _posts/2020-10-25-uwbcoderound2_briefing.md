---
layout: post
title: "Rankings for  UWBCode Round 2"
date: 2020-10-25 12:00:00
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
var countDownDate = new Date("Nov 20, 2020 14:00:00 PDT").getTime();

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
    document.getElementById("clk").innerHTML = "FINAL ROUND ENDED!";
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
        <div class="d-inline-block">Final Round starts in</div> <br>
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

The UWBCode Round 2 just ended at 10:00AM this morning. Thanks to all contestants who participated in this round. Here are some insights:

**Our top participants for this round**
1. ulzgoroth 
2. Twangybeast
3. ashwinkbanwari
4. victoreis1
5. syaniv
6. 2016B5A70471G
7. mshang_
8. mansisinha1609 
9. qiujames
10. jkuang7

**Twangybeast (#2)** was the first who solved B-MaxReward at minute 374 and got a perfect score at minute 374. The first solution of the contest was submitted at minute 11 by **victoreis1 (#4)** who also submitted the first solution for A-KAmount. and C-VisualCoding and got a perfect score at minute 1073. The first solution for D-LemonLeMons was submitted by **mshang_ (#7)**.  

**ulzgoroth (#1)**, **ashwinkbanwari (#3)**, and **syaniv (#5)** finished this round with a perfect score at minute 1714, 1956, and 2151, respectively.

The accumulated Leaderboard is live <a href="https://competitiveprog.uwbacm.com/blog/uwbcode_leaderboard.htm" target="blank" style="color: blue">here</a>

**UWBCode Final Round** will be hosted on HackerRank on **Friday, Nov. 20 at 2:00PM – 6:00PM PDT**. <br>
Register: <a href="https://www.hackerrank.com/uwbcode2020-final" target="blank" style="color: blue"> https://www.hackerrank.com/uwbcode2020-final </a>

Congrats!
 
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






