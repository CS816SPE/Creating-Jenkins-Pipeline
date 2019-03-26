# Setting up a Jenkins Build Pipeline

- There are a lot of ways to setup a pipeline. We will show you the simplest of all methods. You are free to try other methods and setup a pipeline
- Steps
  1. Install the *[Build pipeline](https://plugins.jenkins.io/build-pipeline-plugin)* plugin
  2. Create multiple Jenkins jobs for each stage such as Build, Test, Deploy, so on depending on your requirement
  3. Create a new pipeline view & choose the first job in the pipeline
  4. Now, configure each jobs to form a stream. Trigger the next Job by configuring 'post build actions' in each Job
  5. Once configured, the first job should be triggered at least once for the pipeline to start
  6. Given the pipeline is all set up, now on just triggering the first job will trigger all the jobs in the pipeline and the status can be checked in the pipeline view
