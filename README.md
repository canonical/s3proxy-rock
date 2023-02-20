# s3prox-rock

[![Build ROCK](https://github.com/canonical/s3proxy-rock/actions/workflows/build-rock.yaml/badge.svg)](https://github.com/canonical/s3proxy-rock/actions/workflows/build-rock.yaml)

Automation for building a ROCK for S3Proxy. Every fourth hour, the automation checks whether 
a new release has been cut in the upstream S3Proxy repo, and if so, creates a pull request with 
the new version info.

Once the PR gets merged, a new ROCK is built and published on ghcr.io/canonical/s3proxy.
