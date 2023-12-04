# Flow2

![image](https://github.com/ManiShanker43/Flow2/assets/130231291/25715a54-b4df-4428-8071-c4a52cf9bf9e)

This is a Flow Cadence contract that defines a `SomeContract` contract with various structs, functions, and resources.

## SomeStruct

### Properties
- `a`: A publicly settable string variable.
- `b`: A publicly readable string variable.
- `c`: A contract-level accessible string variable.
- `d`: A self-level accessible string variable.

### Functions
- `publicFunc()`: A public function that can be called from any context.
- `contractFunc()`: A contract-level accessible function that can only be called by the contract itself.
- `privateFunc()`: A self-level accessible function that can only be called by the struct itself.
- `structFunc()`: A public function that demonstrates an area within the struct.

## SomeResource

### Properties
- `e`: An integer variable.

### Functions
- `resourceFunc()`: A function within the `SomeResource` resource that demonstrates an area within the resource.

## Usage

1. Deploy the `SomeContract` contract to the desired Flow blockchain network.
2. Interact with the contract using your preferred Flow blockchain development tools and libraries.
3. Access the properties and call the functions as needed:
   - Use `testStruct` to access the properties and functions within the `SomeStruct` struct.
   - Use `createSomeResource` to create an instance of `SomeResource` and return it as a resource.
   - Call `questsAreFun` to execute the code in the respective area.
