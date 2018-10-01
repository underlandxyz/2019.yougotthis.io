---
layout: default
title: Schedule
---

<div class="w">
  <h1 class="title">Schedule</h1>
  <p>This schedule is incomplete, but we hope that by providing this ahead of time you can make plans around this event.</p>
  <ul class='t'>
    <li>
      <div class="time">09:30</div>
      <div class="info">
        <div class="c">
          <h2>Doors open</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">10:30</div>
      <div class="info">
        <div class="c">
          <h2>Welcome talk</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">10:15</div>
      <div class="info">
        <span class="type">Keynote</span>
        <div class="c">
          <h2>Perfectionism, Impostor Syndrome and Anxiety - Understanding your fears and learning to be kind to yourself</h2>
          <div class="desc">
            <p>Working in the tech industry can sometimes make us feel inferior. It is easy to start believing that everyone knows more, or finds the work easier. When we’re surrounded by so many clever people, how can we not start to judge ourselves against them and our work against theirs?</p>
            <p>Impostor syndrome - the belief that you don’t deserve to be where you are, and perfectionism - a need to work to impossibly high standards, are exhausting.</p>
            <p>Learn how to spot these destructive thought patterns in yourself, how to manage anxiety and procrastination and how to start being kinder to yourself, because you’re awesome and you deserve to be here.</p>
          </div>
        </div>
        <div class="s">
          <div class="img">
            <img src="/assets/img/speakers/jo.jpg" alt="Photo of Jo">
          </div>
          <div class="c">
            <h2>Jo Franchetti</h2>
            <p>Jo is a Web Developer Advocate for Samsung Internet who is passionate about VR, Web Bluetooth, PWAs and great CSS. She’s got 6 years experience as a front end developer and has worked in various parts of the tech industry from startups, agencies, charities to large organisations. She is also mentor and organiser at codebar.io where she is able to action her passion not only for teaching good use of the web but also for improving the diversity and inclusivity of the tech industry.</p>
          </div>
        </div>
      </div>
    </li>
    <li>
      <div class="time">11:35</div>
      <div class="info">
        <div class="c">
          <h2>Comfort break</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">13:25</div>
      <div class="info">
        <div class="c">
          <h2>Lunch</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">15:50</div>
      <div class="info">
        <div class="c">
          <h2>Comfort break</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">16:50</div>
      <div class="info">
        <span class="type">Keynote</span>
        <div class="c">
          <h2>The transformative power of junior developers</h2>
          <div class="desc">
            <p>How do you help junior developers succeed? How do you maintain your team’s productivity while building a culture of learning?</p>
            <p>Borrowing from interactions with hundreds of companies successfully integrating their first junior team members – companies like the FT, Telegraph, Deloitte, Tesco, and Santander – this 30-minute talk will give an overview of what works, and what doesn’t. We’ll focus on practical, easy-to-implement insights which will not only help you support your new developers’ success and growth, but enhance your team’s progress as a whole, making it a more fun and productive place to work.</p>
          </div>
        </div>
        <div class="s">
          <div class="img">
            <img src="/assets/img/speakers/sam.jpg" alt="Photo of Sam">
          </div>
          <div class="c">
            <h2>Sam Morgan</h2>
            <p>Sam is Head of Education at Makers. He’s trained and placed over 1,500 software engineers in London and around the world.</p>
          </div>
        </div>
      </div>
    </li>
    <li>
      <div class="time">17:25</div>
      <div class="info">
        <div class="c">
          <h2>Closing remarks</h2>
        </div>
      </div>
    </li>
    <li>
      <div class="time">17:45</div>
      <div class="info">
        <div class="c">
          <h2>End of conference</h2>
        </div>
      </div>
    </li>
  </ul>
</div>

<style>
h1.title {
  margin-bottom: 1rem;
}
.t {
  padding-left: 0;
  margin-left: 0;
  list-style: none;
}
.t li {
  background: #f5f5f5;
  border: 2px solid var(--white);
  margin-left: 0;
  display: grid;
  grid-template-columns: 100px auto;
  padding: 1em;
  margin: 2rem 0;
}
.t .time {
  font-size: 1.25em;
  font-weight: bold;
}
.t .type {
  background: var(--light);
  color: white;
  padding: 0.4em 0.75em;
  display: inline-block;
  margin-bottom: 1rem;
}
.t h2 {
  color: var(--dark);
  font-size: 1.25em;
}
.t .desc * {
  margin-top: 1em;
}
.t .s {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-bottom: 0;
  border-top: 1px solid var(--white);
  padding-top: 2em;
  margin-top: 2em;
}
.t .s * {
  margin-bottom: 0;
}
.t .s .img {
  min-width: 150px;
  max-width: 150px;
  margin-top: 5px;
}
.t .s img {
  width: 100%;
  border: 2px solid var(--white);
}
.t .s .c {
  padding-left: 1em;
}
.t .s .c h2 {
  margin-bottom: 1rem;
  font-size: 1.25em;
}
.t .s .c p {
  font-size: 0.8em;
}

@media screen and (max-width: 800px) {
  .t li {
    grid-template-columns: 1fr;
    grid-gap: 1em;
  }
  .t .s .img {
    min-width: 100px;
    max-width: 100px;
    margin-top: 0;
  }
}

@media screen and (max-width: 480px) {
  .t .s {
    display: block;
  }
  .t .s .c {
    padding-left: 0;
    margin-top: 1em;
  }
}
</style>