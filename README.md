# SpikyBot from SpiceEngine

Autonomous coding assistant running on GitHub Actions with Claude Code.

Please check the Claude Code terms and conditions carefully before executing.

Sharing this agent with more than one person is prohibited.

We assume no responsibility.

## Required Environment

- Claude CLI (`claude`)
- GitHub CLI (`gh`)

## Usage

```yaml
- uses: spikybot/spikybot@main
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```
