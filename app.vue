<template>
  <div class="eco-design-app">
    <header>
      <h1>Build to Cycle</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#principles">Principles</a></li>
          <li><a href="#examples">Examples</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <NuxtRouteAnnouncer />
      <section id="about">
        <h2>About Build to Cycle</h2>
        <p>Build to Cycle is a design philosophy that focuses on creating technology products that are easy to repair and recycle, promoting sustainability and reducing e-waste.</p>
      </section>
      <section id="principles">
        <h2>Key Principles</h2>
        <ul>
          <li>Design for easy disassembly</li>
          <li>Use recyclable materials</li>
          <li>Standardize components</li>
          <li>Provide repair documentation</li>
        </ul>
      </section>
      <section id="examples">
        <h2>Examples</h2>
        <ul>
          <li>Modular smartphones with replaceable parts</li>
          <li>Laptops with easily accessible components</li>
          <li>Home appliances designed for longevity and repair</li>
        </ul>
      </section>
    </main>
    <footer>
      <p>© 2023 Build to Cycle Initiative</p>
    </footer>
  </div>
</template>

<style scoped>
.eco-design-app {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

header {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 1rem;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

main {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

section {
  margin-bottom: 2rem;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem;
  position: fixed;
  bottom: 0;
  width: 100%;
}
</style>
