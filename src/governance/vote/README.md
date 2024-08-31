# Vote

<https://dogswap.xyz/vote>

---

## What is Vote?

Vote is how the DogSwap community resolves hard to answer questions about the future of DogSwap.

## How to vote on a proposal?

Simply navigate to <https://dogswap.xyz/vote> and view the open proposals. Clicking on them will show more of the proposal, and clicking "View proposal details" will show the full information. It is recommended to join [Discord](https://discord.com/invite/) and navigate to the `#governance` channel to view the relevant discussion about the proposal. Please only vote if you are informed on the topic.

The BONE you held at the snapshot block will count for your vote weight. Currently, single choice voting is the only type supported. 



## How to create a proposal?

### Bring topic up for discussion

First join [Discord](https://discord.com/invite/) and navigate to the `#governance` channel. 

Make a comment describing your proposal in the following format:

```
PROPOSAL: [Your proposal title here]

Write a longer description here, including the following (if relevant):
* economic impact
* impact on users
* expected positive impact
* known potential negatives or downsides
* unknown impacts or aspects


OPTIONS:
- [Option #1]
- [Option #2]
- [...]

```

People will be able to respond to your proposal request and give feedback. This can help you to improve your proposal, so don't worry if initial reaction is negative. You can incorporate feedback and try again.

### Create Pull Request on bone-governance

Once a proposal has been discussed sufficiently to where you think it makes sense to open it to a vote, you can make a PR at the [bone-governance](https://github.com/dogtoken/bone-governance) repository. If you need assistance making a PR, do not hesitate to ask in the `#governance` group - a member of the DogSwap team can assist.

After 1 week of being available as a PR for people to read, the snapshot block will be updated and the PR will be merged and available for people to vote.

## How are proposals decided upon?

First, a quorum of at least 20% of BONE total supply must have voted on the proposal. If this number is not reached the vote is declared undecided and may be retried in the future.

Then, if quorum is reached, the majority voted upon option is selected as winner.

Doggo has technical veto power as the owner of the dApp, however this power should only be used in the most extreme circumstance, and in future will be decentralized as DogSwap becomes a DAO.
