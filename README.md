# AgenticDAO
Agentic DAO for the Chromion 2025 - ChainLink Hackathon Submission

# Approach
We present a novel Agentic DAO system on Vision Chain, a next-generation Ethereum-compatible blockchain protocol featuring Dynamic DAG-based consensus, which enables scalable, low-latency coordination among autonomous AI agents powered by ElizaOS. This DAO framework goes beyond traditional human-governed organizations by allowing AI agents with verifiable decentralized identities (DIDs) to autonomously propose, vote, and act within a permissioned DAO, backed by smart contracts and real-time identity event handling.

🛑 Limitation of Existing DAOs Solved by Agentic DAO
1. Human bottleneck
DAOs often rely heavily on manual voting, proposal creation, and quorum maintenance, leading to delays and governance fatigue.
AI agents autonomously create, vote, and act on proposals using pre-verified identities. No manual input is required for routine governance.
2. Weak identity trust layer
Many DAOs lack robust identity verification. Wallet addresses are pseudonymous and lack metadata.
DID-based Agent Identity Registry ensures each agent has verifiable roles, capabilities, and historical reputation on-chain.
3. Low participation rates
Due to passive communities or time constraints, DAO proposals frequently fail to reach quorum.
Event-driven smart contracts trigger automated, identity-based voting, maintaining high engagement and timely resolutions.
4. Rigid role delegation
Delegation in DAOs is typically static (one key to another), with no fine-grained or contextual control.
Dynamic multi-delegation using DID enables context-aware permissions (e.g., proposal, vote, treasury access).
5. Governance overload
DAOs with many proposals overwhelm voters with decisions that aren’t all relevant.
Agents are filtered into proposal types based on DID attributes, ensuring domain-specific engagement.

🛑 Limitation of Existing Agents Solved by Agentic DAO
1. Stateless intelligence
Most AI agents lack persistent on-chain memory or identity, making them ephemeral and untrustworthy.
Each agent is registered with a unique, persistent DID on Vision Chain—tracked, updated, and verified over time.
2. Lack of coordination
Agents often operate in silos, with no native governance or consensus on actions.
The DAO forms a consensus layer for agents to coordinate, validate, and collectively act.
3. No on-chain authority
Autonomous agents are usually restricted to read-only analytics or off-chain simulations.
The Agent Registry Owner contract authorizes actions on-chain, giving agents real execution power.
4. No secure delegation
When agents act on behalf of others, key management becomes a security liability.
Multi-key DID-based delegation with scoped roles ensures secure and revocable action permissions.
5. Ambiguity in accountability
AI agent behavior lacks traceability. Who decided? Why?
Event logs linked to the DID and proposal context ensure full accountability for each agent's decision and action.



