# Brief
```
Exercise name:        Simple Registry
Assignment #:         1
Testing framework:    Foundry
Deployment framework: Foundry (forge create)
Node provider:        Infura
Target network:       Kovan
```

## Assignment summary

Code a registry inspired by the [Hashmasks name registry](https://www.thehashmasks.com/names), but with some simplifications.

* Users (identified by an address) can claim a name, which is recorded on-chain.
* Once a name has been claimed, no other user can claim it.
* A name owner can release a name.
* A user can claim any number of names.
* The contract should be fully [tested](https://book.getfoundry.sh/forge/tests.html) ([example](https://github.com/yieldprotocol/vault-v2/blob/master/contracts/foundry-tests/ChainlinkMultiOracle.t.sol)), [deployed](https://book.getfoundry.sh/forge/deploying.html#deploying) on the Kovan testnet ([example](https://kovan.etherscan.io/address/0xd0a1e359811322d97991e03f863a0c30c2cf029c#code)), and [verified](https://book.getfoundry.sh/forge/deploying.html#verifying) in Etherscan.
* Include the link to the deployed and verified contract in your pull request.

## Tips to get started

* Set up a new Ethereum wallet for the mentorship. Get some testnet eth from the [Paradigm faucet](https://faucet.paradigm.xyz/)
* Create a new gh repo. Don't use a template. Be sure to set the visibility to PUBLIC so it can be shared with mentors and fellow mentees. For future exercises, it's up to you if you'd like to create a new repo for each assignment, build on top of one main branch in one repo, or have a different branches in one repo for each assignment. The important part is being able to submit a pr with a clean diff for each assignment to be reviewed by mentors (as well as fellow mentees).
* [Install Foundry](https://book.getfoundry.sh/getting-started/installation.html). Note: [The Foundry Book](https://book.getfoundry.sh/) is your primary resource for all of your Foundry ?'s.
* Use `forge init` to [create a new Foundry project](https://book.getfoundry.sh/projects/creating-a-new-project.html). Do not use a template for the mentorship so that you may understand everything going into your project.
* If you don't already have one, you will need an [Infura](https://infura.io/) account for this assignment to deploy this assignment to Kovan. Future assignments may use different node providers such as Alchemy and may deploy to different testnets.
* You will also need an [etherscan account](https://etherscan.io/) for an api key to verify your contracts after deploy.

## Mentorship peripheral goals

We are proponents of learning in public. For this reason we encourage the use of the Slack channel for questions, as opposed to dm's. There are no dumb questions, and if you have a question chances are good someone else has it as well. We also encourage the use of StackOverflow and Twitter for asking questions in public.

A great way to reinforce learning is to write about it. We encourage all mentees to consider writing at least one article or blog post during the course of the mentorship. Keep that in mind as you are learning. Good places to publish the article include HackerNoon or Medium. Some people prefer Twitter threads or even video format. You can solicit feedback on article ideas or on your draft articles in the Slack channel. In addition to reinforcing your learning, this is also an opportunity to give back to the Ethereum and greater web3 community.

Another way to contribute to the community is through open source software (OSS). During the course of the mentorship we also encourage you to make pull requests in OSS libraries or repos that you use. An easy first contribution could be to [The Foundry Book](https://github.com/foundry-rs/book). If you find mistakes or that something could be explained better, consider submitting a pr.