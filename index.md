---
title: Homepage
layout: default
current: index
---
<main>
  <section class="homepage-hero">
    <div class="slideshow--mobile">
      <img src="{{ "/img/slideshow/homepage-hero-01.jpg" | relative_url }}" alt="Preacher speaking to group of homeless men">
      <h1 class="homepage-hero__caption  text--light">SHARING GOD’S LOVE WITH THE LEAST OF THESE</h1>
    </div>
    
    <div class="slideshow" id="slideshow">
      <div class="slide  show">
        <img src="{{ "/img/slideshow/homepage-hero-01.jpg" | relative_url }}" alt="Preacher speaking to group of homeless men">
        <h1 class="homepage-hero__caption  text--light">SHARING GOD’S LOVE WITH THE LEAST OF THESE</h1>
      </div>
      <div class="slide">
        <img src="{{ "/img/slideshow/homepage-hero-02.jpg" | relative_url }}" alt="A view of the mission at 4 North Central Avenue from across the street">
        <h1 class="homepage-hero__caption  text--light">REACHING THE POOR OF BALTIMORE SINCE 1956</h1>
      </div>
      <div class="slide">
        <img src="{{ "/img/slideshow/homepage-hero-03.jpg" | relative_url }}" alt="Men recieve Christmas gifts">
        <h1 class="homepage-hero__caption  text--light">MEETING SPIRITUAL AND PHYSICAL NEEDS</h1>
      </div>
    </div>
  </section>

  <section class="container  white">
    <h2>Who are we?</h2>
    <div class="row  text--center">
          <div class="textbox">
            <p>The Baltimore Rescue Mission has been reaching out to the poor of Baltimore since 1956. We are a Christian, non-profit, non-denominational Gospel ministry. <a href="{{ "mission/philosophy" | relative_url }}">Read more...</a></p>
          </div>
    </div>

    <h2>What is our purpose?</h2>
    <div class="row  text--center">
          <div class="textbox">
            <p>The great, central purpose and duty of the Baltimore Rescue Mission is to proclaim the “unsearchable riches” of the Lord Jesus Christ (Ephesians 3:8-9); to seek the salvation of the lost; to instruct believers in the Word of God; to conduct gospel and Bible teaching services; to feed, clothe, and help the needy; and to foster, promote and encourage all phases of general rescue mission work. <a href="{{ "mission/statement-of-faith" | relative_url }}">Read our Statement of Faith...</a></p>
          </div>
    </div>

    <h2>Our Ministries</h2>
    <div class="row  homepage-ministry">
      <div class="textbox  homepage-ministry__textbox">
        <h3 class="homepage-ministry__header">Men's Divison</h3>
        <p>The Men’s Division is an emergency overnight shelter for homeless men 18 years old and up that provides food, clothing, shelter, showers, and a one-hour gospel service each evening. <a href="{{ "ministries/mens-division" | relative_url }}">Read more...</a></p>
      </div>
      <a href="{{ "ministries/mens-division" | relative_url }}" class="homepage-ministry__image">
        <img src="{{ "/img/mens.jpg" | relative_url }}" alt="Preacher speakin to group of homeless men">
      </a>
    </div>

    <div class="row  homepage-ministry">
      <a href="{{ "ministries/karis-home" | relative_url }}" class="homepage-ministry__image">
        <img src="{{ "/img/karis.jpg" | relative_url }}" alt="Preacher speakin to group of homeless men">
      </a>
      <div class="textbox  homepage-ministry__textbox">
        <h3 class="homepage-ministry__header">Karis Home</h3>
        <p>The Karis Home is the women and children’s division of the Baltimore Rescue Mission.  The term “Karis Home” means “Grace Home” - <em>Karis</em> is the Greek word for <em>grace</em>. <a href="{{ "ministries/karis-home" | relative_url }}">Read more...</a></p>
      </div>
    </div>
  </section>
</main>
