| Name               | Type                                           | Slot | Offset | Bytes | Contract                                                                   |
|--------------------|------------------------------------------------|------|--------|-------|----------------------------------------------------------------------------|
| strategyBeacon     | contract IBeacon                               | 0    | 0      | 20    | src/contracts/strategies/StrategyFactoryStorage.sol:StrategyFactoryStorage |
| deployedStrategies | mapping(contract IERC20 => contract IStrategy) | 1    | 0      | 32    | src/contracts/strategies/StrategyFactoryStorage.sol:StrategyFactoryStorage |
| isBlacklisted      | mapping(contract IERC20 => bool)               | 2    | 0      | 32    | src/contracts/strategies/StrategyFactoryStorage.sol:StrategyFactoryStorage |
| __gap              | uint256[48]                                    | 3    | 0      | 1536  | src/contracts/strategies/StrategyFactoryStorage.sol:StrategyFactoryStorage |
