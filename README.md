# portalhsebde.github.io
HSE Portal PT. BERLIAN DUTA ENERGI
body {
  font-family: Arial, sans-serif;
  background: #f6f7f9;
  margin: 0;
  padding: 20px;
}

h2 {
  margin: 20px 0 10px;
  font-size: 18px;
  color: #333;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
}

.menu-card {
  background: #fff;
  border-radius: 15px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  text-align: center;
  padding: 20px 10px;
  transition: transform 0.2s;
  cursor: pointer;
}

.menu-card:hover {
  transform: translateY(-5px);
}

.icon {
  background: #ffecec;
  border-radius: 15px;
  font-size: 28px;
  padding: 15px;
  display: inline-block;
  margin-bottom: 10px;
}

.menu-card p {
  margin: 0;
  font-size: 14px;
  color: #333;
  font-weight: 600;
}
