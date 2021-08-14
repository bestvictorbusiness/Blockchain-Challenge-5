/*
    ========== OGL Prokect ==========
    OGL Uniswap Introduction
    
    OGL is offering green Dapp access. This means that through OGL, the user is able to
    interact with any Dapp, while at the same time supporting green causes like planting trees.
    
    Specifically for Uniswap, the so-called "Climate Fee" is collected by collecting any excess 
    slippage of Uniswap trades going through the OGL Platform.
    
    As a practical example: Alice wants to buy 100 BRKL at the current price of 0.01 ETH, with
    a slippage of 5% through the OGL platform. She agrees on excess slippage going to green
    projects around the world. Now, at the time of execution, the price seems to have slightly
    moved higher, so that Alice only receives 97 BRKL for 0.01ETH, because she was fine with
    having a slippage of 5% though, the trade still goes through.
    
    Now, because of the 5% slippage, we know Alice was also fine with just getting 95 BRKL for
    her ETH. In this case, there is a slippage of exactly 2 BRKL tokens. Because Alice agreed
    on the excess slippage going to charitable causes, she will only receive 95 BRKL, while the
    other 2 BRKL will be held in the contract.
*/

/*
    OGL Coding Challenge
    
    Complete the tasks to the best of your understanding. The code should does not need to be 
    functional - the rating solely depends on the logic applied and understanding of the concepts.
    
    No further task information should be needed to finish the exercises.
*/

/*
    Exercise 1 - Utilize Uniswap V3 Router
    
    Utilize the Uniswap V3 router from a OGL smart contract, to perform trades where excess slippage
    defined in the User Interface is being held in the contract.
    
    Note: One way of doing it is to call the function exactInputSingle()
    
    
    Uniswap V3 Router: 0xe592427a0aece92de3edee1f18e0157c05861564
*/


// SPDX-License-Identifier: GPL-3.0

pragma solidity >=0.7.0 <0.9.0;

contract ExerciseOne {
    // assume all needed contracts and interfaces to have been properly imported

    /*
        Swap through the Uniswap V3 Router and keep excess slippage inside the contract.
    */
    function OGLSwap(/*params*/) external payable returns(uint256 excessSlippage) {
        
    }
}


/*
    Exercise 2 - Replace Uniswap V2 Router
    
    Replace one method in the Uniswap V2 router with a OGL Swap Router, to perform trades directly 
    through the pools, where excess slippage defined in the User Interface is being held in the contract.
    
    Note: Replace the method swapExactETHForTokens
    
    Uniswap V2 Router: 0x7a250d5630b4cf539739df2c5dacb4c659f2488d
*/

contract ExerciseTwo {
    // assume all needed contracts and interfaces to have been properly imported
    
    /*
        Swap directly through the Uniswap V2 pair and keep excess slippage inside the  contract.
    */
    function OGLSwap(/*params*/) external payable returns(uint256 excessSlippage) {}
}





