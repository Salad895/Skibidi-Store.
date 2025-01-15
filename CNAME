<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Futuristic Toilet Products</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: #f5f7fa;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 3rem;
            color: #00bcd4;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            color: #ff4081;
        }

        .products-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            justify-items: center;
            margin-bottom: 40px;
            width: 100%;
        }

        .product-card {
            background: #fff;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
            cursor: pointer;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
            overflow: hidden;
            position: relative;
            width: 100%;
            max-width: 320px;
        }

        .product-card:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
        }

        .product-card img {
            width: 100%;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .product-card:hover img {
            transform: scale(1.1);
        }

        .product-card h3 {
            font-size: 1.6rem;
            margin-top: 15px;
            color: #00bcd4;
        }

        .product-card p {
            font-size: 1rem;
            color: #555;
            margin-top: 10px;
        }

        .add-to-cart-btn {
            background: #ff4081;
            color: white;
            padding: 12px 24px;
            border-radius: 10px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
            font-size: 1.1rem;
            transition: background 0.3s ease;
        }

        .add-to-cart-btn:hover {
            background: #e50063;
        }

        .cart-section {
            position: fixed;
            top: 0;
            right: 0;
            background: #fff;
            color: #333;
            width: 320px;
            height: 100vh;
            padding: 30px;
            box-shadow: -5px 0 15px rgba(0, 0, 0, 0.1);
            transform: translateX(100%);
            transition: transform 0.3s ease;
            overflow-y: auto;
            border-left: 4px solid #ff4081;
        }

        .cart-section.active {
            transform: translateX(0);
        }

        .cart-section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .cart-items {
            margin-bottom: 30px;
            max-height: 60vh;
            overflow-y: auto;
        }

        .cart-items p {
            font-size: 1rem;
            margin-bottom: 10px;
        }

        .cart-total {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .checkout-btn {
            background: #ff4081;
            color: white;
            padding: 15px;
            border-radius: 10px;
            border: none;
            font-size: 1.2rem;
            cursor: pointer;
            width: 100%;
            transition: background 0.3s ease;
        }

        .checkout-btn:hover {
            background: #e50063;
        }

        .toggle-cart-btn {
            position: fixed;
            top: 20px;
            left: 20px;
            background: #00bcd4;
            color: white;
            padding: 12px 24px;
            border-radius: 10px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .toggle-cart-btn:hover {
            background: #ff4081;
        }

        .cart-item-remove {
            background: transparent;
            color: #ff4081;
            border: none;
            cursor: pointer;
            font-size: 1.2rem;
            padding: 0;
            transition: color 0.3s ease;
        }

        .cart-item-remove:hover {
            color: #e50063;
        }

        .confirmation {
            background: #00bcd4;
            color: white;
            padding: 20px;
            border-radius: 10px;
            font-size: 1.2rem;
            margin-top: 20px;
            text-align: center;
        }

        .delivery-info {
            font-size: 1rem;
            color: #ff4081;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Futuristic Toilet Products</h1>
    <p>Shop the most innovative toilet-themed items!</p>
</header>

<section class="products-container">
    <div class="product-card">
        <img src="https://via.placeholder.com/250?text=Toilet+Plush" alt="Toilet Plush">
        <h3>Toilet Plush</h3>
        <p>Soft, cute, and perfect for your bathroom!</p>
        <p class="delivery-info">Delivered in 3-5 days.</p>
        <button class="add-to-cart-btn" onclick="addToCart('Toilet Plush', 25)">Add to Cart</button>
    </div>
    <div class="product-card">
        <img src="https://via.placeholder.com/250?text=Toilet+Figure" alt="Toilet Figure">
        <h3>Toilet Figure</h3>
        <p>Bring humor to your home or office!</p>
        <p class="delivery-info">Delivered in 4-6 days.</p>
        <button class="add-to-cart-btn" onclick="addToCart('Toilet Figure', 35)">Add to Cart</button>
    </div>
    <div class="product-card">
        <img src="https://via.placeholder.com/250?text=Toilet+T-Shirt" alt="Toilet T-Shirt">
        <h3>Toilet T-Shirt</h3>
        <p>Comfortable and stylish with a quirky design!</p>
        <p class="delivery-info">Delivered in 5-7 days.</p>
        <button class="add-to-cart-btn" onclick="addToCart('Toilet T-Shirt', 20)">Add to Cart</button>
    </div>
    <div class="product-card">
        <img src="https://via.placeholder.com/250?text=Toilet+Mug" alt="Toilet Mug">
        <h3>Toilet Mug</h3>
        <p>Start your day with a laugh!</p>
        <p class="delivery-info">Delivered in 3-5 days.</p>
        <button class="add-to-cart-btn" onclick="addToCart('Toilet Mug', 15)">Add to Cart</button>
    </div>
    <div class="product-card">
        <img src="https://via.placeholder.com/250?text=Toilet+Clock" alt="Toilet Clock">
        <h3>Toilet Clock</h3>
        <p>Perfect for the bathroom, with a quirky twist!</p>
        <p class="delivery-info">Delivered in 4-6 days.</p>
        <button class="add-to-cart-btn" onclick="addToCart('Toilet Clock', 30)">Add to Cart</button>
    </div>
</section>

<div class="toggle-cart-btn" onclick="toggleCart()">View Cart</div>

<div class="cart-section" id="cartSection">
    <h2>Your Cart</h2>
    <div class="cart-items" id="cartItems">
        <p>No items in the cart.</p>
    </div>
    <div class="cart-total" id="cartTotal">
        Total: $0
    </div>
    <button class="checkout-btn" onclick="checkout()">Checkout</button>
</div>

<div id="confirmationMessage" class="confirmation" style="display:none;">
    Thank you for your purchase! Your order is being processed.
</div>

<script>
    let cart = JSON.parse(localStorage.getItem('cart')) || [];
    let discount = 0;

    window.onload = () => {
        updateCart();
    };

    function addToCart(productName, price) {
        const productIndex = cart.findIndex(item => item.name === productName);

        if (productIndex !== -1) {
            cart[productIndex].quantity += 1;  // Increase quantity if the item exists
        } else {
            cart.push({ name: productName, price: price, quantity: 1 });
        }

        localStorage.setItem('cart', JSON.stringify(cart));
        updateCart();
    }

    function updateCart() {
        const cartItemsContainer = document.getElementById('cartItems');
        const cartTotalContainer = document.getElementById('cartTotal');
        cartItemsContainer.innerHTML = ''; // Clear current cart

        let total = 0;

        if (cart.length === 0) {
            cartItemsContainer.innerHTML = '<p>No items in the cart.</p>';
        }

        cart.forEach((item, index) => {
            const itemElement = document.createElement('p');
            itemElement.innerHTML = `${item.name} - $${item.price} x ${item.quantity} <button class="cart-item-remove" onclick="removeFromCart(${index})">Remove</button>`;
            cartItemsContainer.appendChild(itemElement);
            total += item.price * item.quantity;
        });

        if (discount) {
            total *= (1 - discount);
        }

        cartTotalContainer.textContent = `Total: $${total.toFixed(2)}`;
    }

    function removeFromCart(index) {
        cart.splice(index, 1);
        localStorage.setItem('cart', JSON.stringify(cart));
        updateCart();
    }

    function toggleCart() {
        const cartSection = document.getElementById('cartSection');
        cartSection.classList.toggle('active');
    }

    function checkout() {
        document.getElementById('cartSection').style.display = 'none';  // Hide the cart section
        document.getElementById('confirmationMessage').style.display = 'block';  // Show confirmation message

        setTimeout(() => {
            localStorage.removeItem('cart'); // Clear cart after checkout
            cart = [];  // Reset cart variable
            discount = 0;  // Reset discount
            updateCart();  // Update the cart display
            document.getElementById('confirmationMessage').style.display = 'none';  // Hide confirmation
            document.getElementById('cartSection').style.display = 'block';  // Show cart again
        }, 3000);  // After 3 seconds, reset everything
    }
</script>
<script>
(function(){if(!window.chatbase||window.chatbase("getState")!=="initialized"){window.chatbase=(...arguments)=>{if(!window.chatbase.q){window.chatbase.q=[]}window.chatbase.q.push(arguments)};window.chatbase=new Proxy(window.chatbase,{get(target,prop){if(prop==="q"){return target.q}return(...args)=>target(prop,...args)}})}const onLoad=function(){const script=document.createElement("script");script.src="https://www.chatbase.co/embed.min.js";script.id="8bISD6IpbsxkuQm5Jttc-";script.domain="www.chatbase.co";document.body.appendChild(script)};if(document.readyState==="complete"){onLoad()}else{window.addEventListener("load",onLoad)}})();
</script>
</body>
</html>
