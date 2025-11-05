<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 4: Add branch protections

*Great job uploading test reports! :partying\_face:*

Take a look at the merge box, you'll notice you can merge this even though the review process hasn't been met.

Protected branches ensure that collaborators on your repository cannot make irrevocable changes to branches. Enabling protected branches also allows you to enable other optional checks and requirements, like required status checks and required reviews.

### :keyboard: Activity: Add branch protections

1. Go to **Branches** settings. You can navigate to that page manually by selecting the right-most tab in the top of the repository called **Settings** and then clicking **Branches**.
2. Click **Add classic branch protection rule** under "Branch protection rules".
3. Type `main` in **Branch name pattern**.
4. Check **Require a pull request before merging**.
5. Uncheck **Require approvals**.
6. Check **Require status checks to pass before merging**.
7. Check all build and test jobs that you'd like to see in the newly visible gray box.
8. Click **Create**.
9. *Once you turn on branch protection, Actions can no longer push directly to the `main` branch. Wait about 20 seconds and then go to the `ci` branch. [GitHub Actions](https://docs.github.com/actions) will automatically update to the next step on the `ci` branch. You'll need to follow instructions on this branch.*
