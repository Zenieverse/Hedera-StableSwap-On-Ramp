# Hedera-StableSwap-On-Ramp
A decentralized application enabling seamless fiat-to-crypto onboarding, stablecoin minting, and token swaps on the Hedera network — complete with HCS settlement transparency and Mirror Node liquidity analytics.

https://vimeo.com/1133448870

https://poe.com/Hedera-StableSwap-OR

The vision for Hedera-StableSwap-On-Ramp is to become the definitive, intelligence-driven gateway for bringing global fiat liquidity into the Hedera ecosystem, setting a new standard for stability, transparency, and ease of use in decentralized finance.

Vision Statement
"To unlock the next era of mass digital asset adoption by providing an enterprise-grade, intelligently guided, and fully transparent on-ramp that turns the complexity of fiat-to-crypto conversion into a single, seamless, stable experience on the Hedera network."

Strategic Pillars of the Vision
This vision is supported by the unique technological advantages and features of the dApp:

1. The Pillar of Enterprise-Grade Stability and Speed

Goal: Eliminate volatility and friction from the onboarding process.

Focus: Leveraging Hedera's high-throughput, fixed-fee infrastructure to ensure that minting stablecoins and executing swaps are not just fast, but reliably cost-predictable—a critical factor for enterprise and institutional adoption. We will be the most reliable entry point for value onto the Hedera network.

2. The Pillar of Intelligent Liquidity (Gemini API Integration)

Goal: Turn raw data into actionable intelligence for every user.

Focus: Utilizing the Gemini API to analyze complex Mirror Node data, generating real-time, human-readable market sentiment, optimizing swap routing, and summarizing HCS-recorded transactions. The platform will proactively guide users toward the best trades and provide the clearest financial transparency, democratizing access to professional-grade market analysis.

3. The Pillar of Unrivaled Transparency (HCS Settlement)

Goal: Build unshakeable trust by making every action verifiable.

Focus: Treating every fiat on-ramp, stablecoin mint, and token swap as an auditable event recorded via the Hedera Consensus Service (HCS). This ensures transactions are secured with military-grade finality and an immutable, publicly verifiable timestamp, making the dApp the industry benchmark for regulatory compliance and settlement transparency.

4. The Pillar of Seamless Onboarding

Goal: Lower the barrier to entry for the next billion crypto users.

Focus: Abstracting away the technical complexities of wallets, keys, and network fees, providing a user experience as simple as traditional online banking. By integrating robust KYC/AML tools and offering AI-powered assistance, we make it effortless for any user, from retail to corporate, to acquire the stable digital assets needed to participate in the Hedera-powered economy.

The Hedera-StableSwap-On-Ramp dApp is not just a decentralized exchange (DEX); it's an intelligent, compliant, and lightning-fast financial gateway designed to bridge traditional finance (fiat) with the Hedera ecosystem.

Here is a full description of the application, detailing its core functionalities, unique advantages, and the role of the Gemini AI integration.

Hedera-StableSwap-On-Ramp: Application Description
The Hedera-StableSwap-On-Ramp dApp is a next-generation DeFi primitive built natively on the Hedera Hashgraph public network. Its primary function is to serve as a low-friction, high-transparency entry point for users and institutions seeking to acquire digital assets, specifically stablecoins, and perform efficient token swaps.

Core Functions

The dApp is structured around three critical features:

Fiat-to-Stablecoin On-Ramp: This is the primary function. Users connect their traditional bank accounts (via integrated third-party payment processors) to instantly convert fiat currency (USD, EUR, etc.) into Hedera-native stablecoins (like USDC on Hedera).

Advantage: By leveraging Hedera’s speed and fixed, low fees, this process ensures immediate settlement, avoiding the long wait times and unpredictable gas costs of other networks.

StableSwap Protocol: The dApp incorporates a custom Automated Market Maker (AMM) optimized for exchanging stable assets (e.g., USDC to USDT, or even stablecoin to fiat-pegged CBDCs).

Advantage: The swap minimizes slippage for large transactions and supports the quick exchange of stable assets, essential for payments and treasury management.

Token Swaps: Users can easily exchange their newly acquired stablecoins for other Hedera ecosystem tokens (e.g., Stablecoin ↔ HBAR, or Stablecoin ↔ DAO tokens).

Unique Differentiators

The application’s strength lies in how it utilizes Hedera’s specialized services and the integrated AI:

A. Hedera Consensus Service (HCS) Transparency

Every transaction—from the fiat conversion instruction to the stablecoin minting event and the final token swap—is logged as a message on the Hedera Consensus Service (HCS).

This provides a public, immutable, and verifiable record with a cryptographically secure consensus timestamp, delivering the highest level of auditability and compliance readiness.

B. Mirror Node Liquidity Analytics

The dApp actively pulls and processes real-time transaction data and token supply metrics from Hedera Mirror Nodes.

This data is fed into the Gemini API to generate the "Gemini Liquidity Analysis," which provides users with professional insights on market depth, volatility warnings, and optimal trade timing, all in simple language.

C. AI-Powered User Experience (Gemini Integration)

The application uses the Gemini API to streamline complex DeFi operations:

Smart Transaction Summaries: Instead of showing raw transaction hashes and hexadecimal data, Gemini converts complex transaction details into a concise, human-readable summary for easy activity tracking.

Liquidity Analysis: As noted above, it translates raw on-chain data into simple, actionable market intelligence.

Onboarding Assistance: The integrated chatbot acts as an AI assistant, guiding new users step-by-step through the on-ramp and stablecoin minting process, reducing friction and support costs.

In essence, Hedera-StableSwap-On-Ramp is designed to be the smartest, fastest, and most transparent bridge between traditional money and the Hedera DeFi world.

<title>Hedera StableSwap On-Ramp</title> <script src="https://cdn.tailwindcss.com"></script> <script src="https://unpkg.com/big.js@6.2.1/big.min.js"></script> <script> tailwind.config = { theme: { extend: { colors: { primary: '#5D5CDE', 'hedera-green': '#00D4AA', 'dark-bg': '#181818' } } }, darkMode: 'class' } </script>
H
Hedera StableSwap On-Ramp

Wallet Disconnected
Connect HashPack
    <!-- Navigation -->
    <nav class="bg-gray-100 dark:bg-gray-800 border-b border-gray-200 dark:border-gray-700">
        <div class="container mx-auto px-4">
            <div class="flex space-x-1">
                <button class="nav-tab active px-4 py-3 text-sm font-medium" data-tab="dashboard">Dashboard</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="mint">Mint Tokens</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="swap">Swap</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="pools">Liquidity Pools</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="redeem">Redeem</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="governance">Governance</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="analytics">Analytics</button>
                <button class="nav-tab px-4 py-3 text-sm font-medium" data-tab="logs">HCS Logs</button>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-6">
        <!-- Dashboard Tab -->
        <div id="dashboard-tab" class="tab-content">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                <div class="bg-gradient-to-r from-primary to-purple-600 text-white p-6 rounded-xl">
                    <h3 class="text-sm font-medium opacity-90">Total Value Locked</h3>
                    <p class="text-2xl font-bold mt-1" id="total-tvl">$0</p>
                </div>
                <div class="bg-gradient-to-r from-hedera-green to-green-500 text-white p-6 rounded-xl">
                    <h3 class="text-sm font-medium opacity-90">USDH Minted</h3>
                    <p class="text-2xl font-bold mt-1" id="usdh-minted">0</p>
                </div>
                <div class="bg-gradient-to-r from-blue-500 to-blue-600 text-white p-6 rounded-xl">
                    <h3 class="text-sm font-medium opacity-90">Active Pools</h3>
                    <p class="text-2xl font-bold mt-1" id="active-pools">0</p>
                </div>
                <div class="bg-gradient-to-r from-orange-500 to-red-500 text-white p-6 rounded-xl">
                    <h3 class="text-sm font-medium opacity-90">24h Volume</h3>
                    <p class="text-2xl font-bold mt-1" id="volume-24h">$0</p>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h3 class="text-lg font-semibold mb-4">Your Portfolio</h3>
                    <div id="portfolio-balances" class="space-y-3">
                        <div class="flex justify-between items-center py-2 border-b border-gray-100 dark:border-gray-700">
                            <span class="text-gray-600 dark:text-gray-400">HBAR</span>
                            <span class="font-medium">0.00</span>
                        </div>
                        <div class="flex justify-between items-center py-2 border-b border-gray-100 dark:border-gray-700">
                            <span class="text-gray-600 dark:text-gray-400">USDH</span>
                            <span class="font-medium">0.00</span>
                        </div>
                        <div class="flex justify-between items-center py-2">
                            <span class="text-gray-600 dark:text-gray-400">Total Value</span>
                            <span class="font-bold text-primary">$0.00</span>
                        </div>
                    </div>
                </div>

                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h3 class="text-lg font-semibold mb-4">Recent Activity</h3>
                    <div id="recent-activity" class="space-y-3">
                        <div class="text-center text-gray-500 dark:text-gray-400 py-4">
                            No recent activity
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Mint Tokens Tab -->
        <div id="mint-tab" class="tab-content hidden">
            <div class="max-w-md mx-auto">
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h2 class="text-xl font-semibold mb-6">Mint USDH Stablecoin</h2>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">Fiat Amount (USD)</label>
                            <input type="number" id="fiat-amount" placeholder="100.00" step="0.01" min="0"
                                class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium mb-2">Payment Method</label>
                            <select id="payment-method" 
                                class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                <option value="card">Credit/Debit Card</option>
                                <option value="bank">Bank Transfer</option>
                                <option value="paypal">PayPal</option>
                            </select>
                        </div>

                        <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded-lg">
                            <div class="flex justify-between text-sm mb-2">
                                <span>Processing Fee (0.5%)</span>
                                <span id="processing-fee">$0.00</span>
                            </div>
                            <div class="flex justify-between font-medium">
                                <span>USDH to Receive</span>
                                <span id="usdh-receive">0.00 USDH</span>
                            </div>
                        </div>

                        <button id="mint-btn" class="w-full bg-primary text-white py-3 rounded-lg font-medium hover:bg-purple-600 transition-colors">
                            Mint USDH
                        </button>
                    </div>
                </div>
            </div>
        </div>

        <!-- Swap Tab -->
        <div id="swap-tab" class="tab-content hidden">
            <div class="max-w-md mx-auto">
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h2 class="text-xl font-semibold mb-6">Token Swap</h2>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">From</label>
                            <div class="flex space-x-2">
                                <select id="from-token" 
                                    class="flex-1 px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                    <option value="HBAR">HBAR</option>
                                    <option value="USDH">USDH</option>
                                </select>
                                <input type="number" id="from-amount" placeholder="0.0" step="0.01" min="0"
                                    class="flex-1 px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                            </div>
                            <div class="text-xs text-gray-500 mt-1">Balance: <span id="from-balance">0.00</span></div>
                        </div>

                        <div class="flex justify-center">
                            <button id="swap-direction" class="p-2 bg-gray-100 dark:bg-gray-700 rounded-full hover:bg-gray-200 dark:hover:bg-gray-600 transition-colors">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4"></path>
                                </svg>
                            </button>
                        </div>

                        <div>
                            <label class="block text-sm font-medium mb-2">To</label>
                            <div class="flex space-x-2">
                                <select id="to-token" 
                                    class="flex-1 px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                    <option value="USDH">USDH</option>
                                    <option value="HBAR">HBAR</option>
                                </select>
                                <input type="number" id="to-amount" placeholder="0.0" readonly
                                    class="flex-1 px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-600">
                            </div>
                            <div class="text-xs text-gray-500 mt-1">Balance: <span id="to-balance">0.00</span></div>
                        </div>

                        <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded-lg text-sm space-y-2">
                            <div class="flex justify-between">
                                <span>Exchange Rate</span>
                                <span id="exchange-rate">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Price Impact</span>
                                <span id="price-impact" class="text-orange-500">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Slippage Tolerance</span>
                                <span>0.5%</span>
                            </div>
                        </div>

                        <button id="swap-btn" class="w-full bg-primary text-white py-3 rounded-lg font-medium hover:bg-purple-600 transition-colors disabled:bg-gray-400 disabled:cursor-not-allowed">
                            Swap Tokens
                        </button>
                    </div>
                </div>
            </div>
        </div>

        <!-- Redeem Tab -->
        <div id="redeem-tab" class="tab-content hidden">
            <div class="max-w-md mx-auto">
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h2 class="text-xl font-semibold mb-6">Redeem USDH to Fiat</h2>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">USDH Amount</label>
                            <div class="relative">
                                <input type="number" id="redeem-amount" placeholder="100.00" step="0.01" min="0"
                                    class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                <button id="redeem-max" class="absolute right-2 top-1/2 transform -translate-y-1/2 text-primary text-sm font-medium hover:underline">
                                    MAX
                                </button>
                            </div>
                            <div class="text-xs text-gray-500 mt-1">Available: <span id="usdh-available">0.00</span> USDH</div>
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium mb-2">Withdrawal Method</label>
                            <select id="withdrawal-method" 
                                class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                <option value="bank">Bank Transfer (ACH)</option>
                                <option value="wire">Wire Transfer</option>
                                <option value="paypal">PayPal</option>
                                <option value="card">Debit Card (Instant)</option>
                            </select>
                        </div>

                        <div id="withdrawal-details" class="space-y-3">
                            <div>
                                <label class="block text-sm font-medium mb-2">Bank Account</label>
                                <select id="bank-account" 
                                    class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700 focus:ring-2 focus:ring-primary focus:border-transparent">
                                    <option value="">Select account...</option>
                                    <option value="checking-1234">Checking ****1234</option>
                                    <option value="savings-5678">Savings ****5678</option>
                                    <option value="new">+ Add new account</option>
                                </select>
                            </div>
                        </div>

                        <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded-lg space-y-2">
                            <div class="flex justify-between text-sm">
                                <span>Processing Fee</span>
                                <span id="redeem-fee">$0.00</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span>Processing Time</span>
                                <span id="redeem-time">1-3 business days</span>
                            </div>
                            <div class="border-t border-gray-200 dark:border-gray-600 pt-2 mt-2">
                                <div class="flex justify-between font-medium">
                                    <span>You'll Receive</span>
                                    <span id="fiat-receive">$0.00</span>
                                </div>
                            </div>
                        </div>

                        <div class="bg-blue-50 dark:bg-blue-900/20 border border-blue-200 dark:border-blue-800 p-4 rounded-lg">
                            <div class="flex items-start space-x-2">
                                <svg class="w-5 h-5 text-blue-500 mt-0.5" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"></path>
                                </svg>
                                <div class="text-sm text-blue-700 dark:text-blue-300">
                                    <p class="font-medium">Compliance Notice</p>
                                    <p class="mt-1">All redemptions are subject to AML/KYC verification. Large withdrawals may require additional documentation.</p>
                                </div>
                            </div>
                        </div>

                        <button id="redeem-btn" class="w-full bg-red-500 text-white py-3 rounded-lg font-medium hover:bg-red-600 transition-colors disabled:bg-gray-400 disabled:cursor-not-allowed">
                            Initiate Redemption
                        </button>
                    </div>
                </div>

                <!-- Redemption History -->
                <div class="mt-6 bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h3 class="text-lg font-semibold mb-4">Redemption History</h3>
                    <div id="redemption-history" class="space-y-3">
                        <div class="text-center text-gray-500 dark:text-gray-400 py-4">
                            No redemption history
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Governance Tab -->
        <div id="governance-tab" class="tab-content hidden">
            <div class="space-y-6">
                <div class="flex justify-between items-center">
                    <div>
                        <h2 class="text-xl font-semibold">Protocol Governance</h2>
                        <p class="text-gray-600 dark:text-gray-400 mt-1">Participate in protocol decisions and parameter updates</p>
                    </div>
                    <div class="text-right">
                        <div class="text-sm text-gray-500 dark:text-gray-400">Your Voting Power</div>
                        <div class="text-lg font-semibold" id="voting-power">0.00%</div>
                    </div>
                </div>

                <!-- Active Proposals -->
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h3 class="text-lg font-semibold mb-4">Active Proposals</h3>
                    <div id="active-proposals" class="space-y-4">
                        <!-- Proposals will be dynamically added here -->
                    </div>
                </div>

                <!-- Protocol Parameters -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="text-lg font-semibold mb-4">Current Parameters</h3>
                        <div class="space-y-3">
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Mint Fee</span>
                                <span class="font-medium">0.5%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Redeem Fee</span>
                                <span class="font-medium">0.3%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Swap Fee</span>
                                <span class="font-medium">0.3%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Min Collateral Ratio</span>
                                <span class="font-medium">110%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Emergency Stop</span>
                                <span class="font-medium text-green-500">Disabled</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="text-lg font-semibold mb-4">Your Governance Tokens</h3>
                        <div class="space-y-3">
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">HSS (StableSwap)</span>
                                <span class="font-medium" id="hss-balance">0.00</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Delegated To</span>
                                <span class="font-medium">Self</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Proposals Voted</span>
                                <span class="font-medium">0</span>
                            </div>
                            <button class="w-full mt-3 bg-primary text-white py-2 rounded-lg hover:bg-purple-600 transition-colors text-sm">
                                Delegate Voting Power
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Liquidity Pools Tab -->
        <div id="pools-tab" class="tab-content hidden">
            <div class="space-y-6">
                <div class="flex justify-between items-center">
                    <h2 class="text-xl font-semibold">Liquidity Pools</h2>
                    <button id="create-pool-btn" class="bg-primary text-white px-4 py-2 rounded-lg hover:bg-purple-600 transition-colors">
                        Create Pool
                    </button>
                </div>

                <div id="pools-list" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Pools will be dynamically added here -->
                </div>
            </div>
        </div>

        <!-- Analytics Tab -->
        <div id="analytics-tab" class="tab-content hidden">
            <div class="space-y-6">
                <h2 class="text-xl font-semibold">Analytics Dashboard</h2>
                
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="text-lg font-semibold mb-4">Mirror Node Statistics</h3>
                        <div class="space-y-3">
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Network TPS</span>
                                <span class="font-medium">~10,000</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Transaction Count</span>
                                <span class="font-medium">2,547,891</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Active Accounts</span>
                                <span class="font-medium">45,672</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Total HTS Tokens</span>
                                <span class="font-medium">1,234</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="text-lg font-semibold mb-4">Pool Performance</h3>
                        <div class="space-y-3">
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">HBAR/USDH APY</span>
                                <span class="font-medium text-green-500">15.6%</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Trading Volume 24h</span>
                                <span class="font-medium">$127,543</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Total Fees Earned</span>
                                <span class="font-medium">$3,821</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-600 dark:text-gray-400">Impermanent Loss</span>
                                <span class="font-medium text-orange-500">-1.2%</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <h3 class="text-lg font-semibold mb-4">Price Chart Simulation</h3>
                    <div class="h-64 bg-gray-100 dark:bg-gray-700 rounded-lg flex items-center justify-center">
                        <div class="text-center">
                            <svg class="w-16 h-16 mx-auto mb-2 text-gray-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M16 6l2.29 2.29-4.88 4.88-4-4L2 16.59 3.41 18l6-6 4 4 6.3-6.29L22 12V6z"/>
                            </svg>
                            <p class="text-gray-500 dark:text-gray-400">Chart visualization would integrate with Mirror Node API</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- HCS Logs Tab -->
        <div id="logs-tab" class="tab-content hidden">
            <div class="space-y-6">
                <div class="flex justify-between items-center">
                    <h2 class="text-xl font-semibold">HCS Settlement Logs</h2>
                    <div class="text-sm text-gray-500 dark:text-gray-400">
                        Topic ID: 0.0.123456
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-800 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                    <div class="p-4 border-b border-gray-200 dark:border-gray-700">
                        <div class="flex space-x-4">
                            <button class="log-filter active px-3 py-1 text-sm rounded-full" data-filter="all">All</button>
                            <button class="log-filter px-3 py-1 text-sm rounded-full" data-filter="mint">Mints</button>
                            <button class="log-filter px-3 py-1 text-sm rounded-full" data-filter="swap">Swaps</button>
                            <button class="log-filter px-3 py-1 text-sm rounded-full" data-filter="redeem">Redemptions</button>
                            <button class="log-filter px-3 py-1 text-sm rounded-full" data-filter="governance">Governance</button>
                        </div>
                    </div>
                    <div id="hcs-logs" class="max-h-96 overflow-y-auto">
                        <!-- Logs will be dynamically added here -->
                    </div>
                </div>
            </div>
        </div>
    </main>
</div>

<!-- Modal for Pool Creation -->
<div id="pool-modal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
    <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg max-w-md w-full mx-4">
        <h3 class="text-lg font-semibold mb-4">Create Liquidity Pool</h3>
        <div class="space-y-4">
            <div>
                <label class="block text-sm font-medium mb-2">Token A</label>
                <select id="pool-token-a" class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700">
                    <option value="HBAR">HBAR</option>
                    <option value="USDH">USDH</option>
                </select>
            </div>
            <div>
                <label class="block text-sm font-medium mb-2">Token B</label>
                <select id="pool-token-b" class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700">
                    <option value="USDH">USDH</option>
                    <option value="HBAR">HBAR</option>
                </select>
            </div>
            <div>
                <label class="block text-sm font-medium mb-2">Initial Liquidity A</label>
                <input type="number" id="pool-amount-a" placeholder="1000" step="0.01" min="0"
                    class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700">
            </div>
            <div>
                <label class="block text-sm font-medium mb-2">Initial Liquidity B</label>
                <input type="number" id="pool-amount-b" placeholder="100" step="0.01" min="0"
                    class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-700">
            </div>
            <div class="flex space-x-3">
                <button id="cancel-pool" class="flex-1 px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg">Cancel</button>
                <button id="confirm-pool" class="flex-1 px-4 py-2 bg-primary text-white hover:bg-purple-600 rounded-lg">Create Pool</button>
            </div>
        </div>
    </div>
</div>

<script>
    // Dark mode detection
    if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
        document.documentElement.classList.add('dark');
    }
    window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
        if (event.matches) {
            document.documentElement.classList.add('dark');
        } else {
            document.documentElement.classList.remove('dark');
        }
    });

    // Application State
    const AppState = {
        walletConnected: false,
        accountId: null,
        balances: {
            HBAR: 0,
            USDH: 0
        },
        pools: [],
        transactions: [],
        hcsLogs: []
    };

    // AMM Calculations using Big.js for precision
    class AMM {
        static calculateSwapOutput(inputAmount, inputReserve, outputReserve, fee = 0.003) {
            const input = new Big(inputAmount);
            const reserveIn = new Big(inputReserve);
            const reserveOut = new Big(outputReserve);
            const feeRate = new Big(1).minus(fee);
            
            const inputWithFee = input.times(feeRate);
            const numerator = inputWithFee.times(reserveOut);
            const denominator = reserveIn.plus(inputWithFee);
            
            return numerator.div(denominator);
        }

        static calculatePriceImpact(inputAmount, inputReserve, outputReserve) {
            const input = new Big(inputAmount);
            const reserveIn = new Big(inputReserve);
            const reserveOut = new Big(outputReserve);
            
            const spotPrice = reserveOut.div(reserveIn);
            const output = this.calculateSwapOutput(inputAmount, inputReserve, outputReserve);
            const effectivePrice = output.div(input);
            
            return spotPrice.minus(effectivePrice).div(spotPrice).times(100);
        }
    }

    // Initialize default pool
    AppState.pools.push({
        id: 'hbar-usdh',
        tokenA: 'HBAR',
        tokenB: 'USDH',
        reserveA: 10000,
        reserveB: 1000,
        liquidityTokens: 3162.27766,
        apy: 15.6,
        volume24h: 127543
    });

    // Tab Navigation
    function initializeTabNavigation() {
        document.querySelectorAll('.nav-tab').forEach(tab => {
            tab.addEventListener('click', () => {
                document.querySelectorAll('.nav-tab').forEach(t => t.classList.remove('active'));
                document.querySelectorAll('.tab-content').forEach(c => c.classList.add('hidden'));

                tab.classList.add('active');
                const tabId = tab.dataset.tab + '-tab';
                const tabContent = document.getElementById(tabId);
                if (tabContent) {
                    tabContent.classList.remove('hidden');
                }

                // Tab-specific updates
                switch(tab.dataset.tab) {
                    case 'pools':
                        updatePoolsDisplay();
                        break;
                    case 'logs':
                        updateHCSLogs();
                        break;
                    case 'redeem':
                        updateRedeemAvailable();
                        updateRedemptionHistory();
                        break;
                    case 'governance':
                        updateGovernanceDisplay();
                        break;
                }
            });
        });
    }

    // Wallet Connection
    document.getElementById('connect-wallet').addEventListener('click', () => {
        if (!AppState.walletConnected) {
            // Simulate wallet connection
            AppState.walletConnected = true;
            AppState.accountId = '0.0.123456';
            AppState.balances.HBAR = 1000;
            AppState.balances.USDH = 500;
            
            document.getElementById('wallet-status').textContent = 'Connected: 0.0.123456';
            document.getElementById('connect-wallet').textContent = 'Disconnect';
            
            updateDashboard();
            addHCSLog('wallet', 'Wallet connected successfully', { accountId: AppState.accountId });
        } else {
            // Disconnect wallet
            AppState.walletConnected = false;
            AppState.accountId = null;
            AppState.balances.HBAR = 0;
            AppState.balances.USDH = 0;
            
            document.getElementById('wallet-status').textContent = 'Wallet Disconnected';
            document.getElementById('connect-wallet').textContent = 'Connect HashPack';
            
            updateDashboard();
        }
    });

    // Mint functionality
    document.getElementById('fiat-amount').addEventListener('input', (e) => {
        const amount = parseFloat(e.target.value) || 0;
        const fee = amount * 0.005;
        const usdh = amount - fee;
        
        document.getElementById('processing-fee').textContent = `$${fee.toFixed(2)}`;
        document.getElementById('usdh-receive').textContent = `${usdh.toFixed(2)} USDH`;
    });

    document.getElementById('mint-btn').addEventListener('click', () => {
        if (!AppState.walletConnected) {
            showAlert('Please connect your wallet first');
            return;
        }
        
        const amount = parseFloat(document.getElementById('fiat-amount').value);
        if (!amount || amount <= 0) {
            showAlert('Please enter a valid amount');
            return;
        }
        
        const fee = amount * 0.005;
        const usdh = amount - fee;
        
        // Simulate minting
        AppState.balances.USDH += usdh;
        AppState.transactions.push({
            type: 'mint',
            amount: usdh,
            timestamp: new Date(),
            txId: generateTxId()
        });
        
        addHCSLog('mint', `Minted ${usdh.toFixed(2)} USDH from $${amount} fiat deposit`, {
            fiatAmount: amount,
            usdhAmount: usdh,
            fee: fee,
            accountId: AppState.accountId
        });
        
        document.getElementById('fiat-amount').value = '';
        document.getElementById('processing-fee').textContent = '$0.00';
        document.getElementById('usdh-receive').textContent = '0.00 USDH';
        
        updateDashboard();
        showAlert('Successfully minted USDH!');
    });

    // Swap functionality
    function updateSwapCalculation() {
        const fromToken = document.getElementById('from-token').value;
        const toToken = document.getElementById('to-token').value;
        const fromAmount = parseFloat(document.getElementById('from-amount').value) || 0;
        
        if (fromAmount <= 0) {
            document.getElementById('to-amount').value = '';
            document.getElementById('exchange-rate').textContent = '-';
            document.getElementById('price-impact').textContent = '-';
            return;
        }
        
        const pool = AppState.pools.find(p => 
            (p.tokenA === fromToken && p.tokenB === toToken) ||
            (p.tokenA === toToken && p.tokenB === fromToken)
        );
        
        if (!pool) {
            document.getElementById('to-amount').value = '';
            document.getElementById('exchange-rate').textContent = 'No pool available';
            document.getElementById('price-impact').textContent = '-';
            return;
        }
        
        const isAtoB = pool.tokenA === fromToken;
        const inputReserve = isAtoB ? pool.reserveA : pool.reserveB;
        const outputReserve = isAtoB ? pool.reserveB : pool.reserveA;
        
        const outputAmount = AMM.calculateSwapOutput(fromAmount, inputReserve, outputReserve);
        const priceImpact = AMM.calculatePriceImpact(fromAmount, inputReserve, outputReserve);
        const exchangeRate = outputAmount.div(fromAmount);
        
        document.getElementById('to-amount').value = outputAmount.toFixed(6);
        document.getElementById('exchange-rate').textContent = `1 ${fromToken} = ${exchangeRate.toFixed(6)} ${toToken}`;
        document.getElementById('price-impact').textContent = `${priceImpact.toFixed(2)}%`;
        
        // Update price impact color
        const impactElement = document.getElementById('price-impact');
        if (priceImpact.gt(5)) {
            impactElement.className = 'text-red-500';
        } else if (priceImpact.gt(1)) {
            impactElement.className = 'text-orange-500';
        } else {
            impactElement.className = 'text-green-500';
        }
    }

    document.getElementById('from-amount').addEventListener('input', updateSwapCalculation);
    document.getElementById('from-token').addEventListener('change', () => {
        updateSwapBalances();
        updateSwapCalculation();
    });
    document.getElementById('to-token').addEventListener('change', () => {
        updateSwapBalances();
        updateSwapCalculation();
    });

    document.getElementById('swap-direction').addEventListener('click', () => {
        const fromToken = document.getElementById('from-token');
        const toToken = document.getElementById('to-token');
        const fromAmount = document.getElementById('from-amount');
        const toAmount = document.getElementById('to-amount');
        
        [fromToken.value, toToken.value] = [toToken.value, fromToken.value];
        fromAmount.value = toAmount.value;
        toAmount.value = '';
        
        updateSwapBalances();
        updateSwapCalculation();
    });

    function updateSwapBalances() {
        const fromToken = document.getElementById('from-token').value;
        const toToken = document.getElementById('to-token').value;
        
        document.getElementById('from-balance').textContent = AppState.balances[fromToken]?.toFixed(2) || '0.00';
        document.getElementById('to-balance').textContent = AppState.balances[toToken]?.toFixed(2) || '0.00';
    }

    document.getElementById('swap-btn').addEventListener('click', () => {
        if (!AppState.walletConnected) {
            showAlert('Please connect your wallet first');
            return;
        }
        
        const fromToken = document.getElementById('from-token').value;
        const toToken = document.getElementById('to-token').value;
        const fromAmount = parseFloat(document.getElementById('from-amount').value);
        const toAmount = parseFloat(document.getElementById('to-amount').value);
        
        if (!fromAmount || fromAmount <= 0) {
            showAlert('Please enter a valid amount');
            return;
        }
        
        if (AppState.balances[fromToken] < fromAmount) {
            showAlert('Insufficient balance');
            return;
        }
        
        // Execute swap
        AppState.balances[fromToken] -= fromAmount;
        AppState.balances[toToken] += toAmount;
        
        // Update pool reserves
        const pool = AppState.pools.find(p => 
            (p.tokenA === fromToken && p.tokenB === toToken) ||
            (p.tokenA === toToken && p.tokenB === fromToken)
        );
        
        if (pool) {
            const isAtoB = pool.tokenA === fromToken;
            if (isAtoB) {
                pool.reserveA += fromAmount;
                pool.reserveB -= toAmount;
            } else {
                pool.reserveB += fromAmount;
                pool.reserveA -= toAmount;
            }
            pool.volume24h += fromAmount * (fromToken === 'HBAR' ? 0.1 : 1); // Approximate USD value
        }
        
        AppState.transactions.push({
            type: 'swap',
            fromToken,
            toToken,
            fromAmount,
            toAmount,
            timestamp: new Date(),
            txId: generateTxId()
        });
        
        addHCSLog('swap', `Swapped ${fromAmount} ${fromToken} for ${toAmount.toFixed(6)} ${toToken}`, {
            fromToken,
            toToken,
            fromAmount,
            toAmount,
            accountId: AppState.accountId
        });
        
        document.getElementById('from-amount').value = '';
        document.getElementById('to-amount').value = '';
        updateSwapBalances();
        updateSwapCalculation();
        updateDashboard();
        
        showAlert('Swap completed successfully!');
    });

    // Pool management
    document.getElementById('create-pool-btn').addEventListener('click', () => {
        document.getElementById('pool-modal').classList.remove('hidden');
        document.getElementById('pool-modal').classList.add('flex');
    });

    document.getElementById('cancel-pool').addEventListener('click', () => {
        document.getElementById('pool-modal').classList.add('hidden');
        document.getElementById('pool-modal').classList.remove('flex');
    });

    document.getElementById('confirm-pool').addEventListener('click', () => {
        const tokenA = document.getElementById('pool-token-a').value;
        const tokenB = document.getElementById('pool-token-b').value;
        const amountA = parseFloat(document.getElementById('pool-amount-a').value);
        const amountB = parseFloat(document.getElementById('pool-amount-b').value);
        
        if (!amountA || !amountB || amountA <= 0 || amountB <= 0) {
            showAlert('Please enter valid amounts');
            return;
        }
        
        if (tokenA === tokenB) {
            showAlert('Please select different tokens');
            return;
        }
        
        // Check if pool already exists
        const existingPool = AppState.pools.find(p => 
            (p.tokenA === tokenA && p.tokenB === tokenB) ||
            (p.tokenA === tokenB && p.tokenB === tokenA)
        );
        
        if (existingPool) {
            showAlert('Pool already exists');
            return;
        }
        
        const liquidityTokens = Math.sqrt(amountA * amountB);
        const newPool = {
            id: `${tokenA.toLowerCase()}-${tokenB.toLowerCase()}`,
            tokenA,
            tokenB,
            reserveA: amountA,
            reserveB: amountB,
            liquidityTokens,
            apy: Math.random() * 20 + 5, // Random APY between 5-25%
            volume24h: 0
        };
        
        AppState.pools.push(newPool);
        
        addHCSLog('pool', `Created liquidity pool ${tokenA}/${tokenB}`, {
            tokenA,
            tokenB,
            reserveA: amountA,
            reserveB: amountB,
            liquidityTokens,
            accountId: AppState.accountId
        });
        
        document.getElementById('pool-modal').classList.add('hidden');
        document.getElementById('pool-modal').classList.remove('flex');
        
        // Clear form
        document.getElementById('pool-amount-a').value = '';
        document.getElementById('pool-amount-b').value = '';
        
        updatePoolsDisplay();
        updateDashboard();
        showAlert('Pool created successfully!');
    });

    function updatePoolsDisplay() {
        const poolsList = document.getElementById('pools-list');
        
        if (AppState.pools.length === 0) {
            poolsList.innerHTML = '<div class="col-span-full text-center text-gray-500 dark:text-gray-400 py-8">No liquidity pools created yet</div>';
            return;
        }
        
        poolsList.innerHTML = AppState.pools.map(pool => `
            <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-sm border border-gray-200 dark:border-gray-700">
                <div class="flex items-center justify-between mb-4">
                    <h3 class="text-lg font-semibold">${pool.tokenA}/${pool.tokenB}</h3>
                    <span class="bg-green-100 dark:bg-green-900 text-green-800 dark:text-green-200 px-2 py-1 rounded-full text-xs font-medium">
                        ${pool.apy.toFixed(1)}% APY
                    </span>
                </div>
                <div class="space-y-2 text-sm">
                    <div class="flex justify-between">
                        <span class="text-gray-600 dark:text-gray-400">${pool.tokenA} Reserve</span>
                        <span class="font-medium">${pool.reserveA.toLocaleString()}</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-gray-600 dark:text-gray-400">${pool.tokenB} Reserve</span>
                        <span class="font-medium">${pool.reserveB.toLocaleString()}</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-gray-600 dark:text-gray-400">24h Volume</span>
                        <span class="font-medium">$${pool.volume24h.toLocaleString()}</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-gray-600 dark:text-gray-400">LP Tokens</span>
                        <span class="font-medium">${pool.liquidityTokens.toFixed(2)}</span>
                    </div>
                </div>
            </div>
        `).join('');
    }

    // HCS Logging
    function addHCSLog(type, message, data = {}) {
        const log = {
            id: generateTxId(),
            type,
            message,
            data,
            timestamp: new Date(),
            consensusTimestamp: new Date(Date.now() + Math.random() * 1000), // Simulate consensus delay
            topicId: '0.0.123456'
        };
        
        AppState.hcsLogs.unshift(log);
        
        // Keep only last 100 logs
        if (AppState.hcsLogs.length > 100) {
            AppState.hcsLogs = AppState.hcsLogs.slice(0, 100);
        }
    }

    function updateHCSLogs() {
        const activeFilter = document.querySelector('.log-filter.active').dataset.filter;
        const filteredLogs = activeFilter === 'all' 
            ? AppState.hcsLogs 
            : AppState.hcsLogs.filter(log => log.type === activeFilter);
        
        const logsContainer = document.getElementById('hcs-logs');
        
        if (filteredLogs.length === 0) {
            logsContainer.innerHTML = '<div class="p-4 text-center text-gray-500 dark:text-gray-400">No logs found</div>';
            return;
        }
        
        logsContainer.innerHTML = filteredLogs.map(log => `
            <div class="p-4 border-b border-gray-200 dark:border-gray-700 last:border-b-0">
                <div class="flex items-start justify-between mb-2">
                    <div class="flex items-center space-x-2">
                        <span class="log-type-badge ${log.type}">${log.type.toUpperCase()}</span>
                        <span class="text-sm text-gray-500 dark:text-gray-400">ID: ${log.id}</span>
                    </div>
                    <span class="text-xs text-gray-500 dark:text-gray-400">${log.consensusTimestamp.toLocaleString()}</span>
                </div>
                <p class="text-sm mb-2">${log.message}</p>
                ${Object.keys(log.data).length > 0 ? `
                    <details class="text-xs text-gray-600 dark:text-gray-400">
                        <summary class="cursor-pointer">View Details</summary>
                        <pre class="mt-2 p-2 bg-gray-100 dark:bg-gray-700 rounded text-xs overflow-x-auto">${JSON.stringify(log.data, null, 2)}</pre>
                    </details>
                ` : ''}
            </div>
        `).join('');
    }

    // Log filter functionality
    document.querySelectorAll('.log-filter').forEach(filter => {
        filter.addEventListener('click', () => {
            document.querySelectorAll('.log-filter').forEach(f => f.classList.remove('active'));
            filter.classList.add('active');
            updateHCSLogs();
        });
    });

    // Dashboard updates
    function updateDashboard() {
        // Portfolio balances
        const portfolioBalances = document.getElementById('portfolio-balances');
        const totalValue = AppState.balances.HBAR * 0.1 + AppState.balances.USDH; // Assume HBAR = $0.10
        
        portfolioBalances.innerHTML = `
            <div class="flex justify-between items-center py-2 border-b border-gray-100 dark:border-gray-700">
                <span class="text-gray-600 dark:text-gray-400">HBAR</span>
                <span class="font-medium">${AppState.balances.HBAR.toFixed(2)}</span>
            </div>
            <div class="flex justify-between items-center py-2 border-b border-gray-100 dark:border-gray-700">
                <span class="text-gray-600 dark:text-gray-400">USDH</span>
                <span class="font-medium">${AppState.balances.USDH.toFixed(2)}</span>
            </div>
            <div class="flex justify-between items-center py-2">
                <span class="text-gray-600 dark:text-gray-400">Total Value</span>
                <span class="font-bold text-primary">$${totalValue.toFixed(2)}</span>
            </div>
        `;
        
        // Top metrics
        const totalTVL = AppState.pools.reduce((sum, pool) => sum + (pool.reserveA * 0.1 + pool.reserveB), 0);
        const total24hVolume = AppState.pools.reduce((sum, pool) => sum + pool.volume24h, 0);
        
        document.getElementById('total-tvl').textContent = `$${totalTVL.toLocaleString()}`;
        document.getElementById('usdh-minted').textContent = AppState.balances.USDH.toLocaleString();
        document.getElementById('active-pools').textContent = AppState.pools.length;
        document.getElementById('volume-24h').textContent = `$${total24hVolume.toLocaleString()}`;
        
        // Recent activity
        const recentActivity = document.getElementById('recent-activity');
        const recentTxs = AppState.transactions.slice(0, 5);
        
        if (recentTxs.length === 0) {
            recentActivity.innerHTML = '<div class="text-center text-gray-500 dark:text-gray-400 py-4">No recent activity</div>';
        } else {
            recentActivity.innerHTML = recentTxs.map(tx => `
                <div class="flex justify-between items-center py-2 border-b border-gray-100 dark:border-gray-700 last:border-b-0">
                    <div>
                        <span class="text-sm font-medium capitalize">${tx.type}</span>
                        <span class="text-xs text-gray-500 dark:text-gray-400 block">${tx.timestamp.toLocaleString()}</span>
                    </div>
                    <span class="text-sm font-medium">
                        ${tx.type === 'mint' ? `+${tx.amount.toFixed(2)} USDH` : 
                          tx.type === 'swap' ? `${tx.fromAmount} ${tx.fromToken} → ${tx.toAmount.toFixed(2)} ${tx.toToken}` : 
                          'Unknown'}
                    </span>
                </div>
            `).join('');
        }
        
        updateSwapBalances();
    }

    // Utility functions
    function generateTxId() {
        return '0.0.' + Date.now() + Math.floor(Math.random() * 1000);
    }

    function showAlert(message) {
        const modal = document.createElement('div');
        modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
        modal.innerHTML = `
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                <div class="flex justify-end">
                    <button class="px-4 py-2 bg-primary text-white hover:bg-purple-600 rounded" onclick="this.closest('.fixed').remove()">OK</button>
                </div>
            </div>
        `;
        document.body.appendChild(modal);
        
        // Auto-remove after 3 seconds
        setTimeout(() => {
            if (modal.parentNode) {
                modal.remove();
            }
        }, 3000);
    }

    // CSS for dynamic classes
    const style = document.createElement('style');
    style.textContent = `
        .nav-tab.active {
            border-bottom: 2px solid #5D5CDE;
            color: #5D5CDE;
            background-color: white;
        }
        .dark .nav-tab.active {
            background-color: #374151;
        }
        .log-filter.active {
            background-color: #5D5CDE;
            color: white;
        }
        .log-filter {
            background-color: #f3f4f6;
            color: #6b7280;
            cursor: pointer;
            transition: all 0.2s;
        }
        .dark .log-filter {
            background-color: #4b5563;
            color: #d1d5db;
        }
        .log-type-badge {
            display: inline-block;
            padding: 2px 6px;
            border-radius: 4px;
            font-size: 10px;
            font-weight: 600;
            text-transform: uppercase;
        }
        .log-type-badge.mint { background-color: #dcfce7; color: #166534; }
        .log-type-badge.swap { background-color: #dbeafe; color: #1e40af; }
        .log-type-badge.redeem { background-color: #fed7d7; color: #c53030; }
        .log-type-badge.wallet { background-color: #f3e8ff; color: #7c3aed; }
        .log-type-badge.pool { background-color: #fef3c7; color: #92400e; }
        .log-type-badge.governance { background-color: #e0e7ff; color: #3730a3; }
        .dark .log-type-badge.mint { background-color: #166534; color: #dcfce7; }
        .dark .log-type-badge.swap { background-color: #1e40af; color: #dbeafe; }
        .dark .log-type-badge.redeem { background-color: #c53030; color: #fed7d7; }
        .dark .log-type-badge.wallet { background-color: #7c3aed; color: #f3e8ff; }
        .dark .log-type-badge.pool { background-color: #92400e; color: #fef3c7; }
        .dark .log-type-badge.governance { background-color: #3730a3; color: #e0e7ff; }
    `;
    document.head.appendChild(style);

    // Redemption functionality
    AppState.redemptions = [];
    AppState.governance = {
        hssBalance: 0,
        votingPower: 0,
        proposals: [],
        votes: []
    };

    // Update available USDH for redemption
    function updateRedeemAvailable() {
        document.getElementById('usdh-available').textContent = AppState.balances.USDH.toFixed(2);
    }

    // Redeem amount calculations
    document.getElementById('redeem-amount').addEventListener('input', (e) => {
        const amount = parseFloat(e.target.value) || 0;
        const method = document.getElementById('withdrawal-method').value;
        
        let feeRate, processingTime;
        switch (method) {
            case 'bank':
                feeRate = 0.003; // 0.3%
                processingTime = '1-3 business days';
                break;
            case 'wire':
                feeRate = 0.005; // 0.5%
                processingTime = '1-2 business days';
                break;
            case 'paypal':
                feeRate = 0.004; // 0.4%
                processingTime = '1 business day';
                break;
            case 'card':
                feeRate = 0.02; // 2%
                processingTime = 'Instant';
                break;
            default:
                feeRate = 0.003;
                processingTime = '1-3 business days';
        }
        
        const fee = amount * feeRate;
        const receive = amount - fee;
        
        document.getElementById('redeem-fee').textContent = `$${fee.toFixed(2)}`;
        document.getElementById('redeem-time').textContent = processingTime;
        document.getElementById('fiat-receive').textContent = `$${receive.toFixed(2)}`;
    });

    document.getElementById('withdrawal-method').addEventListener('change', () => {
        // Trigger recalculation
        document.getElementById('redeem-amount').dispatchEvent(new Event('input'));
    });

    document.getElementById('redeem-max').addEventListener('click', () => {
        document.getElementById('redeem-amount').value = AppState.balances.USDH.toFixed(2);
        document.getElementById('redeem-amount').dispatchEvent(new Event('input'));
    });

    document.getElementById('redeem-btn').addEventListener('click', () => {
        if (!AppState.walletConnected) {
            showAlert('Please connect your wallet first');
            return;
        }
        
        const amount = parseFloat(document.getElementById('redeem-amount').value);
        const method = document.getElementById('withdrawal-method').value;
        const account = document.getElementById('bank-account').value;
        
        if (!amount || amount <= 0) {
            showAlert('Please enter a valid amount');
            return;
        }
        
        if (amount > AppState.balances.USDH) {
            showAlert('Insufficient USDH balance');
            return;
        }
        
        if (!account) {
            showAlert('Please select a withdrawal account');
            return;
        }
        
        // Calculate fees based on method
        let feeRate;
        switch (method) {
            case 'bank': feeRate = 0.003; break;
            case 'wire': feeRate = 0.005; break;
            case 'paypal': feeRate = 0.004; break;
            case 'card': feeRate = 0.02; break;
            default: feeRate = 0.003;
        }
        
        const fee = amount * feeRate;
        const receive = amount - fee;
        
        showConfirmDialog(
            `Confirm redemption of ${amount.toFixed(2)} USDH for $${receive.toFixed(2)} (fee: $${fee.toFixed(2)})?`,
            () => {
                // Execute redemption
                AppState.balances.USDH -= amount;
                
                const redemption = {
                    id: generateTxId(),
                    amount,
                    fee,
                    receive,
                    method,
                    account,
                    status: 'pending',
                    timestamp: new Date(),
                    estimatedCompletion: new Date(Date.now() + (method === 'card' ? 0 : 1000 * 60 * 60 * 24)) // 1 day for non-instant
                };
                
                AppState.redemptions.unshift(redemption);
                AppState.transactions.push({
                    type: 'redeem',
                    amount,
                    method,
                    receive,
                    timestamp: new Date(),
                    txId: redemption.id
                });
                
                addHCSLog('redeem', `Initiated redemption of ${amount.toFixed(2)} USDH to ${method}`, {
                    usdhAmount: amount,
                    fiatAmount: receive,
                    fee: fee,
                    method: method,
                    account: account,
                    accountId: AppState.accountId
                });
                
                // Clear form
                document.getElementById('redeem-amount').value = '';
                document.getElementById('redeem-fee').textContent = '$0.00';
                document.getElementById('fiat-receive').textContent = '$0.00';
                
                updateDashboard();
                updateRedemptionHistory();
                showAlert('Redemption initiated successfully!');
                
                // Simulate status updates
                setTimeout(() => {
                    redemption.status = 'processing';
                    updateRedemptionHistory();
                    addHCSLog('redeem', `Redemption ${redemption.id} is being processed`, { redemptionId: redemption.id });
                }, 2000);
                
                if (method !== 'card') {
                    setTimeout(() => {
                        redemption.status = 'completed';
                        updateRedemptionHistory();
                        addHCSLog('redeem', `Redemption ${redemption.id} completed`, { redemptionId: redemption.id });
                    }, 5000);
                }
            }
        );
    });

    function updateRedemptionHistory() {
        const historyContainer = document.getElementById('redemption-history');
        
        if (AppState.redemptions.length === 0) {
            historyContainer.innerHTML = '<div class="text-center text-gray-500 dark:text-gray-400 py-4">No redemption history</div>';
            return;
        }
        
        historyContainer.innerHTML = AppState.redemptions.slice(0, 5).map(redemption => {
            let statusColor, statusText;
            switch (redemption.status) {
                case 'pending':
                    statusColor = 'text-yellow-600 bg-yellow-100 dark:bg-yellow-900';
                    statusText = 'Pending';
                    break;
                case 'processing':
                    statusColor = 'text-blue-600 bg-blue-100 dark:bg-blue-900';
                    statusText = 'Processing';
                    break;
                case 'completed':
                    statusColor = 'text-green-600 bg-green-100 dark:bg-green-900';
                    statusText = 'Completed';
                    break;
                case 'failed':
                    statusColor = 'text-red-600 bg-red-100 dark:bg-red-900';
                    statusText = 'Failed';
                    break;
                default:
                    statusColor = 'text-gray-600 bg-gray-100 dark:bg-gray-900';
                    statusText = 'Unknown';
            }
            
            return `
                <div class="flex justify-between items-center py-3 border-b border-gray-200 dark:border-gray-700 last:border-b-0">
                    <div>
                        <div class="font-medium">${redemption.amount.toFixed(2)} USDH → $${redemption.receive.toFixed(2)}</div>
                        <div class="text-sm text-gray-500 dark:text-gray-400">${redemption.timestamp.toLocaleString()}</div>
                        <div class="text-xs text-gray-400 dark:text-gray-500">${redemption.method.toUpperCase()} • ${redemption.account}</div>
                    </div>
                    <span class="px-2 py-1 rounded-full text-xs font-medium ${statusColor}">
                        ${statusText}
                    </span>
                </div>
            `;
        }).join('');
    }

    // Governance functionality
    function initializeGovernance() {
        // Award governance tokens based on usage
        AppState.governance.hssBalance = AppState.transactions.length * 10; // 10 HSS per transaction
        AppState.governance.votingPower = (AppState.governance.hssBalance / 10000) * 100; // Total supply of 10k HSS
        
        // Create sample proposals
        AppState.governance.proposals = [
            {
                id: 'prop-001',
                title: 'Reduce Mint Fee to 0.3%',
                description: 'Proposal to reduce the mint fee from 0.5% to 0.3% to increase competitiveness',
                proposer: '0.0.789012',
                status: 'active',
                votesFor: 2150,
                votesAgainst: 850,
                totalVotes: 3000,
                endTime: new Date(Date.now() + 1000 * 60 * 60 * 24 * 3), // 3 days
                userVote: null
            },
            {
                id: 'prop-002',
                title: 'Add USDC as Collateral',
                description: 'Proposal to accept USDC as additional collateral for USDH minting',
                proposer: '0.0.345678',
                status: 'active',
                votesFor: 1800,
                votesAgainst: 1200,
                totalVotes: 3000,
                endTime: new Date(Date.now() + 1000 * 60 * 60 * 24 * 5), // 5 days
                userVote: null
            },
            {
                id: 'prop-003',
                title: 'Increase Emergency Stop Threshold',
                description: 'Proposal to increase the threshold for emergency stop activation to require 60% consensus',
                proposer: '0.0.901234',
                status: 'active',
                votesFor: 900,
                votesAgainst: 600,
                totalVotes: 1500,
                endTime: new Date(Date.now() + 1000 * 60 * 60 * 24 * 7), // 7 days
                userVote: null
            }
        ];
        
        updateGovernanceDisplay();
    }

    function updateGovernanceDisplay() {
        document.getElementById('voting-power').textContent = AppState.governance.votingPower.toFixed(2) + '%';
        document.getElementById('hss-balance').textContent = AppState.governance.hssBalance.toFixed(2) + ' HSS';
        
        const proposalsContainer = document.getElementById('active-proposals');
        
        if (AppState.governance.proposals.length === 0) {
            proposalsContainer.innerHTML = '<div class="text-center text-gray-500 dark:text-gray-400 py-4">No active proposals</div>';
            return;
        }
        
        proposalsContainer.innerHTML = AppState.governance.proposals.map(proposal => {
            const forPercentage = (proposal.votesFor / proposal.totalVotes) * 100;
            const againstPercentage = (proposal.votesAgainst / proposal.totalVotes) * 100;
            const timeLeft = Math.ceil((proposal.endTime - new Date()) / (1000 * 60 * 60 * 24));
            
            return `
                <div class="border border-gray-200 dark:border-gray-700 rounded-lg p-4">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h4 class="font-semibold">${proposal.title}</h4>
                            <p class="text-sm text-gray-600 dark:text-gray-400 mt-1">${proposal.description}</p>
                            <div class="text-xs text-gray-500 dark:text-gray-500 mt-2">
                                Proposed by ${proposal.proposer} • ${timeLeft} days left
                            </div>
                        </div>
                        <span class="bg-green-100 dark:bg-green-900 text-green-800 dark:text-green-200 px-2 py-1 rounded-full text-xs font-medium">
                            ${proposal.status.toUpperCase()}
                        </span>
                    </div>
                    
                    <div class="space-y-2 mb-4">
                        <div class="flex justify-between text-sm">
                            <span>For: ${proposal.votesFor.toLocaleString()} (${forPercentage.toFixed(1)}%)</span>
                            <span>Against: ${proposal.votesAgainst.toLocaleString()} (${againstPercentage.toFixed(1)}%)</span>
                        </div>
                        <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
                            <div class="bg-green-500 h-2 rounded-l-full" style="width: ${forPercentage}%"></div>
                        </div>
                    </div>
                    
                    <div class="flex space-x-2">
                        <button onclick="vote('${proposal.id}', 'for')" 
                            class="flex-1 bg-green-500 text-white py-2 px-3 rounded text-sm hover:bg-green-600 transition-colors ${proposal.userVote ? 'opacity-50 cursor-not-allowed' : ''}"
                            ${proposal.userVote ? 'disabled' : ''}>
                            ${proposal.userVote === 'for' ? '✓ Voted For' : 'Vote For'}
                        </button>
                        <button onclick="vote('${proposal.id}', 'against')" 
                            class="flex-1 bg-red-500 text-white py-2 px-3 rounded text-sm hover:bg-red-600 transition-colors ${proposal.userVote ? 'opacity-50 cursor-not-allowed' : ''}"
                            ${proposal.userVote ? 'disabled' : ''}>
                            ${proposal.userVote === 'against' ? '✓ Voted Against' : 'Vote Against'}
                        </button>
                    </div>
                </div>
            `;
        }).join('');
    }

    // Global vote function
    window.vote = function(proposalId, voteType) {
        if (!AppState.walletConnected) {
            showAlert('Please connect your wallet first');
            return;
        }
        
        if (AppState.governance.hssBalance <= 0) {
            showAlert('You need HSS tokens to vote. Complete transactions to earn HSS tokens.');
            return;
        }
        
        const proposal = AppState.governance.proposals.find(p => p.id === proposalId);
        if (!proposal) return;
        
        if (proposal.userVote) {
            showAlert('You have already voted on this proposal');
            return;
        }
        
        const voteWeight = AppState.governance.hssBalance;
        
        showConfirmDialog(
            `Cast ${voteWeight.toFixed(2)} HSS tokens ${voteType === 'for' ? 'FOR' : 'AGAINST'} this proposal?`,
            () => {
                proposal.userVote = voteType;
                
                if (voteType === 'for') {
                    proposal.votesFor += voteWeight;
                } else {
                    proposal.votesAgainst += voteWeight;
                }
                
                proposal.totalVotes += voteWeight;
                
                AppState.governance.votes.push({
                    proposalId,
                    voteType,
                    weight: voteWeight,
                    timestamp: new Date()
                });
                
                addHCSLog('governance', `Voted ${voteType} on proposal: ${proposal.title}`, {
                    proposalId,
                    voteType,
                    weight: voteWeight,
                    accountId: AppState.accountId
                });
                
                updateGovernanceDisplay();
                showAlert(`Vote cast successfully! ${voteWeight.toFixed(2)} HSS tokens voted ${voteType.toUpperCase()}.`);
            }
        );
    };


    // Enhanced dashboard update to include redemption and governance data
    const originalUpdateDashboard = updateDashboard;
    updateDashboard = function() {
        originalUpdateDashboard();
        updateRedeemAvailable();
        
        // Update governance tokens based on activity
        AppState.governance.hssBalance = AppState.transactions.length * 10;
        AppState.governance.votingPower = (AppState.governance.hssBalance / 10000) * 100;
    };

    // Confirmation dialog function
    function showConfirmDialog(message, onConfirm) {
        const modal = document.createElement('div');
        modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
        modal.innerHTML = `
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                <div class="flex justify-end space-x-3">
                    <button class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded" onclick="this.closest('.fixed').remove()">Cancel</button>
                    <button class="px-4 py-2 bg-primary text-white hover:bg-purple-600 rounded" onclick="this.closest('.fixed').remove(); (${onConfirm.toString()})()">Confirm</button>
                </div>
            </div>
        `;
        document.body.appendChild(modal);
    }

    // Initialize app
    initializeTabNavigation();
    updateDashboard();
    updatePoolsDisplay();
    updateSwapBalances();
    initializeGovernance();
    
    // Add some initial HCS logs for demo
    addHCSLog('pool', 'Initial HBAR/USDH liquidity pool created', {
        tokenA: 'HBAR',
        tokenB: 'USDH',
        reserveA: 10000,
        reserveB: 1000,
        accountId: '0.0.system'
    });
</script>
