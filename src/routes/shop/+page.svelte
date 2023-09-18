<svelte:head>
  <title>Shop</title>
  <meta name="description" content="Shop" />
</svelte:head>

<div class="text-column">
  <h1>Merchandise</h1>

  <h3>
    Take a piece of Deep Breadth home with you. Shop exclusive merchandise
    that's as unique as our sound.
  </h3>

  <!-- Shop Items Placeholder -->
  <div class="shop-items">
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
    <div class="shop-item">
      <img src="https://via.placeholder.com/300x300" alt="Shop Item" />
      <h4>Shop Item</h4>
      <h5>$9.99</h5>
      <button>Add to Cart</button>
    </div>
  </div>
</div>

<style>
  .shop-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1em;
  }

  .shop-item {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 300px;
    max-width: 100%;
  }

  .shop-item img {
    width: 100%;
    max-width: 300px;
    height: auto;
  }

  .shop-item h4 {
    font-weight: bold;
  }

  .shop-item h5 {
    font-weight: bold;
    color: #666;
  }

  .shop-item button {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 0.5em;
    background-color: #fff;
    cursor: pointer;
  }
</style>
