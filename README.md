# We Vote

A simple YES/NO voting smart contract built with Clarity 4 for the Stacks blockchain.

## Features
- Cast a vote (YES or NO).
- Update an existing vote (original vote is replaced).
- View total YES and NO counts.
- Check if a specific user has voted.

## Contract Details
- **Language**: Clarity 4
- **Functions**:
  - `vote(choice)`: Cast your vote (`true` for YES, `false` for NO).
  - `get-results`: Returns the current counts.
  - `has-voted(user)`: Returns the vote details for a user.
