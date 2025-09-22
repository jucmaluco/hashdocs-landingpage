<template>
  <div class="landing-page">
    <!-- Navigation -->
    <nav class="navbar">
      <div class="nav-container">
        <div class="nav-logo">
          <h2>HashDocs</h2>
        </div>
        <div class="nav-menu">
          <a href="#features" class="nav-link">Hashdocs</a>
          <a href="#about" class="nav-link">About</a>
          <a href="#contact" class="nav-link">Contact</a>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-container">
        <div class="hero-content">
          <h1 class="hero-title">
            Revolutionize Your Documentation with
            <span class="gradient-text">HashDocs</span>
          </h1>
          <p class="hero-description">
            Create, manage, and sign documents effortlessly. 
            Built using <strong> blockchain </strong> for teams who value control and security.
          </p>
        </div>
        <div class="hero-video-section">
          <div class="hero-video-container">
            <video 
              class="hero-video" 
              autoplay 
              muted 
              loop 
              playsinline
            >
              <source src="/videos/landingvideo.mp4" type="video/mp4">
              <source src="/videos/landingvideo.webm" type="video/webm">
              <!-- Fallback for browsers that don't support video -->
              <div class="video-fallback">
                <p>Your browser doesn't support video playback.</p>
              </div>
            </video>
          </div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
      <div class="container">
        <div class="section-header">
          <h2>Why Choose HashDocs?</h2>
          <p>Everything you need to create stunning documentation</p>
        </div>
        <div class="features-grid">
          <div class="feature-card">
            <div class="feature-icon">📝</div>
            <h3>Easy Editing</h3>
            <p>Intuitive markdown editor with live preview. No technical knowledge required.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">👥</div>
            <h3>Team Collaboration</h3>
            <p>Real-time collaboration with comments, suggestions, and version control.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🎨</div>
            <h3>Beautiful Themes</h3>
            <p>Choose from dozens of professional themes or create your own custom design.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🔍</div>
            <h3>Smart Search</h3>
            <p>Find any content instantly with our powerful full-text search engine.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">📱</div>
            <h3>Mobile Ready</h3>
            <p>Access and edit your documentation from any device, anywhere.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🔒</div>
            <h3>Secure & Private</h3>
            <p>Enterprise-grade security with granular permissions and data encryption.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section">
      <div class="container">
        <div class="cta-content">
          <h2>Ready to Get Started?</h2>
          <p>Join thousands of teams already using HashDocs to create amazing documentation.</p>
          <div class="cta-buttons">
            <button class="primary-button large">Start Your Free Trial</button>
            <button class="secondary-button large">Schedule a Demo</button>
          </div>
          <p class="cta-note">No credit card required • 14-day free trial • Cancel anytime</p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <div class="footer-content">
          <div class="footer-section">
            <h3>HashDocs</h3>
            <p>Making documentation beautiful and accessible for everyone.</p>
          </div>
          <div class="footer-section">
            <h4>Product</h4>
            <ul>
              <li><a href="#">Features</a></li>
              <li><a href="#">Pricing</a></li>
              <li><a href="#">API</a></li>
              <li><a href="#">Integrations</a></li>
            </ul>
          </div>
          <div class="footer-section">
            <h4>Company</h4>
            <ul>
              <li><a href="#">About</a></li>
              <li><a href="#">Blog</a></li>
              <li><a href="#">Careers</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
          </div>
          <div class="footer-section">
            <h4>Support</h4>
            <ul>
              <li><a href="#">Help Center</a></li>
              <li><a href="#">Documentation</a></li>
              <li><a href="#">Community</a></li>
              <li><a href="#">Status</a></li>
            </ul>
          </div>
        </div>
        <div class="footer-bottom">
          <p>&copy; 2024 HashDocs. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
// Component logic can be added here if needed
</script>

<style scoped>
.landing-page {
  min-height: 100vh;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Navigation */
.navbar {
  background: transparent;
  padding: 1rem 0;
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-logo h2 {
  margin: 0;
  color: white;
  font-weight: 700;
}

.nav-menu {
  display: flex;
  align-items: center;
  gap: 2rem;
}

.nav-link {
  text-decoration: none;
  color: white;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #ffd89b;
}

.cta-button {
  background: white;
  color: #667eea;
  border: none;
  padding: 0.75rem 1.5rem;
  border-radius: 25px;
  font-weight: 600;
  cursor: pointer;
  transition: transform 0.3s ease;
}

.cta-button:hover {
  transform: translateY(-2px);
  background: #ffd89b;
  color: #2c3e50;
}

/* Hero Section */
.hero {
  padding: 8rem 0 4rem;
  min-height: 100vh;
  display: flex;
  align-items: center;
}

.hero-container {
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 3rem;
}

.hero-title {
  font-size: 3.5rem;
  font-weight: 800;
  line-height: 1.2;
  margin-bottom: 1.5rem;
  color: white;
}

.gradient-text {
  background: linear-gradient(135deg, #98c9e9 0%, #1197f0 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-description {
  font-size: 1.25rem;
  line-height: 1.6;
  margin-bottom: 2rem;
  color: rgba(255, 255, 255, 0.9);
}

.hero-buttons {
  display: flex;
  gap: 1rem;
  margin-bottom: 3rem;
}

.primary-button {
  background: white;
  color: #667eea;
  border: none;
  padding: 1rem 2rem;
  border-radius: 30px;
  font-weight: 600;
  font-size: 1.1rem;
  cursor: pointer;
  transition: all 0.3s ease;
}

.primary-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

.secondary-button {
  background: transparent;
  color: white;
  border: 2px solid white;
  padding: 1rem 2rem;
  border-radius: 30px;
  font-weight: 600;
  font-size: 1.1rem;
  cursor: pointer;
  transition: all 0.3s ease;
}

.secondary-button:hover {
  background: white;
  color: #667eea;
  transform: translateY(-2px);
}

.hero-stats {
  display: flex;
  gap: 2rem;
}

.stat {
  text-align: center;
}

.stat-number {
  display: block;
  font-size: 2rem;
  font-weight: 700;
  color: white;
}

.stat-label {
  font-size: 0.9rem;
  color: rgba(255, 255, 255, 0.8);
}

/* Hero Video Section */
.hero-video-section {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.hero-video-container {
  width: 65%;
  max-width: 800px;
  height: 400px;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.hero-video {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 20px;
}

.video-fallback {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  padding: 2rem;
}

/* Features Section */
.features {
  padding: 6rem 0;
  background: white;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section-header {
  text-align: center;
  margin-bottom: 4rem;
}

.section-header h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: #2c3e50;
}

.section-header p {
  font-size: 1.2rem;
  color: #6c757d;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.feature-card {
  text-align: center;
  padding: 2rem;
  border-radius: 15px;
  background: #f8f9fa;
  transition: transform 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.feature-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1rem;
  color: #2c3e50;
}

.feature-card p {
  color: #6c757d;
  line-height: 1.6;
}

/* CTA Section */
.cta-section {
  padding: 6rem 0;
  background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
  color: white;
  text-align: center;
}

.cta-content h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

.cta-content p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  opacity: 0.9;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  margin-bottom: 2rem;
}

.cta-buttons .primary-button {
  background: #667eea;
  color: white;
}

.cta-buttons .secondary-button {
  background: transparent;
  color: white;
  border: 2px solid white;
}

.cta-buttons .secondary-button:hover {
  background: white;
  color: #2c3e50;
}

.large {
  padding: 1.25rem 2.5rem;
  font-size: 1.2rem;
}

.cta-note {
  font-size: 0.9rem;
  opacity: 0.7;
}

/* Footer */
.footer {
  background: #1a1a1a;
  color: white;
  padding: 3rem 0 1rem;
}

.footer-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-bottom: 2rem;
}

.footer-section h3,
.footer-section h4 {
  margin-bottom: 1rem;
  color: white;
}

.footer-section ul {
  list-style: none;
  padding: 0;
}

.footer-section ul li {
  margin-bottom: 0.5rem;
}

.footer-section ul li a {
  color: #ccc;
  text-decoration: none;
  transition: color 0.3s ease;
}

.footer-section ul li a:hover {
  color: white;
}

.footer-bottom {
  text-align: center;
  padding-top: 2rem;
  border-top: 1px solid #333;
  color: #ccc;
}

/* Responsive Design */
@media (max-width: 768px) {
  .nav-menu {
    display: none;
  }
  
  .hero-container {
    gap: 2rem;
  }
  
  .hero-title {
    font-size: 2.5rem;
  }
  
  .hero-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .hero-stats {
    justify-content: center;
  }
  
  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .features-grid {
    grid-template-columns: 1fr;
  }

  .hero-video-container {
    width: 90%;
    height: 300px;
  }
}
</style>