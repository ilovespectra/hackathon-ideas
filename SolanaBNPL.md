# SolanaBNPL - Buy Now Pay Later on the Solana Blockchain

## Description

SolanaBNPL is a decentralized financial application built on the Solana blockchain that offers a Buy Now Pay Later (BNPL) service. It enables users to make purchases and defer payments over a predefined period, making it easier for both lenders and borrowers to manage their finances. The application leverages the speed, security, and transparency of the Solana blockchain to provide a seamless and efficient BNPL experience.

## Key Features

- **Lender Staking:** Lenders can stake a loan position by providing collateral in the form of SOL and USDC. This collateralization ensures that the funds are available to cover the deferred payments from borrowers.

- **Borrower Redemption:** Borrowers can redeem loan positions to finance their purchases. They can select items, choose the BNPL option at checkout, and receive instant approval based on their creditworthiness and collateral provided by lenders.

- **Automatic Payments:** SolanaBNPL automates the repayment process. Borrowers agree to repay their loans in 25% installments every two weeks for a total of 8 weeks. The application ensures timely deductions from borrowers' accounts, with a fee of $1 per payment. For example, users pay an additional $4 when agreeing to split a payment 4 ways.

- **Purchase Splitting:** Purchases under $200 can be split for new users. Users can split incrementally larger purchases every time they successfully complete the final of 4 payments.

- **Security:** The application implements robust security measures to protect user funds and sensitive data. Access control mechanisms and audits are in place to prevent unauthorized interactions.

- **Oracle Integration:** To accurately calculate loan positions, SolanaBNPL integrates with a trusted price oracle service that provides real-time SOL/USDC price data.

- **Governance:** The program includes a governance model, allowing users to participate in decision-making and vote on proposed program upgrades or changes. 1-3% of all trading fees generated from the liquidity pool goes to the creators.

## Programs Required

1. **Staking Program:**
   - Handles lender staking of loan positions.
   - Manages collateral, including SOL and USDC deposits.
   - Ensures collateralization ratios are maintained.

2. **Redemption Program:**
   - Facilitates borrower redemption of loan positions.
   - Verifies eligibility and creditworthiness of borrowers.
   - Manages collateral release upon successful repayment.

3. **Payment Scheduler Program:**
   - Orchestrates the automatic payment schedule for borrowers.
   - Deducts 25% of the outstanding loan amount every two weeks, including a $1 fee per payment.
   - Manages payment status and notifications.

4. **Security Program:**
   - Implements access control and permissions.
   - Monitors and addresses security vulnerabilities.
   - Conducts security audits and code reviews.

5. **Oracle Integration Program:**
   - Integrates with a trusted price oracle service.
   - Fetches real-time SOL/USDC price data.
   - Updates loan positions based on the latest prices.

6. **Governance Program:**
   - Manages governance proposals and voting.
   - Executes program upgrades through community consensus.
   - Provides transparency in decision-making, with a portion of trading fees going to the creators.

7. **User Interface (UI) Program:**
   - Develops user-friendly interfaces for lenders and borrowers to interact with the application.
   - Displays account balances, loan status, and payment schedules.
   - Allows users to initiate actions such as staking, redemption, and voting.

8. **Documentation and Educational Program:**
   - Creates comprehensive documentation explaining how to use the application.
   - Offers educational resources on BNPL best practices, Solana, and blockchain security.

SolanaBNPL is designed to empower both lenders and borrowers by offering a secure and transparent BNPL solution on the Solana blockchain. It introduces innovative features such as purchase splitting, staked loans, and a liquidity pool, enhancing the overall user experience and financial opportunities.
