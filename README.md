# CombineFramework
Example code to learn and understand combine framework.
#Key Concepts:
Publisher:
- Defines how values and errors are produced
- Value type
- Allows registration of a Subscriber

Subscriber:
- Receives values and a completion
- Reference type

Operator:
- Adopts Publisher
- Describes a behavior for changing values
- Subscribes to a Publisher(Upstream)
- Sends results to a Subscriber(Downstream)
- Value type
