# recent-github-activity

Generate a markdown report of your recent activity on GitHub

## Usage

```
npx recent-github-activity
```

The first time you run this command, you'll be asked to log in to GitHub using your password or a personal access token, and the resulting token will be saved to disk for future use using [ghauth](https://github.com/rvagg/ghauth).

You can save the output to a file:

```
npx recent-github-activity > recent.md
```

or pipe it right to [`vmd`](https://ghub.io/vmd):

```
npx recent-github-activity | npx vmd
```

This is what a generated report looks like in `vmd`:

<img width="1009" alt="screenshot" src="https://user-images.githubusercontent.com/2289/76592714-7bf71200-64b1-11ea-8294-4d26ef90499a.png">