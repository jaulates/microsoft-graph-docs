---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestConfiguration = new ApplicationsRequestBuilderGetRequestConfiguration();

$queryParameters = new ApplicationsRequestBuilderGetQueryParameters();
$queryParameters->filter = "owners/$count eq 0 or owners/$count eq 1";
$queryParameters->count = true;

$headers = [
'ConsistencyLevel' => 'eventual',
];

$requestConfiguration->queryParameters = $queryParameters;
$requestConfiguration->headers = $headers;


$requestResult = $graphServiceClient->applications()->get($requestConfiguration);


```