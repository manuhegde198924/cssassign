/* file: index.html */
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cafe Menu</title>
  <link href="styles.css" rel="stylesheet"/>
</head>
<body>
  <div class="menu">
    <header>
      <h1>CAMPER CAFE</h1>
      <p>Est. 2020</p>
    </header>
    <main>
      <section>
        <h2>Coffee</h2>
        <article class="item">
          <p class="flavor">French Vanilla</p><p class="price">3.00</p>
        </article>
        <article class="item">
          <p class="flavor">Caramel Macchiato</p><p class="price">3.75</p>
        </article>
        <article class="item">
          <p class="flavor">Pumpkin Spice</p><p class="price">3.50</p>
        </article>
        <article class="item">
          <p class="flavor">Hazelnut</p><p class="price">4.00</p>
        </article>
        <article class="item">
          <p class="flavor">Mocha</p><p class="price">4.50</p>
        </article>
      </section>
      <section>
        <h2>Desserts</h2>
        <article class="item">
          <p class="dessert">Donut</p><p class="price">1.50</p>
        </article>
      </section>
    </main>
  </div>
</body>
</html>
body {
background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
}

h1, h2, p {
text-align: center;
}

.menu {
width: 80%;
background-color: burlywood;
margin-left: auto;
margin-right: auto;
}

.item p {
display: inline-block;
}

.flavor {
text-align: left;
width: 75%;
}
.dessert{
  text-align:left;
  width: 75%;
}

.price {
text-align: right;
width: 25%
}
