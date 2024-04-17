# Greetings 🤝 fellow voyager 🤹 thanks for dropping by 🚗

## I'm known by "noslav" or "n0slav" on the interwebs

![Profile views](https://komarev.com/ghpvc/?username=noslav)

### Who am I?

🕵️‍♂️ Reasoning from fundamentals is critical for impactful research. My formative years were spent in deep fondness (and study) of physics and engineering. Eventually getting to apply these as a plasma physicist focussed on nuclear fusion reactors and engineering (applied) physics at the Max Planck Institute of Plasma Physics in Germany was a personal milestone.

🇪🇺 Appreciating and accommodating perspectives, cultures and languages is key to building trust. I learnt this from spending over 8 years in my 20s working, studying and traveling in over 45 countries across 5 different continents.

🙋‍♂️ Actions speak louder than words. I learnt this from building my own startups and projects (data science, ml, blockchain) from scratch, either failing and shutting down or succeeding and scaling up.

☯️ Patterns are embedded everywhere while disciplinary boundaries are only arbitrary. I learnt this from engaging extensively across a variety of subjects including but not limited to history, economics, religion, biology, philosophy, anthropology, mathematics, neuroscience, complexity, music and spirituality hence, I aim to learn something new every day.

🪬 Knowledge builds up exponentially over time with experience. As humans, we aim to live in tune with our surroundings, experience a variety of situations and push beyond our comfort zone. To grow the knowledge that can help others better any experience gathered to this aim is never lost as we are always standing on the shoulders of giants.

🎢 Knowing the why enables facing the how. To continually work in the web3 space one must embrace its ethos for openness, decentralization, and democratization of knowledge, resources and capital. This is the next quantum leap in making the world a more inclusive place for all.

✨ The Universe is a magical paradox. Education, reasoning, knowledge and experience only lead us to deeper and larger unresolved questions with complicated intertwined answers. This doesn't alter the fact that the universe is not a problem to be solved but a gift to be lived.

### What do I do?

👨‍💻 Senior decentralized ledger technology and distributed systems engineer with a proven product adoption record, strong research fundamentals (former physicist/data scientist) & an entrepreneurial mindset based in Vancouver, Canada 🇨🇦. I enjoy developing secure, scalable web3 products & infrastructure leveraging applied cryptography protocols and have a knack for sharing technical insights with experts & non-experts alike. I previously worked in software engineering projects based in Germany 🇩🇪 within various sectors - SaaS, Fintech, AI and Crypto for companies like [upvest.co](https://upvest.co), [joinef.com](https://upvest.co), [ost.com](https://github.com/OpenST) and [freshworks.com](https://www.freshworks.com).

🔗 Current expertise is in working extensively with Ethereum Virtual Machine (EVM) blockchains leveraging Golang / Elixir / Node (JS/TS) / Python / Solidity / Docker / GCP / Linux.

### What have I done?

⛓️ Led end-to-end research, development, launch & maintenance of the Covalent decentralized ETL network coupled to a utility token staking programme for over USD 20 MIO in retail-owned CQT with 20+ 3rd party validators like ChorusOne, 1kx, Woodstock, Stakely.io, BwareLabs etc. The ["Block Specimen Product" (BSP)](https://github.com/covalenthq/bsp-geth) is an independent representation of the blockchain state detached from the underlying chain database. Here a canonical unified data export schema is adopted across the blockchain industry for columnar packaging & storage of data generated from transactions execution (as blocks) for fully decentralized POS/POW networks. An [in-smart contract validating mechanism using cryptographic proofs](https://github.com/covalenthq/bsp-staking) ensures a staked [distributed set of validators](https://github.com/covalenthq/bsp-agent) performing the expected honest extraction and export. Penalties are imposed for not staying with live (or invalid) production of block specimens. The core of the Covalent Network, the Block Specimen and the Block Specimen Producer (BSP), is a bulk chain state export method that ultimately leads to the generation of  the canonical representation of a blockchain's historical state. Currently implemented on existing blockchain clients running Geth and Erigon (that work with any CL client). What is ultimately created is a "Block Specimen", a universal canonical representation of a blockchain’s historical state. There are two further considerations regarding the Block Specimen, specifically:
  * BSPs are completely standalone on the forks of Geth while also capable of running validator workloads for any EVM chain.
  * Separation of the storage layer from the block execution and distributed consensus functionality leads to better segregation and upgrades of functionality and re-execution in the blockchain data processing pipeline.
As a result, anyone can run full tracing on the block specimen and accurately recreate the blockchain without access to blockchain client software and build further tooling down the pipeline like "the Refiner".

🗄️ Led design, specification, testing and deployment of a high granularity decentralized data transformation solution - [the "Refiner"](https://github.com/covalenthq/rudder) addressing blockchain data read scalability for EVM forks (Erigon, Go-Ethereum). Exported BSPs form the underlying layer through a [wrapped IPFS node](https://github.com/covalenthq/ipfs-pinner) forming a decentralized storage network. The manifest of all proofs can be read by anyone from a separate EVM public blockchain (soon the Covalent L1) that contains cryptographically validated content hashes for indexable refined chain data objects. The Refiner's Erlang runtime, being highly concurrent has soft real-time fault tolerance & high throughput, scaling transformations to 10x-20x on [finalized BSPs](https://github.com/covalenthq/bsp-finalizer). The Refiner essentially is a concurrent Block Specimen data processing framework designed for scalable and verified data transformations. The output, one of many possible, is a Block Result; a one-to-one representation of block data returned from an RPC call to a blockchain node with optional and additional informative fields. And importantly, the BRP can perform arbitrary transformations over any input Block Specimens concurrently with other transformations, which essentially means that the BRP can concurrently re-execute Ethereum blocks and transactions completely external to their source blockchain node client software, something that no blockchain node clients can currently do. By leveraging the BRP's concurrent processing capability, one can effortlessly perform customizable data indexing with minimal overhead.

💸 Led product design & backend development efforts on a USD [1 MIO project for Ethereum transaction fee predictions](https://www.theblock.co/post/67731/tokenization-startup-upvest-raises-1-million-to-develop-prediction-tool-for-ethereum-gas-fees) using deep neural networks from a POC to an API product scaled to up to 10 MIO calls per week resulting in 18% savings in crypto transfer costs for clients. Stack: Python 3, Jupyter, MongoDB (Atlas, Realm), Tensorflow, Node.JS; GCP, Cloud Functions, Tables & Scheduler.

💨 For a [digital assets (crypto) custody solution](https://upvest.co), co-authored a scalable transaction engine backend for up to 1000 txps using the Ethereum protocol within a microservices & events messaging (redis/rabbitmq) architecture, this being the second most used client API developed at Upvest handling up to 10,000 txs within 2 days. Stack: Golang, TypeScript, Node.JS, Rabbitmq, MongoDB, Kubernetes, Docker, PostgreSQL, Github CI/CD workflows, APM.

👨‍🎓 Prior to moving into the software industry, I was devoted to (computational simulations) research and development at 6 international experimental nuclear fusion energy projects across Europe - Madrid (CIEMAT), Prague (IPP), Cadarache (CEA-ITER), and Lisbon (IPF), with significant portions at Max-Planck Institute for Plasma Physics (MPI) in Greifswald (Wendelstein-7X) & in Munich (ASDEX-UG) resulting in [authorship (and co-authorship) for over 20 papers within international nuclear fusion research journals](https://scholar.google.com/citations?user=rY5ZXHEAAAAJ&hl=en)

## 🚀 Let's build the web3 for the web3 by the web3
