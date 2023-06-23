
<div class="card">
    <figure>
        <img src="/src/assets/illustration-hero.svg" alt="Cartoon dancing with headphones">
    </figure>
    <div class="content">
        <h1>Order Summary</h1>
        <p>You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
        <div class="order-container">
            <div class="order-plan">
                <img src="/src/assets/icon-music.svg" alt="Music note icon">
                <div class="order-price">
                    <span>Annual Plan</span>
                    <span>$59.99/year</span>
                </div>
            </div>
            <a href="#">Change</a>
        </div>
        <button class="primary-button">Proceed to Payment</button>
        <button class="secondary-button">Cancel Order</button>
    </div>
</div>
  
<style>
.card { 
    background-color: white;
    border-radius: 20px;
    color: black;
    font-family: var(--font-family);
    overflow: hidden;
    max-height: 697px;
    width: 450px;
}

.card > figure {
    display: grid;
    justify-content: center;
    margin: 0;
}

.content {
    display: grid;
    gap: 0.5rem;
    padding: 1rem 2rem;
    text-align: center;
}

.content h1 {
    font-size: 28px;
    font-weight: 900;
    line-height: 37px;
    margin-top: 0;
    margin-bottom: 0;
}

.content p {
    color: var(--third-color);
    font-size: 16px;
    font-weight: 500;
    line-height: 26px;
}

.order-container {
    background-color: #F7F9FF;
    border-radius: 11px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 25px;
    margin-bottom: 16px;
}

.order-container a {
    color: var(--second-color);
    font-size: 14px;
    font-weight: 700;
    line-height: 18px;
}

.order-plan {
    display: flex;
    align-items: center;
    gap: 20px;
}

.order-price {
    display: grid;
    font-size: 16px;
    font-weight: 500;
    line-height: 21px;
}

.order-price span:first-child {
    font-weight: 900;
}

.order-price span:last-child {
    color: var(--third-color);
}

.primary-button {
    background-color: var(--second-color);
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
    border: none;
    border-radius: 11px;
    color: white;
    font-size: 16px;
    font-weight: 900;
    Offset: 0px, 4px rgba(0, 0, 0, 0.25);
    padding: 15px;
}

.primary-button:hover {
    background-color: var(--second-color-hover);
}

.secondary-button {
    background-color: transparent;
    border: none;
    color: var(--third-color);
    font-size: 16px;
    font-weight: 900;
    line-height: 15px;
    padding: 15px;
}

.secondary-button:hover {
    color: black;
}

@media (max-width: 1023px) {
    .card {
        width: 300px;
    }
    .content {
        gap: 0.25rem;
        padding: 1rem 1rem;
    }
    .content p {
        font-size: 14px;
    }
    .order-container {
        padding: 7.5px;
        margin-bottom: 8px;
    }

}
</style>