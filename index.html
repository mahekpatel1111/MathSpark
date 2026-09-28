<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MathSpark - Smart Step-by-Step Solver</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Outfit', sans-serif;
    }

    body {
      background-color: #f4f6f9;
      color: #1e293b;
      padding: 20px 10px;
      min-height: 100vh;
    }

    header {
      text-align: center;
      margin-bottom: 25px;
    }

    h1 {
      font-size: 2.2rem;
      color: #4f46e5;
      font-weight: 700;
      letter-spacing: -0.5px;
    }

    p.subtitle {
      font-size: 1rem;
      color: #64748b;
      margin-top: 4px;
    }

    /* Navigation Tabs */
    .nav-tabs {
      display: flex;
      justify-content: center;
      gap: 8px;
      margin-bottom: 25px;
      flex-wrap: wrap;
    }

    .tab-btn {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      color: #475569;
      padding: 10px 18px;
      font-size: 0.95rem;
      font-weight: 600;
      border-radius: 12px;
      cursor: pointer;
      transition: all 0.2s ease;
      box-shadow: 0 1px 3px rgba(0,0,0,0.05);
    }

    .tab-btn.active, .tab-btn:hover {
      background: #4f46e5;
      color: #ffffff;
      border-color: #4f46e5;
      box-shadow: 0 4px 12px rgba(79, 70, 229, 0.25);
    }

    /* Container Modules */
    .module {
      display: none;
      max-width: 720px;
      margin: 0 auto;
    }

    .module.active {
      display: block;
      animation: fadeIn 0.3s ease-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(6px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Clean Card Layouts */
    .card {
      background: #ffffff;
      border-radius: 16px;
      padding: 20px;
      margin-bottom: 20px;
      border: 1px solid #e2e8f0;
      box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
    }

    .card h3 {
      font-size: 1.15rem;
      color: #0f172a;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      gap: 10px;
    }

    label {
      display: block;
      font-size: 0.85rem;
      font-weight: 600;
      color: #475569;
      margin-bottom: 4px;
    }

    input, select {
      width: 100%;
      padding: 10px 12px;
      border-radius: 8px;
      border: 1px solid #cbd5e1;
      font-size: 0.95rem;
      outline: none;
      background: #f8fafc;
      transition: border-color 0.2s;
    }

    input:focus {
      border-color: #4f46e5;
      background: #ffffff;
    }

    .btn-solve {
      width: 100%;
      background: #4f46e5;
      color: #ffffff;
      border: none;
      padding: 11px;
      font-size: 0.95rem;
      font-weight: 600;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 14px;
      transition: background 0.2s;
    }

    .btn-solve:hover {
      background: #4338ca;
    }

    /* Result Box */
    .result-box {
      margin-top: 14px;
      padding: 14px;
      background: #f1f5f9;
      border-left: 4px solid #4f46e5;
      border-radius: 8px;
      font-size: 0.95rem;
      line-height: 1.5;
      display: none;
      color: #1e293b;
    }

    .matrix-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 8px;
      margin-bottom: 10px;
    }

    .matrix-grid input {
      text-align: center;
    }
  </style>
</head>
<body>

  <header>
    <h1>MathSpark</h1>
    <p class="subtitle">Multi-Step Solvers & Instant Formula Engines</p>
  </header>

  <div class="nav-tabs">
    <button class="tab-btn active" onclick="switchTab('class10')">📘 10th & Algebra</button>
    <button class="tab-btn" onclick="switchTab('geometry')">📐 Geometry & Trig</button>
    <button class="tab-btn" onclick="switchTab('college')">🎓 Matrix & Stats</button>
  </div>

  <!-- MODULE 1: 10TH & ALGEBRA -->
  <div id="class10" class="module active">
    
    <!-- Quadratic Equation Solver -->
    <div class="card">
      <h3>⚡ Quadratic Equation Root Finder ($ax^2 + bx + c = 0$)</h3>
      <div class="grid-3">
        <div>
          <label>Value a</label>
          <input type="number" id="quad-a" placeholder="1">
        </div>
        <div>
          <label>Value b</label>
          <input type="number" id="quad-b" placeholder="-5">
        </div>
        <div>
          <label>Value c</label>
          <input type="number" id="quad-c" placeholder="6">
        </div>
      </div>
      <button class="btn-solve" onclick="solveQuadratic()">Find Roots & Discriminant</button>
      <div id="quad-result" class="result-box"></div>
    </div>

    <!-- Simultaneous Linear Equations -->
    <div class="card">
      <h3>⚖️ Linear Equations in 2 Variables</h3>
      <p style="font-size: 0.8rem; color:#64748b; margin-bottom:10px;">Eq 1: $a_1x + b_1y = c_1$ | Eq 2: $a_2x + b_2y = c_2$</p>
      <div class="grid-3" style="margin-bottom:8px;">
        <input type="number" id="eq1-a" placeholder="a1">
        <input type="number" id="eq1-b" placeholder="b1">
        <input type="number" id="eq1-c" placeholder="c1">
      </div>
      <div class="grid-3">
        <input type="number" id="eq2-a" placeholder="a2">
        <input type="number" id="eq2-b" placeholder="b2">
        <input type="number" id="eq2-c" placeholder="c2">
      </div>
      <button class="btn-solve" onclick="solveLinear2Var()">Solve for X and Y</button>
      <div id="linear-result" class="result-box"></div>
    </div>

    <!-- Arithmetic Progression (AP) -->
    <div class="card">
      <h3>🔢 Arithmetic Progression (AP) Solver</h3>
      <div class="grid-3">
        <div>
          <label>First Term ($a$)</label>
          <input type="number" id="ap-a" placeholder="2">
        </div>
        <div>
          <label>Difference ($d$)</label>
          <input type="number" id="ap-d" placeholder="3">
        </div>
        <div>
          <label>Terms ($n$)</label>
          <input type="number" id="ap-n" placeholder="10">
        </div>
      </div>
      <button class="btn-solve" onclick="solveAP()">Calculate $a_n$ and Sum ($S_n$)</button>
      <div id="ap-result" class="result-box"></div>
    </div>

  </div>

  <!-- MODULE 2: GEOMETRY & TRIGONOMETRY -->
  <div id="geometry" class="module">
    
    <!-- Distance & Midpoint Formula -->
    <div class="card">
      <h3>📍 Coordinate Distance & Midpoint</h3>
      <div class="grid-2" style="margin-bottom:8px;">
        <div>
          <label>Point A ($x_1, y_1$)</label>
          <div class="grid-2">
            <input type="number" id="pt-x1" placeholder="x1">
            <input type="number" id="pt-y1" placeholder="y1">
          </div>
        </div>
        <div>
          <label>Point B ($x_2, y_2$)</label>
          <div class="grid-2">
            <input type="number" id="pt-x2" placeholder="x2">
            <input type="number" id="pt-y2" placeholder="y2">
          </div>
        </div>
      </div>
      <button class="btn-solve" onclick="solveCoordinates()">Calculate Distance & Midpoint</button>
      <div id="coord-result" class="result-box"></div>
    </div>

    <!-- Custom Base Logarithm -->
    <div class="card">
      <h3>🪵 Logarithm Solver with Any Custom Base</h3>
      <div class="grid-2">
        <div>
          <label>Base ($b$)</label>
          <input type="number" id="log-b" placeholder="e.g., 2 or 10">
        </div>
        <div>
          <label>Number ($x$)</label>
          <input type="number" id="log-x" placeholder="e.g., 64">
        </div>
      </div>
      <button class="btn-solve" onclick="solveCustomLog()">Compute $\log_b(x)$</button>
      <div id="log-result" class="result-box"></div>
    </div>

  </div>

  <!-- MODULE 3: COLLEGE & ADVANCED MATH -->
  <div id="college" class="module">
    
    <!-- 3x3 Matrix Determinant -->
    <div class="card">
      <h3>🔲 $3 \times 3$ Matrix Determinant Solver</h3>
      <div class="matrix-grid">
        <input type="number" id="m00" value="1"><input type="number" id="m01" value="2"><input type="number" id="m02" value="3">
        <input type="number" id="m10" value="0"><input type="number" id="m11" value="1"><input type="number" id="m12" value="4">
        <input type="number" id="m20" value="5"><input type="number" id="m21" value="6"><input type="number" id="m22" value="0">
      </div>
      <button class="btn-solve" onclick="solveMatrixDet()">Compute Determinant $\det(A)$</button>
      <div id="matrix-result" class="result-box"></div>
    </div>

    <!-- Statistics & Deviation Master -->
    <div class="card">
      <h3>📊 Statistics & Standard Deviation Master</h3>
      <label>Paste numbers separated by commas:</label>
      <input type="text" id="stats-input" placeholder="e.g., 12, 15, 20, 25, 30, 35">
      <button class="btn-solve" onclick="solveStats()">Compute Mean, Variance & SD</button>
      <div id="stats-result" class="result-box"></div>
    </div>

  </div>

  <script>
    function switchTab(tabId) {
      document.querySelectorAll('.module').forEach(m => m.classList.remove('active'));
      document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');
      event.currentTarget.classList.add('active');
    }

    // Quadratic Solver
    function solveQuadratic() {
      const a = parseFloat(document.getElementById('quad-a').value);
      const b = parseFloat(document.getElementById('quad-b').value);
      const c = parseFloat(document.getElementById('quad-c').value);
      const res = document.getElementById('quad-result');

      if (isNaN(a) || isNaN(b) || isNaN(c)) {
        res.innerHTML = "Please enter valid numbers for a, b, and c.";
        res.style.display = "block";
        return;
      }

      const D = b*b - 4*a*c;
      let output = `<b>Discriminant (D):</b> ${D}<br>`;

      if (D > 0) {
        const r1 = ((-b + Math.sqrt(D)) / (2*a)).toFixed(4);
        const r2 = ((-b - Math.sqrt(D)) / (2*a)).toFixed(4);
        output += `<b>Roots:</b> Real & Distinct<br><b>Root 1:</b> ${r1}<br><b>Root 2:</b> ${r2}`;
      } else if (D === 0) {
        const r = (-b / (2*a)).toFixed(4);
        output += `<b>Roots:</b> Real & Equal<br><b>Root:</b> ${r}`;
      } else {
        const real = (-b / (2*a)).toFixed(4);
        const imag = (Math.sqrt(-D) / (2*a)).toFixed(4);
        output += `<b>Roots:</b> Complex / Imaginary<br><b>Root 1:</b> ${real} + ${imag}i<br><b>Root 2:</b> ${real} - ${imag}i`;
      }

      res.innerHTML = output;
      res.style.display = "block";
    }

    // Linear 2 Variables
    function solveLinear2Var() {
      const a1 = parseFloat(document.getElementById('eq1-a').value);
      const b1 = parseFloat(document.getElementById('eq1-b').value);
      const c1 = parseFloat(document.getElementById('eq1-c').value);
      const a2 = parseFloat(document.getElementById('eq2-a').value);
      const b2 = parseFloat(document.getElementById('eq2-b').value);
      const c2 = parseFloat(document.getElementById('eq2-c').value);
      const res = document.getElementById('linear-result');

      const D = a1*b2 - a2*b1;
      if (D === 0) {
        res.innerHTML = "No unique solution (Lines are parallel or coincident).";
      } else {
        const x = ((c1*b2 - c2*b1) / D).toFixed(4);
        const y = ((a1*c2 - a2*c1) / D).toFixed(4);
        res.innerHTML = `<b>Solution:</b><br><b>X =</b> ${x}<br><b>Y =</b> ${y}`;
      }
      res.style.display = "block";
    }

    // AP Solver
    function solveAP() {
      const a = parseFloat(document.getElementById('ap-a').value);
      const d = parseFloat(document.getElementById('ap-d').value);
      const n = parseInt(document.getElementById('ap-n').value);
      const res = document.getElementById('ap-result');

      const an = a + (n - 1) * d;
      const Sn = (n / 2) * (2 * a + (n - 1) * d);

      res.innerHTML = `<b>${n}th Term (a_n):</b> ${an}<br><b>Sum of ${n} terms (S_n):</b> ${Sn}`;
      res.style.display = "block";
    }

    // Distance & Midpoint
    function solveCoordinates() {
      const x1 = parseFloat(document.getElementById('pt-x1').value);
      const y1 = parseFloat(document.getElementById('pt-y1').value);
      const x2 = parseFloat(document.getElementById('pt-x2').value);
      const y2 = parseFloat(document.getElementById('pt-y2').value);
      const res = document.getElementById('coord-result');

      const dist = Math.sqrt(Math.pow(x2 - x1, 2) + Math.pow(y2 - y1, 2)).toFixed(4);
      const mx = ((x1 + x2) / 2).toFixed(2);
      const my = ((y1 + y2) / 2).toFixed(2);

      res.innerHTML = `<b>Distance:</b> ${dist} units<br><b>Midpoint:</b> (${mx}, ${my})`;
      res.style.display = "block";
    }

    // Custom Log Base
    function solveCustomLog() {
      const b = parseFloat(document.getElementById('log-b').value);
      const x = parseFloat(document.getElementById('log-x').value);
      const res = document.getElementById('log-result');

      if (b <= 0 || b === 1 || x <= 0) {
        res.innerHTML = "Base must be > 0 and ≠ 1. Number must be > 0.";
      } else {
        const val = (Math.log(x) / Math.log(b)).toFixed(6);
        res.innerHTML = `<b>log<sub>${b}</sub>(${x}) =</b> ${val}`;
      }
      res.style.display = "block";
    }

    // Matrix Determinant
    function solveMatrixDet() {
      const m00 = parseFloat(document.getElementById('m00').value) || 0;
      const m01 = parseFloat(document.getElementById('m01').value) || 0;
      const m02 = parseFloat(document.getElementById('m02').value) || 0;
      const m10 = parseFloat(document.getElementById('m10').value) || 0;
      const m11 = parseFloat(document.getElementById('m11').value) || 0;
      const m12 = parseFloat(document.getElementById('m12').value) || 0;
      const m20 = parseFloat(document.getElementById('m20').value) || 0;
      const m21 = parseFloat(document.getElementById('m21').value) || 0;
      const m22 = parseFloat(document.getElementById('m22').value) || 0;
      const res = document.getElementById('matrix-result');

      const det = m00*(m11*m22 - m12*m21) - m01*(m10*m22 - m12*m20) + m02*(m10*m21 - m11*m20);
      res.innerHTML = `<b>Determinant det(A):</b> ${det}`;
      res.style.display = "block";
    }

    // Statistics
    function solveStats() {
      const input = document.getElementById('stats-input').value;
      const res = document.getElementById('stats-result');
      const nums = input.split(',').map(n => parseFloat(n.trim())).filter(n => !isNaN(n));

      if (nums.length === 0) {
        res.innerHTML = "Please enter valid numbers separated by commas.";
        res.style.display = "block";
        return;
      }

      const mean = nums.reduce((a, b) => a + b, 0) / nums.length;
      const variance = nums.reduce((a, b) => a + Math.pow(b - mean, 2), 0) / nums.length;
      const sd = Math.sqrt(variance);

      res.innerHTML = `<b>Count:</b> ${nums.length}<br><b>Mean (Average):</b> ${mean.toFixed(4)}<br><b>Variance (σ²):</b> ${variance.toFixed(4)}<br><b>Standard Deviation (σ):</b> ${sd.toFixed(4)}`;
      res.style.display = "block";
    }
  </script>
</body>
</html>
