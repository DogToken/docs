# Entities
___

### MasterChef

| Field | Type | Description |
| :--- | :--- | :--- |
| id | ID | chef address |
| bonusMultiplier | BigInt | bonus multiplier |
| devaddr | Bytes | dev address |
| migrator | Bytes | migrator address |
| owner | Bytes | owner address |
| startBlock | BigInt | start block |
| bone | Bytes | bone token address |
| bonePerBlock | BigInt | bone per block |
| totalAllocPoint | BigInt | total allocation point |
| pools | [Pools] | array of pools |
| poolCount | BigInt | pool count |
| slpBalance | BigDecimal | slp balance |
| slpAge | BigDecimal | slp age |
| slpAgeRemoved | BigDecimal | slp age removed |
| slpDeposited | BigDecimal | slp deposited |
| slpWithdrawn | BigDecimal | slp withdrawn |
| history | [History] | array of history |
| updatedAt | BigInt | updated at |

### History

| Field | Type | Description |
| :--- | :--- | :--- |
| id | ID | chef address |
| bonusMultiplier | BigInt | bonus multiplier |
| devaddr | Bytes | dev address |
| migrator | Bytes | migrator address |
| owner | Bytes | owner address |
| startBlock | BigInt | start block |
| bone | Bytes | bone token address |
| bonePerBlock | BigInt | bone per block |
| totalAllocPoint | BigInt | total allocation point |
| pools | [Pools] | array of pools |
| poolCount | BigInt | pool count |
| slpBalance | BigDecimal | slp balance |
| slpAge | BigDecimal | slp age |
| slpAgeRemoved | BigDecimal | slp age removed |
| slpDeposited | BigDecimal | slp deposited |
| slpWithdrawn | BigDecimal | slp withdrawn |
| history | [History] | array of history |
| updatedAt | BigInt | updated at |

### Pool

| Field | Type | Description |
| :--- | :--- | :--- |
| id | ID | id |
| owner | Bytes | owner address |
| pair | Bytes | pair address |
| allocPoint | BigInt | allocation point |
| lastRewardBlock | BigInt | last reward block |
| accBonePerShare | BigInt | accumulated bone per share |
| users | [User] | array of users |
| userCount | BigInt | user count |
| slpBalance | BigDecimal | slp balance |
| slpAge | BigDecimal | slp age |
| slpAgeRemoved | BigDecimal | slp age removed |
| slpDeposited | BigDecimal | slp deposited |
| slpWithdrawn | BigDecimal | slp withdrawn |
| boneHarvested | BigDecimal | bone harvested |
| boneHarvestedUSD | BigDecimal | bone harvested usd |
| entryUSD | BigDecimal | all-time entries in USD |
| exitUSD | BigDecimal | all-time exits in USD |
| timestamp | BigInt | timestamp |
| block | BigInt | block |
| updatedAt | BigInt | updated at timestamp |

### Pool History

| Field | Type | Description |
| :--- | :--- | :--- |
| id | ID | pool id concatenated with unix timestamp for the start of the day / 86400 |
| pool | Pool | pool |
| pair | Bytes | pair address |
| users | [User] | array of users |
| userCount | BigInt | user count |
| slpBalance | BigDecimal | slp balance |
| slpAge | BigDecimal | slp age |
| slpAgeRemoved | BigDecimal | slp age removed |
| slpDeposited | BigDecimal | slp deposited |
| slpWithdrawn | BigDecimal | slp withdrawn |
| boneHarvested | BigDecimal | bone harvested |
| boneHarvestedUSD | BigDecimal | bone harvested usd |
| entryUSD | BigDecimal | all-time entries in usd |
| exitUSD | BigDecimal | all-time exits in usd |
| timestamp | BigInt | timestamp |
| block | BigInt | block |
| updatedAt | BigInt | updated at timestamp |

### User

| Field | Type | Description |
| :--- | :--- | :--- |
| id | ID | user address |
| pool | Pool | pool |
| amount | BigInt | amount |
| rewardDebt | BigInt | reward debt |
| entryUSD | BigDecimal | all-time entries in usd |
| exitUSD | BigDecimal | all-time exits in usd |
| boneHarvested | BigDecimal | bone harvested |
| boneHarvestedUSD | BigDecimal | bone harvested usd |
| boneHarvestedSinceLockup | BigDecimal | bone harvested since lockup |
| boneHarvestedSinceLockupUSD | BigDecimal | bone harvested since lockup usd |
| timestamp | BigInt | timestamp |
| block | BigInt | block |