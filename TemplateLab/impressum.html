let cart = [];

function addToCart(productName) {
    cart.push(productName);
    alert(productName + " wurde dem Warenkorb hinzugefügt!");
    updateCartCounter();
}

function updateCartCounter() {
    const counter = document.getElementById('cart-counter');
    if (counter) {
        counter.textContent = cart.length;
    }
}

// PayPal-Integration (Sandbox-Modus)
function checkout() {
    paypal.Buttons({
        createOrder: function(data, actions) {
            return actions.order.create({
                purchase_units: [{
                    amount: {
                        value: '0.01' // Testbetrag
                    }
                }]
            });
        },
        onApprove: function(data, actions) {
            return actions.order.capture().then(function(details) {
                alert('Zahlung erfolgreich: ' + details.payer.name.given_name);
                cart = [];
                updateCartCounter();
            });
        }
    }).render('#paypal-button-container');
}

// Initialisierung nach Laden der Seite
document.addEventListener('DOMContentLoaded', checkout);
