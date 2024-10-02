---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======
Hi!
I am *Pouya Sadeghi*, a computer engineering B.Sc. student at the 
[Department of ECE](https://ece.ut.ac.ir/en/ece){:target="_blank"} at the [University of Tehran](https://ut.ac.ir/en){:target="_blank"}.
I have the pleasure of working with [Azadeh Shakery](https://ece.ut.ac.ir/en/~shakery){:target="_blank"} and
[Yadollah Yaghoobzadeh](https://yyaghoobzadeh.github.io/){:target="_blank"} on various research projects in the field of Natural Language Processing (NLP),
Deep Learning (DL) and Explainable AI (XAI).


My primary research interest lies in the area of
- Natural Language Processing (NLP)
- AI Safety and Ethics
- Trustworthy AI
- Explainable AI (XAI)
- Formal methods for AI systems and Probabilistic Verification


News
======

- **2024.08**: I joined **Fatima Fellow** as a fellow, working on *Multilingual Multicultural Red Teaming of LLMs*.

- **2024.08**: I joined **Singapore Management University (SMU)** as a Visiting Research Student, working on *Formal Methods for Safe and Trustworthy Probabilistic Systems*.

- **2024.03**: Awarded the _Gold Medal_ for achieving **1st place** at the **28th Scientific Olympiad of University Students of Iran** (Computer Science branch).

- **2024.03**: Our paper, "[uTeBC-NLP at SemEval-2024 Task 9: Can LLMs be Lateral Thinkers?](https://aclanthology.org/2024.semeval-1.251/)," along with two other papers, has been accepted to [SemEval@NAACL 2024](https://semeval.github.io/SemEval2024/).

- **2024.02**: Our paper, "[Benchmarking Large Language Models for Persian: A Preliminary Study Focusing on ChatGPT](https://aclanthology.org/2024.lrec-main.197/)," has been accepted for presentation at [LREC-CoLing 2024](https://lrec-coling-2024.org/).

- **2022.10**: Ranked **2nd** at the University of Tehran, Computer Engineering, School of ECE.


Timeline
======

.timeline {
  position: relative;
  width: 800px;
  margin: 0 auto;
  margin-top: 20px;
  padding: 1em 0;
  list-style-type: none;
}

.timeline:before {
  position: absolute;
  left: 50%;
  top: 0;
  content: ' ';
  display: block;
  width: 6px;
  height: 100%;
  margin-left: -3px;
  background: rgb(80,80,80);
  background: -moz-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(30,87,153,1)), color-stop(100%,rgba(125,185,232,1)));
  background: -webkit-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -o-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -ms-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: linear-gradient(to bottom, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);

  z-index: 5;
}

.timeline li {
  padding: 1em 0;
}

.timeline li:after {
  content: "";
  display: block;
  height: 0;
  clear: both;
  visibility: hidden;
}

.direction-l {
  position: relative;
  width: 370px;
  float: left;
  text-align: right;
}

.direction-r {
  position: relative;
  width: 370px;
  float: right;
}

.flag-wrapper {
  position: relative;
  display: inline-block;

  text-align: center;
}

.flag {
  position: relative;
  display: inline;
  background: rgb(248,248,248);
  padding: 6px 10px;
  border-radius: 5px;

  font-weight: 600;
  text-align: left;
}

.direction-l .flag {
  -webkit-box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  -moz-box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
}

.direction-r .flag {
  -webkit-box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  -moz-box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
}

.direction-l .flag:before,
.direction-r .flag:before {
  position: absolute;
  top: 50%;
  right: -40px;
  content: ' ';
  display: block;
  width: 12px;
  height: 12px;
  margin-top: -10px;
  background: #fff;
  border-radius: 10px;
  border: 4px solid rgb(30, 174, 219);
  z-index: 10;
}

.direction-r .flag:before {
  left: -40px;
}

.direction-l .flag:after {
  content: "";
  position: absolute;
  left: 100%;
  top: 50%;
  height: 0;
  width: 0;
  margin-top: -8px;
  border: solid transparent;
  border-left-color: rgb(248,248,248);
  border-width: 8px;
  pointer-events: none;
}

.direction-r .flag:after {
  content: "";
  position: absolute;
  right: 100%;
  top: 50%;
  height: 0;
  width: 0;
  margin-top: -8px;
  border: solid transparent;
  border-right-color: rgb(248,248,248);
  border-width: 8px;
  pointer-events: none;
}

.time-wrapper {
  display: inline;

  line-height: 1em;
  font-size: 0.66666em;
  color: rgb(30, 174, 219);
  vertical-align: middle;
}

.direction-l .time-wrapper {
  float: left;
}

.direction-r .time-wrapper {
  float: right;
}

.time {
  display: inline-block;
  padding: 4px 6px;
  background: rgb(248,248,248);
}

.desc {
  margin: 1em 0.75em 0 0;
  font-size: 0.77777em;
  /* font-style: italic; */
  line-height: 1.5em;
}

.direction-r .desc {
  margin: 1em 0 0 0.75em;
}

/* ================ Timeline Media Queries ================ */

@media screen and (max-width: 1000px) {
  .timeline {
    width: 640px;
  }

  .direction-l {
    position: relative;
    width: 290px;
    float: left;
    text-align: right;
  }

  .direction-r {
    position: relative;
    width: 290px;
    float: right;
  }
}

@media screen and (max-width: 800px) {
  .timeline {
    width: 620px;
  }

  .direction-l {
    position: relative;
    width: 280px;
    float: left;
    text-align: right;
  }

  .direction-r {
    position: relative;
    width: 280px;
    float: right;
  }
}

@media screen and (max-width: 660px) {

  .timeline {
    width: 100%;
    padding: 4em 0 1em 0;
  }

  .timeline li {
    padding: 2em 0;
  }

  .direction-l,
  .direction-r {
    float: none;
    width: 100%;

    text-align: center;
  }

  .flag-wrapper {
    text-align: center;
  }

  .flag {
    background: rgb(255,255,255);
    z-index: 15;
  }

  .direction-l .flag:before,
  .direction-r .flag:before {
    position: absolute;
    top: -30px;
    left: 50%;
    content: ' ';
    display: block;
    width: 12px;
    height: 12px;
    margin-left: -9px;
    background: #fff;
    border-radius: 10px;
    border: 4px solid rgb(255,80,80);
    z-index: 10;
  }

  .direction-l .flag:after,
  .direction-r .flag:after {
    content: "";
    position: absolute;
    left: 50%;
    top: -8px;
    height: 0;
    width: 0;
    margin-left: -8px;
    border: solid transparent;
    border-bottom-color: rgb(255,255,255);
    border-width: 8px;
    pointer-events: none;
  }

  .time-wrapper {
    display: block;
    position: relative;
    margin: 4px 0 0 0;
    z-index: 14;
  }

  .direction-l .time-wrapper {
    float: none;
  }

  .direction-r .time-wrapper {
    float: none;
  }

  .desc {
    position: relative;
    margin: 1em 0 0 0;
    padding: 1em;
    background: rgb(245,245,245);
    -webkit-box-shadow: 0 0 1px rgba(0,0,0,0.20);
    -moz-box-shadow: 0 0 1px rgba(0,0,0,0.20);
    box-shadow: 0 0 1px rgba(0,0,0,0.20);

    z-index: 15;
  }

  .direction-l .desc,
  .direction-r .desc {
    position: relative;
    margin: 1em 1em 0 1em;
    padding: 1em;

    z-index: 15;
  }
}

@media screen and (min-width: 400px ?? max-width: 660px) {
  .direction-l .desc,
  .direction-r .desc {
    margin: 1em 4em 0 4em;
  }
}

<div class="docs-section">

  <!-- The Timeline -->
  <ul class="timeline">
    
    <li>
      <div class="direction-r">
        <div class="flag-wrapper">
          <span class="flag">Fatima Fellow</span>
          <span class="time-wrapper"><span class="time">2024.08</span></span>
        </div>
        <div class="desc"><b>Fellow</b> <br/> Working on Multilingual Multicultural Red Teaming of LLMs.</div>
      </div>
    </li>

    <li>
      <div class="direction-l">
        <div class="flag-wrapper">
          <span class="flag">Singapore Management University (SMU)</span>
          <span class="time-wrapper"><span class="time">2024.08</span></span>
        </div>
        <div class="desc"><b>Visiting Research Student</b> <br/> Working on Formal Methods for Safe and Trustworthy Probabilistic Systems under the supervision of <a href="https://djordjezikelic.github.io" target="_blank">Prof. Djordje Zikelic</a>.</div>
      </div>
    </li>

    <li>
      <div class="direction-r">
        <div class="flag-wrapper">
          <span class="flag">28th Scientific Olympiad of University Students of Iran</span>
          <span class="time-wrapper"><span class="time">2024.03</span></span>
        </div>
        <div class="desc"><b>Gold Medal</b> <br/> Achieved 1st place in the Computer Science branch.</div>
      </div>
    </li>

    <li>
      <div class="direction-l">
        <div class="flag-wrapper">
          <span class="flag">SemEval@NAACL 2024</span>
          <span class="time-wrapper"><span class="time">2024.03</span></span>
        </div>
        <div class="desc"><b>Paper Accepted</b> <br/> "uTeBC-NLP at SemEval-2024 Task 9: Can LLMs be Lateral Thinkers?" <a href="https://aclanthology.org/2024.semeval-1.251/" target="_blank">(Read here)</a>.</div>
      </div>
    </li>

    <li>
      <div class="direction-r">
        <div class="flag-wrapper">
          <span class="flag">LREC-CoLing 2024</span>
          <span class="time-wrapper"><span class="time">2024.02</span></span>
        </div>
        <div class="desc"><b>Paper Accepted</b> <br/> "Benchmarking Large Language Models for Persian: A Preliminary Study Focusing on ChatGPT." <a href="https://aclanthology.org/2024.lrec-main.197/" target="_blank">(Read here)</a>.</div>
      </div>
    </li>

    <li>
      <div class="direction-l">
        <div class="flag-wrapper">
          <span class="flag">University of Tehran</span>
          <span class="time-wrapper"><span class="time">2022.10</span></span>
        </div>
        <div class="desc"><b>Ranked 2nd</b> <br/> In Computer Engineering, School of ECE.</div>
      </div>
    </li>

    <li>
      <div class="direction-r">
        <div class="flag-wrapper">
          <span class="flag">University of Tehran</span>
          <span class="time-wrapper"><span class="time">2020.09</span></span>
        </div>
        <div class="desc"><b>Bachelor of Science</b> <br/> Started undergraduate studies in Computer Engineering.</div>
      </div>
    </li>

    <li>
      <div class="direction-l">
        <div class="flag-wrapper">
          <span class="flag">Iranian Highschoolers University Entry Exam</span>
          <span class="time-wrapper"><span class="time">2020.07</span></span>
        </div>
        <div class="desc"><b>Ranked 49th</b> <br/> In the national Konkour exam.</div>
      </div>
    </li>

  </ul>
</div>