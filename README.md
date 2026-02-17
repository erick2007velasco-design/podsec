<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

    <nav>
        <div class="container">
            <h2 style="margin:0;">PodsEC</h2>
            <div>
                <a href="#products-section">Productos</a>
                <a href="#reviews-section">Reseñas</a>
                <a href="#customer-service">Contacto</a>
                <a href="#faq">FAQ</a>
            </div>
        </div>
    </nav>

    <header>
        <h1>PodsEC</h1>
        <p>AirPods de alta calidad al precio que mereces. ¡Envío rápido a todo Ecuador!</p>
    </header>

    <section id="products-section">
        <h2>Nuestros Mejores Modelos</h2>
        <div class="products" id="products"></div>
    </section>

    <section id="payments-section">
        <h2>Formas de Pago y Envío</h2>
        <p style="text-align:center;">Aceptamos transferencias bancarias, efectivo contra entrega y tarjetas de crédito. Envíos a todo Ecuador desde $5. ¡Desde Quito, llegamos rápido!</p>
    </section>

    <section id="reviews-section">
        <h2>Reseñas de Clientes Felices</h2>
        <div id="reviews-list"></div>
        <form id="review-form">
            <input type="text" id="review-name" placeholder="Tu nombre (ej: Juan P.)" required>
            <textarea id="review-text" placeholder="Comparte tu experiencia con PodsEC... ¿Qué te gustó más?" rows="5" required></textarea>
            <button type="submit">Enviar Reseña</button>
        </form>
    </section>

    <section id="faq">
        <h2>Preguntas Frecuentes</h2>
        <ul>
            <li><strong>¿Son originales?</strong> Son réplicas de alta calidad, con sonido premium y durabilidad.</li>
            <li><strong>¿Cuánto demora el envío?</strong> 1-3 días en Quito, 3-5 al resto de Ecuador.</li>
            <li><strong>¿Hay garantía?</strong> Sí, 30 días por defectos.</li>
        </ul>
    </section>

    <section id="newsletter">
        <h2>Suscríbete para Ofertas Exclusivas</h2>
        <form id="newsletter-form">
            <input type="email" id="newsletter-email" placeholder="Tu email" required>
            <button type="submit">Suscribirme</button>
        </form>
    </section>

    <section id="customer-service">
        <h2>¿Dudas? ¡Contáctanos!</h2>
        <p style="text-align:center; font-size:1.3em;">Llama o escribe al: <strong>0987495830</strong></p>
    </section>

    <div id="cart-icon" onclick="toggleCart()" data-count="0">🛒</div>
    <a href="https://wa.me/593987495830?text=Hola%20PodsEC%2C%20tengo%20una%20pregunta%20sobre%20los%20AirPods" id="whatsapp-float" target="_blank">💬</a>

    <div id="cart">
        <h2>Tu Carrito</h2>
        <ul id="cart-items"></ul>
        <p>Total: $<span id="cart-total">0.00</span></p>
        <a href="https://wa.me/593987495830?text=Hola%20PodsEC%2C%20quiero%20comprar%20mi%20carrito%3A%20[detalles]" style="background:var(--verde); color:white; padding:10px; display:block; text-align:center; border-radius:10px; text-decoration:none;">Comprar Ahora via WhatsApp</a>
        <button onclick="toggleCart()" style="background:#808080; width:100%; margin-top:10px;">Cerrar</button>
    </div>

    <section id="admin"></section>

    <footer>© 2026 PodsEC - Hecho con cariño en Quito 💚</footer>
