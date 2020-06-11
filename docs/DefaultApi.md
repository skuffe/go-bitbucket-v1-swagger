# {{classname}}

All URIs are relative to *http://example.com/rest/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddGroupToUser**](DefaultApi.md#AddGroupToUser) | **Post** /api/1.0/admin/users/add-group | addGroupToUser
[**AddLabel**](DefaultApi.md#AddLabel) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/labels | addLabel
[**AddUserToGroup**](DefaultApi.md#AddUserToGroup) | **Post** /api/1.0/admin/groups/add-user | addUserToGroup
[**AddUserToGroups**](DefaultApi.md#AddUserToGroups) | **Post** /api/1.0/admin/users/add-groups | addUserToGroups
[**AddUsersToGroup**](DefaultApi.md#AddUsersToGroup) | **Post** /api/1.0/admin/groups/add-users | addUsersToGroup
[**Approve**](DefaultApi.md#Approve) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/approve | approve
[**AssignParticipantRole**](DefaultApi.md#AssignParticipantRole) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | assignParticipantRole
[**CanMerge**](DefaultApi.md#CanMerge) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/merge | canMerge
[**CancelExportJob**](DefaultApi.md#CancelExportJob) | **Post** /api/1.0/migration/exports/{jobId}/cancel | cancelExportJob
[**CancelImportJob**](DefaultApi.md#CancelImportJob) | **Post** /api/1.0/migration/imports/{jobId}/cancel | cancelImportJob
[**ClearSenderAddress**](DefaultApi.md#ClearSenderAddress) | **Delete** /api/1.0/admin/mail-server/sender-address | clearSenderAddress
[**ClearUserCaptchaChallenge**](DefaultApi.md#ClearUserCaptchaChallenge) | **Delete** /api/1.0/admin/users/captcha | clearUserCaptchaChallenge
[**CountPullRequestTasks**](DefaultApi.md#CountPullRequestTasks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/tasks/count | countPullRequestTasks
[**Create**](DefaultApi.md#Create) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests | create
[**CreateBranch**](DefaultApi.md#CreateBranch) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches | createBranch
[**CreateComment**](DefaultApi.md#CreateComment) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments | createComment
[**CreateGroup**](DefaultApi.md#CreateGroup) | **Post** /api/1.0/admin/groups | createGroup
[**CreateProject**](DefaultApi.md#CreateProject) | **Post** /api/1.0/projects | createProject
[**CreateRepository**](DefaultApi.md#CreateRepository) | **Post** /api/1.0/projects/{projectKey}/repos | createRepository
[**CreateTag**](DefaultApi.md#CreateTag) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags | createTag
[**CreateTask**](DefaultApi.md#CreateTask) | **Post** /api/1.0/tasks | createTask
[**CreateUser**](DefaultApi.md#CreateUser) | **Post** /api/1.0/admin/users | createUser
[**CreateWebhook**](DefaultApi.md#CreateWebhook) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks | createWebhook
[**Decline**](DefaultApi.md#Decline) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/decline | decline
[**Delete**](DefaultApi.md#Delete) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | delete
[**DeleteAvatar**](DefaultApi.md#DeleteAvatar) | **Delete** /api/1.0/users/{userSlug}/avatar.png | deleteAvatar
[**DeleteComment**](DefaultApi.md#DeleteComment) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | deleteComment
[**DeleteGroup**](DefaultApi.md#DeleteGroup) | **Delete** /api/1.0/admin/groups | deleteGroup
[**DeleteMailConfig**](DefaultApi.md#DeleteMailConfig) | **Delete** /api/1.0/admin/mail-server | deleteMailConfig
[**DeleteProject**](DefaultApi.md#DeleteProject) | **Delete** /api/1.0/projects/{projectKey} | deleteProject
[**DeleteRepository**](DefaultApi.md#DeleteRepository) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | deleteRepository
[**DeleteRepositoryHook**](DefaultApi.md#DeleteRepositoryHook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey} | deleteRepositoryHook
[**DeleteTask**](DefaultApi.md#DeleteTask) | **Delete** /api/1.0/tasks/{taskId} | deleteTask
[**DeleteUser**](DefaultApi.md#DeleteUser) | **Delete** /api/1.0/admin/users | deleteUser
[**DeleteWebhook**](DefaultApi.md#DeleteWebhook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | deleteWebhook
[**DeletedeleteComment**](DefaultApi.md#DeletedeleteComment) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | deleteComment
[**DeletedisableHook**](DefaultApi.md#DeletedisableHook) | **Delete** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/enabled | disableHook
[**DeleterevokePermissionsForGroup**](DefaultApi.md#DeleterevokePermissionsForGroup) | **Delete** /api/1.0/projects/{projectKey}/permissions/groups | revokePermissionsForGroup
[**DeleterevokePermissionsForGroup1**](DefaultApi.md#DeleterevokePermissionsForGroup1) | **Delete** /api/1.0/admin/permissions/groups | revokePermissionsForGroup
[**DeleterevokePermissionsForUser**](DefaultApi.md#DeleterevokePermissionsForUser) | **Delete** /api/1.0/projects/{projectKey}/permissions/users | revokePermissionsForUser
[**DeleterevokePermissionsForUser1**](DefaultApi.md#DeleterevokePermissionsForUser1) | **Delete** /api/1.0/admin/permissions/users | revokePermissionsForUser
[**DeleteunassignParticipantRole**](DefaultApi.md#DeleteunassignParticipantRole) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} | unassignParticipantRole
[**Deleteunwatch**](DefaultApi.md#Deleteunwatch) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/watch | unwatch
[**Deleteunwatch1**](DefaultApi.md#Deleteunwatch1) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/watch | unwatch
[**DisableHook**](DefaultApi.md#DisableHook) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/enabled | disableHook
[**EditFile**](DefaultApi.md#EditFile) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse/{path:.*} | editFile
[**EnableHook**](DefaultApi.md#EnableHook) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/enabled | enableHook
[**EraseUser**](DefaultApi.md#EraseUser) | **Post** /api/1.0/admin/users/erasure | eraseUser
[**FindContributing**](DefaultApi.md#FindContributing) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/contributing | findContributing
[**FindGroupsForUser**](DefaultApi.md#FindGroupsForUser) | **Get** /api/1.0/admin/users/more-members | findGroupsForUser
[**FindLicense**](DefaultApi.md#FindLicense) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/license | findLicense
[**FindOtherGroupsForUser**](DefaultApi.md#FindOtherGroupsForUser) | **Get** /api/1.0/admin/users/more-non-members | findOtherGroupsForUser
[**FindReadme**](DefaultApi.md#FindReadme) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/readme | findReadme
[**FindUsersInGroup**](DefaultApi.md#FindUsersInGroup) | **Get** /api/1.0/admin/groups/more-members | findUsersInGroup
[**FindUsersNotInGroup**](DefaultApi.md#FindUsersNotInGroup) | **Get** /api/1.0/admin/groups/more-non-members | findUsersNotInGroup
[**FindWebhooks**](DefaultApi.md#FindWebhooks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks | findWebhooks
[**ForkRepository**](DefaultApi.md#ForkRepository) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | forkRepository
[**Get**](DefaultApi.md#Get) | **Get** /api/1.0/admin/license | get
[**GetActivities**](DefaultApi.md#GetActivities) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/activities | getActivities
[**GetAllLabelsForRepository**](DefaultApi.md#GetAllLabelsForRepository) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/labels | getAllLabelsForRepository
[**GetApplicationProperties**](DefaultApi.md#GetApplicationProperties) | **Get** /api/1.0/application-properties | getApplicationProperties
[**GetArchive**](DefaultApi.md#GetArchive) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/archive | getArchive
[**GetAvatar**](DefaultApi.md#GetAvatar) | **Get** /api/1.0/hooks/{hookKey}/avatar | getAvatar
[**GetBranches**](DefaultApi.md#GetBranches) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches | getBranches
[**GetChanges**](DefaultApi.md#GetChanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/changes | getChanges
[**GetComment**](DefaultApi.md#GetComment) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | getComment
[**GetComments**](DefaultApi.md#GetComments) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments | getComments
[**GetCommit**](DefaultApi.md#GetCommit) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId} | getCommit
[**GetCommits**](DefaultApi.md#GetCommits) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/commits | getCommits
[**GetContent**](DefaultApi.md#GetContent) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse | getContent
[**GetDefaultBranch**](DefaultApi.md#GetDefaultBranch) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches/default | getDefaultBranch
[**GetExportJob**](DefaultApi.md#GetExportJob) | **Get** /api/1.0/migration/exports/{jobId} | getExportJob
[**GetExportJobMessages**](DefaultApi.md#GetExportJobMessages) | **Get** /api/1.0/migration/exports/{jobId}/messages | getExportJobMessages
[**GetForkedRepositories**](DefaultApi.md#GetForkedRepositories) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/forks | getForkedRepositories
[**GetGroups**](DefaultApi.md#GetGroups) | **Get** /api/1.0/admin/groups | getGroups
[**GetGroups1**](DefaultApi.md#GetGroups1) | **Get** /api/1.0/groups | getGroups1
[**GetGroupsWithAnyPermission**](DefaultApi.md#GetGroupsWithAnyPermission) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | getGroupsWithAnyPermission
[**GetGroupsWithoutAnyPermission**](DefaultApi.md#GetGroupsWithoutAnyPermission) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups/none | getGroupsWithoutAnyPermission
[**GetImportJob**](DefaultApi.md#GetImportJob) | **Get** /api/1.0/migration/imports/{jobId} | getImportJob
[**GetImportJobMessages**](DefaultApi.md#GetImportJobMessages) | **Get** /api/1.0/migration/imports/{jobId}/messages | getImportJobMessages
[**GetInformation**](DefaultApi.md#GetInformation) | **Get** /api/1.0/admin/cluster | getInformation
[**GetLabel**](DefaultApi.md#GetLabel) | **Get** /api/1.0/labels/{labelName} | getLabel
[**GetLabelables**](DefaultApi.md#GetLabelables) | **Get** /api/1.0/labels/{labelName}/labeled | getLabelables
[**GetLabels**](DefaultApi.md#GetLabels) | **Get** /api/1.0/labels | getLabels
[**GetLatestInvocation**](DefaultApi.md#GetLatestInvocation) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/latest | getLatestInvocation
[**GetLevel**](DefaultApi.md#GetLevel) | **Get** /api/1.0/logs/logger/{loggerName} | getLevel
[**GetMailConfig**](DefaultApi.md#GetMailConfig) | **Get** /api/1.0/admin/mail-server | getMailConfig
[**GetMergeConfig**](DefaultApi.md#GetMergeConfig) | **Get** /api/1.0/admin/pull-requests/{scmId} | getMergeConfig
[**GetPage**](DefaultApi.md#GetPage) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests | getPage
[**GetProject**](DefaultApi.md#GetProject) | **Get** /api/1.0/projects/{projectKey} | getProject
[**GetProjectAvatar**](DefaultApi.md#GetProjectAvatar) | **Get** /api/1.0/projects/{projectKey}/avatar.png | getProjectAvatar
[**GetProjects**](DefaultApi.md#GetProjects) | **Get** /api/1.0/projects | getProjects
[**GetPullRequestCount**](DefaultApi.md#GetPullRequestCount) | **Get** /api/1.0/inbox/pull-requests/count | getPullRequestCount
[**GetPullRequestSettings**](DefaultApi.md#GetPullRequestSettings) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/pull-requests | getPullRequestSettings
[**GetPullRequestSuggestions**](DefaultApi.md#GetPullRequestSuggestions) | **Get** /api/1.0/dashboard/pull-request-suggestions | getPullRequestSuggestions
[**GetPullRequestTasks**](DefaultApi.md#GetPullRequestTasks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/tasks | getPullRequestTasks
[**GetPullRequests**](DefaultApi.md#GetPullRequests) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/pull-requests | getPullRequests
[**GetRelatedRepositories**](DefaultApi.md#GetRelatedRepositories) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/related | getRelatedRepositories
[**GetRepositories**](DefaultApi.md#GetRepositories) | **Get** /api/1.0/repos | getRepositories
[**GetRepositoriesRecentlyAccessed**](DefaultApi.md#GetRepositoriesRecentlyAccessed) | **Get** /api/1.0/profile/recent/repos | getRepositoriesRecentlyAccessed
[**GetRepository**](DefaultApi.md#GetRepository) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | getRepository
[**GetRepositoryHook**](DefaultApi.md#GetRepositoryHook) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey} | getRepositoryHook
[**GetRepositoryHooks**](DefaultApi.md#GetRepositoryHooks) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks | getRepositoryHooks
[**GetRootLevel**](DefaultApi.md#GetRootLevel) | **Get** /api/1.0/logs/rootLogger | getRootLevel
[**GetSenderAddress**](DefaultApi.md#GetSenderAddress) | **Get** /api/1.0/admin/mail-server/sender-address | getSenderAddress
[**GetSettings**](DefaultApi.md#GetSettings) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/settings | getSettings
[**GetStatistics**](DefaultApi.md#GetStatistics) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/statistics | getStatistics
[**GetStatisticsSummary**](DefaultApi.md#GetStatisticsSummary) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId}/statistics/summary | getStatisticsSummary
[**GetTag**](DefaultApi.md#GetTag) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags/{name:.*} | getTag
[**GetTags**](DefaultApi.md#GetTags) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/tags | getTags
[**GetTask**](DefaultApi.md#GetTask) | **Get** /api/1.0/tasks/{taskId} | getTask
[**GetUser**](DefaultApi.md#GetUser) | **Get** /api/1.0/users/{userSlug} | getUser
[**GetUserSettings**](DefaultApi.md#GetUserSettings) | **Get** /api/1.0/users/{userSlug}/settings | getUserSettings
[**GetUsers**](DefaultApi.md#GetUsers) | **Get** /api/1.0/admin/users | getUsers
[**GetUsersWithAnyPermission**](DefaultApi.md#GetUsersWithAnyPermission) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | getUsersWithAnyPermission
[**GetUsersWithoutAnyPermission**](DefaultApi.md#GetUsersWithoutAnyPermission) | **Get** /api/1.0/admin/permissions/users/none | getUsersWithoutAnyPermission
[**GetUsersWithoutPermission**](DefaultApi.md#GetUsersWithoutPermission) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users/none | getUsersWithoutPermission
[**GetWebhook**](DefaultApi.md#GetWebhook) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | getWebhook
[**Getget**](DefaultApi.md#Getget) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | get
[**GetgetChanges**](DefaultApi.md#GetgetChanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/changes | getChanges
[**GetgetComment**](DefaultApi.md#GetgetComment) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | getComment
[**GetgetComments**](DefaultApi.md#GetgetComments) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments | getComments
[**GetgetCommits**](DefaultApi.md#GetgetCommits) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits | getCommits
[**GetgetContent**](DefaultApi.md#GetgetContent) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/browse/{path:.*} | getContent
[**GetgetGroupsWithAnyPermission**](DefaultApi.md#GetgetGroupsWithAnyPermission) | **Get** /api/1.0/projects/{projectKey}/permissions/groups | getGroupsWithAnyPermission
[**GetgetGroupsWithAnyPermission1**](DefaultApi.md#GetgetGroupsWithAnyPermission1) | **Get** /api/1.0/admin/permissions/groups | getGroupsWithAnyPermission
[**GetgetGroupsWithoutAnyPermission**](DefaultApi.md#GetgetGroupsWithoutAnyPermission) | **Get** /api/1.0/projects/{projectKey}/permissions/groups/none | getGroupsWithoutAnyPermission
[**GetgetGroupsWithoutAnyPermission1**](DefaultApi.md#GetgetGroupsWithoutAnyPermission1) | **Get** /api/1.0/admin/permissions/groups/none | getGroupsWithoutAnyPermission
[**GetgetPullRequestSettings**](DefaultApi.md#GetgetPullRequestSettings) | **Get** /api/1.0/projects/{projectKey}/settings/pull-requests/{scmId} | getPullRequestSettings
[**GetgetPullRequests**](DefaultApi.md#GetgetPullRequests) | **Get** /api/1.0/inbox/pull-requests | getPullRequests
[**GetgetPullRequests1**](DefaultApi.md#GetgetPullRequests1) | **Get** /api/1.0/dashboard/pull-requests | getPullRequests
[**GetgetRepositories**](DefaultApi.md#GetgetRepositories) | **Get** /api/1.0/projects/{projectKey}/repos | getRepositories
[**GetgetRepositoryHook**](DefaultApi.md#GetgetRepositoryHook) | **Get** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey} | getRepositoryHook
[**GetgetRepositoryHooks**](DefaultApi.md#GetgetRepositoryHooks) | **Get** /api/1.0/projects/{projectKey}/settings/hooks | getRepositoryHooks
[**GetgetSettings**](DefaultApi.md#GetgetSettings) | **Get** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/settings | getSettings
[**GetgetUsers**](DefaultApi.md#GetgetUsers) | **Get** /api/1.0/users | getUsers
[**GetgetUsersWithAnyPermission**](DefaultApi.md#GetgetUsersWithAnyPermission) | **Get** /api/1.0/projects/{projectKey}/permissions/users | getUsersWithAnyPermission
[**GetgetUsersWithAnyPermission1**](DefaultApi.md#GetgetUsersWithAnyPermission1) | **Get** /api/1.0/admin/permissions/users | getUsersWithAnyPermission
[**GetgetUsersWithoutPermission**](DefaultApi.md#GetgetUsersWithoutPermission) | **Get** /api/1.0/projects/{projectKey}/permissions/users/none | getUsersWithoutPermission
[**Getstream**](DefaultApi.md#Getstream) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/last-modified/{path:.*} | stream
[**GetstreamChanges**](DefaultApi.md#GetstreamChanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/changes | streamChanges
[**GetstreamDiff**](DefaultApi.md#GetstreamDiff) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/diff | streamDiff
[**GetstreamDiff1**](DefaultApi.md#GetstreamDiff1) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/diff/{path:.*} | streamDiff
[**GetstreamDiff12**](DefaultApi.md#GetstreamDiff12) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/diff | streamDiff
[**GetstreamDiff123**](DefaultApi.md#GetstreamDiff123) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/diff/{path:.*} | streamDiff
[**GetstreamDiff1234**](DefaultApi.md#GetstreamDiff1234) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/diff | streamDiff
[**GetstreamDiff12345**](DefaultApi.md#GetstreamDiff12345) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/diff/{path:.*} | streamDiff
[**GetstreamFiles**](DefaultApi.md#GetstreamFiles) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/files/{path:.*} | streamFiles
[**GetstreamRaw**](DefaultApi.md#GetstreamRaw) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/raw/{path:.*} | streamRaw
[**HasAllUserPermission**](DefaultApi.md#HasAllUserPermission) | **Get** /api/1.0/projects/{projectKey}/permissions/{permission}/all | hasAllUserPermission
[**ListParticipants**](DefaultApi.md#ListParticipants) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | listParticipants
[**Merge**](DefaultApi.md#Merge) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/merge | merge
[**ModifyAllUserPermission**](DefaultApi.md#ModifyAllUserPermission) | **Post** /api/1.0/projects/{projectKey}/permissions/{permission}/all | modifyAllUserPermission
[**PostcreateComment**](DefaultApi.md#PostcreateComment) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments | createComment
[**PostupdatePullRequestSettings**](DefaultApi.md#PostupdatePullRequestSettings) | **Post** /api/1.0/projects/{projectKey}/settings/pull-requests/{scmId} | updatePullRequestSettings
[**PostuploadAvatar**](DefaultApi.md#PostuploadAvatar) | **Post** /api/1.0/users/{userSlug}/avatar.png | uploadAvatar
[**Postwatch**](DefaultApi.md#Postwatch) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/watch | watch
[**Postwatch1**](DefaultApi.md#Postwatch1) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/watch | watch
[**Preview**](DefaultApi.md#Preview) | **Post** /api/1.0/markup/preview | preview
[**PreviewExport**](DefaultApi.md#PreviewExport) | **Post** /api/1.0/migration/exports/preview | previewExport
[**PutenableHook**](DefaultApi.md#PutenableHook) | **Put** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/enabled | enableHook
[**PutsetPermissionForGroups**](DefaultApi.md#PutsetPermissionForGroups) | **Put** /api/1.0/admin/permissions/groups | setPermissionForGroups
[**PutsetPermissionForUsers**](DefaultApi.md#PutsetPermissionForUsers) | **Put** /api/1.0/admin/permissions/users | setPermissionForUsers
[**PutsetSettings**](DefaultApi.md#PutsetSettings) | **Put** /api/1.0/projects/{projectKey}/settings/hooks/{hookKey}/settings | setSettings
[**Putupdate**](DefaultApi.md#Putupdate) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId} | update
[**PutupdateComment**](DefaultApi.md#PutupdateComment) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/comments/{commentId} | updateComment
[**RemoveGroupFromUser**](DefaultApi.md#RemoveGroupFromUser) | **Post** /api/1.0/admin/users/remove-group | removeGroupFromUser
[**RemoveLabel**](DefaultApi.md#RemoveLabel) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/labels/{labelName} | removeLabel
[**RemoveUserFromGroup**](DefaultApi.md#RemoveUserFromGroup) | **Post** /api/1.0/admin/groups/remove-user | removeUserFromGroup
[**RenameUser**](DefaultApi.md#RenameUser) | **Post** /api/1.0/admin/users/rename | renameUser
[**Reopen**](DefaultApi.md#Reopen) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/reopen | reopen
[**RetryCreateRepository**](DefaultApi.md#RetryCreateRepository) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/recreate | retryCreateRepository
[**RevokePermissionsForGroup**](DefaultApi.md#RevokePermissionsForGroup) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | revokePermissionsForGroup
[**RevokePermissionsForUser**](DefaultApi.md#RevokePermissionsForUser) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | revokePermissionsForUser
[**Search**](DefaultApi.md#Search) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/participants | search
[**SetDefaultBranch**](DefaultApi.md#SetDefaultBranch) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/branches/default | setDefaultBranch
[**SetLevel**](DefaultApi.md#SetLevel) | **Put** /api/1.0/logs/logger/{loggerName}/{levelName} | setLevel
[**SetMailConfig**](DefaultApi.md#SetMailConfig) | **Put** /api/1.0/admin/mail-server | setMailConfig
[**SetMergeConfig**](DefaultApi.md#SetMergeConfig) | **Post** /api/1.0/admin/pull-requests/{scmId} | setMergeConfig
[**SetPermissionForGroup**](DefaultApi.md#SetPermissionForGroup) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/groups | setPermissionForGroup
[**SetPermissionForGroups**](DefaultApi.md#SetPermissionForGroups) | **Put** /api/1.0/projects/{projectKey}/permissions/groups | setPermissionForGroups
[**SetPermissionForUser**](DefaultApi.md#SetPermissionForUser) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/permissions/users | setPermissionForUser
[**SetPermissionForUsers**](DefaultApi.md#SetPermissionForUsers) | **Put** /api/1.0/projects/{projectKey}/permissions/users | setPermissionForUsers
[**SetRootLevel**](DefaultApi.md#SetRootLevel) | **Put** /api/1.0/logs/rootLogger/{levelName} | setRootLevel
[**SetSenderAddress**](DefaultApi.md#SetSenderAddress) | **Put** /api/1.0/admin/mail-server/sender-address | setSenderAddress
[**SetSettings**](DefaultApi.md#SetSettings) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/hooks/{hookKey}/settings | setSettings
[**StartExport**](DefaultApi.md#StartExport) | **Post** /api/1.0/migration/exports | startExport
[**StartImport**](DefaultApi.md#StartImport) | **Post** /api/1.0/migration/imports | startImport
[**Stream**](DefaultApi.md#Stream) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/last-modified | stream
[**StreamChanges**](DefaultApi.md#StreamChanges) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/changes | streamChanges
[**StreamCommits**](DefaultApi.md#StreamCommits) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/commits | streamCommits
[**StreamDiff**](DefaultApi.md#StreamDiff) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/compare/diff{path:.*} | streamDiff
[**StreamFiles**](DefaultApi.md#StreamFiles) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/files | streamFiles
[**StreamRaw**](DefaultApi.md#StreamRaw) | **Get** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/raw | streamRaw
[**TestWebhook**](DefaultApi.md#TestWebhook) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/test | testWebhook
[**UnassignParticipantRole**](DefaultApi.md#UnassignParticipantRole) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants | unassignParticipantRole
[**Unwatch**](DefaultApi.md#Unwatch) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/watch | unwatch
[**Update**](DefaultApi.md#Update) | **Post** /api/1.0/admin/license | update
[**UpdateComment**](DefaultApi.md#UpdateComment) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/comments/{commentId} | updateComment
[**UpdateProject**](DefaultApi.md#UpdateProject) | **Put** /api/1.0/projects/{projectKey} | updateProject
[**UpdatePullRequestSettings**](DefaultApi.md#UpdatePullRequestSettings) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/settings/pull-requests | updatePullRequestSettings
[**UpdateRepository**](DefaultApi.md#UpdateRepository) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug} | updateRepository
[**UpdateSettings**](DefaultApi.md#UpdateSettings) | **Post** /api/1.0/users/{userSlug}/settings | updateSettings
[**UpdateStatus**](DefaultApi.md#UpdateStatus) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} | updateStatus
[**UpdateTask**](DefaultApi.md#UpdateTask) | **Put** /api/1.0/tasks/{taskId} | updateTask
[**UpdateUserDetails**](DefaultApi.md#UpdateUserDetails) | **Put** /api/1.0/admin/users | updateUserDetails
[**UpdateUserDetails1**](DefaultApi.md#UpdateUserDetails1) | **Put** /api/1.0/users | updateUserDetails1
[**UpdateUserPassword**](DefaultApi.md#UpdateUserPassword) | **Put** /api/1.0/admin/users/credentials | updateUserPassword
[**UpdateUserPassword1**](DefaultApi.md#UpdateUserPassword1) | **Put** /api/1.0/users/credentials | updateUserPassword1
[**UpdateWebhook**](DefaultApi.md#UpdateWebhook) | **Put** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/webhooks/{webhookId} | updateWebhook
[**UploadAvatar**](DefaultApi.md#UploadAvatar) | **Post** /api/1.0/projects/{projectKey}/avatar.png | uploadAvatar
[**ValidateErasable**](DefaultApi.md#ValidateErasable) | **Get** /api/1.0/admin/users/erasure | validateErasable
[**Watch**](DefaultApi.md#Watch) | **Post** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/commits/{commitId}/watch | watch
[**WithdrawApproval**](DefaultApi.md#WithdrawApproval) | **Delete** /api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/approve | withdrawApproval

# **AddGroupToUser**
> string AddGroupToUser(ctx, body)
addGroupToUser

<strong>Deprecated since 2.10</strong>. Use /rest/users/add-groups instead.  <p>  Add a user to a group. This is very similar to <code>groups/add-user</code>, but with the <em>context</em> and  <em>itemName</em> attributes of the supplied request entity reversed. On the face of it this may appear  redundant, but it facilitates a specific UI component in Stash.  <p>  In the request entity, the <em>context</em> attribute is the user and the <em>itemName</em> is the group.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AddGroupToUserRequest**](AddGroupToUserRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AddLabel**
> string AddLabel(ctx, body, projectKey, repositorySlug)
addLabel

Applies a label to the repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AddLabelRequest**](AddLabelRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AddUserToGroup**
> string AddUserToGroup(ctx, body)
addUserToGroup

<strong>Deprecated since 2.10</strong>. Use /rest/users/add-groups instead.  <p>  Add a user to a group.  <p>  In the request entity, the <em>context</em> attribute is the group and the <em>itemName</em> is the user.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AddUserToGroupRequest**](AddUserToGroupRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AddUserToGroups**
> string AddUserToGroups(ctx, body)
addUserToGroups

Add a user to one or more groups.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AddUserToGroupsRequest**](AddUserToGroupsRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AddUsersToGroup**
> string AddUsersToGroup(ctx, body)
addUsersToGroup

Add multiple users to a group.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AddUsersToGroupRequest**](AddUsersToGroupRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Approve**
> string Approve(ctx, pullRequestId, projectKey, repositorySlug)
approve

Approve a pull request as the current user. Implicitly adds the user as a participant if they are not already.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.  <p>  <strong>Deprecated since 4.2</strong>. Use  /rest/api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} instead

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AssignParticipantRole**
> string AssignParticipantRole(ctx, body, pullRequestId, projectKey, repositorySlug)
assignParticipantRole

Assigns a participant to an explicit role in pull request. Currently only the REVIEWER role may be assigned.  <p>  If the user is not yet a participant in the pull request, they are made one and assigned the supplied role.  <p>  If the user is already a participant in the pull request, their previous role is replaced with the supplied role  unless they are already assigned the AUTHOR role which cannot be changed and will result in a Bad Request (400)  response code.  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**AssignParticipantRoleRequest**](AssignParticipantRoleRequest.md)|  | 
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CanMerge**
> string CanMerge(ctx, pullRequestId, projectKey, repositorySlug)
canMerge

Test whether a pull request can be merged.  <p>  A pull request may not be merged if:  <ul>      <li>there are conflicts that need to be manually resolved before merging; and/or</li>      <li>one or more merge checks have vetoed the merge.</li>  </ul>  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CancelExportJob**
> string CancelExportJob(ctx, jobId)
cancelExportJob

Requests the cancellation of an export job.   <p>The request to cancel a job will be processed successfully if the job is actually still running. If it has  already finished (successfully or with errors) or if it has already been canceled before, then an error will be  returned.   <p>There might be a small delay between accepting the request and actually cancelling the job. In most cases,  the delay will be close to instantaneously. In the unlikely case of communication issues across a cluster,  it can however take a few seconds to cancel a job.   <p>A client should always actively query the job status to confirm that a job has been successfully canceled.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job to cancel | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CancelImportJob**
> string CancelImportJob(ctx, jobId)
cancelImportJob

Requests the cancellation of an import job.   <p>The request to cancel a job will be processed successfully if the job is actually still running. If it has  already finished (successfully or with errors) or if it has already been canceled before, then an error will be  returned.   <p>Note that import jobs are not canceled as instantaneously as export jobs. Rather, once the request has been  accepted, there are a number of checkpoints at which the job will actually apply it and stop. This is to keep  the system in a reasonably consistent state:   <ul>      <li>After the current fork hierarchy has been imported and verified.</li>      <li>Before the next repository is imported.</li>      <li>Before the next pull request is imported.</li>  </ul>   <p>A client should always actively query the job status to confirm that a job has been successfully canceled.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job to cancel | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ClearSenderAddress**
> string ClearSenderAddress(ctx, )
clearSenderAddress

Clears the server email address.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ClearUserCaptchaChallenge**
> string ClearUserCaptchaChallenge(ctx, optional)
clearUserCaptchaChallenge

Clears any CAPTCHA challenge that may constrain the user with the supplied username when they authenticate.  Additionally any counter or metric that contributed towards the user being issued the CAPTCHA challenge  (for instance too many consecutive failed logins) will also be reset.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource, and may not clear  the CAPTCHA of a user with greater permissions than themselves.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiClearUserCaptchaChallengeOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiClearUserCaptchaChallengeOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CountPullRequestTasks**
> string CountPullRequestTasks(ctx, projectKey, repositorySlug, pullRequestId)
countPullRequestTasks

Retrieve the total number of {@link TaskState#OPEN open} and  {@link TaskState#RESOLVED resolved} tasks associated with a pull request.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Create**
> string Create(ctx, body, projectKey, repositorySlug)
create

Create a new pull request between two branches. The branches may be in the same repository, or different ones.  When using different repositories, they must still be in the same {@link Repository#getHierarchyId() hierarchy}.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the \"from\" and \"to\"repositories to  call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateRequest**](CreateRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateBranch**
> string CreateBranch(ctx, body, projectKey, repositorySlug)
createBranch

Creates a branch using the information provided in the {@link RestCreateBranchRequest request}  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the context repository to call  this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateBranchRequest**](CreateBranchRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateComment**
> string CreateComment(ctx, body, commitId, projectKey, repositorySlug, optional)
createComment

Add a new comment.  <p>  Comments can be added in a few places by setting different attributes:  <p>  General commit comment:   <pre>      {          \"text\": \"An insightful general comment on a commit.\"      }      </pre>   Reply to a comment:   <pre>      {          \"text\": \"A measured reply.\",          \"parent\": {              \"id\": 1          }      }      </pre>   General file comment:   <pre>      {          \"text\": \"An insightful general comment on a file.\",          \"anchor\": {              \"diffType\": \"COMMIT\",              \"fromHash\": \"6df3858eeb9a53a911cd17e66a9174d44ffb02cd\",              \"path\": \"path/to/file\",              \"srcPath\": \"path/to/file\",              \"toHash\": \"04c7c5c931b9418ca7b66f51fe934d0bd9b2ba4b\"          }      }      </pre>   File line comment:   <pre>      {          \"text\": \"A pithy comment on a particular line within a file.\",          \"anchor\": {              \"diffType\": \"COMMIT\",              \"line\": 1,              \"lineType\": \"CONTEXT\",              \"fileType\": \"FROM\",              \"fromHash\": \"6df3858eeb9a53a911cd17e66a9174d44ffb02cd\",              \"path\": \"path/to/file\",              \"srcPath\": \"path/to/file\",              \"toHash\": \"04c7c5c931b9418ca7b66f51fe934d0bd9b2ba4b\"      }      }      </pre>  <strong>Note: general file comments are an experimental feature and may change in the near future!</strong>  <p>  For file and line comments, 'path' refers to the path of the file to which the comment should be applied and  'srcPath' refers to the path the that file used to have (only required for copies and moves). Also,  fromHash and toHash refer to the sinceId / untilId (respectively) used to produce the diff on which the comment  was added. Finally diffType refers to the type of diff the comment was added on.  <p>  For line comments, 'line' refers to the line in the diff that the comment should apply to. 'lineType' refers to  the type of diff hunk, which can be:  <ul>      <li>'ADDED' - for an added line;</li>      <li>'REMOVED' - for a removed line; or</li>      <li>'CONTEXT' - for a line that was unmodified but is in the vicinity of the diff.</li>  </ul>  'fileType' refers to the file of the diff to which the anchor should be attached - which is of relevance when  displaying the diff in a side-by-side way. Currently the supported values are:  <ul>      <li>'FROM' - the source file of the diff</li>      <li>'TO' - the destination file of the diff</li>  </ul>  If the current user is not a participant the user is added as one and updated to watch the commit.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that the commit  is in to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateCommentRequest**](CreateCommentRequest.md)|  | 
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiCreateCommentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiCreateCommentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **since** | **optional.**| For a merge commit, a parent can be provided to specify which diff the comments should be on. For                  a commit range, a {@code sinceId} can be provided to specify where the comments should be                  anchored from. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateGroup**
> string CreateGroup(ctx, optional)
createGroup

Create a new group.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiCreateGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiCreateGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| Name of the group. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateProject**
> string CreateProject(ctx, body)
createProject

Create a new project.  <p>  To include a custom avatar for the project, the project definition should contain an additional attribute with  the key <code>avatar</code> and the value a data URI containing Base64-encoded image data. The URI should be in  the following format:  <pre>      data:(content type, e.g. image/png);base64,(data)  </pre>  If the data is not Base64-encoded, or if a character set is defined in the URI, or the URI is otherwise invalid,  <em>project creation will fail</em>.  <p>  The authenticated user must have <strong>PROJECT_CREATE</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateProjectRequest**](CreateProjectRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateRepository**
> string CreateRepository(ctx, body, projectKey)
createRepository

Create a new repository. Requires an existing project in which this repository will be created.  The only parameters which will be used are name and scmId.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the context project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateRepositoryRequest**](CreateRepositoryRequest.md)|  | 
  **projectKey** | **string**| the parent project key | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateTag**
> string CreateTag(ctx, body, projectKey, repositorySlug)
createTag

Creates a tag using the information provided in the {@link RestCreateTagRequest request}  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the context repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateTagRequest**](CreateTagRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateTask**
> string CreateTask(ctx, body)
createTask

Create a new task.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateTaskRequest**](CreateTaskRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateUser**
> string CreateUser(ctx, optional)
createUser

Creates a new user from the assembled query parameters.  <p>  The default group can be used to control initial permissions for new users, such as granting users the ability  to login or providing read access to certain projects or repositories. If the user is not added to the default  group, they may not be able to login after their account is created until explicit permissions are configured.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiCreateUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiCreateUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the username for the new user | 
 **password** | **optional.String**| the password for the new user | 
 **displayName** | **optional.String**| the display name for the new user | 
 **emailAddress** | **optional.String**| the e-mail address for the new user | 
 **addToDefaultGroup** | **optional.Bool**| &lt;code&gt;true&lt;/code&gt; to add the user to the default group, which can be used to grant them                           a set of initial permissions; otherwise, &lt;code&gt;false&lt;/code&gt; to not add them to a group | [default to true]
 **notify** | **optional.String**| if present and not &lt;code&gt;false&lt;/code&gt; instead of requiring a password,                           the create user will be notified via email their account has been created and requires                           a password to be reset. This option can only be used if a mail server has been configured | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateWebhook**
> string CreateWebhook(ctx, body, projectKey, repositorySlug)
createWebhook

Create a webhook for the repository specified via the URL.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateWebhookRequest**](CreateWebhookRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Decline**
> string Decline(ctx, pullRequestId, projectKey, repositorySlug, optional)
decline

Decline a pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiDeclineOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeclineOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **version** | **optional.Int32**| the current version of the pull request. If the server&#x27;s version isn&#x27;t the same as the specified                 version the operation will fail. To determine the current version of the pull request it should be                 fetched from the server prior to this operation. Look for the &#x27;version&#x27; attribute in the returned                 JSON structure. | [default to -1]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Delete**
> string Delete(ctx, body, pullRequestId, projectKey, repositorySlug)
delete

Deletes a pull request.  <p>  To call this resource, users must be authenticated and have permission to view the pull request.  Additionally, they must:  <ul>      <li>          be the pull request author, if the system is configured to allow authors to delete their own          pull requests (this is the default) OR      </li>      <li>have repository administrator permission for the repository the pull request is targeting</li>  </ul>   A body containing the version of the pull request must be provided with this request.   <pre><code>{ \"version\": 1 }</code></pre>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**DeleteRequest**](DeleteRequest.md)|  | 
  **pullRequestId** | **int64**| the ID of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteAvatar**
> string DeleteAvatar(ctx, userSlug)
deleteAvatar

Delete the avatar associated to a user.  <p>  Users are always allowed to delete their own avatar. To delete someone else's avatar the authenticated user must  have global <strong>ADMIN</strong> permission, or global <strong>SYS_ADMIN</strong> permission to update a  <strong>SYS_ADMIN</strong> user's avatar.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userSlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteComment**
> string DeleteComment(ctx, commentId, commitId, projectKey, repositorySlug, optional)
deleteComment

Delete a commit comment. Anyone can delete their own comment. Only users with <strong>REPO_ADMIN</strong>  and above may delete comments created by other users. Comments which have replies <i>may not be deleted</i>,  regardless of the user's granted permissions.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that the commit  is in to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commentId** | **int64**| the ID of the comment to retrieve | 
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiDeleteCommentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleteCommentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **version** | **optional.Int32**| The expected version of the comment. This must match the server&#x27;s version of the comment or                   the delete will fail. To determine the current version of the comment, the comment should be                   fetched from the server prior to the delete. Look for the &#x27;version&#x27; attribute in the returned                   JSON structure. | [default to -1]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteGroup**
> string DeleteGroup(ctx, optional)
deleteGroup

Deletes the specified group, removing them from the system. This also removes any permissions that may have been  granted to the group.  <p>  A user may not delete the last group that is granting them administrative permissions, or a group with greater  permissions than themselves.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiDeleteGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleteGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the name identifying the group to delete | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteMailConfig**
> string DeleteMailConfig(ctx, )
deleteMailConfig

Deletes the current mail configuration.  <p>  The authenticated user must have the <strong>SYS_ADMIN</strong> permission to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteProject**
> string DeleteProject(ctx, projectKey)
deleteProject

Delete the project matching the supplied <strong>projectKey</strong>.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteRepository**
> string DeleteRepository(ctx, projectKey, repositorySlug)
deleteRepository

Schedule the repository matching the supplied <strong>projectKey</strong> and <strong>repositorySlug</strong> to  be deleted. If the request repository is not present  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**| the parent project key | 
  **repositorySlug** | **string**| the repository slug | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteRepositoryHook**
> string DeleteRepositoryHook(ctx, hookKey, projectKey, repositorySlug)
deleteRepositoryHook

Delete repository hook configuration for the supplied <strong>hookKey</strong> and <strong>repositorySlug</strong>  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteTask**
> string DeleteTask(ctx, taskId)
deleteTask

Delete a task.  <p>  Note that only the task's creator, the context's author or an admin of the context's repository can delete a  task. (For a pull request task, those are the task's creator, the pull request's author or an admin on the  repository containing the pull request). Additionally a task cannot be deleted if it has already been resolved.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **taskId** | **int64**| the id identifying the task to delete | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteUser**
> string DeleteUser(ctx, optional)
deleteUser

Deletes the specified user, removing them from the system. This also removes any permissions that may have been  granted to the user.  <p>  A user may not delete themselves, and a user with <strong>ADMIN</strong> permissions may not delete a user with  <strong>SYS_ADMIN</strong>permissions.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiDeleteUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleteUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the username identifying the user to delete | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteWebhook**
> string DeleteWebhook(ctx, webhookId, projectKey, repositorySlug)
deleteWebhook

Delete a webhook for the repository specified via the URL.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **webhookId** | **int32**| the existing webhook id | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeletedeleteComment**
> string DeletedeleteComment(ctx, commentId, projectKey, repositorySlug, pullRequestId, optional)
deleteComment

Delete a pull request comment. Anyone can delete their own comment. Only users with <strong>REPO_ADMIN</strong>  and above may delete comments created by other users.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commentId** | **int64**| the id of the comment to retrieve | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 
 **optional** | ***DefaultApiDeletedeleteCommentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeletedeleteCommentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **version** | **optional.Int32**| The expected version of the comment. This must match the server&#x27;s version of the comment or                     the delete will fail. To determine the current version of the comment, the comment should be                     fetched from the server prior to the delete. Look for the &#x27;version&#x27; attribute in the                     returned JSON structure. | [default to -1]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeletedisableHook**
> interface{} DeletedisableHook(ctx, hookKey, projectKey)
disableHook

Disable a repository hook for this project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleterevokePermissionsForGroup**
> interface{} DeleterevokePermissionsForGroup(ctx, projectKey, optional)
revokePermissionsForGroup

Revoke all permissions for the specified project for a group.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.  <p>  In addition, a user may not revoke a group's permissions if it will reduce their own permission level.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiDeleterevokePermissionsForGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleterevokePermissionsForGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **name** | **optional.String**| the name of the group | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleterevokePermissionsForGroup1**
> string DeleterevokePermissionsForGroup1(ctx, optional)
revokePermissionsForGroup

Revoke all global permissions for a group.   <p>  The authenticated user must have:  <ul>      <li><strong>ADMIN</strong> permission or higher; and</li>      <li>greater or equal permissions than the current permission level of the group (a user may not demote the      permission level of a group with higher permissions than them)</li>  </ul>  to call this resource. In addition, a user may not revoke a group's permissions if their own permission level  would be reduced as a result.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiDeleterevokePermissionsForGroup1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleterevokePermissionsForGroup1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the name of the group | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleterevokePermissionsForUser**
> interface{} DeleterevokePermissionsForUser(ctx, projectKey, optional)
revokePermissionsForUser

Revoke all permissions for the specified project for a user.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.  <p>  In addition, a user may not revoke their own project permissions if they do not have a higher global permission.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiDeleterevokePermissionsForUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleterevokePermissionsForUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **name** | **optional.String**| the name of the user | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleterevokePermissionsForUser1**
> string DeleterevokePermissionsForUser1(ctx, optional)
revokePermissionsForUser

Revoke all global permissions for a user.  <p>  The authenticated user must have:  <ul>      <li><strong>ADMIN</strong> permission or higher; and</li>      <li>greater or equal permissions than the current permission level of the user (a user may not demote the      permission level of a user with higher permissions than them)</li>  </ul>  to call this resource. In addition, a user may not demote their own permission level.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiDeleterevokePermissionsForUser1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiDeleterevokePermissionsForUser1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the name of the user | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteunassignParticipantRole**
> string DeleteunassignParticipantRole(ctx, userSlug, pullRequestId, projectKey, repositorySlug)
unassignParticipantRole

Unassigns a participant from the REVIEWER role they may have been given in a pull request.  <p>  If the participant has no explicit role this method has no effect.  <p>  Afterwards, the user will still remain a participant in the pull request but their role will be reduced to  PARTICIPANT. This is because once made a participant of a pull request,  a user will forever remain a participant. Only their role may be altered.  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the repository that this pull request  targets to call this resource.  <p>  <strong>Deprecated since 4.2</strong>. Use  /rest/api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug}  instead.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userSlug** | **string**| the slug for the user changing their status | 
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Deleteunwatch**
> string Deleteunwatch(ctx, projectKey, repositorySlug, pullRequestId)
unwatch

Remove the authenticated user as a watcher for the specified pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Deleteunwatch1**
> string Deleteunwatch1(ctx, projectKey, repositorySlug)
unwatch

Remove the authenticated user as a watcher for the specified repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DisableHook**
> interface{} DisableHook(ctx, hookKey, projectKey, repositorySlug)
disableHook

Disable a repository hook for this repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EditFile**
> interface{} EditFile(ctx, path, projectKey, repositorySlug, path_)
editFile

Update the content of <code>path</code>, on the given <code>repository</code> and <code>branch</code>.  <p>  This resource accepts PUT multipart form data, containing the file in a form-field named <code>content</code>.  <p>  An example <a href=\"http://curl.haxx.se/\">curl</a> request to update 'README.md' would be:  <pre>  curl -X PUT -u username:password -F content=@README.md  -F 'message=Updated using file-edit REST API'  -F branch=master -F  sourceCommitId=5636641a50b   http://example.com/rest/api/latest/projects/PROJECT_1/repos/repo_1/browse/README.md  </pre>  <p>  <ui>  <li>branch:  the branch on which the <code>path</code> should be modified or created</li>  <li>content: the full content of the file at <code>path</code> </li>  <li>message: the message associated with this change, to be used as the commit message.  Or null if the default message should be used.</li>  <li>sourceCommitId: the commit ID of the file before it was edited, used to identify if  content has changed. Or null if this is a new file</li>  </ui>  <p>  The file can be updated or created on a new branch. In this case, the <code>sourceBranch</code> parameter should  be provided to identify the starting point for the new branch and the <code>branch</code> parameter identifies  the branch to create the new commit on.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path of the file that is to be modified or created | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnableHook**
> interface{} EnableHook(ctx, hookKey, projectKey, repositorySlug, optional)
enableHook

Enable a repository hook for this repository and optionally apply new configuration.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.  <p>  A JSON document may be provided to use as the settings for the hook. These structure and validity of  the document is decided by the plugin providing the hook.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiEnableHookOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiEnableHookOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **contentLength** | **optional.Int32**|  | [default to 0]

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EraseUser**
> string EraseUser(ctx, optional)
eraseUser

Erases personally identifying user data for a deleted user.  <p>  References in the application to the original username will be either removed or updated to a new non-identifying  username. Refer to the  <a href=\"https://confluence.atlassian.com/gdpr/bitbucket-right-to-erasure-949770560.html\">support guide</a> for  details about what data is and isn't erased.  <p>  User erasure can only be performed on a deleted user. If the user has not been deleted first then this endpoint  will return a bad request and no erasure will be performed.  <p>  Erasing user data is <strong>irreversible</strong> and may lead to a degraded user experience. This method should  not be used as part of a standard user deletion and cleanup process.  <p>  Plugins can participate in user erasure by defining a {@code <user-erasure-handler>} module. If one or more plugin  modules fail, an error summary of the failing modules is returned.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiEraseUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiEraseUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the username identifying the user to erase | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindContributing**
> interface{} FindContributing(ctx, projectKey, repositorySlug)
findContributing

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=UTF-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindGroupsForUser**
> string FindGroupsForUser(ctx, optional)
findGroupsForUser

Retrieves a list of groups the specified user is a member of.  <p>  The authenticated user must have the <strong>LICENSED_USER</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiFindGroupsForUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiFindGroupsForUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **context** | **optional.String**| the user which should be used to locate groups | 
 **filter** | **optional.String**| if specified only groups with names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindLicense**
> interface{} FindLicense(ctx, projectKey, repositorySlug)
findLicense

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=UTF-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindOtherGroupsForUser**
> string FindOtherGroupsForUser(ctx, optional)
findOtherGroupsForUser

Retrieves a list of groups the specified user is <em>not</em> a member of.  <p>  The authenticated user must have the <strong>LICENSED_USER</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiFindOtherGroupsForUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiFindOtherGroupsForUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **context** | **optional.String**| the user which should be used to locate groups | 
 **filter** | **optional.String**| if specified only groups with names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindReadme**
> interface{} FindReadme(ctx, projectKey, repositorySlug)
findReadme

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=UTF-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindUsersInGroup**
> string FindUsersInGroup(ctx, optional)
findUsersInGroup

Retrieves a list of users that are members of a specified group.  <p>  The authenticated user must have the <strong>LICENSED_USER</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiFindUsersInGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiFindUsersInGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **context** | **optional.String**| the group which should be used to locate members | 
 **filter** | **optional.String**| if specified only users with usernames, display names or email addresses containing the                   supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindUsersNotInGroup**
> string FindUsersNotInGroup(ctx, optional)
findUsersNotInGroup

Retrieves a list of users that are <em>not</em> members of a specified group.  <p>  The authenticated user must have the <strong>LICENSED_USER</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiFindUsersNotInGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiFindUsersNotInGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **context** | **optional.String**| the group which should be used to locate non-members | 
 **filter** | **optional.String**| if specified only users with usernames, display names or email addresses containing the                   supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FindWebhooks**
> string FindWebhooks(ctx, projectKey, repositorySlug, optional)
findWebhooks

Find webhooks in this repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiFindWebhooksOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiFindWebhooksOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **event** | **optional.String**| list of {@link com.atlassian.webhooks.WebhookEvent} ids to filter for | 
 **statistics** | **optional.Bool**| {@code true} if statistics should be provided for all found webhooks | [default to false]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ForkRepository**
> string ForkRepository(ctx, body, projectKey, repositorySlug)
forkRepository

Create a new repository forked from an existing repository.  <p>  The JSON body for this {@code POST} is not required to contain <i>any</i> properties. Even the name may be  omitted. The following properties will be used, if provided:  <ul>      <li>{@code \"name\":\"Fork name\"} - Specifies the forked repository's name      <ul>          <li>Defaults to the name of the origin repository if not specified</li>      </ul>      </li>      <li>{@code \"project\":{\"key\":\"TARGET_KEY\"}} - Specifies the forked repository's target project by key      <ul>          <li>Defaults to the current user's personal project if not specified</li>      </ul>      </li>  </ul>  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository and  <strong>PROJECT_ADMIN</strong> on the target project to call this resource. Note that users <i>always</i>  have <b>PROJECT_ADMIN</b> permission on their personal projects.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**ForkRepositoryRequest**](ForkRepositoryRequest.md)|  | 
  **projectKey** | **string**| the parent project key | 
  **repositorySlug** | **string**| the repository slug | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Get**
> string Get(ctx, )
get

Retrieves details about the current license, as well as the current status of the system with regards to the  installed license. The status includes the current number of users applied toward the license limit, as well  as any status messages about the license (warnings about expiry or user counts exceeding license limits).  <p>  The authenticated user must have <b>ADMIN</b> permission. Unauthenticated users, and non-administrators, are  not permitted to access license details.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetActivities**
> string GetActivities(ctx, pullRequestId, projectKey, repositorySlug, optional)
getActivities

Retrieve a page of activity associated with a pull request.  <p>  Activity items include comments, approvals, rescopes (i.e. adding and removing of commits), merges and more.  <p>  Different types of activity items may be introduced in newer versions of Stash or by user installed plugins, so  clients should be flexible enough to handle unexpected entity shapes in the returned page.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetActivitiesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetActivitiesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **fromId** | **optional.Int64**| (optional) the id of the activity item to use as the first item in the returned page | 
 **fromType** | **optional.String**| (required if &lt;strong&gt;fromId&lt;/strong&gt; is present) the type of the activity item specified by                  &lt;strong&gt;fromId&lt;/strong&gt; (either &lt;strong&gt;COMMENT&lt;/strong&gt; or &lt;strong&gt;ACTIVITY&lt;/strong&gt;) | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAllLabelsForRepository**
> string GetAllLabelsForRepository(ctx, projectKey, repositorySlug)
getAllLabelsForRepository

Get all labels applied to the given repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetApplicationProperties**
> string GetApplicationProperties(ctx, )
getApplicationProperties

Retrieve version information and other application properties.  <p>  No authentication is required to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetArchive**
> string GetArchive(ctx, projectKey, repositorySlug, optional)
getArchive

Streams an archive of the repository's contents at the requested commit. If no <code>at=</code> commit is  requested, an archive of the default branch is streamed.  <p>  The <code>filename=</code> query parameter may be used to specify the exact filename to include in the  <code>\"Content-Disposition\"</code> header. If an explicit filename is not provided, one will be automatically  generated based on what is being archived. Its format depends on the <code>at=</code> value:  <ul>      <li>No <code>at=</code> commit:      <code>&lt;slug&gt;-&lt;default-branch-name&gt;@&lt;commit&gt;.&lt;format&gt;</code>;      e.g. example-master@43c2f8a0fe8.zip</li>      <li><code>at=sha</code>: <code>&lt;slug&gt;-&lt;at&gt;.&lt;format&gt;</code>; e.g.      example-09bcbb00100cfbb5310fb6834a1d5ce6cac253e9.tar.gz</li>      <li><code>at=branchOrTag</code>: <code>&lt;slug&gt;-&lt;branchOrTag&gt;@&lt;commit&gt;.&lt;format&gt;</code>;      e.g. example-feature@bbb225f16e1.tar      <ul>          <li>If the branch or tag is qualified (e.g. <code>refs/heads/master</code>, the short name          (<code>master</code>) will be included in the filename</li>          <li>If the branch or tag's <i>short name</i> includes slashes (e.g. <code>release/4.6</code>),          they will be converted to hyphens in the filename (<code>release-4.5</code>)</li>      </ul>      </li>  </ul>  <p>  Archives may be requested in the following formats by adding the <code>format=</code> query parameter:  <ul>      <li><code>zip</code>: A zip file using standard compression (Default)</li>      <li><code>tar</code>: An uncompressed tarball</li>      <li><code>tar.gz</code> or <code>tgz</code>: A GZip-compressed tarball</li>  </ul>  The contents of the archive may be filtered by using the <code>path=</code> query parameter to specify paths to  include. <code>path=</code> may be specified multiple times to include multiple paths.  <p>  The <code>prefix=</code> query parameter may be used to define a directory (or multiple directories) where  the archive's contents should be placed. If the prefix does not end with <code>/</code>, one will be added  automatically. The prefix is <i>always</i> treated as a directory; it is not possible to use it to prepend  characters to the entries in the archive.  <p>  Archives of public repositories may be streamed by any authenticated or anonymous user. Streaming archives for  non-public repositories requires an <i>authenticated user</i> with at least <b>REPO_READ</b> permission.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetArchiveOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetArchiveOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **at** | **optional.String**| the commit to stream an archive of; if not supplied, an archive of the default branch is streamed | 
 **filename** | **optional.String**| a filename to include the \&quot;Content-Disposition\&quot; header | 
 **format** | **optional.String**| the format to stream the archive in; must be one of: zip, tar, tar.gz or tgz | 
 **path** | **optional.String**| paths to include in the streamed archive; may be repeated to include multiple paths | 
 **prefix** | **optional.String**| a prefix to apply to all entries in the streamed archive; if the supplied prefix does not end                  with a trailing &lt;code&gt;/&lt;/code&gt;, one will be added automatically | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/octet-stream; application/x-tar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAvatar**
> string GetAvatar(ctx, hookKey, optional)
getAvatar

Retrieve the avatar for the project matching the supplied <strong>moduleKey</strong>.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**| the complete module key of the hook module | 
 **optional** | ***DefaultApiGetAvatarOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetAvatarOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **version** | **optional.String**| optional version used for HTTP caching only - any non-blank version will result in a large max-age Cache-Control header.                 Note that this does not affect the Last-Modified header. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: image/png

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetBranches**
> string GetBranches(ctx, projectKey, repositorySlug, optional)
getBranches

Retrieve the branches matching the supplied <strong>filterText</strong> param.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetBranchesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetBranchesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **base** | **optional.String**| base branch or tag to compare each branch to (for the metadata providers that uses that information) | 
 **details** | **optional.Bool**| whether to retrieve plugin-provided metadata about each branch | 
 **filterText** | **optional.String**| the text to match on | 
 **orderBy** | **optional.String**| ordering of refs either ALPHABETICAL (by name) or MODIFICATION (last updated) | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetChanges**
> string GetChanges(ctx, projectKey, repositorySlug, optional)
getChanges

Retrieve a page of changes made in a specified commit.  <p>  <strong>Note:</strong> The implementation will apply a hard cap ({@code page.max.changes}) and it is not  possible to request subsequent content when that cap is exceeded.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetChangesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetChangesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **since** | **optional.String**| the commit to which &lt;code&gt;until&lt;/code&gt; should be compared to produce a page of changes.                      If not specified the commit&#x27;s first parent is assumed (if one exists) | 
 **until** | **optional.String**| the commit to retrieve changes for | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetComment**
> string GetComment(ctx, commentId, commitId, projectKey, repositorySlug)
getComment

Retrieves a commit discussion comment.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that the commit  is in to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commentId** | **int64**| the ID of the comment to retrieve | 
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetComments**
> string GetComments(ctx, commitId, projectKey, repositorySlug, optional)
getComments

Retrieves the commit discussion comments that match the specified search criteria.  <p>  It is possible to retrieve commit discussion comments that are anchored to a range of commits by providing the  {@code sinceId} that the comments anchored from.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that the commit  is in to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetCommentsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetCommentsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **path** | **optional.String**| the path to the file on which comments were made | 
 **since** | **optional.String**| For a merge commit, a parent can be provided to specify which diff the comments are on. For                       a commit range, a {@code sinceId} can be provided to specify where the comments are anchored                       from. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCommit**
> string GetCommit(ctx, commitId, projectKey, repositorySlug, optional)
getCommit

Retrieve a single commit <i>identified by its ID</i>>. In general, that ID is a SHA1. <u>From 2.11, ref names  like \"refs/heads/master\" are no longer accepted by this resource.</u>  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**| the commit ID to retrieve | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetCommitOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetCommitOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **path** | **optional.String**| an optional path to filter the commit by. If supplied the details returned &lt;i&gt;may not&lt;/i&gt;              be for the specified commit. Instead, starting from the specified commit, they will be the              details for the first commit affecting the specified path. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCommits**
> string GetCommits(ctx, pullRequestId, projectKey, repositorySlug, optional)
getCommits

Retrieve commits for the specified pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetCommitsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetCommitsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **withCounts** | **optional.Bool**| if set to true, the service will add \&quot;authorCount\&quot; and \&quot;totalCount\&quot; at the end of the page.                      \&quot;authorCount\&quot; is the number of different authors and \&quot;totalCount\&quot; is the total number of commits. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetContent**
> string GetContent(ctx, projectKey, repositorySlug, optional)
getContent

Retrieve a page of content for a file path at a specified revision.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetContentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetContentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **at** | **optional.String**| the commit ID or ref to retrieve the content for. | 
 **type_** | **optional.Bool**| if true only the type will be returned for the file path instead of the contents. | [default to false]
 **blame** | **optional.String**| if present the blame will be returned for the file as well. | 
 **noContent** | **optional.String**| if present and used with blame only the blame is retrieved instead of the contents. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetDefaultBranch**
> string GetDefaultBranch(ctx, projectKey, repositorySlug)
getDefaultBranch

Get the default branch of the repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetExportJob**
> string GetExportJob(ctx, jobId)
getExportJob

Gets the details, including the current status and progress, of the export job identified by the given ID.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetExportJobMessages**
> string GetExportJobMessages(ctx, jobId, optional)
getExportJobMessages

Gets the messages generated by the job.   <p>Without any filter, all messages will be returned, but the response can optionally be filtered for the  following severities. The severity parameter can be repeated to include multiple severities  in one response.   <ul>      <li>INFO</li>      <li>WARN</li>      <li>ERROR</li>  </ul>   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job | 
 **optional** | ***DefaultApiGetExportJobMessagesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetExportJobMessagesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **severity** | **optional.String**| the severity to include in the results | 
 **subject** | **optional.String**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetForkedRepositories**
> string GetForkedRepositories(ctx, projectKey, repositorySlug)
getForkedRepositories

Retrieve repositories which have been forked from this one. Unlike {@link #getRelatedRepositories(Repository,  PageRequest) related repositories}, this only looks at a given repository's direct forks. If those forks have  themselves been the origin of more forks, such \"grandchildren\" repositories will not be retrieved.  <p>  Only repositories to which the authenticated user has <b>REPO_READ</b> permission will be included, even  if other repositories have been forked from this one.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGroups**
> string GetGroups(ctx, optional)
getGroups

Retrieve a page of groups.  <p>  The authenticated user must have <strong>LICENSED_USER</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetGroupsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetGroupsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGroups1**
> string GetGroups1(ctx, optional)
getGroups1

Retrieve a page of group names.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetGroups1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetGroups1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGroupsWithAnyPermission**
> string GetGroupsWithAnyPermission(ctx, projectKey, repositorySlug, optional)
getGroupsWithAnyPermission

Retrieve a page of groups that have been granted at least one permission for the specified repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetGroupsWithAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetGroupsWithAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGroupsWithoutAnyPermission**
> string GetGroupsWithoutAnyPermission(ctx, projectKey, repositorySlug, optional)
getGroupsWithoutAnyPermission

Retrieve a page of groups that have no granted permissions for the specified repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetGroupsWithoutAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetGroupsWithoutAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetImportJob**
> string GetImportJob(ctx, jobId)
getImportJob

Gets the details, including the current status and progress, of the import job identified by the given ID.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetImportJobMessages**
> string GetImportJobMessages(ctx, jobId, optional)
getImportJobMessages

Gets the messages generated by the job.   <p>Without any filter, all messages will be returned, but the response can optionally be filtered for the  following severities. The severity parameter can be repeated to include multiple severities  in one response.   <ul>      <li>INFO</li>      <li>WARN</li>      <li>ERROR</li>  </ul>   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **jobId** | **int64**| the ID of the job | 
 **optional** | ***DefaultApiGetImportJobMessagesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetImportJobMessagesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **severity** | **optional.String**| the severity to include in the results | 
 **subject** | **optional.String**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetInformation**
> interface{} GetInformation(ctx, )
getInformation

Gets information about the nodes that currently make up the stash cluster.  <p>  The authenticated user must have the <strong>SYS_ADMIN</strong> permission to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLabel**
> string GetLabel(ctx, labelName)
getLabel

Returns a label.  <p>  The user needs to be authenticated to use this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **labelName** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLabelables**
> string GetLabelables(ctx, labelName, optional)
getLabelables

Returns a page of labelables for a given label.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **labelName** | **string**|  | 
 **optional** | ***DefaultApiGetLabelablesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetLabelablesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **optional.String**| the type of labelables to be returned. Supported values: REPOSITORY | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLabels**
> string GetLabels(ctx, optional)
getLabels

Returns a paged response of all the labels in the system.  <p>  The user needs to be authenticated to use this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetLabelsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetLabelsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **prefix** | **optional.String**| (optional) prefix to filter the labels on. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLatestInvocation**
> string GetLatestInvocation(ctx, webhookId, projectKey, repositorySlug, optional)
getLatestInvocation

Get the latest invocations for a specific webhook.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **webhookId** | **int32**| id of the webhook | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetLatestInvocationOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetLatestInvocationOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **event** | **optional.String**| the string id of a specific event to retrieve the last invocation for. | 
 **outcome** | **optional.String**| the outcome to filter for. Can be SUCCESS, FAILURE, ERROR. None specified means that the all                   will be considered | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLevel**
> string GetLevel(ctx, loggerName)
getLevel

Retrieve the current log level for a given logger.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **loggerName** | **string**| the name of the logger. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetMailConfig**
> string GetMailConfig(ctx, )
getMailConfig

Retrieves the current mail configuration.   The authenticated user must have the <strong>SYS_ADMIN</strong> permission to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetMergeConfig**
> string GetMergeConfig(ctx, scmId)
getMergeConfig

Retrieve the merge strategies available for this instance.  <p>  The user must be authenticated to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **scmId** | **string**| the id of the scm to get strategies for | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPage**
> string GetPage(ctx, projectKey, repositorySlug, optional)
getPage

Retrieve a page of pull requests to or from the specified repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call  this resource.   Optionally clients can specify PR participant filters. Each filter has a mandatory {@code username.N}  parameter, and the optional {@code role.N} and {@code approved.N} parameters.  <ul>      <li>          {@code username.N} - the \"root\" of a single participant filter, where \"N\" is a natural number          starting from 1. This allows clients to specify multiple participant filters, by providing consecutive          filters as {@code username.1}, {@code username.2} etc. Note that the filters numbering has to start          with 1 and be continuous for all filters to be processed. The total allowed number of participant          filters is 10 and all filters exceeding that limit will be dropped.      </li>      <li>          {@code role.N}(optional) the role associated with {@code username.N}.          This must be one of {@code AUTHOR}, {@code REVIEWER}, or{@code PARTICIPANT}      </li>      <li>          {@code approved.N}(optional) the approved status associated with {@code username.N}.          That is whether {@code username.N} has approved the PR. Either {@code true}, or {@code false}      </li>  </ul>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetPageOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetPageOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **direction** | **optional.String**| (optional, defaults to &lt;strong&gt;INCOMING&lt;/strong&gt;) the direction relative to the specified                   repository. Either &lt;strong&gt;INCOMING&lt;/strong&gt; or &lt;strong&gt;OUTGOING&lt;/strong&gt;. | [default to incoming]
 **at** | **optional.String**| (optional) a &lt;i&gt;fully-qualified&lt;/i&gt; branch ID to find pull requests to or from,            such as {@code refs/heads/master} | 
 **state** | **optional.String**| (optional, defaults to &lt;strong&gt;OPEN&lt;/strong&gt;). Supply &lt;strong&gt;ALL&lt;/strong&gt; to return pull request                in any state. If a state is supplied only pull requests in the specified state will be returned.                Either &lt;strong&gt;OPEN&lt;/strong&gt;, &lt;strong&gt;DECLINED&lt;/strong&gt; or &lt;strong&gt;MERGED&lt;/strong&gt;. | 
 **order** | **optional.String**| (optional, defaults to &lt;strong&gt;NEWEST&lt;/strong&gt;) the order to return pull requests in, either               &lt;strong&gt;OLDEST&lt;/strong&gt; (as in: \&quot;oldest first\&quot;) or &lt;strong&gt;NEWEST&lt;/strong&gt;. | 
 **withAttributes** | **optional.Bool**| (optional) defaults to true, whether to return additional pull request attributes | [default to true]
 **withProperties** | **optional.Bool**| (optional) defaults to true, whether to return additional pull request properties | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetProject**
> string GetProject(ctx, projectKey)
getProject

Retrieve the project matching the supplied <strong>projectKey</strong>.  <p>  The authenticated user must have <strong>PROJECT_VIEW</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetProjectAvatar**
> string GetProjectAvatar(ctx, projectKey, optional)
getProjectAvatar

Retrieve the avatar for the project matching the supplied <strong>projectKey</strong>.  <p>  The authenticated user must have <strong>PROJECT_VIEW</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetProjectAvatarOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetProjectAvatarOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **s** | **optional.Int32**| The desired size of the image. The server will return an image as close as possible to the specified              size. | [default to 0]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: image/png

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetProjects**
> string GetProjects(ctx, optional)
getProjects

Retrieve a page of projects.  <p>  Only projects for which the authenticated user has the <strong>PROJECT_VIEW</strong> permission will be returned.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetProjectsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetProjectsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**|  | 
 **permission** | **optional.String**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPullRequestCount**
> interface{} GetPullRequestCount(ctx, )
getPullRequestCount

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=UTF-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPullRequestSettings**
> interface{} GetPullRequestSettings(ctx, projectKey, repositorySlug)
getPullRequestSettings

Retrieve the pull request settings for the context repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the context repository to call this  resource.  <p>  This resource will call all RestFragments that are registered with the key  <strong>bitbucket.repository.settings.pullRequests</strong>. If any fragment fails validations by returning a  non-empty Map of errors, then no fragments will execute.  <p>  The property keys for the settings that are bundled with the application are  <ul>      <li>mergeConfig - the merge strategy configuration for pull requests</li>      <li>requiredApprovers - (Deprecated, please use com.atlassian.bitbucket.server.bundled-hooks.requiredApproversMergeHook instead) the number of approvals required on a pull request for it to be mergeable, or 0 if the merge check is disabled</li>      <li>com.atlassian.bitbucket.server.bundled-hooks.requiredApproversMergeHook - the merge check configuration for required approvers</li>      <li>requiredAllApprovers - whether or not all approvers must approve a pull request for it to be mergeable</li>      <li>requiredAllTasksComplete - whether or not all tasks on a pull request need to be completed for it to be mergeable</li>      <li>requiredSuccessfulBuilds - (Deprecated, please use com.atlassian.bitbucket.server.bitbucket-build.requiredBuildsMergeCheck instead) the number of successful builds on a pull request for it to be mergeable, or 0 if the merge check is disabled</li>      <li>com.atlassian.bitbucket.server.bitbucket-build.requiredBuildsMergeCheck - the merge check configuration for required builds</li>  </ul>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPullRequestSuggestions**
> string GetPullRequestSuggestions(ctx, optional)
getPullRequestSuggestions

Retrieves a page of suggestions for pull requests that the currently authenticated user may wish to  raise. Such suggestions are based on ref changes occurring and so contain the ref change that  prompted the suggestion plus the time the change event occurred. Changes will be returned in  descending order based on the time the change that prompted the suggestion occurred.  <p>  Note that although the response is a page object, the interface does not support paging, however  a limit can be applied to the size of the returned page.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetPullRequestSuggestionsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetPullRequestSuggestionsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changesSince** | **optional.String**| restrict pull request suggestions to be based on events that occurred since some time                      in the past. This is expressed in seconds since \&quot;now\&quot;. So to return suggestions                      based only on activity within the past 48 hours, pass a value of 172800. | [default to 172800]
 **limit** | **optional.Int32**| restricts the result set to return at most this many suggestions. | [default to 3]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPullRequestTasks**
> string GetPullRequestTasks(ctx, projectKey, repositorySlug, pullRequestId)
getPullRequestTasks

Retrieve the tasks associated with a pull request.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPullRequests**
> string GetPullRequests(ctx, commitId, projectKey, repositorySlug)
getPullRequests

Retrieve a page of pull requests in the current repository that contain the given commit.  <p>  The user must be authenticated and have access to the specified repository to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRelatedRepositories**
> string GetRelatedRepositories(ctx, projectKey, repositorySlug)
getRelatedRepositories

Retrieve repositories which are related to this one. Related repositories are from the same  {@link Repository#getHierarchyId() hierarchy} as this repository.  <p>  Only repositories to which the authenticated user has <b>REPO_READ</b> permission will be included, even  if more repositories are part of this repository's hierarchy.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRepositories**
> string GetRepositories(ctx, optional)
getRepositories

Retrieve a page of repositories based on query parameters that control the search. See the documentation of the  parameters for more details.  <p>  This resource is anonymously accessible.  <p>  <b>Note on permissions.</b> In absence of the <code>permission</code> query parameter the implicit 'read' permission  is assumed. Please note that this permission is lower than the REPO_READ permission rather than being equal to  it. The implicit 'read' permission for a given repository is assigned to any user that has any of the higher  permissions, such as <tt>REPO_READ</tt>, as well as to anonymous users if the repository is marked as public.  The important implication of the above is that an anonymous request to this resource with a permission level  <tt>REPO_READ</tt> is guaranteed to receive an empty list of repositories as a result. For anonymous requests  it is therefore recommended to not specify the <tt>permission</tt> parameter at all.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetRepositoriesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetRepositoriesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| (optional) if specified, this will limit the resulting repository list to ones whose name                     matches this parameter&#x27;s value. The match will be done case-insensitive and any leading                     and/or trailing whitespace characters on the &lt;code&gt;name&lt;/code&gt; parameter will be stripped. | 
 **projectname** | **optional.String**| (optional) if specified, this will limit the resulting repository list to ones whose project&#x27;s                     name matches this parameter&#x27;s value. The match will be done case-insensitive and any leading                     and/or trailing whitespace characters on the &lt;code&gt;projectname&lt;/code&gt; parameter will                     be stripped. | 
 **permission** | **optional.String**| (optional) if specified, it must be a valid repository permission level name and will limit                     the resulting repository list to ones that the requesting user has the specified permission                     level to. If not specified, the default implicit &#x27;read&#x27; permission level will be assumed. The                     currently supported explicit permission values are &lt;tt&gt;REPO_READ&lt;/tt&gt;, &lt;tt&gt;REPO_WRITE&lt;/tt&gt;                     and &lt;tt&gt;REPO_ADMIN&lt;/tt&gt;. | 
 **state** | **optional.String**| (optional) if specified, it must be a valid repository state name and will limit the resulting                     repository list to ones that are in the specified state. The currently supported explicit state                     values are &lt;tt&gt;AVAILABLE&lt;/tt&gt;, &lt;tt&gt;INITIALISING&lt;/tt&gt; and &lt;tt&gt;INITIALISATION_FAILED&lt;/tt&gt;.&lt;br&gt;                     &lt;em&gt;Available since 5.13&lt;/em&gt; | 
 **visibility** | **optional.String**| (optional) if specified, this will limit the resulting repository list based on the                     repositories visibility. Valid values are &lt;em&gt;public&lt;/em&gt; or &lt;em&gt;private&lt;/em&gt;. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRepositoriesRecentlyAccessed**
> string GetRepositoriesRecentlyAccessed(ctx, optional)
getRepositoriesRecentlyAccessed

Retrieve a page of recently accessed repositories for the currently authenticated user.  <p>  Repositories are ordered from most recently to least recently accessed.  <p>  Only authenticated users may call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetRepositoriesRecentlyAccessedOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetRepositoriesRecentlyAccessedOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **permission** | **optional.String**| (optional) if specified, it must be a valid repository permission level name and will limit                    the resulting repository list to ones that the requesting user has the specified permission                    level to. If not specified, the default &lt;code&gt;REPO_READ&lt;/code&gt; permission level will be assumed. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRepository**
> string GetRepository(ctx, projectKey, repositorySlug)
getRepository

Retrieve the repository matching the supplied <strong>projectKey</strong> and <strong>repositorySlug</strong>.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**| the parent project key | 
  **repositorySlug** | **string**| the repository slug | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRepositoryHook**
> interface{} GetRepositoryHook(ctx, hookKey, projectKey, repositorySlug)
getRepositoryHook

Retrieve a repository hook for this repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRepositoryHooks**
> string GetRepositoryHooks(ctx, projectKey, repositorySlug, optional)
getRepositoryHooks

Retrieve a page of repository hooks for this repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetRepositoryHooksOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetRepositoryHooksOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **type_** | **optional.String**| the optional type to filter by. Valid values are &lt;code&gt;PRE_RECEIVE&lt;/code&gt; or &lt;code&gt;POST_RECEIVE&lt;/code&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetRootLevel**
> string GetRootLevel(ctx, )
getRootLevel

Retrieve the current log level for the root logger.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetSenderAddress**
> string GetSenderAddress(ctx, )
getSenderAddress

Retrieves the server email address

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetSettings**
> interface{} GetSettings(ctx, hookKey, projectKey, repositorySlug)
getSettings

Retrieve the settings for a repository hook for this repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetStatistics**
> string GetStatistics(ctx, webhookId, projectKey, repositorySlug, optional)
getStatistics

Get the statistics for a specific webhook.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **webhookId** | **int32**| id of the webhook | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetStatisticsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetStatisticsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **event** | **optional.String**| the string id of a specific event to retrieve the last invocation for. May be empty, in which                   case all events are considered | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetStatisticsSummary**
> string GetStatisticsSummary(ctx, webhookId, projectKey, repositorySlug)
getStatisticsSummary

Get the statistics summary for a specific webhook.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **webhookId** | **int32**| id of the webhook | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTag**
> string GetTag(ctx, name, projectKey, repositorySlug, name_)
getTag

Retrieve a tag in the specified repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the context repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **name** | **string**| the name of the tag to be retrieved | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **name_** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTags**
> string GetTags(ctx, projectKey, repositorySlug, optional)
getTags

Retrieve the tags matching the supplied <strong>filterText</strong> param.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the context repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetTagsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetTagsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filterText** | **optional.String**| the text to match on | 
 **orderBy** | **optional.String**| ordering of refs either ALPHABETICAL (by name) or MODIFICATION (last updated) | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTask**
> string GetTask(ctx, taskId)
getTask

Retrieve a existing task.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **taskId** | **int64**| the id identifying the task to delete | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUser**
> string GetUser(ctx, userSlug)
getUser

Retrieve the user matching the supplied <strong>userSlug</strong>.  <p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userSlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserSettings**
> string GetUserSettings(ctx, userSlug)
getUserSettings

Retrieve a map of user setting key values for a specific user identified by the user slug.  <p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userSlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUsers**
> string GetUsers(ctx, optional)
getUsers

Retrieve a page of users.  <p>  The authenticated user must have the <strong>LICENSED_USER</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetUsersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUsersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only users with usernames, display name or email addresses containing the supplied                string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUsersWithAnyPermission**
> string GetUsersWithAnyPermission(ctx, projectKey, repositorySlug, optional)
getUsersWithAnyPermission

Retrieve a page of users that have been granted at least one permission for the specified repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetUsersWithAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUsersWithAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUsersWithoutAnyPermission**
> string GetUsersWithoutAnyPermission(ctx, optional)
getUsersWithoutAnyPermission

Retrieve a page of users that have no granted global permissions.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetUsersWithoutAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUsersWithoutAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUsersWithoutPermission**
> string GetUsersWithoutPermission(ctx, projectKey, repositorySlug, optional)
getUsersWithoutPermission

Retrieve a page of <i>licensed</i> users that have no granted permissions for the specified repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetUsersWithoutPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUsersWithoutPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetWebhook**
> string GetWebhook(ctx, webhookId, projectKey, repositorySlug, optional)
getWebhook

Get a webhook by id.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **webhookId** | **int32**| the existing webhook id | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetWebhookOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetWebhookOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **statistics** | **optional.Bool**|  | [default to false]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Getget**
> string Getget(ctx, pullRequestId, projectKey, repositorySlug)
get

Retrieve a pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the ID of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetChanges**
> string GetgetChanges(ctx, commitId, projectKey, repositorySlug, optional)
getChanges

Retrieve a page of changes made in a specified commit.  <p>  <strong>Note:</strong> The implementation will apply a hard cap ({@code page.max.changes}) and it is not  possible to request subsequent content when that cap is exceeded.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**| the commit to retrieve changes for | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetgetChangesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetChangesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **since** | **optional.String**| the commit to which &lt;code&gt;until&lt;/code&gt; should be compared to produce a page of changes.                       If not specified the commit&#x27;s first parent is assumed (if one exists) | 
 **withComments** | **optional.Bool**| {@code true} to apply comment counts in the changes (the default); otherwise, {@code false}                       to stream changes without comment counts | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetComment**
> string GetgetComment(ctx, commentId, projectKey, repositorySlug, pullRequestId)
getComment

Retrieves a pull request comment.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commentId** | **int64**| the id of the comment to retrieve | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetComments**
> string GetgetComments(ctx, projectKey, repositorySlug, pullRequestId, optional)
getComments

Gets comments for the specified PullRequest.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 
 **optional** | ***DefaultApiGetgetCommentsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetCommentsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **anchorState** | **optional.String**| {@code ACTIVE} to stream the active comments;                     {@code ORPHANED} to stream the orphaned comments;                     {@code ALL} to stream both the active and the orphaned comments; | [default to ACTIVE]
 **diffType** | **optional.String**| {@code EFFECTIVE} to stream the comments related to the effective diff of the pull request;                     {@code RANGE} to stream comments related to a commit range between two arbitrary commits                                   (requires {@code fromHash} and {@code toHash});                     {@code COMMIT} to stream comments related to a commit between two arbitrary commits (requires                         {@code fromHash} and {@code toHash}) | 
 **fromHash** | **optional.String**| the from commit hash to stream comments for a {@code RANGE} or {@code COMMIT} arbitrary change scope | 
 **path** | **optional.String**| the path to stream comments for a given path | 
 **toHash** | **optional.String**| the to commit hash to stream comments for a {@code RANGE} or {@code COMMIT} arbitrary change scope | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetCommits**
> string GetgetCommits(ctx, projectKey, repositorySlug, optional)
getCommits

Retrieve a page of commits from a given starting commit or \"between\" two commits. If no explicit commit is  specified, the tip of the repository's default branch is assumed. commits may be identified by branch or tag  name or by ID. A path may be supplied to restrict the returned commits to only those which affect that path.  <p>  The authenticated user must have <b>REPO_READ</b> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetgetCommitsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetCommitsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **followRenames** | **optional.Bool**| if &lt;code&gt;true&lt;/code&gt;, the commit history of the specified file will be followed past renames.                       Only valid for a path to a single file. | [default to false]
 **ignoreMissing** | **optional.Bool**| &lt;code&gt;true&lt;/code&gt; to ignore missing commits, &lt;code&gt;false&lt;/code&gt; otherwise | [default to false]
 **merges** | **optional.String**| if present, controls how merge commits should be filtered. Can be either &lt;code&gt;exclude&lt;/code&gt;,                to exclude merge commits, &lt;code&gt;include&lt;/code&gt;, to include both merge commits and non-merge                commits or &lt;code&gt;only&lt;/code&gt;, to only return merge commits. | 
 **path** | **optional.String**| an optional path to filter commits by | 
 **since** | **optional.String**| the commit ID or ref (exclusively) to retrieve commits after | 
 **until** | **optional.String**| the commit ID (SHA1) or ref (inclusively) to retrieve commits before | 
 **withCounts** | **optional.Bool**| optionally include the total number of commits and total number of unique authors | [default to false]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetContent**
> string GetgetContent(ctx, path, projectKey, repositorySlug, path_, optional)
getContent

Retrieve a page of content for a file path at a specified revision.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path of the file that is to be modified or created | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetgetContentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetContentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **at** | **optional.String**| the commit ID or ref to retrieve the content for. | 
 **type_** | **optional.Bool**| if true only the type will be returned for the file path instead of the contents. | [default to false]
 **blame** | **optional.String**| if present the blame will be returned for the file as well. | 
 **noContent** | **optional.String**| if present and used with blame only the blame is retrieved instead of the contents. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetGroupsWithAnyPermission**
> string GetgetGroupsWithAnyPermission(ctx, projectKey, optional)
getGroupsWithAnyPermission

Retrieve a page of groups that have been granted at least one permission for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetgetGroupsWithAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetGroupsWithAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetGroupsWithAnyPermission1**
> string GetgetGroupsWithAnyPermission1(ctx, optional)
getGroupsWithAnyPermission

Retrieve a page of groups that have been granted at least one global permission.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetgetGroupsWithAnyPermission1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetGroupsWithAnyPermission1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetGroupsWithoutAnyPermission**
> string GetgetGroupsWithoutAnyPermission(ctx, projectKey, optional)
getGroupsWithoutAnyPermission

Retrieve a page of groups that have no granted permissions for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetgetGroupsWithoutAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetGroupsWithoutAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetGroupsWithoutAnyPermission1**
> string GetgetGroupsWithoutAnyPermission1(ctx, optional)
getGroupsWithoutAnyPermission

Retrieve a page of groups that have no granted global permissions.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetgetGroupsWithoutAnyPermission1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetGroupsWithoutAnyPermission1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only group names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetPullRequestSettings**
> string GetgetPullRequestSettings(ctx, scmId, projectKey)
getPullRequestSettings

Retrieve the merge strategy configuration for this project and SCM.  <p>  The authenticated user must have <strong>PROJECT_READ</strong> permission for the context repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **scmId** | **string**| the SCM to get strategies for | 
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetPullRequests**
> interface{} GetgetPullRequests(ctx, optional)
getPullRequests

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetgetPullRequestsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetPullRequestsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **start** | **optional.Int32**|  | [default to 0]
 **limit** | **optional.Int32**|  | [default to 25]
 **role** | **optional.String**|  | [default to reviewer]

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=UTF-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetPullRequests1**
> string GetgetPullRequests1(ctx, optional)
getPullRequests

Retrieve a page of pull requests where the current authenticated user is involved as either a reviewer, author  or a participant. The request may be filtered by pull request state, role or participant status.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetgetPullRequests1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetPullRequests1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **state** | **optional.String**| (optional, defaults to returning pull requests in any state). If a state is supplied only pull               requests in the specified state will be returned. Either &lt;strong&gt;OPEN&lt;/strong&gt;,               &lt;strong&gt;DECLINED&lt;/strong&gt; or &lt;strong&gt;MERGED&lt;/strong&gt;.               Omit this parameter to return pull request in any state. | 
 **role** | **optional.String**| (optional, defaults to returning pull requests for any role). If a role is supplied only pull               requests where the authenticated user is a participant in the given role will be returned.               Either &lt;strong&gt;REVIEWER&lt;/strong&gt;, &lt;strong&gt;AUTHOR&lt;/strong&gt; or &lt;strong&gt;PARTICIPANT&lt;/strong&gt;. | 
 **participantStatus** | **optional.String**| (optional, defaults to returning pull requests with any participant status). A comma                           separated list of participant status. That is, one or more of                           &lt;strong&gt;UNAPPROVED&lt;/strong&gt;, &lt;strong&gt;NEEDS_WORK&lt;/strong&gt;, or &lt;strong&gt;APPROVED&lt;/strong&gt;. | 
 **order** | **optional.String**| (optional, defaults to &lt;strong&gt;NEWEST&lt;/strong&gt;) the order to return pull requests in, either               &lt;strong&gt;OLDEST&lt;/strong&gt; (as in: \&quot;oldest first\&quot;), &lt;strong&gt;NEWEST&lt;/strong&gt;,               &lt;strong&gt;PARTICIPANT_STATUS&lt;/strong&gt;, or &lt;strong&gt;CLOSED_DATE&lt;/strong&gt;. Where               &lt;strong&gt;CLOSED_DATE&lt;/strong&gt; is specified and the result set includes pull requests that are not in               the closed state, these pull requests will appear first in the result set, followed by most recently               closed pull requests. | 
 **closedSince** | **optional.String**| (optional, defaults to returning pull requests regardless of closed since date). Permits                       returning only pull requests with a closed timestamp set more recently that                       (now - closedSince). Units are in seconds. So for example if closed since 86400 is set only                       pull requests closed in the previous 24 hours will be returned. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetRepositories**
> string GetgetRepositories(ctx, projectKey)
getRepositories

Retrieve repositories from the project corresponding to the supplied <strong>projectKey</strong>.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**| the parent project key | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetRepositoryHook**
> interface{} GetgetRepositoryHook(ctx, hookKey, projectKey)
getRepositoryHook

Retrieve a repository hook for this project.  <p>  The authenticated user must have <strong>PROJECT_READ</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetRepositoryHooks**
> string GetgetRepositoryHooks(ctx, projectKey, optional)
getRepositoryHooks

Retrieve a page of repository hooks for this project.  <p>  The authenticated user must have <strong>PROJECT_READ</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetgetRepositoryHooksOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetRepositoryHooksOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **optional.String**| the optional type to filter by. Valid values are &lt;code&gt;PRE_RECEIVE&lt;/code&gt; or &lt;code&gt;POST_RECEIVE&lt;/code&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetSettings**
> interface{} GetgetSettings(ctx, hookKey, projectKey)
getSettings

Retrieve the settings for a repository hook for this project.  <p>  The authenticated user must have <strong>PROJECT_READ</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetUsers**
> string GetgetUsers(ctx, )
getUsers

Retrieve a page of users, optionally run through provided filters.  <p>  Only authenticated users may call this resource.   <h3>Supported Filters</h3>  <p>  Filters are provided in query parameters in a standard <code>name=value</code> fashion. The following filters are  currently supported:  <ul>      <li>          {@code filter} - return only users, whose username, name or email address <i>contain</i> the          {@code filter} value      </li>      <li>          {@code group} - return only users who are members of the given group      </li>      <li>          {@code permission} - the \"root\" of a permission filter, whose value must be a valid global,          project, or repository permission. Additional filter parameters referring to this filter that specify the          resource (project or repository) to apply the filter to must be prefixed with <code>permission.</code>. See the          section \"Permission Filters\" below for more details.      </li>      <li>          {@code permission.N} - the \"root\" of a single permission filter, similar to the {@code permission}          parameter, where \"N\" is a natural number starting from 1. This allows clients to specify multiple permission          filters, by providing consecutive filters as {@code permission.1}, {@code permission.2} etc. Note that          the filters numbering has to start with 1 and be continuous for all filters to be processed. The total allowed          number of permission filters is 50 and all filters exceeding that limit will be dropped. See the section          \"Permission Filters\" below for more details on how the permission filters are processed.      </li>  </ul>     <h3>Permission Filters</h3>  <p>  The following three sub-sections list parameters supported for permission filters (where <code>[root]</code> is  the root permission filter name, e.g. {@code permission}, {@code permission.1} etc.) depending on the  permission resource. The system determines which filter to apply (Global, Project or Repository permission)  based on the <code>[root]</code> permission value. E.g. {@code ADMIN} is a global permission,  {@code PROJECT_ADMIN} is a project permission and {@code REPO_ADMIN} is a repository permission. Note  that the parameters for a given resource will be looked up in the order as they are listed below, that is e.g.  for a project resource, if both {@code projectId} and {@code projectKey} are provided, the system will  use {@code projectId} for the lookup.  <h4>Global permissions</h4>  <p>  The permission value under <code>[root]</code> is the only required and recognized parameter, as global  permissions do not apply to a specific resource.  <p>  Example valid filter: <code>permission=ADMIN</code>.  <h4>Project permissions</h4>  <ul>      <li><code>[root]</code>- specifies the project permission</li>      <li><code>[root].projectId</code> - specifies the project ID to lookup the project by</li>      <li><code>[root].projectKey</code> - specifies the project key to lookup the project by</li>  </ul>  <p>  Example valid filter: <code>permission.1=PROJECT_ADMIN&permission.1.projectKey=TEST_PROJECT</code>.  <h4>Repository permissions</h4>  <ul>      <li><code>[root]</code>- specifies the repository permission</li>      <li><code>[root].projectId</code> - specifies the repository ID to lookup the repository by</li>      <li><code>[root].projectKey</code> and <code>[root].repositorySlug</code>- specifies the project key and      repository slug to lookup the repository by; both values <i>need to</i> be provided for this look up to be      triggered</li>  </ul>  Example valid filter: <code>permission.2=REPO_ADMIN&permission.2.projectKey=TEST_PROJECT&permission.2.repositorySlug=test_repo</code>.

### Required Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetUsersWithAnyPermission**
> string GetgetUsersWithAnyPermission(ctx, projectKey, optional)
getUsersWithAnyPermission

Retrieve a page of users that have been granted at least one permission for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetgetUsersWithAnyPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetUsersWithAnyPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetUsersWithAnyPermission1**
> string GetgetUsersWithAnyPermission1(ctx, optional)
getUsersWithAnyPermission

Retrieve a page of users that have been granted at least one global permission.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetgetUsersWithAnyPermission1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetUsersWithAnyPermission1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetgetUsersWithoutPermission**
> string GetgetUsersWithoutPermission(ctx, projectKey, optional)
getUsersWithoutPermission

Retrieve a page of <i>licensed</i> users that have no granted permissions for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiGetgetUsersWithoutPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetgetUsersWithoutPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **optional.String**| if specified only user names containing the supplied string will be returned | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Getstream**
> string Getstream(ctx, path, projectKey, repositorySlug, path_, optional)
stream

Streams files in the requested <code>path</code> with the last commit to modify each file. Commit modifications  are traversed starting from the <code>at</code> commit or, if not specified, from the tip of the default branch.  <p>  Unless the repository is public, the authenticated user must have <b>REPO_READ</b> access to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path within the repository whose files should be streamed | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetstreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **at** | **optional.String**| the commit to use as the starting point when listing files and calculating modifications | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamChanges**
> string GetstreamChanges(ctx, projectKey, repositorySlug, pullRequestId, optional)
streamChanges

Gets changes for the specified PullRequest.  <p>  If the {@code changeScope} query parameter is set to {@code unreviewed}, the application will attempt to stream  unreviewed changes based on the {@code lastReviewedCommit} of the current user, which are the changes between the  {@code lastReviewedCommit} and the latest commit of the source branch. The current user is considered to  <i>not</i> have any unreviewed changes for the pull request when the {@code lastReviewedCommit} is either  {@code null} (everything is unreviewed, so all changes are streamed), equal to the latest commit of the source  branch (everything is reviewed), or no longer on the source branch (the source branch has been rebased). In these  cases, the application will fall back to streaming all changes (the default), which is the effective diff for the  pull request. The type of changes streamed can be determined by the {@code changeScope} parameter included in the  properties map of the response.  <p>  Note: This resource is currently <i>not paged</i>. The server will return at most one page. The server will  truncate the number of changes to either the request's page limit or an internal maximum, whichever is smaller.  The start parameter of the page request is also ignored.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 
 **optional** | ***DefaultApiGetstreamChangesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamChangesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **changeScope** | **optional.String**| {@code UNREVIEWED} to stream the unreviewed changes for the current user (if they exist);                     {@code RANGE} to stream changes between two arbitrary commits (requires {@code sinceId} and                     {@code untilId}); otherwise {@code ALL} to stream all changes (the default) | [default to ALL]
 **sinceId** | **optional.String**| the since commit hash to stream changes for a {@code RANGE} arbitrary change scope | 
 **untilId** | **optional.String**| the until commit hash to stream changes for a {@code RANGE} arbitrary change scope | 
 **withComments** | **optional.Bool**| {@code true} to apply comment counts in the changes (the default); otherwise, {@code false}                      to stream changes without comment counts | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff**
> string GetstreamDiff(ctx, projectKey, repositorySlug, optional)
streamDiff

Retrieve the diff for a specified file path between two provided revisions.  <p>  <strong>Note:</strong> This resource is currently <i>not paged</i>. The server will internally apply a hard cap  to the streamed lines, and it is not possible to request subsequent pages if that cap is exceeded. In the event  that the cap is reached, the diff will be cut short and one or more <code>truncated</code> flags will be set to  <code>true</code> on the segments, hunks and diffs substructures in the returned JSON response.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiffOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiffOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **since** | **optional.String**| the base revision to diff from. If omitted the parent revision of the until revision is used | 
 **srcPath** | **optional.String**| the source path for the file, if it was copied, moved or renamed | 
 **until** | **optional.String**| the target revision to diff to (required) | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to &lt;code&gt;ignore-all&lt;/code&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff1**
> string GetstreamDiff1(ctx, path, projectKey, repositorySlug, path_, optional)
streamDiff

Retrieve the diff for a specified file path between two provided revisions.  <p>  <strong>Note:</strong> This resource is currently <i>not paged</i>. The server will internally apply a hard cap  to the streamed lines, and it is not possible to request subsequent pages if that cap is exceeded. In the event  that the cap is reached, the diff will be cut short and one or more <code>truncated</code> flags will be set to  <code>true</code> on the segments, hunks and diffs substructures in the returned JSON response.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path to the file which should be diffed (required) | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiff1Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiff1Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **since** | **optional.String**| the base revision to diff from. If omitted the parent revision of the until revision is used | 
 **srcPath** | **optional.String**| the source path for the file, if it was copied, moved or renamed | 
 **until** | **optional.String**| the target revision to diff to (required) | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to &lt;code&gt;ignore-all&lt;/code&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff12**
> string GetstreamDiff12(ctx, projectKey, repositorySlug, pullRequestId, optional)
streamDiff

Streams a diff within a pull request.  <p>  If the specified file has been copied, moved or renamed, the <code>srcPath</code> must also be specified to  produce the correct diff.  <p>  Note: This RESTful endpoint is currently <i>not paged</i>. The server will internally apply a hard cap to the  streamed lines, and it is not possible to request subsequent pages if that cap is exceeded.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiff12Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiff12Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **diffType** | **optional.String**| the type of diff being requested. When {@code withComments} is {@code true}                      this works as a hint to the system to attach the correct set of comments to the diff | [default to EFFECTIVE]
 **sinceId** | **optional.String**| the since commit hash to stream a diff between two arbitrary hashes | 
 **srcPath** | **optional.String**| the previous path to the file, if the file has been copied, moved or renamed | 
 **untilId** | **optional.String**| the until commit hash to stream a diff between two arbitrary hashes | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to &lt;code&gt;ignore-all&lt;/code&gt; | 
 **withComments** | **optional.Bool**| &lt;code&gt;true&lt;/code&gt; to embed comments in the diff (the default); otherwise, &lt;code&gt;false&lt;/code&gt;                      to stream the diff without comments | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff123**
> string GetstreamDiff123(ctx, path, projectKey, repositorySlug, pullRequestId, path_, optional)
streamDiff

Streams a diff within a pull request.  <p>  If the specified file has been copied, moved or renamed, the <code>srcPath</code> must also be specified to  produce the correct diff.  <p>  Note: This RESTful endpoint is currently <i>not paged</i>. The server will internally apply a hard cap to the  streamed lines, and it is not possible to request subsequent pages if that cap is exceeded.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path to the file which should be diffed (optional) | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiff123Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiff123Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------





 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **diffType** | **optional.String**| the type of diff being requested. When {@code withComments} is {@code true}                      this works as a hint to the system to attach the correct set of comments to the diff | [default to EFFECTIVE]
 **sinceId** | **optional.String**| the since commit hash to stream a diff between two arbitrary hashes | 
 **srcPath** | **optional.String**| the previous path to the file, if the file has been copied, moved or renamed | 
 **untilId** | **optional.String**| the until commit hash to stream a diff between two arbitrary hashes | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to &lt;code&gt;ignore-all&lt;/code&gt; | 
 **withComments** | **optional.Bool**| &lt;code&gt;true&lt;/code&gt; to embed comments in the diff (the default); otherwise, &lt;code&gt;false&lt;/code&gt;                      to stream the diff without comments | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff1234**
> string GetstreamDiff1234(ctx, commitId, projectKey, repositorySlug, optional)
streamDiff

Retrieve the diff between two provided revisions.  <p>  <strong>Note:</strong> This resource is currently <i>not paged</i>. The server will internally apply a hard cap  to the streamed lines, and it is not possible to request subsequent pages if that cap is exceeded. In the event  that the cap is reached, the diff will be cut short and one or more {@code truncated} flags will be set to  {@code true} on the {@code \"segments\"}, {@code \"hunks\"} and {@code \"diffs\"} properties, as well as the top-level  object, in the returned JSON response.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiff1234Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiff1234Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **autoSrcPath** | **optional.Bool**| {@code true} to automatically try to find the source path when it&#x27;s not provided,                       {@code false} otherwise. Requires the {@code path} to be provided. | [default to false]
 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **since** | **optional.String**| the base revision to diff from. If omitted the parent revision of the until revision is used | 
 **srcPath** | **optional.String**| the source path for the file, if it was copied, moved or renamed | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to {@code ignore-all} | 
 **withComments** | **optional.Bool**| {@code true} to embed comments in the diff (the default); otherwise {@code false}                       to stream the diff without comments | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamDiff12345**
> string GetstreamDiff12345(ctx, path, commitId, projectKey, repositorySlug, path_, optional)
streamDiff

Retrieve the diff between two provided revisions.  <p>  <strong>Note:</strong> This resource is currently <i>not paged</i>. The server will internally apply a hard cap  to the streamed lines, and it is not possible to request subsequent pages if that cap is exceeded. In the event  that the cap is reached, the diff will be cut short and one or more {@code truncated} flags will be set to  {@code true} on the {@code \"segments\"}, {@code \"hunks\"} and {@code \"diffs\"} properties, as well as the top-level  object, in the returned JSON response.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path to the file which should be diffed (optional) | 
  **commitId** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetstreamDiff12345Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamDiff12345Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------





 **autoSrcPath** | **optional.Bool**| {@code true} to automatically try to find the source path when it&#x27;s not provided,                       {@code false} otherwise. Requires the {@code path} to be provided. | [default to false]
 **contextLines** | **optional.Int32**| the number of context lines to include around added/removed lines in the diff | [default to -1]
 **since** | **optional.String**| the base revision to diff from. If omitted the parent revision of the until revision is used | 
 **srcPath** | **optional.String**| the source path for the file, if it was copied, moved or renamed | 
 **whitespace** | **optional.String**| optional whitespace flag which can be set to {@code ignore-all} | 
 **withComments** | **optional.Bool**| {@code true} to embed comments in the diff (the default); otherwise {@code false}                       to stream the diff without comments | [default to true]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamFiles**
> string GetstreamFiles(ctx, path, projectKey, repositorySlug, path_, optional)
streamFiles

Retrieve a page of files from particular directory of a repository. The search is done recursively, so all files  from any sub-directory of the specified directory will be returned.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the directory to list files for. | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiGetstreamFilesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetstreamFilesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **at** | **optional.String**| the commit ID or ref (e.g. a branch or tag) to list the files at.              If not specified the default branch will be used instead. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetstreamRaw**
> interface{} GetstreamRaw(ctx, path, projectKey, repositorySlug, path_)
streamRaw

Retrieve the raw content for a file path at a specified revision.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call  this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the file path to retrieve content from | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HasAllUserPermission**
> string HasAllUserPermission(ctx, permission, projectKey)
hasAllUserPermission

Check whether the specified permission is the default permission (granted to all users) for a project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **permission** | **string**| the permission to grant                        Available project permissions are:                        &lt;ul&gt;                            &lt;li&gt;PROJECT_READ&lt;/li&gt;                            &lt;li&gt;PROJECT_WRITE&lt;/li&gt;                            &lt;li&gt;PROJECT_ADMIN&lt;/li&gt;                        &lt;/ul&gt; | 
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListParticipants**
> string ListParticipants(ctx, pullRequestId, projectKey, repositorySlug)
listParticipants

Retrieves a page of the participants for a given pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Merge**
> string Merge(ctx, pullRequestId, projectKey, repositorySlug, optional)
merge

Merge the specified pull request.  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiMergeOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiMergeOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **version** | **optional.Int32**| the current version of the pull request. If the server&#x27;s version isn&#x27;t the same as the specified                 version the operation will fail. To determine the current version of the pull request it should be                 fetched from the server prior to this operation. Look for the &#x27;version&#x27; attribute in the returned                 JSON structure. | [default to -1]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ModifyAllUserPermission**
> interface{} ModifyAllUserPermission(ctx, permission, projectKey, optional)
modifyAllUserPermission

Grant or revoke a project permission to all users, i.e. set the default permission.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **permission** | **string**| the permission to grant                        Available project permissions are:                        &lt;ul&gt;                            &lt;li&gt;PROJECT_READ&lt;/li&gt;                            &lt;li&gt;PROJECT_WRITE&lt;/li&gt;                            &lt;li&gt;PROJECT_ADMIN&lt;/li&gt;                        &lt;/ul&gt; | 
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiModifyAllUserPermissionOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiModifyAllUserPermissionOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **allow** | **optional.Bool**| &lt;em&gt;true&lt;/em&gt; to grant the specified permission to all users, or &lt;em&gt;false&lt;/em&gt; to revoke it | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostcreateComment**
> string PostcreateComment(ctx, body, projectKey, repositorySlug, pullRequestId)
createComment

Add a new comment.  <p>  Comments can be added in a few places by setting different attributes:  <p>  General pull request comment:   <pre>      {          \"text\": \"An insightful general comment on a pull request.\"      }      </pre>   Reply to a comment:   <pre>      {          \"text\": \"A measured reply.\",          \"parent\": {              \"id\": 1          }      }      </pre>   General file comment:   <pre>      {          \"text\": \"An insightful general comment on a file.\",          \"anchor\": {              \"diffType\": \"RANGE\",              \"fromHash\": \"6df3858eeb9a53a911cd17e66a9174d44ffb02cd\",              \"path\": \"path/to/file\",              \"srcPath\": \"path/to/file\",              \"toHash\": \"04c7c5c931b9418ca7b66f51fe934d0bd9b2ba4b\"          }      }      </pre>   File line comment:   <pre>      {          \"text\": \"A pithy comment on a particular line within a file.\",          \"anchor\": {              \"diffType\": \"COMMIT\",              \"line\": 1,              \"lineType\": \"CONTEXT\",              \"fileType\": \"FROM\",              \"fromHash\": \"6df3858eeb9a53a911cd17e66a9174d44ffb02cd\",              \"path\": \"path/to/file\",              \"srcPath\": \"path/to/file\",              \"toHash\": \"04c7c5c931b9418ca7b66f51fe934d0bd9b2ba4b\"          }      }      </pre>  <p>  For file and line comments, 'path' refers to the path of the file to which the comment should be applied and  'srcPath' refers to the path the that file used to have (only required for copies and moves). Also,  fromHash and toHash refer to the sinceId / untilId (respectively) used to produce the diff on which the comment  was added. Finally diffType refers to the type of diff the comment was added on. For backwards compatibility  purposes if no diffType is provided and no fromHash/toHash pair is provided the diffType will be resolved to  'EFFECTIVE'. In any other cases the diffType is REQUIRED.  <p>  For line comments, 'line' refers to the line in the diff that the comment should apply to. 'lineType' refers to  the type of diff hunk, which can be:  <ul>      <li>'ADDED' - for an added line;</li>      <li>'REMOVED' - for a removed line; or</li>      <li>'CONTEXT' - for a line that was unmodified but is in the vicinity of the diff.</li>  </ul>  'fileType' refers to the file of the diff to which the anchor should be attached - which is of relevance when  displaying the diff in a side-by-side way. Currently the supported values are:  <ul>      <li>'FROM' - the source file of the diff</li>      <li>'TO' - the destination file of the diff</li>  </ul>  If the current user is not a participant the user is added as a watcher of the pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateCommentRequest**](CreateCommentRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostupdatePullRequestSettings**
> string PostupdatePullRequestSettings(ctx, body, scmId, projectKey)
updatePullRequestSettings

Update the pull request merge strategy configuration for this project and SCM.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the context repository to call this  resource.  <p>  Only the strategies provided will be enabled, the default must be set and included in the set of strategies.  <p>  An explicitly set pull request merge strategy configuration can be deleted by POSTing a document with  an empty \"mergeConfig\" attribute. i.e:  <pre>  {      \"mergeConfig\": {      }  }  </pre>  Upon completion of this request, the effective configuration will be the configuration explicitly set for  the SCM, or if no such explicit configuration is set then the default configuration will be used.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdatePullRequestSettingsRequest**](UpdatePullRequestSettingsRequest.md)|  | 
  **scmId** | **string**| the SCM to get strategies for | 
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostuploadAvatar**
> string PostuploadAvatar(ctx, userSlug)
uploadAvatar

Update the avatar for the user with the supplied <strong>slug</strong>.  <p>  This resource accepts POST multipart form data, containing a single image in a form-field named 'avatar'.  <p>  There are configurable server limits on both the dimensions (1024x1024 pixels by default) and uploaded  file size (1MB by default). Several different image formats are supported, but <strong>PNG</strong> and  <strong>JPEG</strong> are preferred due to the file size limit.  <p>  This resource has Cross-Site Request Forgery (XSRF) protection. To allow the request to  pass the XSRF check the caller needs to send an <code>X-Atlassian-Token</code> HTTP header with the  value <code>no-check</code>.  <p>  An example <a href=\"http://curl.haxx.se/\">curl</a> request to upload an image name 'avatar.png' would be:  <pre>  curl -X POST -u username:password -H \"X-Atlassian-Token: no-check\" http://example.com/rest/api/latest/users/jdoe/avatar.png -F avatar=@avatar.png  </pre>  <p>  Users are always allowed to update their own avatar. To update someone else's avatar the authenticated user must  have global <strong>ADMIN</strong> permission, or global <strong>SYS_ADMIN</strong> permission to update a  <strong>SYS_ADMIN</strong> user's avatar.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userSlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Postwatch**
> string Postwatch(ctx, projectKey, repositorySlug, pullRequestId)
watch

Add the authenticated user as a watcher for the specified pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Postwatch1**
> string Postwatch1(ctx, projectKey, repositorySlug)
watch

Add the authenticated user as a watcher for the specified repository.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Preview**
> string Preview(ctx, body)
preview

Preview generated HTML for the given markdown content.  <p>  Only authenticated users may call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**PreviewRequest**](PreviewRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PreviewExport**
> string PreviewExport(ctx, body)
previewExport

Enumerates the projects and repositories that would be exported for a given export request.   <p>All affected repositories will be enumerated explicitly, and while projects are listed as individual items in  responses from this endpoint, their presence does not imply that all their repositories are included.   <p>While this endpoint can be used to verify that all selectors in the request apply as intended, it should be  noted that a subsequent, actual export might contain a different set of repositories, as they might have been  added or deleted in the meantime.   <p>Note that the overall response from this endpoint can become very large when a lot of repositories end up in  the selection. This is why the server is streaming the response while it is being generated (as opposed to  creating it in memory and then sending it all at once) and it can be consumed in a streaming way, too.   <p>Also, due to the potential size of the response, projects and repositories are listed with fewer details than  in other REST responses.   <p>For a more detailed description of selectors, see the endpoint documentation for starting an export.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**PreviewExportRequest**](PreviewExportRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PutenableHook**
> interface{} PutenableHook(ctx, hookKey, projectKey, optional)
enableHook

Enable a repository hook for this project and optionally apply new configuration.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.  <p>  A JSON document may be provided to use as the settings for the hook. These structure and validity of  the document is decided by the plugin providing the hook.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiPutenableHookOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiPutenableHookOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **contentLength** | **optional.Int32**|  | [default to 0]

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PutsetPermissionForGroups**
> string PutsetPermissionForGroups(ctx, optional)
setPermissionForGroups

Promote or demote a user's global permission level. Available global permissions are:  <ul>      <li>LICENSED_USER</li>      <li>PROJECT_CREATE</li>      <li>ADMIN</li>      <li>SYS_ADMIN</li>  </ul>  See the <a href=\"https://confluence.atlassian.com/display/BitbucketServer/Global+permissions\">Bitbucket Server  documentation</a> for a detailed explanation of what each permission entails.  <p>  The authenticated user must have:  <ul>      <li><strong>ADMIN</strong> permission or higher; and</li>      <li>the permission they are attempting to grant or higher; and</li>      <li>greater or equal permissions than the current permission level of the group (a user may not demote the      permission level of a group with higher permissions than them)</li>  </ul>  to call this resource. In addition, a user may not demote a group's permission level if their own permission  level would be reduced as a result.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiPutsetPermissionForGroupsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiPutsetPermissionForGroupsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **permission** | **optional.String**| the permission to grant | 
 **name** | **optional.String**| the names of the groups | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PutsetPermissionForUsers**
> string PutsetPermissionForUsers(ctx, optional)
setPermissionForUsers

Promote or demote the global permission level of a user. Available global permissions are:  <ul>      <li>LICENSED_USER</li>      <li>PROJECT_CREATE</li>      <li>ADMIN</li>      <li>SYS_ADMIN</li>  </ul>  See the <a href=\"https://confluence.atlassian.com/display/BitbucketServer/Global+permissions\">Bitbucket Server  documentation</a> for a detailed explanation of what each permission entails.  <p>  The authenticated user must have:  <ul>      <li><strong>ADMIN</strong> permission or higher; and</li>      <li>the permission they are attempting to grant; and</li>      <li>greater or equal permissions than the current permission level of the user (a user may not demote the      permission level of a user with higher permissions than them)</li>  </ul>  to call this resource. In addition, a user may not demote their own permission level.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiPutsetPermissionForUsersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiPutsetPermissionForUsersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the names of the users | 
 **permission** | **optional.String**| the permission to grant | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PutsetSettings**
> interface{} PutsetSettings(ctx, body, hookKey, projectKey)
setSettings

Modify the settings for a repository hook for this project.  <p>  The service will reject any settings which are too large, the current limit is 32KB once serialized.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.  <p>  A JSON document can be provided to use as the settings for the hook. These structure and validity of the document  is decided by the plugin providing the hook.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetSettingsRequest**](SetSettingsRequest.md)|  | 
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Putupdate**
> string Putupdate(ctx, body, pullRequestId, projectKey, repositorySlug)
update

Update the title, description, reviewers or destination branch of an existing pull request.  <p>  <strong>Note:</strong> the <em>reviewers</em> list may be updated using this resource. However the  <em>author</em> and <em>participants</em> list may not.  <p>  The authenticated user must either:  <ul>      <li>be the author of the pull request and have the <strong>REPO_READ</strong> permission for the repository      that this pull request targets; or</li>      <li>have the <strong>REPO_WRITE</strong> permission for the repository that this pull request targets</li>  </ul>  to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateRequest**](UpdateRequest.md)|  | 
  **pullRequestId** | **int64**| the ID of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PutupdateComment**
> string PutupdateComment(ctx, body, commentId, projectKey, repositorySlug, pullRequestId)
updateComment

Update the text of a comment. Only the user who created a comment may update it.  <p>  <strong>Note:</strong> the supplied supplied JSON object must contain a <code>version</code> that must match the  server's version of the comment or the update will fail. To determine the current version of  the comment, the comment should be fetched from the server prior to the update. Look for the  'version' attribute in the returned JSON structure.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateCommentRequest**](UpdateCommentRequest.md)|  | 
  **commentId** | **int64**| the id of the comment to retrieve | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **pullRequestId** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RemoveGroupFromUser**
> string RemoveGroupFromUser(ctx, body)
removeGroupFromUser

Remove a user from a group. This is very similar to <code>groups/remove-user</code>, but with the <em>context</em>  and <em>itemName</em> attributes of the supplied request entity reversed. On the face of it this may appear  redundant, but it facilitates a specific UI component in Stash.  <p>  In the request entity, the <em>context</em> attribute is the user and the <em>itemName</em> is the group.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**RemoveGroupFromUserRequest**](RemoveGroupFromUserRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RemoveLabel**
> string RemoveLabel(ctx, labelName, projectKey, repositorySlug)
removeLabel

Remove label that is applied to the given repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **labelName** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RemoveUserFromGroup**
> string RemoveUserFromGroup(ctx, body)
removeUserFromGroup

<strong>Deprecated since 2.10</strong>. Use /rest/users/remove-groups instead.  <p>  Remove a user from a group.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.  <p>  In the request entity, the <em>context</em> attribute is the group and the <em>itemName</em> is the user.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**RemoveUserFromGroupRequest**](RemoveUserFromGroupRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RenameUser**
> string RenameUser(ctx, body)
renameUser

Rename a user.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**RenameUserRequest**](RenameUserRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Reopen**
> string Reopen(ctx, pullRequestId, projectKey, repositorySlug, optional)
reopen

Re-open a declined pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiReopenOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiReopenOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **version** | **optional.Int32**| the current version of the pull request. If the server&#x27;s version isn&#x27;t the same as the specified                 version the operation will fail. To determine the current version of the pull request it should be                 fetched from the server prior to this operation. Look for the &#x27;version&#x27; attribute in the returned                 JSON structure. | [default to -1]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RetryCreateRepository**
> string RetryCreateRepository(ctx, projectKey, repositorySlug)
retryCreateRepository

If a create or fork operation fails, calling this method will clean up the broken repository and try again. The  repository must be in an INITIALISATION_FAILED state.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RevokePermissionsForGroup**
> string RevokePermissionsForGroup(ctx, projectKey, repositorySlug, optional)
revokePermissionsForGroup

Revoke all permissions for the specified repository for a group.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.  <p>  In addition, a user may not revoke a group's permissions if it will reduce their own permission level.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiRevokePermissionsForGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiRevokePermissionsForGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **name** | **optional.String**| the name of the group | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **RevokePermissionsForUser**
> string RevokePermissionsForUser(ctx, projectKey, repositorySlug, optional)
revokePermissionsForUser

Revoke all permissions for the specified repository for a user.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource.  <p>  In addition, a user may not revoke their own repository permissions if they do not have a higher  project or global permission.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiRevokePermissionsForUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiRevokePermissionsForUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **name** | **optional.String**| the name of the user | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Search**
> string Search(ctx, projectKey, repositorySlug, optional)
search

Retrieve a page of participant users for all the pull requests to or from the specified repository.  <p>  <p>  Optionally clients can specify following filters.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiSearchOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiSearchOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **direction** | **optional.String**| (optional, defaults to &lt;strong&gt;INCOMING&lt;/strong&gt;) the direction relative to the specified                   repository. Either &lt;strong&gt;INCOMING&lt;/strong&gt; or &lt;strong&gt;OUTGOING&lt;/strong&gt;. | [default to incoming]
 **filter** | **optional.String**| (optional) return only users, whose username, name or email address &lt;i&gt;contain&lt;/i&gt;                   the {@code filter} value | 
 **role** | **optional.String**| (optional) The role associated with the pull request participant.                   This must be one of {@code AUTHOR}, {@code REVIEWER}, or{@code PARTICIPANT} | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetDefaultBranch**
> string SetDefaultBranch(ctx, body, projectKey, repositorySlug)
setDefaultBranch

Update the default branch of a repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetDefaultBranchRequest**](SetDefaultBranchRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetLevel**
> string SetLevel(ctx, levelName, loggerName)
setLevel

Set the current log level for a given logger.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **levelName** | **string**| the level to set the logger to. Either TRACE, DEBUG, INFO, WARN or ERROR | 
  **loggerName** | **string**| the name of the logger. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetMailConfig**
> string SetMailConfig(ctx, body)
setMailConfig

Updates the mail configuration   The authenticated user must have the <strong>SYS_ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetMailConfigRequest**](SetMailConfigRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetMergeConfig**
> string SetMergeConfig(ctx, body, scmId)
setMergeConfig

Update the pull request merge strategies for the context repository.  <p>  The authenticated user must have <strong>ADMIN</strong> permission for the context repository to call this  resource.  <p>  Only the strategies provided will be enabled, only one may be set to default  <p>  An explicitly set pull request merge strategy configuration can be deleted by POSTing a document with  an empty \"mergeConfig\" attribute. i.e:  <pre>  {      \"mergeConfig\": {      }  }  </pre>  Upon completion of this request, the effective configuration will be the default configuration.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetMergeConfigRequest**](SetMergeConfigRequest.md)|  | 
  **scmId** | **string**| the id of the scm to get strategies for | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetPermissionForGroup**
> string SetPermissionForGroup(ctx, projectKey, repositorySlug, optional)
setPermissionForGroup

Promote or demote a group's permission level for the specified repository. Available repository permissions are:  <ul>      <li>REPO_READ</li>      <li>REPO_WRITE</li>      <li>REPO_ADMIN</li>  </ul>  See the <a href=\"https://confluence.atlassian.com/display/BitbucketServer/Using+repository+permissions\">Bitbucket  Server documentation</a> for a detailed explanation of what each permission entails.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource. In addition, a user may not demote a group's permission level if their  own permission level would be reduced as a result.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiSetPermissionForGroupOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiSetPermissionForGroupOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **permission** | **optional.String**| the permission to grant | 
 **name** | **optional.String**| the names of the groups | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetPermissionForGroups**
> string SetPermissionForGroups(ctx, projectKey, optional)
setPermissionForGroups

Promote or demote a group's permission level for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource. In addition, a user may not demote a group's permission level if their  own permission level would be reduced as a result.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiSetPermissionForGroupsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiSetPermissionForGroupsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **permission** | **optional.String**| The permission to grant.                        See the [permissions documentation](https://confluence.atlassian.com/display/BitbucketServer/Using+project+permissions)                        for a detailed explanation of what each permission entails.                        Available project permissions are:                        &lt;ul&gt;                            &lt;li&gt;PROJECT_READ&lt;/li&gt;                            &lt;li&gt;PROJECT_WRITE&lt;/li&gt;                            &lt;li&gt;PROJECT_ADMIN&lt;/li&gt;                        &lt;/ul&gt; | 
 **name** | **optional.String**| the names of the groups | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetPermissionForUser**
> string SetPermissionForUser(ctx, projectKey, repositorySlug, optional)
setPermissionForUser

Promote or demote a user's permission level for the specified repository. Available repository permissions are:  <ul>      <li>REPO_READ</li>      <li>REPO_WRITE</li>      <li>REPO_ADMIN</li>  </ul>  See the <a href=\"https://confluence.atlassian.com/display/BitbucketServer/Using+repository+permissions\">Bitbucket  Server documentation</a> for a detailed explanation of what each permission entails.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository or a higher  project or global permission to call this resource. In addition, a user may not reduce their own permission level unless  they have a project or global permission that already implies that permission.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiSetPermissionForUserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiSetPermissionForUserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **name** | **optional.String**| the names of the users | 
 **permission** | **optional.String**| the permission to grant | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetPermissionForUsers**
> interface{} SetPermissionForUsers(ctx, projectKey, optional)
setPermissionForUsers

Promote or demote a user's permission level for the specified project.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project or a higher  global permission to call this resource. In addition, a user may not reduce their own permission level unless  they have a global permission that already implies that permission.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
 **optional** | ***DefaultApiSetPermissionForUsersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiSetPermissionForUsersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **name** | **optional.String**| the names of the users | 
 **permission** | **optional.String**| the permission to grant. See the [permissions documentation](https://confluence.atlassian.com/display/BitbucketServer/Using+project+permissions)                        for a detailed explanation of what each permission entails.                        Available project permissions are:                        &lt;ul&gt;                            &lt;li&gt;PROJECT_READ&lt;/li&gt;                            &lt;li&gt;PROJECT_WRITE&lt;/li&gt;                            &lt;li&gt;PROJECT_ADMIN&lt;/li&gt;                        &lt;/ul&gt; | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetRootLevel**
> string SetRootLevel(ctx, levelName)
setRootLevel

Set the current log level for the root logger.  <p>  The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **levelName** | **string**| the level to set the logger to. Either TRACE, DEBUG, INFO, WARN or ERROR | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetSenderAddress**
> string SetSenderAddress(ctx, body)
setSenderAddress

Updates the server email address   The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetSenderAddressRequest**](SetSenderAddressRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SetSettings**
> interface{} SetSettings(ctx, body, hookKey, projectKey, repositorySlug)
setSettings

Modify the settings for a repository hook for this repository.  <p>  The service will reject any settings which are too large, the current limit is 32KB once serialized.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.  <p>  A JSON document can be provided to use as the settings for the hook. These structure and validity of the document  is decided by the plugin providing the hook.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SetSettingsRequest**](SetSettingsRequest.md)|  | 
  **hookKey** | **string**|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StartExport**
> string StartExport(ctx, body)
startExport

<p>Starts a background job that exports the selected repositories.   <p>Only 2 concurrent exports are supported <em>per cluster node</em>. If a request ends up on a node that is already  running that many export jobs, the request will be rejected and an error returned.   <p>The response includes a description of the job that has been started, and its ID can be used to query  these details again, including the current progress, warnings and errors that occurred while processing the job,  and to interrupt and cancel the execution of this job.   <p>The request to start an export is similar to the one for previewing an export. Additionally, it accepts an optional  parameter, <tt>exportLocation</tt>, which can be used to specify a <em>relative</em> path within  <tt>data/migration/export</tt> in the shared home directory. No locations outside of that directory will be  accepted for exports.   <p>There are essentially three ways to select repositories for export. Regardless of which you use, a few  general rules apply:  <ul>      <li>You can supply a list of selectors. The selection will be additive.</li>      <li>Repositories that are selected more than once due to overlapping selectors will be de-duplicated and      effectively exported only once.</li>      <li>For every selected repository, its full fork hierarchy will be considered selected, even if parts of that      hierarchy would otherwise not be matched by the provided selectors. For example, when you explicitly      select a single repository only, but that repository is a fork, then its origin will be exported (and      eventually imported), too.</li>  </ul>   <p>Now, a single repository can be selected like this:   <pre>      {         \"projectKey\": \"PRJ\",         \"slug\": \"my-repo\"      }      </pre>   <p>Second, all repositories in a specific project can be selected like this:   <pre>      {         \"projectKey\": \"PRJ\",         \"slug\": *\"      }      </pre>   <p>And third, all projects and repositories in the system would be selected like this:   <pre>      {         \"projectKey\": \"*\",         \"slug\": *\"      }      </pre>   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**StartExportRequest**](StartExportRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StartImport**
> string StartImport(ctx, body)
startImport

Starts a background job that imports the specified archive.   <p>Only 1 import at a time is supported <em>per cluster</em>. If another request is made while an import is already  running, the request will be rejected and an error returned.   <p>The path in the request must point to a valid archive file. It can be either absolute, or will be interpreted  as relative to the <tt>data/migration/import</tt> directory in the shared home directory.   <p>The authenticated user must have <strong>ADMIN</strong> permission or higher to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**StartImportRequest**](StartImportRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Stream**
> string Stream(ctx, projectKey, repositorySlug, optional)
stream

Streams files in the requested <code>path</code> with the last commit to modify each file. Commit modifications  are traversed starting from the <code>at</code> commit or, if not specified, from the tip of the default branch.  <p>  Unless the repository is public, the authenticated user must have <b>REPO_READ</b> access to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **at** | **optional.String**| the commit to use as the starting point when listing files and calculating modifications | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamChanges**
> string StreamChanges(ctx, projectKey, repositorySlug, optional)
streamChanges

Gets the file changes available in the {@code from} commit but not in the {@code to} commit.  <p>  If either the {@code from} or {@code to} commit are not specified, they will be replaced by the  default branch of their containing repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiStreamChangesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamChangesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **from** | **optional.String**| the source commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **to** | **optional.String**| the target commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **fromRepo** | **optional.String**| an optional parameter specifying the source repository containing the source commit                  if that commit is not present in the current repository; the repository can be specified                  by either its ID &lt;em&gt;fromRepo&#x3D;42&lt;/em&gt; or by its project key plus its repo slug separated by                  a slash: &lt;em&gt;fromRepo&#x3D;projectKey/repoSlug&lt;/em&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamCommits**
> string StreamCommits(ctx, projectKey, repositorySlug, optional)
streamCommits

Gets the commits accessible from the {@code from} commit but not in the {@code to} commit.  <p>  If either the {@code from} or {@code to} commit are not specified, they will be replaced by the  default branch of their containing repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiStreamCommitsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamCommitsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **from** | **optional.String**| the source commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **to** | **optional.String**| the target commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **fromRepo** | **optional.String**| an optional parameter specifying the source repository containing the source commit                  if that commit is not present in the current repository; the repository can be specified                  by either its ID &lt;em&gt;fromRepo&#x3D;42&lt;/em&gt; or by its project key plus its repo slug separated by                  a slash: &lt;em&gt;fromRepo&#x3D;projectKey/repoSlug&lt;/em&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamDiff**
> string StreamDiff(ctx, path, projectKey, repositorySlug, path_, optional)
streamDiff

Gets a diff of the changes available in the {@code from} commit but not in the {@code to} commit.  <p>  If either the {@code from} or {@code to} commit are not specified, they will be replaced by the  default branch of their containing repository.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **path** | **string**| the path to the file to diff (optional) | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
  **path_** | **string**|  | 
 **optional** | ***DefaultApiStreamDiffOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamDiffOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **from** | **optional.String**| the source commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **to** | **optional.String**| the target commit (can be a partial/full commit ID or qualified/unqualified ref name) | 
 **fromRepo** | **optional.String**| an optional parameter specifying the source repository containing the source commit                  if that commit is not present in the current repository; the repository can be specified                  by either its ID &lt;em&gt;fromRepo&#x3D;42&lt;/em&gt; or by its project key plus its repo slug separated by                  a slash: &lt;em&gt;fromRepo&#x3D;projectKey/repoSlug&lt;/em&gt; | 
 **srcPath** | **optional.String**|  | 
 **contextLines** | **optional.Int32**| an optional number of context lines to include around each added or removed lines in the diff | [default to -1]
 **whitespace** | **optional.String**| an optional whitespace flag which can be set to &lt;code&gt;ignore-all&lt;/code&gt; | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamFiles**
> string StreamFiles(ctx, projectKey, repositorySlug, optional)
streamFiles

Retrieve a page of files from particular directory of a repository. The search is done recursively, so all files  from any sub-directory of the specified directory will be returned.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiStreamFilesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamFilesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **at** | **optional.String**| the commit ID or ref (e.g. a branch or tag) to list the files at.              If not specified the default branch will be used instead. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamRaw**
> interface{} StreamRaw(ctx, projectKey, repositorySlug)
streamRaw

Retrieve the raw content for a file path at a specified revision.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the specified repository to call  this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **TestWebhook**
> string TestWebhook(ctx, projectKey, repositorySlug, optional)
testWebhook

Test connectivity to a specific endpoint.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiTestWebhookOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiTestWebhookOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **url** | **optional.String**| the url in which to connect to | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UnassignParticipantRole**
> string UnassignParticipantRole(ctx, pullRequestId, projectKey, repositorySlug, optional)
unassignParticipantRole

Unassigns a participant from the REVIEWER role they may have been given in a pull request.  <p>  If the participant has no explicit role this method has no effect.  <p>  Afterwards, the user will still remain a participant in the pull request but their role will be reduced to  PARTICIPANT. This is because once made a participant of a pull request,  a user will forever remain a participant. Only their role may be altered.  <p>  The authenticated user must have <strong>REPO_WRITE</strong> permission for the repository that this pull request  targets to call this resource.  <p>  <strong>Deprecated since 4.2</strong>. Use  /rest/api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug}  instead.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 
 **optional** | ***DefaultApiUnassignParticipantRoleOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiUnassignParticipantRoleOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **username** | **optional.String**| the participant&#x27;s user name | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Unwatch**
> string Unwatch(ctx, commitId, projectKey, repositorySlug)
unwatch

Remove the authenticated user as a watcher for the specified commit.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository containing the commit  to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Update**
> string Update(ctx, body)
update

Decodes the provided encoded license and sets it as the active license. If no license was provided, a 400 is  returned. If the license cannot be decoded, or cannot be applied, a 409 is returned. Some possible reasons a  license may not be applied include:  <ul>      <li>It is for a different product</li>      <li>It is already expired</li>  </ul>  Otherwise, if the license is updated successfully, details for the new license are returned with a 200 response.  <p>  <b>Warning</b>: It is possible to downgrade the license during update, applying a license with a lower number  of permitted users. If the number of currently-licensed users exceeds the limits of the new license, pushing  will be disabled until the licensed user count is brought into compliance with the new license.  <p>  The authenticated user must have <b>SYS_ADMIN</b> permission. <b>ADMIN</b> users may <i>view</i> the current  license details, but they may not <i>update</i> the license.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateRequest**](UpdateRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateComment**
> string UpdateComment(ctx, body, commentId, commitId, projectKey, repositorySlug)
updateComment

Update the text of a comment. Only the user who created a comment may update it.  <p>  <strong>Note:</strong> the supplied supplied JSON object must contain a <code>version</code> that must match  the server's version of the comment or the update will fail. To determine the current version of the comment,  the comment should be fetched from the server prior to the update. Look for the 'version' attribute in the  returned JSON structure.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that the commit  is in to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateCommentRequest**](UpdateCommentRequest.md)|  | 
  **commentId** | **int64**| the ID of the comment to retrieve | 
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateProject**
> string UpdateProject(ctx, body, projectKey)
updateProject

Update the project matching the <strong>projectKey</strong> supplied in the resource path.  <p>  To include a custom avatar for the updated project, the project definition should contain an additional attribute  with the key <code>avatar</code> and the value a data URI containing Base64-encoded image data. The URI should be  in the following format:  <code>      data:(content type, e.g. image/png);base64,(data)  </code>  If the data is not Base64-encoded, or if a character set is defined in the URI, or the URI is otherwise invalid,  <em>project creation will fail</em>.  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateProjectRequest**](UpdateProjectRequest.md)|  | 
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdatePullRequestSettings**
> string UpdatePullRequestSettings(ctx, body, projectKey, repositorySlug)
updatePullRequestSettings

Update the pull request settings for the context repository.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the context repository to call this  resource.  <p>  This resource will call all RestFragments that are registered with the key  <strong>bitbucket.repository.settings.pullRequests</strong>. If any fragment fails validations by returning a  non-empty Map of errors, then no fragments will execute.  <p>  Only the settings that should be updated need to be included in the request.  <p>  The property keys for the settings that are bundled with the application are  <ul>      <li>mergeConfig - the merge strategy configuration for pull requests</li>      <li>requiredApprovers - (Deprecated, please use com.atlassian.bitbucket.server.bundled-hooks.requiredApproversMergeHook instead) the number of approvals required on a pull request for it to be mergeable, or 0 to disable the merge check</li>      <li>com.atlassian.bitbucket.server.bundled-hooks.requiredApproversMergeHook - a json map containing the keys 'enabled' (a boolean to enable or disable this merge check) and 'count' (an integer to set the number of required approvals)</li>      <li>requiredAllApprovers - whether or not all approvers must approve a pull request for it to be mergeable</li>      <li>requiredAllTasksComplete - whether or not all tasks on a pull request need to be completed for it to be mergeable</li>      <li>requiredSuccessfulBuilds - (Deprecated, please use com.atlassian.bitbucket.server.bitbucket-build.requiredBuildsMergeCheck instead) the number of successful builds on a pull request for it to be mergeable, or 0 to disable the merge check</li>      <li>com.atlassian.bitbucket.server.bitbucket-build.requiredBuildsMergeCheck - a json map containing the keys 'enabled' (a boolean to enable or disable this merge check) and 'count' (an integer to set the number of required builds)</li>  </ul>  <strong>Merge strategy configuration deletion:</strong>  <p>  An explicitly set pull request merge strategy configuration can be deleted by POSTing a document with an empty  \"mergeConfig\" attribute. i.e:  <pre>  {      \"mergeConfig\": {      }  }  </pre>  Upon completion of this request, the effective configuration will be:  <ul>      <li>The configuration set for this repository's SCM type as set at the project level, if present, otherwise</li>      <li>the configuration set for this repository's SCM type as set at the instance level, if present, otherwise</li>      <li>the default configuration for this repository's SCM type</li>  <ul>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdatePullRequestSettingsRequest**](UpdatePullRequestSettingsRequest.md)|  | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateRepository**
> string UpdateRepository(ctx, body, projectKey, repositorySlug)
updateRepository

Update the repository matching the <strong>repositorySlug</strong> supplied in the resource path.  <p>  The repository's slug is derived from its name. If the name changes the slug may also change.  <p>  This API can be used to move the repository to a different project by setting the new project in the request,  example: {@code {\"project\":{\"key\":\"NEW_KEY\"}}} .  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateRepositoryRequest**](UpdateRepositoryRequest.md)|  | 
  **projectKey** | **string**| the parent project key | 
  **repositorySlug** | **string**| the repository slug | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateSettings**
> string UpdateSettings(ctx, body, userSlug)
updateSettings

Update the entries of a map of user setting key/values for a specific user identified by the user slug.  <p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateSettingsRequest**](UpdateSettingsRequest.md)|  | 
  **userSlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateStatus**
> string UpdateStatus(ctx, body, userSlug, pullRequestId, projectKey, repositorySlug)
updateStatus

Change the current user's status for a pull request. Implicitly adds the user as a participant if they are not  already. If the current user is the author, this method will fail.  <p>  The possible values for {@code status} are <strong>UNAPPROVED</strong>, <strong>NEEDS_WORK</strong>, or  <strong>APPROVED</strong>.  <p>  If the new {@code status} is <strong>NEEDS_WORK</strong> or <strong>APPROVED</strong> then the  {@code lastReviewedCommit} for the participant will be updated to the latest commit of the source branch of the  pull request.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateStatusRequest**](UpdateStatusRequest.md)|  | 
  **userSlug** | **string**| the slug for the user changing their status | 
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateTask**
> string UpdateTask(ctx, body, taskId)
updateTask

Update a existing task.  <p>  As of Stash 3.3, only the state and text of a task can be updated.  <p>  Updating the state of a task is allowed for any user having <em>READ</em> access to the repository.  However only the task's creator, the context's author or an admin of the context's repository can update the  task's text. (For a pull request task, those are the task's creator, the pull request's author or an admin on the  repository containing the pull request). Additionally the task's text cannot be updated if it has been resolved.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateTaskRequest**](UpdateTaskRequest.md)|  | 
  **taskId** | **int64**| the id identifying the task to delete | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserDetails**
> string UpdateUserDetails(ctx, body)
updateUserDetails

Update a user's details.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserDetailsRequest**](UpdateUserDetailsRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserDetails1**
> string UpdateUserDetails1(ctx, body)
updateUserDetails1

Update the currently authenticated user's details. The update will always be applied to the currently  authenticated user.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserDetailsRequest**](UpdateUserDetailsRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserPassword**
> string UpdateUserPassword(ctx, body)
updateUserPassword

Update a user's password.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource, and may not update  the password of a user with greater permissions than themselves.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserPasswordRequest**](UpdateUserPasswordRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserPassword1**
> string UpdateUserPassword1(ctx, body)
updateUserPassword1

Update the currently authenticated user's password.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserPasswordRequest**](UpdateUserPasswordRequest.md)|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateWebhook**
> string UpdateWebhook(ctx, body, webhookId, projectKey, repositorySlug)
updateWebhook

Update an existing webhook.  <p>  The authenticated user must have <strong>REPO_ADMIN</strong> permission for the specified repository to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateWebhookRequest**](UpdateWebhookRequest.md)|  | 
  **webhookId** | **int32**| the existing webhook id | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UploadAvatar**
> string UploadAvatar(ctx, projectKey)
uploadAvatar

Update the avatar for the project matching the supplied <strong>projectKey</strong>.  <p>  This resource accepts POST multipart form data, containing a single image in a form-field named 'avatar'.  <p>  There are configurable server limits on both the dimensions (1024x1024 pixels by default) and uploaded file size  (1MB by default). Several different image formats are supported, but <strong>PNG</strong> and  <strong>JPEG</strong> are preferred due to the file size limit.  <p>  This resource has Cross-Site Request Forgery (XSRF) protection. To allow the request to  pass the XSRF check the caller needs to send an <code>X-Atlassian-Token</code> HTTP header with the  value <code>no-check</code>.  <p>  An example <a href=\"http://curl.haxx.se/\">curl</a> request to upload an image name 'avatar.png' would be:  <pre>  curl -X POST -u username:password -H \"X-Atlassian-Token: no-check\" http://example.com/rest/api/1.0/projects/STASH/avatar.png -F avatar=@avatar.png  </pre>  <p>  The authenticated user must have <strong>PROJECT_ADMIN</strong> permission for the specified project to call this  resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **projectKey** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ValidateErasable**
> string ValidateErasable(ctx, optional)
validateErasable

Validate if a user can be erased.  <p>  A username is only valid for erasure if it exists as the username of a deleted user. This endpoint will return  an appropriate error response if the supplied username is invalid for erasure.  <p>  This endpoint does <strong>not</strong> perform the actual user erasure, and will not modify the application in  any way.  <p>  The authenticated user must have the <strong>ADMIN</strong> permission to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiValidateErasableOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiValidateErasableOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **optional.String**| the username of the user to validate erasability for. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Watch**
> string Watch(ctx, commitId, projectKey, repositorySlug)
watch

Add the authenticated user as a watcher for the specified commit.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository containing the commit  to call this resource.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **commitId** | **string**| the &lt;i&gt;full {@link Commit#getId() ID}&lt;/i&gt; of the commit within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **WithdrawApproval**
> string WithdrawApproval(ctx, pullRequestId, projectKey, repositorySlug)
withdrawApproval

Remove approval from a pull request as the current user. This does not remove the user as a participant.  <p>  The authenticated user must have <strong>REPO_READ</strong> permission for the repository that this pull request  targets to call this resource.  <p>  <strong>Deprecated since 4.2</strong>. Use  /rest/api/1.0/projects/{projectKey}/repos/{repositorySlug}/pull-requests/{pullRequestId}/participants/{userSlug} instead

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pullRequestId** | **int64**| the id of the pull request within the repository | 
  **projectKey** | **string**|  | 
  **repositorySlug** | **string**|  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

