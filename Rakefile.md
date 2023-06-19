# RakeFile

Ruby里的RakeFile就和makeFile一样，用于构建程序。


# 查看定义的任务
rake -T

```bash
❯ rake -T
rake base_test        # Run tests for base_test
rake build            # Build fluentd-1.16.1.gem into the pkg directory
rake build:all        # Build gems for all platforms
rake clean            # Remove any temporary products
rake clobber          # Remove any generated files
rake coverage         # Run test with simplecov
rake coverity         # Build Coverity tarball & upload it
rake install          # Build and install fluentd-1.16.1.gem into system gems
rake install:local    # Build and install fluentd-1.16.1.gem into system gems without network access
rake release[remote]  # Create tag v1.16.1 and build and push fluentd-1.16.1.gem to rubygems.org

```