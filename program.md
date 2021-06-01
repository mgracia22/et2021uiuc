---
layout: default
title: Scientific Program
day1_1:
  title: Welcome/ET status
  desc: >-
    some long text with a link
    [google](https://google.com)
day1_2:
  title: School II
day1_3:
  title: School III
day1_4:
  title: School IV
day1_5:
  title: School V
day4_1:
  title: some tutorial
  desc: >-
    Some list:
      * first
      * second
      * third
day2_1:
  title: School I
day2_2:
  title: School II
day2_3:
  title: School III
day2_4:
  title: School IV
day2_5:
  title: School V

day3_1:
  title: School I
day3_2:
  title: School II
day3_3:
  title: School III
day3_4:
  title: School IV
day3_5:
  title: School V

day4_1:
  title: School I
day4_2:
  title: School II
day4_3:
  title: School III
day4_4:
  title: School IV
day4_5:
  title: School V

day5_1:
  title: Topic I
day5_2:
  title: Topic II
day5_3:
  title: Lighting III
day5_4:
  title: Lighting IV
day5_5:
  title: Future of the ET

---

<div class="col-xs-12">
<h1>Program</h1>

TBD
</div>

<div class="col-xs-6">
<h2>Time zones</h2>

<div class="tzinfo" markdown="1">

|                 |  start  |  end     |
|-----------------|---------|----------|
| US Central time | 9:00 AM |  1:20 PM |
| US Pacific time | 7:00 AM | 11:20 AM |
| Central EU time | 4:00 PM |  8:20 PM |
| [Other time zones](https://www.timeanddate.com/worldclock/converter.html?iso=20210726T140000&p1=33&p2=240&p3=64&p4=538&p5=176&p6=196&p7=51&p8=78&p9=213) |  |

</div> <!--tzinfo-->
</div>


<div class="col-xs-12" markdown="1">
## Schedule overview

All times US Central time.

<!-- add schedule entries to the yaml data in the preamble.
     right now you will have to manually add a rowspan attribute and comment
     out some columns for multi-hour entries.
     This templating *could* be all done in Liquid but seems to not be worth
     the effort, though might become interesting if the entries become more
     complex, eg aquire an author and Zoom link entry or so.
-->

<table class="schedule">
<tr><th> start </th><th> end </th>
<th> Day 1 </th>
<th> Day 2 </th>
<th> Day 3 </th>
<th> Day 4 </th>
<th> Day 5 </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td markdown="span" rowspan=1><b>{{page.day1_1.title}}</b></td>
  <td markdown="span"><b>{{page.day1_2.title}}</b></td>
  <td markdown="span"><b>{{page.day1_3.title}}</b></td>
  <td markdown="span"><b>{{page.day1_4.title}}</b></td>
  <td markdown="span"><b>{{page.day1_5.title}}</b></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td markdown="span"><b>{{page.day2_1.title}}</b></td>
  <td markdown="span"><b>{{page.day2_2.title}}</b></td>
  <td markdown="span"><b>{{page.day2_3.title}}</b></td>
  <td markdown="span"><b>{{page.day2_4.title}}</b></td>
  <td markdown="span"><b>{{page.day2_5.title}}</b></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td markdown="span"><b>{{page.day3_1.title}}</b></td>
  <td markdown="span"><b>{{page.day3_2.title}}</b></td>
  <td markdown="span"><b>{{page.day3_3.title}}</b></td>
  <td markdown="span"><b>{{page.day3_4.title}}</b></td>
  <td markdown="span"><b>{{page.day3_5.title}}</b></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
  <td>break</td>
  <td>break</td>
  <td>break</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td markdown="span"><b>{{page.day4_1.title}}</b></td>
  <td markdown="span"><b>{{page.day4_2.title}}</b></td>
  <td markdown="span"><b>{{page.day4_3.title}}</b></td>
  <td markdown="span"><b>{{page.day4_4.title}}</b></td>
  <td markdown="span"><b>{{page.day4_5.title}}</b></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td markdown="span"><b>{{page.day5_1.title}}</b></td>
  <td markdown="span"><b>{{page.day5_2.title}}</b></td>
  <td markdown="span"><b>{{page.day5_3.title}}</b></td>
  <td markdown="span"><b>{{page.day5_4.title}}</b></td>
  <td markdown="span"><b>{{page.day5_5.title}}</b></td>
</tr>
</table>
</div>

<div class="col-xs-12">
<h2>Per-day schedules</h2>

All times US Central time.

<div class="row">

<div class="col-sm-6">
<h3>Day 1: Numerical Relativity</h3>

<table class="day-schedule">
<tr><th> start </th><th> end </th> <th> </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td rowspan=1><div markdown="1"><b>{{page.day1_1.title}}</b><br>{{page.day1_1.desc}}
  </div></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td><div markdown="7"><b><a href="{{site.lectures[7].url}}">{{site.lectures[7].title}}</a></b><br>{{site.lectures[7].author}}
  </div></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td><div markdown="7"><b><a href="{{site.lectures[7].url}}">{{site.lectures[7].title}}</a></b><br>{{site.lectures[7].author}}
  </div></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td><div markdown="10"><b><a href="{{site.lectures[10].url}}">{{site.lectures[10].title}}</a></b><br>{{site.lectures[10].author}}
  </div></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td><div markdown="9"><b><a href="{{site.lectures[9].url}}">{{site.lectures[9].title}}</a></b><br>{{site.lectures[9].author}}
  </div></td>
</tr>
</table>
</div>

<div class="col-sm-6">
<h3>Day 2: Initial data</h3>

<table class="day-schedule">
<tr><th> start </th><th> end </th> <th>  </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td><div markdown="8"><b><a href="{{site.lectures[8].url}}">{{site.lectures[8].title}}</a></b><br>{{site.lectures[8].author}}
  </div></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td><div markdown="12"><b><a href="{{site.lectures[12].url}}">{{site.lectures[12].title}}</a></b><br>{{site.lectures[12].author}}
  </div></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td><div markdown="3"><b><a href="{{site.lectures[3].url}}">{{site.lectures[3].title}}</a></b><br>{{site.lectures[3].author}}
  </div></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td><div markdown="3"><b><a href="{{site.lectures[3].url}}">{{site.lectures[3].title}}</a></b><br>{{site.lectures[3].author}}
  </div></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td><div markdown="1"><b>{{page.day2_5.title}}</b><br>{{page.day2_5.desc}}
  </div></td>
</tr>
</table>
</div>

<div class="col-sm-6">
<h3>Day 3: Relativistic (magneto)-hydrodynamics</h3>

<table class="day-schedule">
<tr><th> start </th><th> end </th> <th>  </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td><div markdown="1"><b>{{page.day2_1.title}}</b><br>{{page.day2_1.desc}}
  </div></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td><div markdown="1"><b>{{page.day2_2.title}}</b><br>{{page.day2_2.desc}}
  </div></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td><div markdown="1"><b>{{page.day2_3.title}}</b><br>{{page.day2_3.desc}}
  </div></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td><div markdown="1"><b><a href="{{site.lectures[0].url}}">{{site.lectures[0].title}}</a></$
  </div></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td><div markdown="1"><b>{{page.day2_5.title}}</b><br>{{page.day2_5.desc}}
  </div></td>
</tr>
</table>
</div>

<div class="col-sm-6">
<h3>Day 4: Thorn writting</h3>

<table class="day-schedule">
<tr><th> start </th><th> end </th> <th>  </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td><div markdown="1"><b>{{page.day2_1.title}}</b><br>{{page.day2_1.desc}}
  </div></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td><div markdown="1"><b>{{page.day2_2.title}}</b><br>{{page.day2_2.desc}}
  </div></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td><div markdown="1"><b>{{page.day2_3.title}}</b><br>{{page.day2_3.desc}}
  </div></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td><div markdown="1"><b><a href="{{site.lectures[0].url}}">{{site.lectures[0].title}}</a></$
  </div></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td><div markdown="1"><b>{{page.day2_5.title}}</b><br>{{page.day2_5.desc}}
  </div></td>
</tr>
</table>
</div>

<div class="col-sm-6">
<h3>Day 5: Data analysis</h3>

<table class="day-schedule">
<tr><th> start </th><th> end </th> <th>  </th>
</tr>
<tr><td>9:00 AM</td><td>9:45 AM</td>
  <td><div markdown="1"><b>{{page.day2_1.title}}</b><br>{{page.day2_1.desc}}
  </div></td>
</tr>
<tr><td>9:50 AM</td><td>10:35 AM</td>
  <td><div markdown="1"><b>{{page.day2_2.title}}</b><br>{{page.day2_2.desc}}
  </div></td>
</tr>
<tr><td>10:40 AM</td><td>10:25 AM</td>
  <td><div markdown="1"><b>{{page.day2_3.title}}</b><br>{{page.day2_3.desc}}
  </div></td>
</tr>
<tr><td>11:25 AM</td><td>11:45 AM</td>
  <td>break</td>
</tr>
<tr><td>11:45 AM</td><td>12:30 PM</td>
  <td><div markdown="1"><b><a href="{{site.lectures[0].url}}">{{site.lectures[0].title}}</a></$
  </div></td>
</tr>
<tr><td>12:35 AM</td><td>1:20 PM</td>
  <td><div markdown="1"><b>{{page.day2_5.title}}</b><br>{{page.day2_5.desc}}
  </div></td>
</tr>
</table>
</div>

</div> <!-- row -->
</div> <!-- per-day schedule -->

