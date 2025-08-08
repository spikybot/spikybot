# SpikyBot from SpiceEngine

Autonomous coding assistant running on GitHub Actions with Claude Code.

## Required Environment

- Claude CLI (`claude`)
- GitHub CLI (`gh`)

## Usage

```yaml
- uses: spikybot/spikybot@main
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```
