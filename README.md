# HashDocs Landing Page

A modern, responsive landing page for **HashDocs** - a blockchain-based document signing platform built on Polygon network.

## 🚀 About HashDocs

HashDocs is a revolutionary document signing platform that combines the security and immutability of blockchain technology with user-friendly design. Built on the Polygon network, it offers:

- **Blockchain Signatures**: Cryptographic signatures stored permanently on Polygon blockchain
- **Immutable Records**: Tamper-proof document storage with permanent verification
- **Web3 Security**: Decentralized architecture eliminating single points of failure
- **User-Friendly**: Accessible to mainstream users without requiring crypto knowledge
- **Cost-Effective**: Minimal transaction fees on Polygon's Layer 2 solution

## 🎨 Landing Page Features

This mock landing page showcases:

- **Hero Section**: Compelling headline with looping video demonstration
- **Feature Grid**: 6 key benefits highlighting blockchain advantages
- **Competitive Comparison**: Side-by-side comparison with traditional e-signature platforms
- **FAQ Section**: Interactive accordion with common questions and answers
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Glass morphism effects, smooth animations, and professional styling

## 🛠️ Technology Stack

- **Vue 3** - Progressive JavaScript framework
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and dev server
- **CSS3** - Modern styling with gradients, animations, and glass morphism
- **Responsive Design** - Mobile-first approach

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd hashdocs-ladingpage
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### 4. Build for Production

```bash
npm run build
```

### 5. Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── views/
│   └── HomeView.vue          # Main landing page component
├── assets/
│   ├── main.css             # Global styles
│   └── base.css             # CSS custom properties and base styles
├── router/
│   └── index.ts             # Vue Router configuration
└── App.vue                  # Root component
```

## 🎯 Future Implementation

This landing page serves as a **mockup and prototype** for the full HashDocs platform. The actual implementation will include:

- **Backend Integration**: Smart contracts on Polygon network
- **Web3 Wallet Integration**: MetaMask, WalletConnect, and other wallet providers
- **Document Management**: Upload, signing, and verification workflows
- **User Authentication**: Account creation and management
- **Payment Processing**: Subscription and transaction fee handling
- **API Integration**: Blockchain interaction and document storage

## 🧪 Testing

### Run Unit Tests

```bash
npm run test:unit
```

### Run End-to-End Tests

```bash
# Install browsers for the first run
npx playwright install

# Run E2E tests
npm run test:e2e
```

### Lint Code

```bash
npm run lint
```

## 🎨 Customization

The landing page is fully customizable:

- **Colors**: Modify CSS custom properties in `src/assets/base.css`
- **Content**: Update text and images in `src/views/HomeView.vue`
- **Styling**: Adjust component styles in the `<style>` section
- **Layout**: Modify the HTML structure as needed

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is for demonstration purposes as part of the HashDocs platform development.

## 🤝 Contributing

This is a mock landing page for the HashDocs project. For contributions to the main platform, please refer to the main HashDocs repository.

---

**Note**: This is a static landing page mockup. The full HashDocs platform will include backend services, smart contracts, and Web3 integration for complete document signing functionality.
