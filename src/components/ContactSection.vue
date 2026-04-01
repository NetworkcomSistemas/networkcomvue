<template>
  <section id="contacto">
    <h2 class="section-title">Contacto</h2>
    <div class="contact-container">
      <div class="contact-form">
        <p>Completá el formulario de contacto:</p>
        
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSdoMGR5J3K2Nb2yzMlSeq5_5HWXVHojY8TwCTPCRmvnUwXXMw/viewform"
          target="_blank"
          rel="noopener noreferrer"
          class="form-btn"
        >
          Abrir formulario →
        </a>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
section {
  padding: 5rem 5%;
}

.section-title {
  text-align: center;
  font-size: 3rem;
  margin-bottom: 3rem;
  background: linear-gradient(135deg, #00ff88, #00ccff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.contact-container {
  max-width: 900px;
  margin: 0 auto;
}

.contact-form {
  background: linear-gradient(145deg, rgba(0,40,80,0.3), rgba(0,20,40,0.3));
  border: 1px solid rgba(0, 255, 255, 0.2);
  border-radius: 20px;
  padding: 2rem;
}

p {
  color: rgba(255, 255, 255, 0.8);
  margin-bottom: 1.5rem;
  font-size: 1rem;
}

.form-btn {
  display: inline-block;
  padding: 1rem 2rem;
  background: linear-gradient(135deg, #00ff88, #00ccff);
  color: #000;
  font-weight: bold;
  border-radius: 10px;
  text-decoration: none;
  transition: opacity 0.3s;
}

.form-btn:hover {
  opacity: 0.85;
}
</style>
