---
title: BookableResourceAssociation - Common Data Model | Microsoft Docs
description: This describes the BookableResourceAssociation entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Bookable Resource Association

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/BookableResourceAssociation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/BookableResourceAssociation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[bookableresourceassociationId](#bookableresourceassociationId)|Unique identifier for entity instances|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[stateCode](#stateCode)|Status of the Bookable Resource Association|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[stateCode_display](#stateCode_display)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[statusCode](#statusCode)|Reason for the status of the Bookable Resource Association|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[statusCode_display](#statusCode_display)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[name](#name)|The name of the custom entity.|<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[fromDate](#fromDate)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[resource1](#resource1)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[resource2](#resource2)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[toDate](#toDate)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[type](#type)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|
|[type_display](#type_display)||<a href="BookableResourceAssociation.md" target="_blank">scheduling/BookableResourceAssociation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableresourceassociationId name="bookableresourceassociationId">bookableresourceassociationId</a>

Unique identifier for entity instances  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource Association</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_bookableresourceassociationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Bookable Resource Association  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Bookable Resource Association</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Bookable Resource Association  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Bookable Resource Association</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#fromDate name="fromDate">fromDate</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fromdate</td></tr></table>

### <a href=#resource1 name="resource1">resource1</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource 1</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resource1</td></tr></table>

### <a href=#resource2 name="resource2">resource2</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource 2</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resource2</td></tr></table>

### <a href=#toDate name="toDate">toDate</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_todate</td></tr></table>

### <a href=#type name="type">type</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Work Location</td><td>192350000</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: scheduling/BookableResourceAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
