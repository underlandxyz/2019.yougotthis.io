---
layout: default
title: Inclusion Programme
---

<div class="content w">
  <h1 class="title">Inclusion Programme</h1>
  <p>We're committed to running an accessible, inclusive and safe conference for everyone. We're working with <a href="http://mykindof.tech/">My Kind of Tech</a> to add extra ✨ to our inclusion programme.</p>
  <p>Our inclusion programme includes tickets for those in under-represented groups in tech. This includes, but isn't limited to: LGBTQIA+ people, people of colour, women, non-binary people, and those with disabilities. Our application process should only take 5 minutes, and doesn't ask you to disclose any information which is sensitive. If you have questions about it, please <a href="mailto:yougotthis@underland.xyz">get in touch</a>.</p>
  <div class="tickets">
    <div class="boxes">
      <div class="box">
        <div class="top">
          <h2>Ticket-only scholarships</h2>
          <p>We are committed to give away 20% of our available tickets to this kind of scholarship.</p>
          <ul>
            <li>Completely free ticket</li>
            <li>Reasonable childcare costs</li>
            <li>You still have to cover the cost of travel (and accommodation if there is any).</li>
          </ul>
        </div>
        <div class="link">
          <a href="#">Apply for ticket-only scholarship soon</a>
        </div>
      </div>
      <div class="box">
        <div class="top">
          <h2>Full scholarships</h2>
          <p>Full scholarships are available thanks to our sponsors and community supporters, notably the amazing folks at mLab who have made it a core part of their sponsorship.</p>
          <ul>
            <li>Completely free ticket</li>
            <li>Reasonable childcare costs</li>
            <li>Accommodation & travel covered in advance</li>
            <li>Stipend to cover related costs</li>
            <li>Only available for people travelling from the UK</li>
          </ul>
        </div>
        <div class="link">
          <a href="#">Apply for full scholarship soon</a>
        </div>
      </div>
    </div>
  </div>
  <div class="boxes">
    <div class="box">
      <h2>Code of Conduct</h2>
      <p>Our event has a <a href="/conduct">Code of Conduct</a> which will be enforced. All attendees, sponsors, team members and vendors will be expected to abide by it.</p>
    </div>
    <div class="box">
      <h2>Venue</h2>
      <p>Our <a href="/venue">venue</a> is accessible to those with wheelchairs and those who would prefer to not use stairs. It also has gender neutral toilets on both floors.</p>
    </div>
    <div class="box">
      <h2>Closed Captioning</h2>
      <p>We've arranged for talks to be transcribed live, which will be displayed on screens in the hall. The transcripts will also be available after the event.</p>
    </div>
    <div class="box">
      <h2>Care Team</h2>
      <p>We have a dedicated care team who exist to support any attendees who need support during the event. This is provided by My Kind Of.</p>
    </div>
    <div class="box">
      <h2>Food</h2>
      <p>All food will be vegan, with good options for anyone who has more specific dietary requirements. This will extend throughout the event.</p>
    </div>
    <div class="box">
      <h2>Speakers</h2>
      <p>Our diverse set of speakers were selected by blind review of their proposed talks. They are being paid, with 1-to-1 mentoring sessions.</p>
    </div>
  </div>
  <p>The Underland and My Kind Of teams hope this will make the event comfortable for everyone. If there's something more you think we could be doing, please <a href="mailto:yougotthis@underland.xyz">get in touch</a>.</p>
</div>

<style>
.tickets {
  background: var(--sky);
  padding: 1em;
  margin-bottom: 4em;
  margin-top: 4em;
}
.boxes {
  display: grid;
  grid-gap: 2em;
  grid-template-columns: 1fr 1fr;
}
.tickets .box {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.tickets .link {
  margin-top: 1em;
  margin-bottom: 0;
}
.tickets .top,
.tickets .boxes {
  margin-bottom: 0;
}
.tickets a {
  padding: 0.25em 0.75em;
  background:var(--green);
  color: white;
  border: 2px solid var(--green-d);
  text-decoration: none;
  font-weight: bold;
  text-transform: uppercase; 
  font-size: 0.9em;
}

@media screen and (max-width: 800px) {
  .boxes {
    grid-template-columns: 1fr;
  }
}
</style>