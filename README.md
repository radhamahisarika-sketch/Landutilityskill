# Landutilityskill
 Landutilityskill is a concept website showcasing a circular system that uses algae and wetland-based processes to convert industrial waste and barren land into clean water, biomass, and sustainable resources.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BioCycle | Circular Innovation</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0f172a;
  color: #e2e8f0;
}

header {
  background: linear-gradient(135deg, #16a34a, #22c55e);
  text-align: center;
  padding: 60px 20px;
}

header h1 {
  margin: 0;
  font-size: 3em;
}

nav {
  display: flex;
  justify-content: center;
  background: #020617;
  padding: 12px;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 60px 20px;
  max-width: 1100px;
  margin: auto;
}

.card {
  background: #1e293b;
  padding: 25px;
  border-radius: 12px;
  margin-bottom: 20px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.3);
}

h2 {
  color: #22c55e;
}

/* FLOW DIAGRAM */
.flow {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  margin-top: 20px;
}

.box {
  flex: 1;
  min-width: 150px;
  background: #020617;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #334155;
}

.arrow {
  font-size: 24px;
}

/* CIRCULAR DIAGRAM */
.circle-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 30px;
}

.circle {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  background: #16a34a;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-weight: bold;
  padding: 10px;
}

/* GRID LAYOUT */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #020617;
  color: #94a3b8;
}
</style>
</head>

<body>

<header>
  <h1>BioCycle</h1>
  <p>Transforming Barren Land into Circular Bio-Resource Systems</p>
</header>

<nav>
  <a href="#problem">Problem</a>
  <a href="#system">System</a>
  <a href="#cycle">Cycle</a>
  <a href="#impact">Impact</a>
</nav>

<section id="problem">
  <h2>🌍 The Problem</h2>
  <div class="card">
    <p>
      Barren land remains unused while industrial wastewater pollutes ecosystems.
      Current systems treat waste but fail to convert it into productive value.
    </p>
  </div>
</section>

<section id="system">
  <h2>⚙️ System Flow Diagram</h2>

  <div class="flow">
    <div class="box">Waste Input 💧</div>
    <div class="arrow">➡</div>
    <div class="box">Filtration</div>
    <div class="arrow">➡</div>
    <div class="box">Pre-Treatment</div>
    <div class="arrow">➡</div>
    <div class="box">Algae Pond 🌱</div>
    <div class="arrow">➡</div>
    <div class="box">Wetland</div>
    <div class="arrow">➡</div>
    <div class="box">Output ✔</div>
  </div>

</section>

<section id="cycle">
  <h2>🔁 Circular BioCycle Model</h2>

  <div class="circle-container">
    <div class="circle">Waste</div>
    <div class="circle">Processing</div>
    <div class="circle">Biomass</div>
    <div class="circle">Energy</div>
    <div class="circle">Land Recovery</div>
  </div>

</section>

<section id="impact">
  <h2>🚀 Impact</h2>

  <div class="grid">
    <div class="card">
      <h3>🌿 Environmental</h3>
      <p>Reduces pollution and restores ecosystems</p>
    </div>

    <div class="card">
      <h3>💰 Economic</h3>
      <p>Generates fuel, fertilizer, and reusable water</p>
    </div>

    <div class="card">
      <h3>👥 Social</h3>
      <p>Creates sustainable jobs and land usability</p>
    </div>
  </div>

</section>

<footer>
  <p>BioCycle Project | Circular Innovation for a Sustainable Future</p>
</footer>

</body>
</html>
