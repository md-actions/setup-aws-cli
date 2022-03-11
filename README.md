# [DEPRECATED]
This action has moved to https://github.com/freenet-actions/setup-aws-cli

# setup AWS CLI
[![LICENSE](https://img.shields.io/github/license/md-actions/setup-aws-cli)](https://github.com/md-actions/setup-aws-cli/blob/main/LICENSE)

This action sets up AWS CLI tool. It downloads AWS CLI binaries from https://s3.amazonaws.com/aws-cli, unpacks the downloaded file, runs the install program and adds path to PATH


Currently the action can only be used on linux plattform.
   
# Usage
## Set up default AWS CLI version (3.7.0)
```yaml
- uses: md-actions/setup-aws-cli@v1
```
## Set up specific AWS CLI version
```yaml
- uses: md-actions/setup-aws-cli@v1
  with:
    version: '3.6.0'
```

# References
[AWS CLI Install Documentation](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
