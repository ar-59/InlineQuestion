## Metadata
Question Type : Text Input

## Question
What is the correct query? :

## Answers
(?=.*^)("specific_data.data.os.type" == "Windows") and (("adapters_data.epo_adapter.id" == ({"$exists":true,"$ne":""}))) and ("specific_data.data.last_seen" >= date("NOW - 3d"))(.*$) : 1

## Correct Answer Feedback
You have provided a correct answer

## Incorrect Answer Feedback
Correct answer is: **("specific_data.data.os.type" == "Windows") and (("adapters_data.epo_adapter.id" == ({"$exists":true,"$ne":""}))) and ("specific_data.data.last_seen" >= date("NOW - 3d"))**

## Tags
tag1
tag2
