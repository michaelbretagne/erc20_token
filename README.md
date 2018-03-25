# erc20_token

This smart contract allow anyone to create an ERC-20 compliant token on the Ethereum blockchain.

## ERC-20 Specifies Six Functions and Two Events:

The ERC-20 is a list of rules that Ethereum tokens must follow.
ERC-20 defines six different functions for the benefit of other tokens within the Ethereum system. These are generally basic functionality issues, including how tokens are transferred and how users can access data about a token. ERC-20 also prescribes two different signals that each token takes on and which other tokens are attuned to.

### The Six Functions:

    - function totalSupply() view returns (uint256 totalSupply) {}
    - function balanceOf(address _someone) public view returns (uint256 balance) {}
    - function transfer(address _to, uint256 _value) public returns (bool success) {}
    - function allowance(address _owner, address _spender) public view returns (uint remaining) {}
    - function approve(address _spender, uint256 _value) public returns (bool success) {}
    - function transferFrom(address _from, address _to, uint256 _value) public returns (bool success) {}

### The Two Events:

    - event Transfer(address _from, address _to, uint256 _value);
    - event Approval(address indexed _owner, address indexed _spender, uint256 _value);
