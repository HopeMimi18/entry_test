# 🚀 Blockchain Developer Entry Test (3-Hour Challenge)

Welcome to the entry test! You have **3 hours** to complete the entire assessment. 

> [!IMPORTANT]
> You must complete **BOTH** Version 1 (Skills Marketplace) and Version 2 (Secure Lottery) for all parts of this assessment.

---

## ⏱️ Timeline & Submission

- **Duration:** 3 Hours
- **Submission:** Fork this repo, commit regularly (every 15-30 mins), and push to your fork.

---

## 📋 Prerequisites

Ensure you have:
- **Node.js** (v20+) & **npm**
- **Git** configured (`git config user.name "Your Name"`)
- **VS Code** (Solidity extension by Juan Blanco recommended)
- A GitLab/GitHub account to host your fork

---

## 🚀 Getting Started

### 1. Fork & Clone
1. **Fork** this repository to your own namespace.
2. Clone your forked repo:
   ```bash
   git clone [YOUR_FORK_URL]
   cd blockchain_dev_entry_test
   ```

### 2. Environment Setup
```bash
# Install dependencies (Hardhat + Toolbox)
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox

# Initialize Hardhat (if not already initialized)
npx hardhat 
# Choose: Create an empty hardhat.config.js
```

---

## 🛠️ Assessment Structure

### Part A: MCQ & Theory (`PartA_MCQ_Answers.md`)
- Answer **ALL** questions for **BOTH** Version 1 and Version 2.
- Provide clear reasoning for your choices.

### Part B: Design & Implementation
You are provided with two contract skeletons in `contracts/`:
1. `SkillsMarketplace.sol` (Version 1)
2. `SecureLottery.sol` (Version 2)

**Your Tasks for BOTH contracts:**
1. **Implementation:** Complete the `TODO` sections in both `.sol` files.
2. **Design Documentation:** Fill in `PartB_Design.md` detailing your architectural choices, security measures, and trade-offs.
3. **Test Planning:** Fill in `PartB_Tests.md` with your test scenarios.
4. **Test Implementation:** Create a `test/` directory and implement automated tests for both contracts using Hardhat.
   - Example: `test/SkillsMarketplace.test.js` and `test/SecureLottery.test.js`
   - Run tests with: `npx hardhat test`

---

## 📁 File Structure

```
blockchain_dev_entry_test/
├── contracts/
│   ├── SkillsMarketplace.sol     # Complete this (Scenario 1)
│   └── SecureLottery.sol         # Complete this (Scenario 2)
├── test/                         # [NEW] Create your tests here
├── PartA_MCQ_Answers.md          # Complete ALL questions
├── PartB_Design.md               # Document BOTH designs
├── PartB_Tests.md                # Describe BOTH test plans
└── docs/                         # Reference materials
```

---

## 💡 Tips for Success
- **Security Matters:** We check for Reentrancy, Access Control, and Integer Handling.
- **Gas is Money:** Mention gas optimization strategies in your design document.
- **Commit History:** We look at your commit frequency to understand your workflow.

**All the best!**