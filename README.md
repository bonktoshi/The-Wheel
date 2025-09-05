# The-Wheel
An automated pumpfun flywheel
🛞 The Wheel -Auto Buyback & Burn on Solana

$WHEEL is a Solana SPL token that integrates with PumpFun’s creator fee reward system.
It automatically uses 50% of accumulated creator fees to buyback and burn $WHEEL, and the other 50% to buyback and burn $PUMP  reducing supply of both tokens.

The system executes once per hour, triggered by a keeper bot or any user calling the program.

✨ Features

	•	SPL Token Mint: 1,000,000,000 $WHEEL starting supply

	•	Fee Treasury: Collects creator fees from PumpFun

Hourly Buyback & Burn:
	•	50% → Buyback + burn $WHEEL.
•	50% → Buyback + burn $WHEEL.
•	50% → Buyback + burn $PUMP.

Keeper Bot: Included script (ts/scripts/keeper.ts) automates this on cron.
