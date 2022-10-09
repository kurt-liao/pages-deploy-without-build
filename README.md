# pages-deploy-without-build

## Usage

1. Press `Use this template` to create a repository.

2. Generate a delpoy key: `Settings`&nbsp;&nbsp;>&nbsp;&nbsp;`Developer settings`&nbsp;&nbsp;>&nbsp;&nbsp;`Personal access token`&nbsp;&nbsp;>&nbsp;&nbsp;`Generate new token`

3. Set that key to your repo *Secrets*, name it `COMMIT_SECRET`: `Settings(In your repo)`&nbsp;&nbsp;>&nbsp;&nbsp;`Secrets`&nbsp;&nbsp;>&nbsp;&nbsp;`Actions`&nbsp;&nbsp;>&nbsp;&nbsp;`New repository secret`

4. Create a new folder called `src` and put all of your *html*, *js*, *css* into it.

5. Push to main branch, and github pages deployment will start.
