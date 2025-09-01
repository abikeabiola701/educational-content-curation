# Educational Content Curation Platform

A decentralized smart contract system for educational content quality assessment, curriculum alignment, and creator compensation built on the Stacks blockchain using Clarity.

## Overview

This platform provides a comprehensive solution for managing educational content through three core smart contracts:

### 🎯 Core Contracts

1. **Content Registry Contract** (`content-registry.clar`)
   - Content submission and metadata management
   - Peer review and quality assessment workflows
   - Content rating and reputation systems
   - Content lifecycle management

2. **Curriculum Alignment Contract** (`curriculum-alignment.clar`)
   - Educational standards mapping and alignment
   - Curriculum compatibility scoring
   - Standards compliance verification
   - Learning outcome tracking

3. **Creator Rewards Contract** (`creator-rewards.clar`)
   - Creator registration and verification
   - Usage-based compensation distribution
   - Revenue sharing mechanisms
   - Intellectual property licensing management

## 🛠️ Technology Stack

- **Blockchain**: Stacks
- **Smart Contract Language**: Clarity
- **Development Framework**: Clarinet 2.8.0
- **Testing**: Vitest with Clarinet testing harness
- **Node.js**: v20.6.1+

## 🚀 Getting Started

### Prerequisites

- [Clarinet](https://github.com/hirosystems/clarinet) 2.8.0+
- [Node.js](https://nodejs.org/) 18.0.0+
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/abikeabiola701/educational-content-curation.git
cd educational-content-curation

# Install dependencies
npm install

# Check contract syntax
clarinet check

# Run tests
npm test
```

## 📋 Project Structure

```
educational-content-curation/
├── contracts/              # Clarity smart contracts
│   ├── content-registry.clar
│   ├── curriculum-alignment.clar
│   └── creator-rewards.clar
├── tests/                  # Contract test files
├── settings/               # Network configurations
├── Clarinet.toml          # Project configuration
├── package.json           # Node.js dependencies
└── README.md              # This file
```

## 🔧 Development

### Testing Contracts

```bash
# Syntax check
clarinet check

# Run all tests
npm test

# Test specific contract
clarinet test tests/content-registry_test.ts
```

### Local Development

```bash
# Start local development environment
clarinet console

# Deploy contracts locally
clarinet integrate
```

## 📊 System Architecture

The platform operates through three interconnected but independent smart contracts:

- **Content Registry**: Manages the entire content lifecycle from submission to publication
- **Curriculum Alignment**: Ensures educational content meets academic standards
- **Creator Rewards**: Handles fair compensation and intellectual property rights

Each contract is self-contained with no cross-contract dependencies, ensuring modularity and security.

## 🎓 Use Cases

- **Educational Institutions**: Curate and verify academic content quality
- **Content Creators**: Receive fair compensation for educational materials
- **Students & Educators**: Access high-quality, standards-aligned content
- **Curriculum Developers**: Map content to educational frameworks
- **Quality Reviewers**: Participate in decentralized content assessment

## 📝 License

This project is developed for educational and demonstration purposes.

## 🤝 Contributing

This is a demonstration project. For production use, additional security audits and testing would be required.

---

Built with ❤️ using Clarity and the Stacks blockchain ecosystem.
