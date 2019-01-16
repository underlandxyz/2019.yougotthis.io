---
layout: default
title: Food
---

<div class="w">
  <h1 class="title">Food</h1>
  <div class="meal">
    <h2>Lunch</h2>
    <p>All lunches are vegan, wheat free and gluten free. None include corriander.</p>
    <ul>
      <li>
        <span>Option 1</span>
        <h3>Meatless Meatballs</h3>
        <p>Aubergine, black olive & rosemary meatballs in tomato sauce with a vegan garlic aioli. Served with brown rice.</p>
        <b>Allergens: soya</b>
      </li>
      <li>
        <span>Option 2</span>
        <h3>Sweet Potato Falafel</h3>
        <p>Baked not fried, made with chickpeas, sweet potato and fresh herbs and spices. Accompanied by grilled red pepper. Served with brown rice and a side salad.</p>
        <b>Allergens: soya, mustard, sesame</b>
      </li>
      <li>
        <span>Option 3</span>
        <h3>Brazillian Black Bean</h3>
        <p>Black beans, carrots and onions, spiced with sweet and smoked paprika, oregano, sprinkled with mint and parsley. Served with brown rice.</p>
        <b>Allergens: soya</b>
      </li>
    </ul>
  </div>
  <div class="meal">
    <h2>Afternoon Ice Cream</h2>
    <p>Smooth liquid nitrogen cooled ice creams from Chin Chin Labs. All vegan.</p>
    <ul>
      <li>
        <span>Option 1</span>
        <h3>Pandan Leaf</h3>
        <p>Tastes like birthday cake</p>
      </li>
      <li>
        <span>Option 2</span>
        <h3>Mango Laasi</h3>
      </li>
      <li>
        <span>Option 3</span>
        <h3>Pineapple</h3>
      </li>
    </ul>
  </div>
  <div class="meal">
    <h2>Hot Drinks</h2>
    <p>Hot drinks to order, availalbe all day. Available with cow's milk, almond milk or coconut milk.</p>
    <ul>
      <li><h3>Americano</h3></li>
      <li><h3>Cappuccino</h3></li>
      <li><h3>Espresso</h3></li>
      <li><h3>Latte</h3></li>
      <li><h3>Hot Chocolate</h3></li>
      <li><h3>Tea</h3></li>
    </ul>
  </div>
</div>

<style>
  .meal {
    background: #f5f5f5;
  border: 1px solid var(--white);
  -webkit-box-shadow: 0 14px 28px rgba(0,0,0,.25), 0 10px 10px rgba(0,0,0,.22);
    box-shadow: 0 14px 28px rgba(0,0,0,.25), 0 10px 10px rgba(0,0,0,.22);
    margin: 2em 0;
    padding: 1em;
  }
  .meal h2 {
    font-size: 1.5em;
  }
  .meal > p {
    margin: 1em 0;
  }
  .meal li {
    margin-top: 2em;
    list-style-type: none;  
  }
  .meal span {
    background: var(--dark);
    color: white;
    padding: 0.25em 0.75em;
    display: inline-block;
  }
  .meal h3 {
    font-size: 1.25em;
    margin-top: 0.5rem;
  }
  .meal li p {
    margin: 0.5em 0;
  }
</style>