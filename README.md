# aws-scripts-mon

This is based on the AWS CloudWatchMonitoringScripts project.

It uses https://aws-cloudwatch.s3.amazonaws.com/downloads/CloudWatchMonitoringScripts-1.2.2.zip as the base.

## Features

### Custom Namespaces

`--custom-namespace=<name>`

Usage: Use a custom metric namespace. Uses `System/Linux` if not provided.

Example: 
```
./mon-put-instance-data.pl --mem-util --mem-used --mem-avail --aggregated=only --custom-namespace=Memory/BeanstalkProject/Production
```
