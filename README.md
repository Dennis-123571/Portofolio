# Portofolio
My web design potofolio
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

body {
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

/* Hero Section */
.hero {
  background: linear-gradient(135deg, #6a11cb, #2575fc);
  color: #fff;
  padding: 100px 20px;
  text-align: center;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 30px;
}

.btn {
  background-color: #fff;
  color: #2575fc;
  padding: 12px 25px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background-color: #2575fc;
  color: #fff;
}

/* Projects Section */
section {
  padding: 60px 20px;
  text-align: center;
}

.projects-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.project-card {
  background: #fff;
  border-radius: 10px;
  padding: 20px;
  width: 280px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.project-card img {
  width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

/* Contact Section */
#contact a.btn {
  margin-top: 15px;
  display: inline-block;
}

/* Footer */
footer {
  text-align: center;
  padding: 30px 20px;
  background-color: #333;
  color: #fff;
}

/* Responsive */
@media (max-width: 768px) {
  .projects-container {
    flex-direction: column;
    align-items: center;
  }

  .hero h1 {
    font-size: 2.2em;
  }
}
