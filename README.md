# ♻️ GreenPoints ICP

GreenPoints ICP is a decentralized Web3 application that rewards citizens for their recycling actions, while promoting digital inclusion for people with disabilities. Built on the Internet Computer Protocol (ICP), this project combines sustainability, accessibility, and token-based incentives to foster real-world environmental action.

## 🌍 Vision

To create a more inclusive and sustainable world through blockchain technology by enabling people — especially those with disabilities — to earn and exchange points based on their contributions to recycling, transparency, and community engagement.

## 🔧 Features

- ♿ **Inclusive Design**: Tailored UI/UX for people with disabilities.
- 🪙 **Recycling Token System**: Earn GreenPoints based on recycling actions.
- 🧾 **Proof of Recycling**: Users upload photos or scan QR codes at partner locations.
- 🏪 **Points Redemption**: Exchange points for goods or services from local allies.
- 🧠 **ICP-based Smart Contracts**: Fully on-chain logic for reward validation and distribution.
- 📊 **Impact Analytics Dashboard**: Visual reports for users and communities.

## 🚀 Tech Stack

- **Frontend**: React + TailwindCSS
- **Backend**: Motoko Smart Contracts on ICP
- **Identity/Auth**: Internet Identity (II)
- **Database**: ICP Canisters
- **Other**: QR code scanner, OCR tools (planned)

## 📦 Repository Structure

```
greenpoints-icp/
├── src/                 # Frontend React code
├── backend/             # Motoko canister logic
├── public/              # Static files
├── docs/                # Architecture, vision, roadmap
└── README.md
```

## 🛠️ Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/geobricex/GreenPointsICP.git
   cd GreenPointsICP
   ```

2. **Install frontend dependencies:**
   ```bash
   npm install
   ```

3. **Start local dev server:**
   ```bash
   dfx start --background
   dfx deploy
   npm run dev
   ```

> Note: Make sure to have `dfx` (DFINITY SDK) and Node.js installed on your machine.

## 📹 Demo

A full video demonstration is available at:  
**[Demo Video (YouTube/Drive link)](https://...)**

## 📑 Project Motivation

Recycling practices lack transparency and incentivization. This project bridges that gap using decentralized technology and prioritizes inclusion by designing interfaces accessible to users with disabilities. GreenPoints ICP is not just a recycling tracker — it's a step toward environmental justice and universal participation.

## 💬 Contact & Contribution

We welcome collaborators!  
Join our Discord or reach out:

- Team Lead: **@IngGeo**
- Email: greenpoints.icp@proton.me
- Discord: [GreenPoints ICP](https://discord.gg/...)

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
