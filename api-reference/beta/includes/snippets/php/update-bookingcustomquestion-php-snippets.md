---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new BookingCustomQuestion();
$requestBody->setOdataType('#microsoft.graph.bookingCustomQuestion');
$requestBody->setDisplayName('What is your age?');
$requestBody->setAnswerInputType(new AnswerInputType('text'));
$requestBody->setAnswerOptions([	]);

$result = $graphServiceClient->bookingBusinesses()->byBookingBusinessId('bookingBusiness-id')->customQuestions()->byBookingCustomQuestionId('bookingCustomQuestion-id')->patch($requestBody)->wait();

```