# Leverme Protocol 🚀

Leverme is a decentralized leverage trading and liquidity pool protocol built on Monad. 

It enables users to amplify their trading positions through borrowing and efficiently manage collateral assets via an integrated liquidity pool system. 

The project supports **Mon**, **USDT**, and **USDC**, and is tightly integrated with Uniswap V2 Contract for seamless token swaps.

---

## Features ✨

- **Leverage Trading**  
  Use collateral to open leveraged positions, amplifying your trading opportunities by borrowing funds.

- **Liquidity Pools**  
  Deposit assets to receive LP tokens, participate in liquidity provision, and manage your assets easily.

- **Uniswap V2/v3 Like Contract Integration**  
  Directly interact with the Uniswap V2 Router for efficient token swaps and trading operations.

- **Flexible Borrowing & Repayment**  
  Borrow without extensive collateral requirements, and enjoy flexible partial repayments with a built-in fee mechanism.

- **Secure Smart Contracts**  
  Built using OpenZeppelin’s secure modules (e.g., Ownable), ensuring robust security for all transactions.

---

## Smart Contract Overview 🔐

### LeverageTrading Contract

- **Functionality:**  
  - **Open Position:** Use ETH, USDT, or USDC as collateral to borrow funds and buy target tokens via Uniswap.  
  - **Close Position:** Sell tokens, calculate fees, repay borrowed funds, and return the remaining assets to the user.  
  - **Event Logging:** Track position openings and closures on-chain for transparency and auditability.

- **Key Logic:**  
  - Integrates borrowing functions from the Vault contract.  
  - Supports multiple token swap paths to adapt to various market conditions.  
  - Implements leverage checks and liquidation criteria to manage risk.

### Vault Contract

- **Functionality:**  
  - **Deposit:** Support for depositing ETH, USDT, and USDC in exchange for LP tokens.  
  - **Withdraw:** Redeem LP tokens to withdraw the underlying assets.  
  - **Borrow:** Lend assets to whitelisted users without collateral.  
  - **Repay:** Flexible partial repayments with a fee structure to maintain pool stability.

- **Key Logic:**  
  - Utilizes an LP token mechanism to incentivize liquidity provision.  
  - Enforces whitelist access for borrowing to enhance system security.  
  - Automatically collects fees to support the sustainability of the protocol.

---

## How to Interact 🚀

- Visit [Our App](https://leverme.xyz/)
- Use [Web3.js](https://web3js.readthedocs.io/) or [Ethers.js](https://docs.ethers.io/) to interact with the contracts.
- Utilize the Uniswap V2 interface for token swapping functionalities.
- Monitor contract events to track trading positions and liquidity pool activities.

---

## Contributing & Feedback 💡

We welcome contributions and feedback! Feel free to submit PRs or open issues.  
- **Contribution Guidelines:** Please refer to [CONTRIBUTING.md](CONTRIBUTING.md).  
- **Community Discussion:** Join our community to discuss ideas and improvements.

---

## License 📄

This project is licensed under the [MIT License](LICENSE).

---

## Contact 📬

For any inquiries or partnership opportunities, please reach out at: [Telegram](https://t.me/wikig16)

---

Happy Trading! 🚀💰  
*The Leverme Team*
