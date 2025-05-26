# SpiceEngine Claude Code Action

Autonomous coding assistant running on GitHub Actions with Claude Code

## Required Environment

- Claude CLI (`claude`)
- GitHub CLI (`gh`)

## Usage

```yaml
- uses: spiceengine/action@main
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```
