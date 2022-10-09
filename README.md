# pages-deploy-without-build

## Usage

1. Press `Use this template` to create a repository.

2. Generate a delpoy key: `Settings`&nbsp;&nbsp;>&nbsp;&nbsp;`Developer settings`&nbsp;&nbsp;>&nbsp;&nbsp;`Personal access token`&nbsp;&nbsp;>&nbsp;&nbsp;`Generate new token`

3. Set your **Name** and **EMail** in `deploy.yml` file

4. Set that key to your repo _Secrets_, name it `COMMIT_SECRET`: `Settings(In your repo)`&nbsp;&nbsp;>&nbsp;&nbsp;`Secrets`&nbsp;&nbsp;>&nbsp;&nbsp;`Actions`&nbsp;&nbsp;>&nbsp;&nbsp;`New repository secret`

5. Create a new folder called `src` and put all of your _html_, _js_, _css_ into it.

6. Push to main branch, and github pages deployment will start.
