### AWS Codepipeline with Github
AWS codepipeline introduced different ways to connect your version control provider like Github, Bitbucket and Gitlab
#### GitHub repo for AWS Codepipeline
- Create  a GitHub repo before connecting to AWS
- Connect Codepipeline through settings -> connection where you will be redirected to the AWS developer tools.
- Create a connection and select your version provider
- Sign in to GitHub and authorise the AWS Github Connector for your repo or repos to avoid delays when configuring Codepipeline
#### Create a codepipeline
- Name,  define the execution mode,  service role
- Select your source provider, add the codepipeline create a connection,   select the repo and branch and artifact output format
- CodeBuild
- Select deployment provider - Amazon S3