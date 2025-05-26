# SpiceEngine Action

GitHub Actions対応の自律型コーディングアシスタント

## 必要な環境

- Claude CLI (`claude`)
- GitHub CLI (`gh`)

## 使用方法

```yaml
- uses: spiceengine/action@main
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```
