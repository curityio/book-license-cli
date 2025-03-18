# Book License for the Curity Identity Server

A utility for readers of the O'Reilly book to get a license file for Curity Identity Server:

- [Cloud Native Data Security with OAuth](https://www.oreilly.com/library/view/cloud-native-data/9781098164874/)
- [Code and Deployment Examples](https://github.com/curityio/cloud-native-oauth-security-examples)

## Option 1: Get a License with a Tool

An API provides license files and requires an access token to authorize the request.\
The first time you run a book example that uses the Curity Identity Server, you receive a prompt:

```text
This script gets a book license file for the Curity Identity Server.
A CLI will run a code flow in your browser to get an access token.
Press a key to continue ...
```

During the code flow you can choose from one of the following login options:

- Verify your email address
- Use an anonymous login
- Use an existing account to sign in to the [Curity developer portal](https://developer.curity.io)

When the code flow completes, the CLI saves a `license.json` file to disk.\
The license saves to the `resources/authorizationserver/license` folder of the deployment examples.

## Option 2: Provide Your Own License

If you prefer, you can instead provide your own licese.\
If for some reason you have problems running the CLI, get a [community edition license](https://developer.curity.io/community-edition/) from the Curity website.\
Copy your `license.json` file into the `resources/authorizationserver/license` folder.

## Using Passkeys

Running the passkeys example from chapter 14 requires extra license features beyond the community license.\
To get one, use the license tool or get a trial license from the Curity website.
