<font size = 7><center><b><u>About Warden Zetachain</u></b></center></font>

* ### **[Zetachain](https://www.zetachain.com)** is the first Universal Blockchain with native access to Bitcoin, Ethereum, Solana, and more, offering seamless UX and unified liquidity to the next billions of users.

* ### With its Universal EVM, ZetaChain empowers developers to build Universal Apps that operate natively across any blockchain, creating a fluid crypto ecosystem from a single platform.
<div align="center">
  <a href="https://www.zetachain.com/"><img src="https://github.com/bartosian/celestia-tools/assets/20209819/85aaef48-7ea4-4857-b339-985645c6850c" alt="Website" width="16%"></a>
  <a href="https://github.com/zeta-chain"><img src="https://github.com/bartosian/celestia-tools/assets/20209819/229ec400-72ff-48ee-ac18-7bdb1f5e221a" alt="Github" width="16%"></a>
  <a href="https://x.com/zetablockchain"><img src="https://github.com/bartosian/celestia-tools/assets/20209819/3978b7fc-d575-44a6-8d41-327c14c8ba31" alt="Twitter" width="16%"></a>
  <a href="https://discord.gg/zetachain"><img src="https://github.com/bartosian/celestia-tools/assets/20209819/944a0b87-548d-4109-ad0c-def572d307cb" alt="Discord" width="16%"></a>
  <a href="https://www.zetachain.com/blog"><img src="https://github.com/bartosian/celestia-tools/assets/20209819/ac52729b-64d7-44d1-9a66-1e0d159848f6" alt="Blog" width="16.2%"></a>
</div>


## TrustedPoint services

#### MAINNET
- RPC: https://rpc-zetachain-mainnet.trusted-point.com:443
- REST API: https://api-zetachain-mainnet.trusted-point.com:443
- WSS: wss://rpc-zetachain-mainnet.trusted-point.com:443/websocket
- P2P Persistent Peer: b314f4b177c5d52a831d2829fdb9d4f069475dca@rpc-zetachain-mainnet.trusted-point.com:20356
#### TESTNET
---
- RPC: https://rpc-zetachain-testnet.trusted-point.com:443
- REST API: https://api-zetachain-testnet.trusted-point.com:443
- WSS: wss://rpc-zetachain-testnet.trusted-point.com:443/websocket
- P2P Persistent Peer: b314f4b177c5d52a831d2829fdb9d4f069475dca@rpc-zetachain-testnet.trusted-point.com:26756
---
## Discord Monitoring Bot by TrustedPoint

(On Zetachain server only Governance Module is enabled for both mainnet and testnet)
- The solution serves as a vital tool for Zetachain network participants, offering comprehensive insights into the network's dynamics, validators, governance proceedings, upcoming upgrades, emergency alerts, and key metrics.

- Alert Services: For validators and stakeholders, the bot provides subscription services for timely alerts. Users receive notifications about critical events such as block skipping, validator exclusion from an active set, commission adjustments, and more.

- Real-Time Block Streaming: The bot supports real-time streaming of newly produced blocks to a particular channel, enabling users to stay updated on network activities instantly.

- Validator Metrics: Users can easily find reliable validators to stake tokens through the bot's detailed metrics. These metrics include governance participation, total number of slashes, number of delegators, uptime, voting power, and more.

- Our bot can also perform an on-chain RPC and persistent peers scanning.
  
<font size = 5><center><b><u>Key Commands</u></b></center></font>

#### Validators:
- `!val <valoper>`: Key validator metrics + real-time blocks signing
- `!vals`: Uptime + VP %
- `!vals_stake`: Number of delegators + stake + 24-h stake changes
- `!vals_slash`: Total number of slashes of each validator + commission %
- `!cons`: Consensus info (Use during upgrades)
- `!vals_all`: All validators including bonded, unbonded, unbonding
- `!vals_live`: Real-Time validators signatures
- `!self`: Check all validators that you are subscribing without providing a valoper

#### Chain
- `!chain`: Useful chain metrics
- `!params`: Network parameters + binary/tendermint/SDK versions
- `!upgrade`: Current upgrade plan. The bot automatically announces new upgrades. You can subscribe to receive a reminder 100 blocks before the upgrade height. You can manually check the current upgrade plan and subscribe to reminders.

#### Governance
- The bot automatically announces new governance proposals. You can view the current voting status & validator votes as well as subscribe to receive a ping once a new proposal is out (All by clicking buttons under the bot's announcement). You can also check details of the given proposal manually.
- `!props`: All proposals & ids of the active ones
- `!prop <id>`: Proposal info
- `!prop_res <id>`: Proposal expected result
- `!prop_votes <id>`: Active validators votes

#### Dubscription
- `!subs`: Check your validators alerts subscriptions
- `!sub <valoper>`: Subscribe validator alerts
- `!unsub <valoper>`: Unsubscribe validator alerts
- `!unsub_all`: Unsubscribe all validators
- `!self`: Check all validators that you are subscribing without providing a valoper

#### Other
- `!feedback`: Leave us feedback / Report a bug
- `!help`: All available commands with description

#### Validator Alert Tresholds
- Level one:   <95%
- Level two:   <85%
- Level three: <55%
- Recovering
- Recovered
- Commission change
- Moniker change
- Dropping out of the active set
- Joining the active set

[<img src='assets\bot-banner.png' alt='banner' width= '99.9%'>]()
