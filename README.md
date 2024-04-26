# SpringOAuth2

Version 1
Page with Default Login
user/[password in Console]

Version 2
securityFilterChain
http://localhost:8080/  ##PermitAll
http://localhost:8080/secured   ##Default Login

Version 3
Set Client ID and Secret
# GitHub Login
# Settings - Developer settings - OAuth Apps - Register a new OAuth application
    # Application name: Spring OAuth2
    # Homepage URL: http://localhost:8080
    # Authorization callback URL: http://localhost:8080/login/oauth2/code/github
# Click Register application
    # Client ID
    # Generate a new client secret

# Google Login
# https://console.cloud.google.com/
# APIs & Services - OAuth consent screen - Credentials - Create Credentials - OAuth client ID
    # Application type: Web application
    # Name: Spring OAuth2
    # Authorized redirect URIs: http://localhost:8080/login/oauth2/code/google
    # Client ID
    # Secret