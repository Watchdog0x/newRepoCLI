## To get an access token on GitHub, you can use the following steps:

1) Log in to your GitHub account.
2) Go to the settings page by clicking on your profile picture in the top right corner and selecting "Settings".
3) In the left sidebar, select "Developer settings".
4) Click on "Personal access tokens".
5) Click on "Generate token" button.
6) Give a name to your token and select the scope of the token (permissions it will have).
7) Click on "Generate token" button to create the token.


Once you have your token, you can use it to authenticate with the GitHub API. In order to use it, you need to include it in the headers of your requests as

```
Authorization: Bearer <YOUR-TOKEN>
