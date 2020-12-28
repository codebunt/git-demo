# `CarboTag`

<docment-me>

You can use this contract for transacting carbon credits.

Contract which executes trade between 2 entities via escrow.

# Functions:

- [`getEscrowList(address _address)`](#CarboTag-getEscrowList-address-)

- [`constructor(address factory, address payable oldAddr)`](#CarboTag-constructor-address-address-payable-)

- [`fallback()`](#CarboTag-fallback--)

- [`addGovernor(address _target)`](#CarboTag-addGovernor-address-)

- [`signUp(string name)`](#CarboTag-signUp-string-)

- [`findEscrowAddr(address _sender, address _receiver)`](#CarboTag-findEscrowAddr-address-address-)

- [`createEscrow(address _receiver)`](#CarboTag-createEscrow-address-)

- [`addCarbon(uint256 carbon)`](#CarboTag-addCarbon-uint256-)

- [`createTransaction(address _receiver, int256 _carbon, int256 _gold)`](#CarboTag-createTransaction-address-int256-int256-)

- [`acceptTransaction(address _sender, address _receiver, uint256 _txID, int256 _carbon, int256 _gold)`](#CarboTag-acceptTransaction-address-address-uint256-int256-int256-)

- [`rejectTransaction(address _counterparty, uint256 _txID)`](#CarboTag-rejectTransaction-address-uint256-)

- [`addStamper(address target, uint256 stamprate, uint256 minpmt)`](#CarboTag-addStamper-address-uint256-uint256-)

- [`updateGold(uint256 stamps, address stamper)`](#CarboTag-updateGold-uint256-address-)

- [`transactionData(address _escrowAddr, uint256 _txID)`](#CarboTag-transactionData-address-uint256-)

- [`getTransactionIds(address _escrowAddr, uint256 from, uint256 to)`](#CarboTag-getTransactionIds-address-uint256-uint256-)

- [`changeOwner(address _newOwner)`](#CarboTag-changeOwner-address-)

- [`killContract()`](#CarboTag-killContract--)

# Events:

- [`EscrowFunded(address sender, uint256 value)`](#CarboTag-EscrowFunded-address-uint256-)

# Function `getEscrowList(address _address) → address[]` {#CarboTag-getEscrowList-address-}

No description

# Function `constructor(address factory, address payable oldAddr)` {#CarboTag-constructor-address-address-payable-}

No description

# Function `fallback()` {#CarboTag-fallback--}

No description

# Function `addGovernor(address _target)` {#CarboTag-addGovernor-address-}

No description

# Function `signUp(string name)` {#CarboTag-signUp-string-}

No description

# Function `findEscrowAddr(address _sender, address _receiver) → address payable _escrow` {#CarboTag-findEscrowAddr-address-address-}

No description

# Function `createEscrow(address _receiver) → address payable _escrowAddr` {#CarboTag-createEscrow-address-}

create a escrow account with you and the receiver

## Parameters:

- `_receiver`: The receiver account

## Return Values:

- Escrow Address

# Function `addCarbon(uint256 carbon)` {#CarboTag-addCarbon-uint256-}

No description

# Function `createTransaction(address _receiver, int256 _carbon, int256 _gold)` {#CarboTag-createTransaction-address-int256-int256-}

No description

# Function `acceptTransaction(address _sender, address _receiver, uint256 _txID, int256 _carbon, int256 _gold)` {#CarboTag-acceptTransaction-address-address-uint256-int256-int256-}

No description

# Function `rejectTransaction(address _counterparty, uint256 _txID)` {#CarboTag-rejectTransaction-address-uint256-}

No description

# Function `addStamper(address target, uint256 stamprate, uint256 minpmt)` {#CarboTag-addStamper-address-uint256-uint256-}

No description

# Function `updateGold(uint256 stamps, address stamper)` {#CarboTag-updateGold-uint256-address-}

No description

# Function `transactionData(address _escrowAddr, uint256 _txID) → uint256` {#CarboTag-transactionData-address-uint256-}

No description

# Function `getTransactionIds(address _escrowAddr, uint256 from, uint256 to) → uint256[] _transactionIds` {#CarboTag-getTransactionIds-address-uint256-uint256-}

No description

# Function `changeOwner(address _newOwner)` {#CarboTag-changeOwner-address-}

No description

# Function `killContract()` {#CarboTag-killContract--}

No description

# Event `EscrowFunded(address sender, uint256 value)` {#CarboTag-EscrowFunded-address-uint256-}

No description
