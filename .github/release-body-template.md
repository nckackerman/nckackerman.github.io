|                 |                                           DEV                                           |                                          QA                                           |                                        UAT                                         |                                         PROD                                          |
|:----------------|:---------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| **deploy**      |      [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/dev-deploy.png">][dev-deploy]      |      [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/qa-deploy.png">][qa-deploy]      |   [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/uat-deploy.png">][uat-deploy]    |    [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/prod-deploy.png">][prod-deploy]    |
| **post-deploy** | [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/dev-post-deploy.png">][dev-post-deploy] | [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/qa-post-deploy.png">][qa-post-deploy] | [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/uat-deploy.png">][uat-post-deploy] | [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/prod-deploy.png">][prod-post-deploy]  |
| **promote**     |    [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/dev-promote.png">][dev-promote]      |     [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/qa-promte.png">][qa-promote]      |  [<img src="{{baseUrl}}{{filePathForDownload}}{{releaseId}}/uat-deploy.png">][uat-promote]    |                                         xxxx                                          |

|   BUILD COMMIT    |            RELEASE PIPELINE            |
|:-----------------:|:--------------------------------------:|
|   {{buildHash}}   | [{{releaseId}}][release-pipeline-link] |
| {{commitMessage}} |             {{changeLog}}              |


[build-link]: {{baseUrl}}releases/tag/{{releaseId}}
[release-pipeline-link]: {{baseUrl}}releases/tag/{{releaseId}}

[dev-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[dev-post-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[dev-promote]: {{baseUrl}}releases/tag/{{releaseId}}
[qa-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[qa-post-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[qa-promote]: {{baseUrl}}releases/tag/{{releaseId}}
[uat-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[uat-post-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[uat-promote]: {{baseUrl}}releases/tag/{{releaseId}}
[prod-deploy]: {{baseUrl}}releases/tag/{{releaseId}}
[prod-post-deploy]: {{baseUrl}}releases/tag/{{releaseId}}