# SpiceEngine Action

GitHub Actions対応の自律型コーディングアシスタント

## 必要な環境

- Claude CLI (`claude`)
- GitHub CLI (`gh`)

## 使用方法

```yaml
- uses: spiceengine/action@v1
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```
