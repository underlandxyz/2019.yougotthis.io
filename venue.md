---
layout: default
title: Venue
---

<div class="content w">
  <h1 class="title">Venue</h1>
  <div class="info">
    <address>
      <h2>Monzo</h2>
      <p>35 Wilson Street</p>
      <p>EC2A 2ER</p>
    </address>
    <p class='more'>
      Monzo have very kindly offered to host us for the day. Their lovely venue is a five minute walk from Moorgate. All of the spaces we're using are wheelchair accessible with gender neutral toilets throughout.
    </p>
  </div>
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.6261809940506!2d-0.08771514865944886!3d51.52007381749742!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761cac2981fb47%3A0xd2e8f6976dd9c670!2s35+Wilson+St%2C+London+EC2A+2ER!5e0!3m2!1sen!2suk!4v1546790451514" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>

<style>
  iframe {
    width: 100%;
    height: 560px;
    box-shadow: var(--elevate);
  }
  .info {
    box-shadow: var(--elevate);
    padding: 1em;
    margin-bottom: 2em;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 2em;
  }
  .info p {
    margin-bottom: 0;
    line-height: 1.75em;
  }
  .info address {
    margin-bottom: 0;
  }
  @media screen and (max-width: 800px) {
    .info {
      grid-template-columns: 1fr;
    }
    iframe {
      height: 56vw;
    }
  }
</style>