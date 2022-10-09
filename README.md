# Smart Contracts For All DApps at One Place

This project is built for making open source Smart Contracts for all use cases. This will make DApps development more secure, faster and better to all.

## Getting Started 
1.Clone Project:

```shell
git clone https://github.com/siddhpurakaran/Smart_Contracts.git
or
git clone git@github.com:siddhpurakaran/Smart_Contracts.git
or
gh repo clone siddhpurakaran/Smart_Contracts
```

2.Install Dependencies

```shell
npm install
```

3.Test Contracts

```shell
REPORT_GAS=true npx hardhat test
```

4.Test Coverage

```shell
npx hardhat coverage
```

5.Deploy Contracts

```shell
npx hardhat run scripts/deploy_contract_name.js --network Network_Name
Example 
npx hardhat run scripts/deploy_crowdfund.js --network hardhat

```