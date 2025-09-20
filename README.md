Github-Contribution

Automatically generate daily GitHub contributions using GitHub Actions.

How to Use

⬇️ Create a new repository from this template. [([Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template))]

🔒 Add your GitHub email address as a secret named USER_EMAIL. [([Docs](https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/use-secrets#creating-encrypted-secrets-for-a-repository))]

😄 That’s it — you’re all set!

How It Works

The workflow runs once a day at 12:00 PM UTC (GMT+0).

It creates an empty commit to keep your GitHub contributions graph active.
