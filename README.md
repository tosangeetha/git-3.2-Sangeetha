# git-3.2-Sangeetha
GitHub authentication refers to the process of verifying the identity of users who interact with GitHub's services and APIs. It ensures that only authorized individuals or applications can access and perform actions on GitHub repositories, issues, pull requests, and other resources.

GitHub provides several methods for implementing authentication:

Username and password: This is the basic authentication method where users provide their GitHub username and password to log in. However, GitHub encourages the use of more secure authentication methods and recommends using personal access tokens or SSH keys instead.

Personal access tokens: Personal access tokens (PATs) are alternative authentication credentials that can be used instead of passwords. Users can create PATs with specific permissions to access their GitHub resources or perform API operations on their behalf. PATs can be generated in the GitHub settings and are associated with a user's account.

SSH keys: Secure Shell (SSH) keys provide a secure way to authenticate and establish encrypted communication between a user's local machine and GitHub. Users can generate an SSH key pair and add the public key to their GitHub account. When interacting with GitHub, the user's local machine uses the private key to authenticate.

OAuth: OAuth (Open Authorization) is an industry-standard protocol used for authorization and allows third-party applications to access a user's GitHub resources without directly handling their credentials. GitHub supports OAuth 2.0, and developers can integrate GitHub authentication into their applications using the OAuth flow. This method is commonly used for building integrations, web applications, or mobile apps.

GitHub Apps: GitHub Apps are first-class integrations that can be installed directly on user repositories or organizations. GitHub Apps have granular permissions and can perform actions on behalf of users or as themselves. They use a combination of webhooks and tokens for authentication and authorization.

Web application flow: For web applications, GitHub provides a web application flow using the GitHub API. It involves redirecting users to GitHub's authentication endpoint, where they log in and authorize the application to access their GitHub resources. Upon authorization, the user is redirected back to the application with an authorization code that can be exchanged for an access token.
