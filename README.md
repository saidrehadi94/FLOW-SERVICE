body {
  font-family: 'Arial', sans-serif;
  direction: rtl;
  background: #f2f2f2;
  margin: 0;
  padding: 0;
}

header {
  background-color: #0078d7;
  color: white;
  text-align: center;
  padding: 30px 10px;
  font-size: 32px;
  font-weight: bold;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

.card {
  background-color: white;
  width: 90%;
  max-width: 500px;
  margin: 15px;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  cursor: pointer;
  transition: 0.3s;
}

.card:hover {
  box-shadow: 0 8px 12px rgba(0,0,0,0.2);
}

.card h2 {
  color: #0078d7;
  margin-bottom: 10px;
}

.card ul {
  list-style: none;
  padding: 0;
}

.card ul li {
  padding: 8px 0;
  border-bottom: 1px solid #eee;
}
