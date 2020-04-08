# Docker Image with Homebrew and AWS CLI 

Linuxbrew with aws cli, cfn_nag, and hugo. Updated for my personal requirements to deploy static content

## Build

```
docker build -t milldr/static-site-deployer:latest ./images/base
```

## Usage

Configure:

```
export AWS_ACCESS_KEY_ID="<id>"
export AWS_SECRET_ACCESS_KEY="<key>"
export AWS_DEFAULT_REGION="<region>"
```

## Maintenance

- The Docker image build & publish is automated by CircleCI 

## References

- AWS CLI Docs: https://aws.amazon.com/documentation/cli/
- Homebrew: https://docs.brew.sh/Homebrew-on-Linux
- CFN_NAG: https://github.com/stelligent/cfn_nag
- Hugo: https://gohugo.io/

