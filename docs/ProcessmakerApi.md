# ProcessMaker_PMIO.ProcessmakerApi

All URIs are relative to *https://CHANGEME.api.processmaker.io/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_client**](ProcessmakerApi.md#add_client) | **POST** /users/{user_id}/clients | 
[**add_event**](ProcessmakerApi.md#add_event) | **POST** /processes/{process_id}/events | 
[**add_event_connector**](ProcessmakerApi.md#add_event_connector) | **POST** /processes/{process_id}/events/{event_id}/connectors | 
[**add_flow**](ProcessmakerApi.md#add_flow) | **POST** /processes/{process_id}/flows | 
[**add_gateway**](ProcessmakerApi.md#add_gateway) | **POST** /processes/{process_id}/gateways | 
[**add_group**](ProcessmakerApi.md#add_group) | **POST** /groups | 
[**add_groups_to_task**](ProcessmakerApi.md#add_groups_to_task) | **PUT** /processes/{process_id}/tasks/{task_id}/groups | 
[**add_input_output**](ProcessmakerApi.md#add_input_output) | **POST** /processes/{process_id}/tasks/{task_id}/inputoutput | 
[**add_instance**](ProcessmakerApi.md#add_instance) | **POST** /processes/{process_id}/instances | 
[**add_process**](ProcessmakerApi.md#add_process) | **POST** /processes | 
[**add_task**](ProcessmakerApi.md#add_task) | **POST** /processes/{process_id}/tasks | 
[**add_task_connector**](ProcessmakerApi.md#add_task_connector) | **POST** /processes/{process_id}/tasks/{task_id}/connectors | 
[**add_user**](ProcessmakerApi.md#add_user) | **POST** /users | 
[**add_users_to_group**](ProcessmakerApi.md#add_users_to_group) | **PUT** /groups/{id}/users | 
[**delete_client**](ProcessmakerApi.md#delete_client) | **DELETE** /users/{user_id}/clients/{client_id} | 
[**delete_event**](ProcessmakerApi.md#delete_event) | **DELETE** /processes/{process_id}/events/{event_id} | 
[**delete_event_connector**](ProcessmakerApi.md#delete_event_connector) | **DELETE** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**delete_flow**](ProcessmakerApi.md#delete_flow) | **DELETE** /processes/{process_id}/flows/{flow_id} | 
[**delete_gateway**](ProcessmakerApi.md#delete_gateway) | **DELETE** /processes/{process_id}/gateways/{gateway_id} | 
[**delete_group**](ProcessmakerApi.md#delete_group) | **DELETE** /groups/{id} | 
[**delete_input_output**](ProcessmakerApi.md#delete_input_output) | **DELETE** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**delete_instance**](ProcessmakerApi.md#delete_instance) | **DELETE** /processes/{process_id}/instances/{instance_id} | 
[**delete_process**](ProcessmakerApi.md#delete_process) | **DELETE** /processes/{id} | 
[**delete_task**](ProcessmakerApi.md#delete_task) | **DELETE** /processes/{process_id}/tasks/{task_id} | 
[**delete_task_connector**](ProcessmakerApi.md#delete_task_connector) | **DELETE** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**delete_user**](ProcessmakerApi.md#delete_user) | **DELETE** /users/{id} | 
[**event_trigger**](ProcessmakerApi.md#event_trigger) | **POST** /processes/{process_id}/events/{event_id}/trigger | 
[**find_client_by_id**](ProcessmakerApi.md#find_client_by_id) | **GET** /users/{user_id}/clients/{client_id} | 
[**find_clients**](ProcessmakerApi.md#find_clients) | **GET** /users/{user_id}/clients | 
[**find_data_model**](ProcessmakerApi.md#find_data_model) | **GET** /processes/{process_id}/instances/{instance_id}/datamodel | 
[**find_event_by_id**](ProcessmakerApi.md#find_event_by_id) | **GET** /processes/{process_id}/events/{event_id} | 
[**find_event_connector_by_id**](ProcessmakerApi.md#find_event_connector_by_id) | **GET** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**find_event_connectors**](ProcessmakerApi.md#find_event_connectors) | **GET** /processes/{process_id}/events/{event_id}/connectors | 
[**find_events**](ProcessmakerApi.md#find_events) | **GET** /processes/{process_id}/events | 
[**find_flow_by_id**](ProcessmakerApi.md#find_flow_by_id) | **GET** /processes/{process_id}/flows/{flow_id} | 
[**find_flows**](ProcessmakerApi.md#find_flows) | **GET** /processes/{process_id}/flows | 
[**find_gateway_by_id**](ProcessmakerApi.md#find_gateway_by_id) | **GET** /processes/{process_id}/gateways/{gateway_id} | 
[**find_gateways**](ProcessmakerApi.md#find_gateways) | **GET** /processes/{process_id}/gateways | 
[**find_group_by_id**](ProcessmakerApi.md#find_group_by_id) | **GET** /groups/{id} | 
[**find_groups**](ProcessmakerApi.md#find_groups) | **GET** /groups | 
[**find_input_output_by_id**](ProcessmakerApi.md#find_input_output_by_id) | **GET** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**find_input_outputs**](ProcessmakerApi.md#find_input_outputs) | **GET** /processes/{process_id}/tasks/{task_id}/inputoutput | 
[**find_instance_by_id**](ProcessmakerApi.md#find_instance_by_id) | **GET** /processes/{process_id}/instances/{instance_id} | 
[**find_instances**](ProcessmakerApi.md#find_instances) | **GET** /processes/{process_id}/instances | 
[**find_process_by_id**](ProcessmakerApi.md#find_process_by_id) | **GET** /processes/{id} | 
[**find_processes**](ProcessmakerApi.md#find_processes) | **GET** /processes | 
[**find_task_by_id**](ProcessmakerApi.md#find_task_by_id) | **GET** /processes/{process_id}/tasks/{task_id} | 
[**find_task_connector_by_id**](ProcessmakerApi.md#find_task_connector_by_id) | **GET** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**find_task_connectors**](ProcessmakerApi.md#find_task_connectors) | **GET** /processes/{process_id}/tasks/{task_id}/connectors | 
[**find_task_instance_by_id**](ProcessmakerApi.md#find_task_instance_by_id) | **GET** /task_instances/{task_instance_id} | 
[**find_task_instances**](ProcessmakerApi.md#find_task_instances) | **GET** /task_instances | 
[**find_tasks**](ProcessmakerApi.md#find_tasks) | **GET** /processes/{process_id}/tasks | 
[**find_user_by_id**](ProcessmakerApi.md#find_user_by_id) | **GET** /users/{id} | 
[**find_users**](ProcessmakerApi.md#find_users) | **GET** /users | 
[**import_bpmn_file**](ProcessmakerApi.md#import_bpmn_file) | **POST** /processes/import | 
[**myself_user**](ProcessmakerApi.md#myself_user) | **GET** /users/myself | 
[**remove_groups_from_task**](ProcessmakerApi.md#remove_groups_from_task) | **DELETE** /processes/{process_id}/tasks/{task_id}/groups | 
[**remove_users_from_group**](ProcessmakerApi.md#remove_users_from_group) | **DELETE** /groups/{id}/users | 
[**sync_groups_to_task**](ProcessmakerApi.md#sync_groups_to_task) | **POST** /processes/{process_id}/tasks/{task_id}/groups | 
[**sync_users_to_group**](ProcessmakerApi.md#sync_users_to_group) | **POST** /groups/{id}/users | 
[**update_client**](ProcessmakerApi.md#update_client) | **PUT** /users/{user_id}/clients/{client_id} | 
[**update_event**](ProcessmakerApi.md#update_event) | **PUT** /processes/{process_id}/events/{event_id} | 
[**update_event_connector**](ProcessmakerApi.md#update_event_connector) | **PUT** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**update_flow**](ProcessmakerApi.md#update_flow) | **PUT** /processes/{process_id}/flows/{flow_id} | 
[**update_gateway**](ProcessmakerApi.md#update_gateway) | **PUT** /processes/{process_id}/gateways/{gateway_id} | 
[**update_group**](ProcessmakerApi.md#update_group) | **PUT** /groups/{id} | 
[**update_input_output**](ProcessmakerApi.md#update_input_output) | **PUT** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**update_instance**](ProcessmakerApi.md#update_instance) | **PUT** /processes/{process_id}/instances/{instance_id} | 
[**update_process**](ProcessmakerApi.md#update_process) | **PUT** /processes/{id} | 
[**update_task**](ProcessmakerApi.md#update_task) | **PUT** /processes/{process_id}/tasks/{task_id} | 
[**update_task_connector**](ProcessmakerApi.md#update_task_connector) | **PUT** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**update_task_instance**](ProcessmakerApi.md#update_task_instance) | **PATCH** /task_instances/{task_instance_id} | 
[**update_user**](ProcessmakerApi.md#update_user) | **PUT** /users/{id} | 


# **add_client**
> ClientItem add_client(user_id, client_create_item)



This method creates a new Oauth client for the user

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_id = 'user_id_example' # str | ID of the user related to the Oauth client
client_create_item = ProcessMaker_PMIO.ClientCreateItem() # ClientCreateItem | JSON API with the Oauth Client object to add

try: 
    api_response = api_instance.add_client(user_id, client_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_client: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| ID of the user related to the Oauth client | 
 **client_create_item** | [**ClientCreateItem**](ClientCreateItem.md)| JSON API with the Oauth Client object to add | 

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_event**
> EventItem add_event(process_id, event_create_item)



This method creates the new event.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of the process related to the event
event_create_item = ProcessMaker_PMIO.EventCreateItem() # EventCreateItem | JSON API response with the Event object to add

try: 
    api_response = api_instance.add_event(process_id, event_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_event: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of the process related to the event | 
 **event_create_item** | [**EventCreateItem**](EventCreateItem.md)| JSON API response with the Event object to add | 

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_event_connector**
> EventConnector1 add_event_connector(process_id, event_id, event_connector_create_item)



This method is intended for creating a new Event connector.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
event_id = 'event_id_example' # str | ID of Event to fetch
event_connector_create_item = ProcessMaker_PMIO.EventConnectorCreateItem() # EventConnectorCreateItem | JSON API with the EventConnector object to add

try: 
    api_response = api_instance.add_event_connector(process_id, event_id, event_connector_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_event_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **event_id** | **str**| ID of Event to fetch | 
 **event_connector_create_item** | [**EventConnectorCreateItem**](EventConnectorCreateItem.md)| JSON API with the EventConnector object to add | 

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_flow**
> FlowItem add_flow(process_id, flow_create_item)



This method creates a new Sequence flow

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of the process related to the flow
flow_create_item = ProcessMaker_PMIO.FlowCreateItem() # FlowCreateItem | JSON API response with the Flow object to add

try: 
    api_response = api_instance.add_flow(process_id, flow_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_flow: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of the process related to the flow | 
 **flow_create_item** | [**FlowCreateItem**](FlowCreateItem.md)| JSON API response with the Flow object to add | 

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_gateway**
> GatewayItem add_gateway(process_id, gateway_create_item)



This method creates a new gateway.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of the process related to the gateway
gateway_create_item = ProcessMaker_PMIO.GatewayCreateItem() # GatewayCreateItem | JSON API response with the gateway object to add

try: 
    api_response = api_instance.add_gateway(process_id, gateway_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_gateway: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of the process related to the gateway | 
 **gateway_create_item** | [**GatewayCreateItem**](GatewayCreateItem.md)| JSON API response with the gateway object to add | 

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_group**
> GroupItem add_group(group_create_item)



This method creates a new group.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
group_create_item = ProcessMaker_PMIO.GroupCreateItem() # GroupCreateItem | JSON API with the Group object to add

try: 
    api_response = api_instance.add_group(group_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_create_item** | [**GroupCreateItem**](GroupCreateItem.md)| JSON API with the Group object to add | 

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_groups_to_task**
> ResultSuccess add_groups_to_task(process_id, task_id, task_add_groups_item)



This method assigns group(s) to the choosen task

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
task_id = 'task_id_example' # str | ID of task to be modified
task_add_groups_item = ProcessMaker_PMIO.TaskAddGroupsItem() # TaskAddGroupsItem | JSON API with Groups ID's to add

try: 
    api_response = api_instance.add_groups_to_task(process_id, task_id, task_add_groups_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_groups_to_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **task_id** | **str**| ID of task to be modified | 
 **task_add_groups_item** | [**TaskAddGroupsItem**](TaskAddGroupsItem.md)| JSON API with Groups ID&#39;s to add | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_input_output**
> InputOutputItem add_input_output(process_id, task_id, input_output_create_item)



This method creates a new Input/Output object

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to Input/Output object
task_id = 'task_id_example' # str | Task instance ID related to Input/Output object
input_output_create_item = ProcessMaker_PMIO.InputOutputCreateItem() # InputOutputCreateItem | Create and add a new Input/Output object with JSON API

try: 
    api_response = api_instance.add_input_output(process_id, task_id, input_output_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_input_output: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to Input/Output object | 
 **task_id** | **str**| Task instance ID related to Input/Output object | 
 **input_output_create_item** | [**InputOutputCreateItem**](InputOutputCreateItem.md)| Create and add a new Input/Output object with JSON API | 

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_instance**
> InstanceItem add_instance(process_id, instance_create_item)



This method creates a new instance.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the nstance
instance_create_item = ProcessMaker_PMIO.InstanceCreateItem() # InstanceCreateItem | JSON API response with the Instance object to add

try: 
    api_response = api_instance.add_instance(process_id, instance_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_instance: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the nstance | 
 **instance_create_item** | [**InstanceCreateItem**](InstanceCreateItem.md)| JSON API response with the Instance object to add | 

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_process**
> ProcessItem add_process(process_create_item)



This method creates a new process

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_create_item = ProcessMaker_PMIO.ProcessCreateItem() # ProcessCreateItem | JSON API response with the Process object to add

try: 
    api_response = api_instance.add_process(process_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_process: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_create_item** | [**ProcessCreateItem**](ProcessCreateItem.md)| JSON API response with the Process object to add | 

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_task**
> TaskItem add_task(process_id, task_create_item)



This method creates a new task.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the task
task_create_item = ProcessMaker_PMIO.TaskCreateItem() # TaskCreateItem | JSON API with the Task object to add

try: 
    api_response = api_instance.add_task(process_id, task_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the task | 
 **task_create_item** | [**TaskCreateItem**](TaskCreateItem.md)| JSON API with the Task object to add | 

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_task_connector**
> TaskConnector1 add_task_connector(process_id, task_id, task_connector_create_item)



This method is intended for creating a new task connector.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
task_id = 'task_id_example' # str | ID of Task to fetch
task_connector_create_item = ProcessMaker_PMIO.TaskConnectorCreateItem() # TaskConnectorCreateItem | JSON API with the TaskConnector object to add

try: 
    api_response = api_instance.add_task_connector(process_id, task_id, task_connector_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_task_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **task_id** | **str**| ID of Task to fetch | 
 **task_connector_create_item** | [**TaskConnectorCreateItem**](TaskConnectorCreateItem.md)| JSON API with the TaskConnector object to add | 

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_user**
> UserItem add_user(user_create_item)



This method creates a new user in the system.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_create_item = ProcessMaker_PMIO.UserCreateItem() # UserCreateItem | JSON API with the User object to add

try: 
    api_response = api_instance.add_user(user_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_user: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_create_item** | [**UserCreateItem**](UserCreateItem.md)| JSON API with the User object to add | 

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_users_to_group**
> ResultSuccess add_users_to_group(id, group_add_users_item)



This method adds one or more new users to a group.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to be modified
group_add_users_item = ProcessMaker_PMIO.GroupAddUsersItem() # GroupAddUsersItem | JSON API response with array of users ID's

try: 
    api_response = api_instance.add_users_to_group(id, group_add_users_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->add_users_to_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to be modified | 
 **group_add_users_item** | [**GroupAddUsersItem**](GroupAddUsersItem.md)| JSON API response with array of users ID&#39;s | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_client**
> ResultSuccess delete_client(user_id, client_id)



This method deletes an Oauth client using the client and user IDs.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_id = 'user_id_example' # str | User ID
client_id = 'client_id_example' # str | ID of client to delete

try: 
    api_response = api_instance.delete_client(user_id, client_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_client: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| User ID | 
 **client_id** | **str**| ID of client to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_event**
> ResultSuccess delete_event(process_id, event_id)



This method deletes an event using the event ID and process ID

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
event_id = 'event_id_example' # str | ID of event to delete

try: 
    api_response = api_instance.delete_event(process_id, event_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_event: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **event_id** | **str**| ID of event to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_event_connector**
> ResultSuccess delete_event_connector(process_id, event_id, connector_id)



This method is intended for deleting a single Event connector based on Event ID, Process ID and Connector ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of of Process item
event_id = 'event_id_example' # str | ID of item to fetch
connector_id = 'connector_id_example' # str | ID of EventConnector to fetch

try: 
    api_response = api_instance.delete_event_connector(process_id, event_id, connector_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_event_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of of Process item | 
 **event_id** | **str**| ID of item to fetch | 
 **connector_id** | **str**| ID of EventConnector to fetch | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_flow**
> ResultSuccess delete_flow(process_id, flow_id)



This method deletes a sequence flow using the flow ID and process ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
flow_id = 'flow_id_example' # str | ID of flow to delete

try: 
    api_response = api_instance.delete_flow(process_id, flow_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_flow: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **flow_id** | **str**| ID of flow to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_gateway**
> ResultSuccess delete_gateway(process_id, gateway_id)



This method is deletes a single item using the gateway ID and process ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
gateway_id = 'gateway_id_example' # str | ID of Process to delete

try: 
    api_response = api_instance.delete_gateway(process_id, gateway_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_gateway: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **gateway_id** | **str**| ID of Process to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_group**
> ResultSuccess delete_group(id)



This method deletes a group using the group ID

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to delete

try: 
    api_response = api_instance.delete_group(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_input_output**
> ResultSuccess delete_input_output(process_id, task_id, inputoutput_uid)



This method deletes the Input/Output based on the Input/Output ID, process ID and task ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the Input/Output object
task_id = 'task_id_example' # str | Task instance ID related to Input/Output object
inputoutput_uid = 'inputoutput_uid_example' # str | Input/Output ID to fetch

try: 
    api_response = api_instance.delete_input_output(process_id, task_id, inputoutput_uid)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_input_output: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the Input/Output object | 
 **task_id** | **str**| Task instance ID related to Input/Output object | 
 **inputoutput_uid** | **str**| Input/Output ID to fetch | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_instance**
> ResultSuccess delete_instance(process_id, instance_id)



This method deletes an instance using the instance ID and process ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
instance_id = 'instance_id_example' # str | ID of instance to delete

try: 
    api_response = api_instance.delete_instance(process_id, instance_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_instance: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **instance_id** | **str**| ID of instance to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_process**
> ResultSuccess delete_process(id)



This method deletes a process using the process ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | Process ID to delete

try: 
    api_response = api_instance.delete_process(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_process: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| Process ID to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_task**
> ResultSuccess delete_task(process_id, task_id)



This method deletes a task using the task ID and process ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
task_id = 'task_id_example' # str | ID of task to delete

try: 
    api_response = api_instance.delete_task(process_id, task_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **task_id** | **str**| ID of task to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_task_connector**
> ResultSuccess delete_task_connector(process_id, task_id, connector_id)



This method is intended for deleting a single Task connector based on Task ID, Process ID and Connector ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process item to fetch
task_id = 'task_id_example' # str | ID of Task item to fetch
connector_id = 'connector_id_example' # str | ID of TaskConnector to fetch

try: 
    api_response = api_instance.delete_task_connector(process_id, task_id, connector_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_task_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process item to fetch | 
 **task_id** | **str**| ID of Task item to fetch | 
 **connector_id** | **str**| ID of TaskConnector to fetch | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_user**
> ResultSuccess delete_user(id)



This method deletes a user from the system.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of user to delete

try: 
    api_response = api_instance.delete_user(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->delete_user: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of user to delete | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **event_trigger**
> DataModelItem1 event_trigger(process_id, event_id, trigger_event_create_item)



This method starts/triggers an event.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the event
event_id = 'event_id_example' # str | ID of event to trigger
trigger_event_create_item = ProcessMaker_PMIO.TriggerEventCreateItem() # TriggerEventCreateItem | Json with some parameters

try: 
    api_response = api_instance.event_trigger(process_id, event_id, trigger_event_create_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->event_trigger: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the event | 
 **event_id** | **str**| ID of event to trigger | 
 **trigger_event_create_item** | [**TriggerEventCreateItem**](TriggerEventCreateItem.md)| Json with some parameters | 

### Return type

[**DataModelItem1**](DataModelItem1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_client_by_id**
> ClientItem find_client_by_id(user_id, client_id)



This method is retrieves an Oauth client based on its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_id = 'user_id_example' # str | ID of user to retrieve
client_id = 'client_id_example' # str | ID of client to retrieve

try: 
    api_response = api_instance.find_client_by_id(user_id, client_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_client_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| ID of user to retrieve | 
 **client_id** | **str**| ID of client to retrieve | 

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_clients**
> ClientCollection find_clients(user_id, pagefind_process_by_id=pagefind_process_by_id, per_page=per_page)



This method retrieves all existing clients belonging to an user.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_id = 'user_id_example' # str | User ID related to the clients
pagefind_process_by_id = 1 # int | Page numbers to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_clients(user_id, pagefind_process_by_id=pagefind_process_by_id, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_clients: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| User ID related to the clients | 
 **pagefind_process_by_id** | **int**| Page numbers to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**ClientCollection**](ClientCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_data_model**
> DataModelItem1 find_data_model(process_id, instance_id, page=page, per_page=per_page)



This method returns the instance DataModel and lets the user work with it directly

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
instance_id = 'instance_id_example' # str | ID of instance to return
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_data_model(process_id, instance_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_data_model: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **instance_id** | **str**| ID of instance to return | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**DataModelItem1**](DataModelItem1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_event_by_id**
> EventItem find_event_by_id(process_id, event_id)



This method retrieves an event using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
event_id = 'event_id_example' # str | ID of event to return

try: 
    api_response = api_instance.find_event_by_id(process_id, event_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_event_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **event_id** | **str**| ID of event to return | 

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_event_connector_by_id**
> EventConnector1 find_event_connector_by_id(process_id, event_id, connector_id)



This method returns all Event connectors related to the run Process and Event.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
event_id = 'event_id_example' # str | ID of Event to fetch
connector_id = 'connector_id_example' # str | ID of EventConnector to fetch

try: 
    api_response = api_instance.find_event_connector_by_id(process_id, event_id, connector_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_event_connector_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **event_id** | **str**| ID of Event to fetch | 
 **connector_id** | **str**| ID of EventConnector to fetch | 

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_event_connectors**
> EventConnectorsCollection find_event_connectors(process_id, event_id, page=page, per_page=per_page)



This method returns all Event connectors related to the run Process and Event.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
event_id = 'event_id_example' # str | ID of Task to fetch
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_event_connectors(process_id, event_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_event_connectors: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **event_id** | **str**| ID of Task to fetch | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**EventConnectorsCollection**](EventConnectorsCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_events**
> EventCollection find_events(process_id, page=page, per_page=per_page)



This method returns all events related to the runned process

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process related to the event
page = 1 # int | Page numbers to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_events(process_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_events: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process related to the event | 
 **page** | **int**| Page numbers to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**EventCollection**](EventCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_flow_by_id**
> FlowItem find_flow_by_id(process_id, flow_id)



This method retrieves a flow based on its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
flow_id = 'flow_id_example' # str | ID of flow to return

try: 
    api_response = api_instance.find_flow_by_id(process_id, flow_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_flow_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **flow_id** | **str**| ID of flow to return | 

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_flows**
> FlowCollection find_flows(process_id, page=page, per_page=per_page)



This method retrieves all existing flows.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process related to the flow
page = 1 # int | Page numbers to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_flows(process_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_flows: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process related to the flow | 
 **page** | **int**| Page numbers to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**FlowCollection**](FlowCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_gateway_by_id**
> GatewayItem find_gateway_by_id(process_id, gateway_id)



This method retrieves a gateway based on its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
gateway_id = 'gateway_id_example' # str | ID of gateway to return

try: 
    api_response = api_instance.find_gateway_by_id(process_id, gateway_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_gateway_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **gateway_id** | **str**| ID of gateway to return | 

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_gateways**
> GatewayCollection find_gateways(process_id, page=page, per_page=per_page)



This method retrieves all existing gateways.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process related to the gateway
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_gateways(process_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_gateways: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process related to the gateway | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**GatewayCollection**](GatewayCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_group_by_id**
> GroupItem find_group_by_id(id)



This method retrieves a group using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to return

try: 
    api_response = api_instance.find_group_by_id(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_group_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to return | 

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_groups**
> GroupCollection find_groups(page=page, per_page=per_page)



This method retrieves all existing groups.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_groups(page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_groups: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**GroupCollection**](GroupCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_input_output_by_id**
> InputOutputItem find_input_output_by_id(process_id, task_id, inputoutput_uid)



This method retrieves an Input/Output object using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the Input/Output object
task_id = 'task_id_example' # str | Task instance ID related to the Input/Output object
inputoutput_uid = 'inputoutput_uid_example' # str | ID of Input/Output to return

try: 
    api_response = api_instance.find_input_output_by_id(process_id, task_id, inputoutput_uid)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_input_output_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the Input/Output object | 
 **task_id** | **str**| Task instance ID related to the Input/Output object | 
 **inputoutput_uid** | **str**| ID of Input/Output to return | 

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_input_outputs**
> InputOutputCollection find_input_outputs(process_id, task_id, page=page, per_page=per_page)



This method retrieves all existing Input/Output objects in the related task instance.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to Input/Output object
task_id = 'task_id_example' # str | Task instance ID related to Input/Output object
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_input_outputs(process_id, task_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_input_outputs: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to Input/Output object | 
 **task_id** | **str**| Task instance ID related to Input/Output object | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**InputOutputCollection**](InputOutputCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_instance_by_id**
> InstanceItem find_instance_by_id(process_id, instance_id)



This method retrieves an instance using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
instance_id = 'instance_id_example' # str | ID of instance to return

try: 
    api_response = api_instance.find_instance_by_id(process_id, instance_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_instance_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **instance_id** | **str**| ID of instance to return | 

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_instances**
> InstanceCollection find_instances(process_id, page=page, per_page=per_page)



This method retrieves related to the process using  the Process ID

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the instances
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_instances(process_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_instances: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the instances | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**InstanceCollection**](InstanceCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_process_by_id**
> ProcessItem find_process_by_id(id)



This method retrieves a process using its ID

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of process to return

try: 
    api_response = api_instance.find_process_by_id(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_process_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of process to return | 

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_processes**
> ProcessCollection find_processes(page=page, per_page=per_page)



This method retrieves all existing processes.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_processes(page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_processes: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**ProcessCollection**](ProcessCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_task_by_id**
> TaskItem find_task_by_id(process_id, task_id)



This method is retrieves a task using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to return
task_id = 'task_id_example' # str | ID of task to return

try: 
    api_response = api_instance.find_task_by_id(process_id, task_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_task_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to return | 
 **task_id** | **str**| ID of task to return | 

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_task_connector_by_id**
> TaskConnector1 find_task_connector_by_id(process_id, task_id, connector_id)



This method is intended for retrieving an Task connector based on it's ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
task_id = 'task_id_example' # str | ID of Task to fetch
connector_id = 'connector_id_example' # str | ID of TaskConnector to fetch

try: 
    api_response = api_instance.find_task_connector_by_id(process_id, task_id, connector_id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_task_connector_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **task_id** | **str**| ID of Task to fetch | 
 **connector_id** | **str**| ID of TaskConnector to fetch | 

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_task_connectors**
> TaskConnectorsCollection find_task_connectors(process_id, task_id, page=page, per_page=per_page)



This method returns all Task connectors related to the run Process and Task.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
task_id = 'task_id_example' # str | ID of Task to fetch
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_task_connectors(process_id, task_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_task_connectors: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **task_id** | **str**| ID of Task to fetch | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**TaskConnectorsCollection**](TaskConnectorsCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_task_instance_by_id**
> InlineResponse200 find_task_instance_by_id(task_instance_id, page=page, per_page=per_page)



This method retrieves a task instance based on its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
task_instance_id = 'task_instance_id_example' # str | ID of task instance to return
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_task_instance_by_id(task_instance_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_task_instance_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **task_instance_id** | **str**| ID of task instance to return | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_task_instances**
> TaskInstanceCollection find_task_instances(page=page, per_page=per_page)



This method retrieves all existing task instances

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_task_instances(page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_task_instances: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**TaskInstanceCollection**](TaskInstanceCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_tasks**
> TaskCollection find_tasks(process_id, page=page, per_page=per_page)



This method is intended for returning a list of all Tasks related to the process

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process relative to task
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per Page (optional) (default to 15)

try: 
    api_response = api_instance.find_tasks(process_id, page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_tasks: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process relative to task | 
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per Page | [optional] [default to 15]

### Return type

[**TaskCollection**](TaskCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_user_by_id**
> UserItem find_user_by_id(id)



This method returns a user using its ID.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of the user to return

try: 
    api_response = api_instance.find_user_by_id(id)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_user_by_id: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of the user to return | 

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_users**
> UserCollection find_users(page=page, per_page=per_page)



This method returs all existing users in the system.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.find_users(page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->find_users: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**UserCollection**](UserCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **import_bpmn_file**
> ProcessCollection1 import_bpmn_file(bpmn_import_item)



This method imports BPMN files. A new process is created when import is successful.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
bpmn_import_item = ProcessMaker_PMIO.BpmnImportItem() # BpmnImportItem | JSON API with the BPMN file to import

try: 
    api_response = api_instance.import_bpmn_file(bpmn_import_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->import_bpmn_file: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bpmn_import_item** | [**BpmnImportItem**](BpmnImportItem.md)| JSON API with the BPMN file to import | 

### Return type

[**ProcessCollection1**](ProcessCollection1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **myself_user**
> UserItem myself_user(page=page, per_page=per_page)



This method returns user information using a token

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
page = 1 # int | Page number to fetch (optional) (default to 1)
per_page = 15 # int | Amount of items per page (optional) (default to 15)

try: 
    api_response = api_instance.myself_user(page=page, per_page=per_page)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->myself_user: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**| Page number to fetch | [optional] [default to 1]
 **per_page** | **int**| Amount of items per page | [optional] [default to 15]

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **remove_groups_from_task**
> ResultSuccess remove_groups_from_task(process_id, task_id, task_remove_groups_item)



This method removes groups from a task

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
task_id = 'task_id_example' # str | Task ID
task_remove_groups_item = ProcessMaker_PMIO.TaskRemoveGroupsItem() # TaskRemoveGroupsItem | JSON API response with Groups IDs to remove

try: 
    api_response = api_instance.remove_groups_from_task(process_id, task_id, task_remove_groups_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->remove_groups_from_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **task_id** | **str**| Task ID | 
 **task_remove_groups_item** | [**TaskRemoveGroupsItem**](TaskRemoveGroupsItem.md)| JSON API response with Groups IDs to remove | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **remove_users_from_group**
> ResultSuccess remove_users_from_group(id, group_remove_users_item)



This method removes one or more users from a group.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to be modified
group_remove_users_item = ProcessMaker_PMIO.GroupRemoveUsersItem() # GroupRemoveUsersItem | JSON API response with Users IDs to remove

try: 
    api_response = api_instance.remove_users_from_group(id, group_remove_users_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->remove_users_from_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to be modified | 
 **group_remove_users_item** | [**GroupRemoveUsersItem**](GroupRemoveUsersItem.md)| JSON API response with Users IDs to remove | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sync_groups_to_task**
> ResultSuccess sync_groups_to_task(process_id, task_id, task_sync_groups_item)



This method synchronizes a one or more groups with a task.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID
task_id = 'task_id_example' # str | ID of task to modify
task_sync_groups_item = ProcessMaker_PMIO.TaskSyncGroupsItem() # TaskSyncGroupsItem | JSON API response with groups IDs to sync

try: 
    api_response = api_instance.sync_groups_to_task(process_id, task_id, task_sync_groups_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->sync_groups_to_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID | 
 **task_id** | **str**| ID of task to modify | 
 **task_sync_groups_item** | [**TaskSyncGroupsItem**](TaskSyncGroupsItem.md)| JSON API response with groups IDs to sync | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sync_users_to_group**
> ResultSuccess sync_users_to_group(id, group_sync_users_item)



This method synchronizes one or more users with a group.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to be modifieded
group_sync_users_item = ProcessMaker_PMIO.GroupSyncUsersItem() # GroupSyncUsersItem | JSON API with array of users IDs to sync

try: 
    api_response = api_instance.sync_users_to_group(id, group_sync_users_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->sync_users_to_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to be modifieded | 
 **group_sync_users_item** | [**GroupSyncUsersItem**](GroupSyncUsersItem.md)| JSON API with array of users IDs to sync | 

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_client**
> ClientItem update_client(user_id, client_id, client_update_item)



This method updates an existing Oauth client.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
user_id = 'user_id_example' # str | ID of user to retrieve
client_id = 'client_id_example' # str | ID of client to retrieve
client_update_item = ProcessMaker_PMIO.ClientUpdateItem() # ClientUpdateItem | Client object to edit

try: 
    api_response = api_instance.update_client(user_id, client_id, client_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_client: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| ID of user to retrieve | 
 **client_id** | **str**| ID of client to retrieve | 
 **client_update_item** | [**ClientUpdateItem**](ClientUpdateItem.md)| Client object to edit | 

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_event**
> EventItem update_event(process_id, event_id, event_update_item)



This method updates an existing event

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to retrieve
event_id = 'event_id_example' # str | ID of event to retrieve
event_update_item = ProcessMaker_PMIO.EventUpdateItem() # EventUpdateItem | Event object to edit

try: 
    api_response = api_instance.update_event(process_id, event_id, event_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_event: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to retrieve | 
 **event_id** | **str**| ID of event to retrieve | 
 **event_update_item** | [**EventUpdateItem**](EventUpdateItem.md)| Event object to edit | 

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_event_connector**
> EventConnector1 update_event_connector(process_id, event_id, connector_id, event_connector_update_item)



This method lets update the existing Event connector with new parameters values

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
event_id = 'event_id_example' # str | ID of Event to fetch
connector_id = 'connector_id_example' # str | ID of Event Connector to fetch
event_connector_update_item = ProcessMaker_PMIO.EventConnectorUpdateItem() # EventConnectorUpdateItem | EventConnector object to edit

try: 
    api_response = api_instance.update_event_connector(process_id, event_id, connector_id, event_connector_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_event_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **event_id** | **str**| ID of Event to fetch | 
 **connector_id** | **str**| ID of Event Connector to fetch | 
 **event_connector_update_item** | [**EventConnectorUpdateItem**](EventConnectorUpdateItem.md)| EventConnector object to edit | 

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_flow**
> FlowItem update_flow(process_id, flow_id, flow_update_item)



This method updates an existing flow.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to retrieve
flow_id = 'flow_id_example' # str | ID of flow to retrieve
flow_update_item = ProcessMaker_PMIO.FlowUpdateItem() # FlowUpdateItem | Flow object to edit

try: 
    api_response = api_instance.update_flow(process_id, flow_id, flow_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_flow: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to retrieve | 
 **flow_id** | **str**| ID of flow to retrieve | 
 **flow_update_item** | [**FlowUpdateItem**](FlowUpdateItem.md)| Flow object to edit | 

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_gateway**
> GatewayItem update_gateway(process_id, gateway_id, gateway_update_item)



This method updates an existing gateway.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of process to retrieve
gateway_id = 'gateway_id_example' # str | ID of gateway to retrieve
gateway_update_item = ProcessMaker_PMIO.GatewayUpdateItem() # GatewayUpdateItem | Gateway object to edit

try: 
    api_response = api_instance.update_gateway(process_id, gateway_id, gateway_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_gateway: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of process to retrieve | 
 **gateway_id** | **str**| ID of gateway to retrieve | 
 **gateway_update_item** | [**GatewayUpdateItem**](GatewayUpdateItem.md)| Gateway object to edit | 

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_group**
> GroupItem update_group(id, group_update_item)



This method updates an existing group.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of group to retrieve
group_update_item = ProcessMaker_PMIO.GroupUpdateItem() # GroupUpdateItem | Group object to edit

try: 
    api_response = api_instance.update_group(id, group_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_group: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of group to retrieve | 
 **group_update_item** | [**GroupUpdateItem**](GroupUpdateItem.md)| Group object to edit | 

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_input_output**
> InputOutputItem update_input_output(process_id, task_id, inputoutput_uid, input_output_update_item)



This method updates an existing Input/Output object.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | Process ID related to the Input/Output object
task_id = 'task_id_example' # str | Task instance ID related to the Input/Output object
inputoutput_uid = 'inputoutput_uid_example' # str | ID of Input/Output to retrieve
input_output_update_item = ProcessMaker_PMIO.InputOutputUpdateItem() # InputOutputUpdateItem | Input/Output object to edit

try: 
    api_response = api_instance.update_input_output(process_id, task_id, inputoutput_uid, input_output_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_input_output: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| Process ID related to the Input/Output object | 
 **task_id** | **str**| Task instance ID related to the Input/Output object | 
 **inputoutput_uid** | **str**| ID of Input/Output to retrieve | 
 **input_output_update_item** | [**InputOutputUpdateItem**](InputOutputUpdateItem.md)| Input/Output object to edit | 

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_instance**
> InstanceItem update_instance(process_id, instance_id, instance_update_item)



This method updates  an existing instance.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to retrieve
instance_id = 'instance_id_example' # str | ID of Instance to retrieve
instance_update_item = ProcessMaker_PMIO.InstanceUpdateItem() # InstanceUpdateItem | Instance object to edit

try: 
    api_response = api_instance.update_instance(process_id, instance_id, instance_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_instance: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to retrieve | 
 **instance_id** | **str**| ID of Instance to retrieve | 
 **instance_update_item** | [**InstanceUpdateItem**](InstanceUpdateItem.md)| Instance object to edit | 

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_process**
> ProcessItem update_process(id, process_update_item)



This method updates an existing process.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of process to retrieve
process_update_item = ProcessMaker_PMIO.ProcessUpdateItem() # ProcessUpdateItem | Process object to edit

try: 
    api_response = api_instance.update_process(id, process_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_process: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of process to retrieve | 
 **process_update_item** | [**ProcessUpdateItem**](ProcessUpdateItem.md)| Process object to edit | 

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_task**
> TaskItem update_task(process_id, task_id, task_update_item)



This method is intended for updating an existing task.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
task_id = 'task_id_example' # str | ID of Task to fetch
task_update_item = ProcessMaker_PMIO.TaskUpdateItem() # TaskUpdateItem | Task object to edit

try: 
    api_response = api_instance.update_task(process_id, task_id, task_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_task: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **task_id** | **str**| ID of Task to fetch | 
 **task_update_item** | [**TaskUpdateItem**](TaskUpdateItem.md)| Task object to edit | 

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_task_connector**
> TaskConnector1 update_task_connector(process_id, task_id, connector_id, task_connector_update_item)



This method lets update the existing Task connector with new parameters values

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
process_id = 'process_id_example' # str | ID of Process to fetch
task_id = 'task_id_example' # str | ID of Task to fetch
connector_id = 'connector_id_example' # str | ID of Task Connector to fetch
task_connector_update_item = ProcessMaker_PMIO.TaskConnectorUpdateItem() # TaskConnectorUpdateItem | TaskConnector object to edit

try: 
    api_response = api_instance.update_task_connector(process_id, task_id, connector_id, task_connector_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_task_connector: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **process_id** | **str**| ID of Process to fetch | 
 **task_id** | **str**| ID of Task to fetch | 
 **connector_id** | **str**| ID of Task Connector to fetch | 
 **task_connector_update_item** | [**TaskConnectorUpdateItem**](TaskConnectorUpdateItem.md)| TaskConnector object to edit | 

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_task_instance**
> InlineResponse200 update_task_instance(task_instance_id, task_instance_update_item)



This method updates an existing task instance.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
task_instance_id = 'task_instance_id_example' # str | ID of task instance to retrieve
task_instance_update_item = ProcessMaker_PMIO.TaskInstanceUpdateItem() # TaskInstanceUpdateItem | Task Instance object to update

try: 
    api_response = api_instance.update_task_instance(task_instance_id, task_instance_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_task_instance: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **task_instance_id** | **str**| ID of task instance to retrieve | 
 **task_instance_update_item** | [**TaskInstanceUpdateItem**](TaskInstanceUpdateItem.md)| Task Instance object to update | 

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_user**
> UserItem update_user(id, user_update_item)



This method updates an existing user.

### Example 
```python
from __future__ import print_statement
import time
import ProcessMaker_PMIO
from ProcessMaker_PMIO.rest import ApiException
from pprint import pprint

# Configure OAuth2 access token for authorization: PasswordGrant
ProcessMaker_PMIO.configuration.access_token = 'YOUR_ACCESS_TOKEN'

# create an instance of the API class
api_instance = ProcessMaker_PMIO.ProcessmakerApi()
id = 'id_example' # str | ID of user to retrieve
user_update_item = ProcessMaker_PMIO.UserUpdateItem() # UserUpdateItem | User object for update

try: 
    api_response = api_instance.update_user(id, user_update_item)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProcessmakerApi->update_user: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| ID of user to retrieve | 
 **user_update_item** | [**UserUpdateItem**](UserUpdateItem.md)| User object for update | 

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

