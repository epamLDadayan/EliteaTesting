| Id | Name | Description | Type | Status | Priority | Test Type | Precondition | Test Step Number | Test Step Description | Test Step Expected Result |
|--------|-------------------------------------------|-----------------------------------------------------------------------------|--------|--------|----------|-------------|---------------|------------------|-------------------------------------------------------------|----------------------------------------------------------------|
| TC_001 | Verify Function Node Initialization | Verify that the function node initializes correctly when added to the pipeline with valid configuration | Manual | New | High | Functional | | 1 | Add a function node to the pipeline | Function node is added to the pipeline |
| | | | | | | | | 2 | Configure the function node with valid settings | Function node configuration is valid |
| | | | | | | | | 3 | Execute the pipeline | Pipeline execution starts |
| | | | | | | | | 4 | Check the initialization status of the function node | Function node initializes correctly |
| | | | | | | | | 5 | Verify the logs for initialization status | Logs show the initialization status of the function node |
| TC_002 | Validate Initialization Log Entry | Validate that the initialization status is logged correctly when the function node initializes | Manual | New | Medium | Functional | | 1 | Add a function node to the pipeline | Function node is added to the pipeline |
| | | | | | | | | 2 | Configure the function node with valid settings | Function node configuration is valid |
| | | | | | | | | 3 | Execute the pipeline | Pipeline execution starts |
| | | | | | | | | 4 | Check the initialization status of the function node | Function node initializes correctly |
| | | | | | | | | 5 | Open the log file or log viewer | Log file or log viewer is opened |
| | | | | | | | | 6 | Verify the log entry for the function node initialization | Log entry shows the correct initialization status of the function node |
| TC_003 | Test Pipeline Execution with Multiple Nodes | Test the pipeline execution with multiple nodes including a function node to ensure correct initialization | Manual | New | Medium | Functional | | 1 | Add multiple nodes including a function node to the pipeline | Multiple nodes including a function node are added to the pipeline |
| | | | | | | | | 2 | Configure all nodes with valid settings | All nodes are configured with valid settings |
| | | | | | | | | 3 | Execute the pipeline | Pipeline execution starts |
| | | | | | | | | 4 | Check the initialization status of the function node | Function node initializes correctly |
| | | | | | | | | 5 | Verify the logs for initialization status of all nodes | Logs show the initialization status of all nodes including the function node |
| TC_004 | Verify Initialization with Different Configurations | Verify that the function node initializes correctly with different valid configurations | Manual | New | Medium | Functional | | 1 | Add a function node to the pipeline | Function node is added to the pipeline |
| | | | | | | | | 2 | Configure the function node with a different valid setting | Function node configuration is valid |
| | | | | | | | | 3 | Execute the pipeline | Pipeline execution starts |
| | | | | | | | | 4 | Check the initialization status of the function node | Function node initializes correctly |
| | | | | | | | | 5 | Verify the logs for initialization status | Logs show the initialization status of the function node |
| TC_005 | Validate Error Handling on Invalid Configuration | Validate that the function node does not initialize and logs an error when configured with invalid settings | Manual | New | High | Functional | | 1 | Add a function node to the pipeline | Function node is added to the pipeline |
| | | | | | | | | 2 | Configure the function node with invalid settings | Function node configuration is invalid |
| | | | | | | | | 3 | Execute the pipeline | Pipeline execution starts |
| | | | | | | | | 4 | Check the initialization status of the function node | Function node does not initialize |
| | | | | | | | | 5 | Verify the logs for error messages | Logs show error messages indicating invalid configuration |