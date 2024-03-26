# gh-get-list-of-open-prs

This GitHub Action gets a list of open PRs of a repository

## Usage

```yaml
jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Get list of open PRs
        id: get-open-prs
        uses: caring/gh-get-list-of-open-prs@v0.1
```

The action will create a output you can call using **steps.get-open-prs.outputs.openPRs**  

## License

This project is licensed under the [MIT License](LICENSE).

## Author

Written by the Devops Team.
