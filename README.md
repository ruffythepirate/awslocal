This is just a simple bashscript that adds the endpoint-url parameter to the aws command so that you can use the AWS cli against a localstack instance that is running.

# Prerequisites

* AWS cli must be installed.
* Linux, will probably work on mac as well.

# Installation

Put the script somewhere in your path, for example /usr/local/bin, then run `awslocal <whatever parameters you would use with aws>`.
