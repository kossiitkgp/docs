# How to contribute?

We are really glad you are reading this. We want to keep KOSS documentation up-to-date all the time.

## 1. Something is bugging you

If you want to discuss a section, a doc or the entire documentation, create a GitHub issue. You can additionally tag some people if you want their inputs.

## 2. Something needs to be changed

You are awesome! You will have to create a Pull Request. Fork the repository, create a new branch, make the changes, and submit a Pull Request. You can read more about Pull Requests [here](https://help.github.com/pull-requests/).

Stick to the following conventions -

### Conventions
- Look for an existing doc or section where your content may go. If you can not find any, create a new document at an appropriate index.
- Do not write anything as an opinion.
- Do not rush through the content, hence write slowly. (A content written in haste, causes uneasiness to the reader.)
- It is discouraged to write in first person *i.e.* do not use `I` or `Me`. NEVER write anything in first person without identifying who wrote it. (e.g. Name, Class of 'YY)
- Check for spelling and grammatical mistakes.
  - You can use [Grammarly](https://app.grammarly.com/) to verify. You can get a [free grammarly account](https://wiki.metakgp.org/w/How_to_get_free_Grammarly_premium_account) if you are an IIT KGP student.
- Use one convention for hyper-links - makes easy for us to update them if file structures changes in future: 
  - For linking a directory: `[Link Text](/DIR_NAME)`
  - For linking a file: `[Link Text](/DIR_NAME/FILE_NAME.md)`. **Make sure you mention the file extension too**.
- Sign your commits. [Read more](https://help.github.com/articles/signing-commits/)
- Make 1 commit per change. Do not commit multiple changes together if they do not serve a single purpose.
- Prefer 1 commit per Pull Request. This will keep the discussions separate and precise to the change.
- Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:
```
$ git commit -S -m "A brief summary of the commit
>
> A paragraph describing what changed and its impact."
```
- Writing meaningful commit messages is important. We are interested in the changelog of KOSS documentation through the commit history of this project.

Refrain from using Slack to discuss any queries related to a doc or any discussion about a serious change. Create an issue here and notify on the Google group about the GitHub issue. You can additionally send a direct email asking for inputs, to any advisor/alumni who might not be actively receiving emails from the Google Group or GitHub.


# How is a change reviewed?

- Do not merge any Pull Request within 48 hours of its creation.
- At least x [TBD] approvals from Executive Heads is required.
- At least x [TBD] approvals from Advisors/Alumni is required.
- Do not merge a Pull Request which you have created yourself.
