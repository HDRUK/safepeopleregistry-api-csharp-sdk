# SafePeopleRegistryApiSdk.Api.NotificationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**NotificationsGetNotificationCounts**](NotificationsApi.md#notificationsgetnotificationcounts) | **GET** /api/v1/users/{id}/notifications/count | Get notification counts for a specific user |
| [**NotificationsGetUserNotifications**](NotificationsApi.md#notificationsgetusernotifications) | **GET** /api/v1/users/{id}/notifications | Get notifications for a specific user |
| [**NotificationsMarkUserNotificationAsRead**](NotificationsApi.md#notificationsmarkusernotificationasread) | **PATCH** /api/v1/users/{id}/notifications/{notificationId}/read | Mark a specific notification as read |
| [**NotificationsMarkUserNotificationAsUnread**](NotificationsApi.md#notificationsmarkusernotificationasunread) | **PATCH** /api/v1/users/{id}/notifications/{notificationId}/unread | Mark a specific notification as unread |
| [**NotificationsMarkUserNotificationsAsRead**](NotificationsApi.md#notificationsmarkusernotificationsasread) | **PATCH** /api/v1/users/{id}/notifications/read | Mark all notifications as read for a specific user |

<a id="notificationsgetnotificationcounts"></a>
# **NotificationsGetNotificationCounts**
> NotificationsGetNotificationCounts200Response NotificationsGetNotificationCounts (int id)

Get notification counts for a specific user

Retrieve the total, read, and unread notification counts for a given user.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |

### Return type

[**NotificationsGetNotificationCounts200Response**](NotificationsGetNotificationCounts200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |
| **401** | Unauthorized |  -  |
| **404** | User not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="notificationsgetusernotifications"></a>
# **NotificationsGetUserNotifications**
> NotificationsGetUserNotifications200Response NotificationsGetUserNotifications (int id, string status = null)

Get notifications for a specific user

Retrieves notifications for a user, with an optional filter for read/unread notifications.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |
| **status** | **string** | Filter notifications by status (read/unread) | [optional]  |

### Return type

[**NotificationsGetUserNotifications200Response**](NotificationsGetUserNotifications200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response |  -  |
| **404** | User not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="notificationsmarkusernotificationasread"></a>
# **NotificationsMarkUserNotificationAsRead**
> NotificationsMarkUserNotificationAsRead200Response NotificationsMarkUserNotificationAsRead (int id, string notificationId)

Mark a specific notification as read


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |
| **notificationId** | **string** | Notification ID |  |

### Return type

[**NotificationsMarkUserNotificationAsRead200Response**](NotificationsMarkUserNotificationAsRead200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Notification marked as read |  -  |
| **404** | User or notification not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="notificationsmarkusernotificationasunread"></a>
# **NotificationsMarkUserNotificationAsUnread**
> void NotificationsMarkUserNotificationAsUnread (int id, string notificationId)

Mark a specific notification as unread


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |
| **notificationId** | **string** | Notification ID |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Notification marked as unread |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="notificationsmarkusernotificationsasread"></a>
# **NotificationsMarkUserNotificationsAsRead**
> NotificationsMarkUserNotificationsAsRead200Response NotificationsMarkUserNotificationsAsRead (int id)

Mark all notifications as read for a specific user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |

### Return type

[**NotificationsMarkUserNotificationsAsRead200Response**](NotificationsMarkUserNotificationsAsRead200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Notifications marked as read |  -  |
| **404** | User not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

