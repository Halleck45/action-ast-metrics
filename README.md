# ast-action

> Github action for AST Metrics

This will automatically add a markdown report to your build, containing metrics about your project (e.g. maintainability, complexity, etc.)

An artifact will also be created, containing the detailed HTML report.

## Usage

```yaml
- name: AST Metrics
  uses: halleck45/action-ast-metrics@v1
```

## Inputs

+ `version`: The version of AST Metrics to use. Default: `latest`
+ `directory`: The directory to analyze. Default: `.`

## License

MIT. See [LICENSE](LICENSE) for more details.