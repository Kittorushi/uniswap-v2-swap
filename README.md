# Uniswap V2 Swap Examples

This repository provides Solidity code examples for performing token swaps using the Uniswap V2 protocol. The code demonstrates different swapping scenarios, including single-hop and multi-hop trades, with tokens such as WETH, DAI, and USDC.

## Code Explanation

The Solidity code in this repository showcases how to interact with the Uniswap V2 Router contract to execute token swaps. It includes the following functions:

- `swapSingleHopExactAmountIn`: Swaps a specified amount of WETH for DAI in a single trade.
- `swapMultiHopExactAmountIn`: Swaps DAI for USDC using a multi-hop trade.
- `swapSingleHopExactAmountOut`: Swaps a desired amount of DAI for WETH.
- `swapMultiHopExactAmountOut`: Swaps a desired amount of DAI for USDC using multiple hops.

For a detailed explanation of each function and how the code works, please refer to the code comments in the [UniswapV2SwapExamples.sol](src/UniswapV2SwapExamples.sol) file.

## Usage

To use these examples, you can deploy the `UniswapV2SwapExamples` contract on the Ethereum network of your choice. Make sure to provide the necessary token addresses for WETH, DAI, and USDC.

Once deployed, you can call the contract functions to perform token swaps according to your requirements.

## Testing

This repository also includes a testing contract, [UniswapV2SwapExamplesTest.sol](test/UniswapV2SwapExamplesTest.sol), which demonstrates how to test the functionality of the `UniswapV2SwapExamples` contract. The tests cover various scenarios for both single-hop and multi-hop trades.

To run the tests, you can use a Solidity testing framework like [Hardhat](https://hardhat.org/) or [Truffle](https://www.trufflesuite.com/truffle).

## License

This code is licensed under the MIT License. You can find the full license text in the [LICENSE](LICENSE) file.

