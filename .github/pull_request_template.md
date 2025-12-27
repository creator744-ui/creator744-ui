CREATOR 74 BTC WALLET

This pull request introduces the Bitcoin-first wallet profile for the Creator74 ecosystem. It establishes BTC as the primary wallet and balance layer, forming the base architecture for all upcoming wallet, dashboard, and conversion logic across Lovable + Supabase.

⸻

🚀 Overview
• BTC becomes the root wallet for each user profile.
• Onboarding begins with CREATOR 74 BTC WALLET as the default account.
• All future assets will map to this BTC layer for balance consistency.
• Forms the core structure for the full dashboard ecosystem.

Objective
Status
Make BTC the main account/wallet
✔️ Implemented (foundation)
Align Lovable + Supabase wallet profile
✔️ Base layer added
Prepare USD → DTX conversion architecture
🔄 In-progress (next PR)
Multi-chain deposit flow expansion
🔜 To be developed

🔧 Technical Context
• BTC is now the reference currency for:
• Profile identity
• Balance load + dashboard view
• Future USD conversion triggers
• Intended routing for deposits:
→ Any Chain (ERC20 / TRC20 / BEP20 / SOL)
→ USD → DTX → BTC Wallet Display
• Establishes structure to connect:
• Lovable components → Supabase tables
• Conversion workflow triggers
• Transaction history logging