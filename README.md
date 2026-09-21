# ERD Studio demo

A small sample data model for trying out [ERD Studio for Confluence](https://erd-studio.w2solutions.ai/confluence/).
The diagram lives in `.erd-studio/silver/showcase.json`, and its tables are in `.erd-studio/logical-models/`.

## Try it in your Confluence site (about 5 minutes)

You need a Confluence Cloud site where you're a site admin, and any GitHub account.

1. **Copy this repository.** Click **Use this template → Create a new repository** (or fork it) into your
   own GitHub account. Private or public both work.
2. **Install the GitHub App.** Go to <https://github.com/apps/erd-studio-for-confluence>, click
   **Install**, choose your account, pick **Only select repositories** and select your copy of this repo.
3. **Connect GitHub in Confluence.** In Confluence, go to **Settings → Apps → ERD Studio** (or
   **Manage apps → ERD Studio → Configure**). Click **Find installations**, sign in to GitHub when asked,
   and choose the installation from step 2.
4. **Add the macro.** Edit any page, type `/ERD Studio`, and insert the macro. In the macro settings pick
   your repository, branch `main` and the diagram `silver/showcase.json`. Publish the page.

Readers can pan, zoom and drag tables around. Push a change to the repo, and the page shows it on the next
view.

Full documentation: <https://erd-studio.w2solutions.ai/confluence/>
