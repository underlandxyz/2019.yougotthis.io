---
layout: default
title: Venue
---

<div class="content w">
  <h1 class="title">Venue</h1>
  <div class="info">
    <address>
      <h2>Monzo</h2>
      <p>35 Wilson Sreet</p>
      <p>EC2A 2ER</p>
    </address>
    <p class='more'>
      Monzo have very kindly offered to host us for the day. Their lovely venue is a five minute walk from Moorgate. All of the spaces we're using are wheelchair accessible with gender neutral toilets throughout.
    </p>
  </div>
  <iframe frameborder="0" allowfullscreen="" src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJ8fccgq4cdkgR3NXnBFdKomE&amp;key=AIzaSyCvjeQM0m8usekK_7Qo-vrpEy-_sJEws6s" class="s_5487"></iframe>
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