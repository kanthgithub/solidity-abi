# solidity-abi
all about abi and abi encoding in solidity and EVM

## ABI - Encoding:
 
 - abi.encode(...) returns (bytes): ABI-encodes the given arguments
 - abi.encodePacked(...) returns (bytes): Performes packed encoding of the given arguments
 - abi.encodeWithSelector(bytes4 selector, ...) returns (bytes): 
    ABI-encodes the given arguments starting from the second and prepends the given four-byte selector
 - abi.encodeWithSignature(string signature, ...) returns (bytes): Equivalent to abi.encodeWithSelector(bytes4(keccak256(signature), ...)
    
    
- https://medium.com/@libertylocked/what-are-abi-encoding-functions-in-solidity-0-4-24-c1a90b5ddce8

