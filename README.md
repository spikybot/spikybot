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
    model: opus # option (default: sonnet)
    thinking: true # option (default: false)
    additional-prompt: "カスタムプロンプト" # option
    upstash-redis-rest-url: ${{ secrets.UPSTASH_REDIS_REST_URL }}
    upstash-redis-rest-token: ${{ secrets.UPSTASH_REDIS_REST_TOKEN }}
```
