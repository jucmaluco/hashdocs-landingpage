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
          <a href="#login" class="nav-link">Login</a>
          <a href="#signup" class="nav-link">Signup</a>
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
          <p>Everything you need to manage your documentation</p>
        </div>
        <div class="features-grid">
          <div class="feature-card">
            <div class="feature-icon">✍️</div>
            <h3>Blockchain Signatures</h3>
            <p>Sign documents with cryptographic signatures stored permanently on Polygon blockchain for ultimate authenticity.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🔐</div>
            <h3>Immutable Records</h3>
            <p>Once signed, documents become tamper-proof with permanent blockchain verification and audit trails.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">⚡</div>
            <h3>Polygon Network</h3>
            <p>Lightning-fast transactions with minimal gas fees on Polygon's Layer 2 solution for cost-effective operations.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🛡️</div>
            <h3>Web3 Security</h3>
            <p>Decentralized architecture eliminates single points of failure and ensures maximum document security.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🔍</div>
            <h3>Verification Portal</h3>
            <p>Instantly verify document authenticity and signature validity through our public blockchain explorer.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">🌐</div>
            <h3>Global Access</h3>
            <p>Access and sign documents from anywhere in the world with just a Web3 wallet connection.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Comparison Section -->
    <section class="comparison-section">
      <div class="container">
        <div class="section-header">
          <h2 style="color: white; text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);">Compare with the Competition</h2>
          <p style="color: rgba(255, 255, 255, 0.9); font-size: 1.1rem;">See how HashDocs stands out from traditional and blockchain document signing solutions</p>
        </div>
        <div class="comparison-table-container">
          <table class="comparison-table">
            <thead>
              <tr>
                <th class="feature-column">Features</th>
                <th class="competitor-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder docu">DocuSign</div>
                  </div>
                </th>
                <th class="competitor-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder zap">ZapSign</div>
                  </div>
                </th>
                <th class="competitor-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder d4">D4Sign</div>
                  </div>
                </th>
                <th class="competitor-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder id">id Sign</div>
                  </div>
                </th>
                <th class="competitor-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder w3">w3sign</div>
                  </div>
                </th>
                <th class="hashdocs-column">
                  <div class="competitor-logo">
                    <div class="logo-placeholder hash">HashDocs</div>
                  </div>
                </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="feature-name">Decentralized Management</td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell hashdocs"><span class="icon yes">✓</span></td>
              </tr>
              <tr>
                <td class="feature-name">Non-Crypto User Friendly</td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell hashdocs"><span class="icon yes">✓</span></td>
              </tr>
              <tr>
                <td class="feature-name">Identity Validation</td>
                <td class="comparison-cell"><span class="icon conditional">$</span></td>
                <td class="comparison-cell"><span class="icon conditional">$</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell hashdocs"><span class="icon yes">✓</span></td>
              </tr>
              <tr>
                <td class="feature-name">Distributed Storage</td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell hashdocs"><span class="icon yes">✓</span></td>
              </tr>
              <tr>
                <td class="feature-name">Free Plan / Trial</td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon yes">✓</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell"><span class="icon no">✗</span></td>
                <td class="comparison-cell hashdocs"><span class="icon yes">✓</span></td>
              </tr>
            </tbody>
          </table>
        </div>
        
      </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq-section">
      <div class="container">
        <div class="faq-header">
          <h2>Frequently Asked Questions</h2>
          <p>Everything you need to know about HashDocs</p>
        </div>
        <div class="faq-container">
          <div class="faq-item" :class="{ active: activeFaq === 0 }" @click="toggleFaq(0)">
            <div class="faq-question">
              <h3>What is HashDocs and how does it work?</h3>
              <span class="faq-icon">{{ activeFaq === 0 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 0">
              <p>HashDocs is a blockchain-based document signing platform that uses Polygon network for secure, immutable document storage and verification. Simply upload your document, add signers, and get cryptographic signatures stored permanently on the blockchain.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 1 }" @click="toggleFaq(1)">
            <div class="faq-question">
              <h3>Do I need cryptocurrency knowledge to use HashDocs?</h3>
              <span class="faq-icon">{{ activeFaq === 1 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 1">
              <p>Not at all! HashDocs is designed for mainstream users. While we use blockchain technology for security, our interface is as simple as traditional e-signature platforms. You don't even need a Web3 wallet to use HashDocs, we immediately create one for you and attatch it to your account.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 2 }" @click="toggleFaq(2)">
            <div class="faq-question">
              <h3>How secure are my documents on the blockchain?</h3>
              <span class="faq-icon">{{ activeFaq === 2 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 2">
              <p>Your documents are extremely secure. Once signed, they become tamper-proof and permanently stored on the Polygon blockchain. The cryptographic signatures ensure authenticity and provide an immutable audit trail that can be verified by anyone, anywhere.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 3 }" @click="toggleFaq(3)">
            <div class="faq-question">
              <h3>What are the costs for using HashDocs?</h3>
              <span class="faq-icon">{{ activeFaq === 3 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 3">
              <p>HashDocs offers a free tier with basic features. Premium plans include advanced features like bulk signing, custom branding, and priority support. </p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 4 }" @click="toggleFaq(4)">
            <div class="faq-question">
              <h3>Can I verify document authenticity without using HashDocs?</h3>
              <span class="faq-icon">{{ activeFaq === 4 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 4">
              <p>Yes! Our public verification portal allows anyone to verify document authenticity using just the document hash. This transparency ensures trust and eliminates the need for centralized verification systems.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 5 }" @click="toggleFaq(5)">
            <div class="faq-question">
              <h3>How does HashDocs compare to DocuSign?</h3>
              <span class="faq-icon">{{ activeFaq === 5 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 5">
              <p>While DocuSign is centralized and stores documents on their servers, HashDocs uses blockchain for decentralized, tamper-proof storage. Our documents are permanently verifiable, more secure, and don't rely on a single company's infrastructure. Apart from this, HashDocs also uses a multi-step identity verifyer, in compliance with national Brazilian legislation.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 6 }" @click="toggleFaq(6)">
            <div class="faq-question">
              <h3>What file formats does HashDocs support?</h3>
              <span class="faq-icon">{{ activeFaq === 6 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 6">
              <p>At the moment, Hashdocks only supports files on PDF format. We're continuously adding support for more formats based on user feedback and demand.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 7 }" @click="toggleFaq(7)">
            <div class="faq-question">
              <h3>Is there a mobile app available?</h3>
              <span class="faq-icon">{{ activeFaq === 7 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 7">
              <p>Even though HashDocs is a web-based platform, it is fully responsive and works seamlessly on mobile devices. You can sign documents, verify authenticity, and manage your account from any smartphone or tablet.</p>
            </div>
          </div>

          <div class="faq-item" :class="{ active: activeFaq === 8 }" @click="toggleFaq(8)">
            <div class="faq-question">
              <h3>What's on the HashDocs roadmap?</h3>
              <span class="faq-icon">{{ activeFaq === 8 ? '−' : '+' }}</span>
            </div>
            <div class="faq-answer" v-show="activeFaq === 8">
              <p>We're currently working on advanced features including multi-signature workflows, integration with popular business tools, enhanced identity verification, and support for additional blockchain networks.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section">
      <div class="container">
        <div class="cta-content">
          <h2>Ready to Get Started?</h2>
          <p>Join our community of users already using HashDocs to handle their documentation.</p>
          <div class="cta-buttons">
            <button class="primary-button large">Create an account and start signing.</button>
          </div>
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
import { ref } from 'vue'

// FAQ accordion functionality
const activeFaq = ref<number | null>(null)

const toggleFaq = (index: number) => {
  activeFaq.value = activeFaq.value === index ? null : index
}
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

/* Comparison Section */
.comparison-section {
  padding: 6rem 0;
  background: linear-gradient(135deg, #6797c7 0%, #4a6fa5 50%, #2c3e50 100%);
  position: relative;
  overflow: hidden;
}

.comparison-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="75" cy="75" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="50" cy="10" r="0.5" fill="rgba(255,255,255,0.05)"/><circle cx="10" cy="60" r="0.5" fill="rgba(255,255,255,0.05)"/><circle cx="90" cy="40" r="0.5" fill="rgba(255,255,255,0.05)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
  opacity: 0.3;
  pointer-events: none;
}

.comparison-table-container {
  overflow-x: auto;
  margin: 3rem 0;
  border-radius: 20px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
  background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  position: relative;
  z-index: 1;
}

.comparison-table {
  width: 100%;
  border-collapse: collapse;
  background: transparent;
  border-radius: 20px;
  overflow: hidden;
  min-width: 800px;
}

.comparison-table th,
.comparison-table td {
  padding: 1.5rem 1rem;
  text-align: center;
  border-bottom: 1px solid #e9ecef;
}

.comparison-table th {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  font-weight: 700;
  font-size: 0.9rem;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
  position: relative;
}

.comparison-table th::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 2px;
  background: linear-gradient(90deg, transparent 0%, rgba(255, 255, 255, 0.3) 50%, transparent 100%);
}

.comparison-table tbody tr {
  transition: all 0.3s ease;
}

.comparison-table tbody tr:hover {
  background: rgba(102, 126, 234, 0.05);
  transform: translateY(-1px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.feature-column {
  text-align: left !important;
  background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%) !important;
  font-weight: 700;
  min-width: 200px;
  color: white !important;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
}

.feature-name {
  text-align: left;
  font-weight: 600;
  color: #2c3e50;
}

.competitor-column {
  min-width: 120px;
}

.hashdocs-column {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%) !important;
  min-width: 120px;
  position: relative;
}

.hashdocs-column::before {
  content: '⭐';
  position: absolute;
  top: -5px;
  right: -5px;
  font-size: 1.2rem;
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 1; }
  50% { transform: scale(1.1); opacity: 0.8; }
}

.comparison-cell {
  font-size: 1.2rem;
}

.comparison-cell.hashdocs {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.15) 0%, rgba(118, 75, 162, 0.15) 100%);
  font-weight: 700;
  color: #667eea;
  position: relative;
}

.comparison-cell.hashdocs::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.1) 0%, rgba(118, 75, 162, 0.1) 100%);
  border-radius: 8px;
  z-index: -1;
}

.competitor-logo {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 0.5rem;
}

.logo-placeholder {
  padding: 0.5rem 1rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 600;
  color: white;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.logo-placeholder::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
  transition: left 0.5s ease;
}

.logo-placeholder:hover::before {
  left: 100%;
}

.logo-placeholder.docu {
  background: #6c5ce7;
}

.logo-placeholder.zap {
  background: #00b894;
}

.logo-placeholder.d4 {
  background: #2d3436;
}

.logo-placeholder.id {
  background: #0984e3;
}

.logo-placeholder.w3 {
  background: #636e72;
}

.logo-placeholder.hash {
  background: linear-gradient(135deg, rgba(255, 255, 255, 0.3) 0%, rgba(255, 255, 255, 0.1) 100%);
  border: 2px solid rgba(255, 255, 255, 0.4);
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
}

.icon {
  display: inline-block;
  width: 28px;
  height: 28px;
  border-radius: 50%;
  line-height: 28px;
  font-weight: bold;
  font-size: 16px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
}

.icon:hover {
  transform: scale(1.1);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.3);
}

.icon.yes {
  background: #00b894;
  color: white;
}

.icon.no {
  background: #e17055;
  color: white;
}

.icon.conditional {
  background: #fdcb6e;
  color: #2d3436;
}

.comparison-legend {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-top: 3rem;
  flex-wrap: wrap;
  background: rgba(255, 255, 255, 0.1);
  padding: 2rem;
  border-radius: 15px;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.legend-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.9rem;
  color: white;
  font-weight: 500;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
}

/* FAQ Section */
.faq-section {
  padding: 6rem 0;
  background: linear-gradient(135deg, #2c3e50 0%, #34495e 50%, #2c3e50 100%);
  position: relative;
  overflow: hidden;
}

.faq-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="faq-grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.05)"/><circle cx="75" cy="75" r="1" fill="rgba(255,255,255,0.05)"/><circle cx="50" cy="10" r="0.5" fill="rgba(255,255,255,0.03)"/><circle cx="10" cy="60" r="0.5" fill="rgba(255,255,255,0.03)"/><circle cx="90" cy="40" r="0.5" fill="rgba(255,255,255,0.03)"/></pattern></defs><rect width="100" height="100" fill="url(%23faq-grain)"/></svg>');
  opacity: 0.4;
  pointer-events: none;
}

.faq-header {
  text-align: center;
  margin-bottom: 4rem;
  position: relative;
  z-index: 1;
}

.faq-header h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: white;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

.faq-header p {
  font-size: 1.2rem;
  color: rgba(255, 255, 255, 0.8);
}

.faq-container {
  max-width: 800px;
  margin: 0 auto;
  position: relative;
  z-index: 1;
}

.faq-item {
  background: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  margin-bottom: 1rem;
  overflow: hidden;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  transition: all 0.3s ease;
  cursor: pointer;
}

.faq-item:hover {
  background: rgba(255, 255, 255, 0.15);
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

.faq-item.active {
  background: rgba(102, 126, 234, 0.2);
  border-color: rgba(102, 126, 234, 0.4);
}

.faq-question {
  padding: 1.5rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: all 0.3s ease;
}

.faq-question h3 {
  font-size: 1.1rem;
  font-weight: 600;
  color: white;
  margin: 0;
  flex: 1;
  padding-right: 1rem;
}

.faq-icon {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.2);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.2rem;
  font-weight: bold;
  color: white;
  transition: all 0.3s ease;
  flex-shrink: 0;
}

.faq-item.active .faq-icon {
  background: rgba(102, 126, 234, 0.8);
  transform: rotate(180deg);
}

.faq-answer {
  padding: 0 2rem 1.5rem 2rem;
  animation: slideDown 0.3s ease;
}

.faq-answer p {
  color: rgba(255, 255, 255, 0.9);
  line-height: 1.6;
  margin: 0;
  font-size: 0.95rem;
}

@keyframes slideDown {
  from {
    opacity: 0;
    transform: translateY(-10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
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

  .comparison-table-container {
    margin: 2rem 0;
  }

  .comparison-table th,
  .comparison-table td {
    padding: 1rem 0.5rem;
    font-size: 0.8rem;
  }

  .feature-column {
    min-width: 150px;
  }

  .competitor-column,
  .hashdocs-column {
    min-width: 80px;
  }

  .logo-placeholder {
    padding: 0.3rem 0.5rem;
    font-size: 0.7rem;
  }

  .comparison-legend {
    gap: 1rem;
  }

  .legend-item {
    font-size: 0.8rem;
  }

  .faq-header h2 {
    font-size: 2rem;
  }

  .faq-header p {
    font-size: 1rem;
  }

  .faq-question {
    padding: 1rem 1.5rem;
  }

  .faq-question h3 {
    font-size: 1rem;
  }

  .faq-answer {
    padding: 0 1.5rem 1rem 1.5rem;
  }

  .faq-answer p {
    font-size: 0.9rem;
  }
}
</style>