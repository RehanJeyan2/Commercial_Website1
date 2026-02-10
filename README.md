# Ex02 Commercial Website
## Date:10.02.2026
## Reg.No:212223040167
## Name : Rehan Jeyan

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nexora — Business Solutions</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- NAVBAR -->
  <header class="navbar">
    <h2 class="logo">Nexora</h2>
    <nav class="nav">
      <a href="#">Home</a>
      <a href="#">Solutions</a>
      <a href="#">Pricing</a>
      <a href="#" class="btn-nav">Contact</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Build. Scale. Dominate.</h1>
      <p>Premium digital solutions for fast-growing businesses.</p>
      <div class="hero-buttons">
        <button class="primary-btn">Get Started</button>
        <button class="secondary-btn">View Demo</button>
      </div>
    </div>
  </section>

  <!-- FEATURES -->
  <section class="features">
    <div class="feature">
      <h3>🚀 Performance</h3>
      <p>Lightning-fast solutions optimized for growth.</p>
    </div>
    <div class="feature">
      <h3>🔒 Security</h3>
      <p>Enterprise-grade security and data protection.</p>
    </div>
    <div class="feature">
      <h3>🎯 Strategy</h3>
      <p>Data-driven decisions that scale with you.</p>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta">
    <h2>Ready to elevate your brand?</h2>
    <button class="primary-btn">Let’s Talk</button>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <p>© 2026 Nexora. Crafted with intent.</p>
  </footer>

</body>
</html>

```
style.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 60px;
  background: rgba(0,0,0,0.6);
  backdrop-filter: blur(10px);
  position: fixed;
  width: 100%;
  color: white;
}

.logo {
  letter-spacing: 1px;
}

.nav {
  display: flex;
  align-items: center;
  gap: 25px;
}

.nav a {
  text-decoration: none;
  color: white;
  opacity: 0.85;
}

.btn-nav {
  padding: 8px 16px;
  border: 1px solid white;
  border-radius: 20px;
}

/* HERO */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
  color: white;
  text-align: center;
  padding: 0 20px;
}

.hero-content {
  max-width: 700px;
}

.hero h1 {
  font-size: 52px;
  margin-bottom: 15px;
}

.hero p {
  font-size: 18px;
  opacity: 0.9;
  margin-bottom: 30px;
}

.hero-buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.primary-btn {
  padding: 14px 28px;
  background: #00e5ff;
  border: none;
  border-radius: 30px;
  font-weight: bold;
  cursor: pointer;
}

.secondary-btn {
  padding: 14px 28px;
  background: transparent;
  border: 1px solid white;
  color: white;
  border-radius: 30px;
  cursor: pointer;
}

/* FEATURES */
.features {
  display: flex;
  justify-content: space-around;
  padding: 80px 60px;
  background: #0b0f14;
  color: white;
}

.feature {
  max-width: 300px;
  text-align: center;
}

.feature h3 {
  margin-bottom: 10px;
}

/* CTA */
.cta {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
  padding: 70px;
  background: #00e5ff;
  color: black;
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 20px;
  background: #000;
  color: white;
}

/* RESPONSIVE */
@media (max-width: 900px) {
  .features {
    flex-direction: column;
    align-items: center;
    gap: 40px;
  }

  .hero h1 {
    font-size: 38px;
  }
}

```

## OUTPUT
<img width="959" height="452" alt="image" src="https://github.com/user-attachments/assets/cd700355-c86f-4554-8337-f667c4181d77" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
