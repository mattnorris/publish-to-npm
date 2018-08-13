#!groovy
library 'sparkPipeline'
pipelineProperties(
    name: 'spark-js-sdk--publish-to-npm',
    numToKeep: 10,
    // notifyAuthorsSince: 'published',
    // notifySparkRoomId: 'Y2lzY29zcGFyazovL3VzL1JPT00vYWYyMDhlMDAtZDNlNC0xMWU3LTkyY2MtNjExOTg1NjAzNWFm'
)

buildStage(env.PIPELINE_NAME) {
  stage('Publish to NPM') {
    sh '''#!/bin/bash -ex
      echo "publish to npm"'''
  }
}