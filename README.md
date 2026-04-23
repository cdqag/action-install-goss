# cdqag/action-install-goss

![GitHub License](https://img.shields.io/github/license/cdqag/action-install-goss)
![GitHub Release](https://img.shields.io/github/v/release/cdqag/action-install-goss)

This is very simple GitHub Action that installs goss.

```yaml
steps:
  - name: Install goss
    id: install-goss
    uses: cdqag/action-install-goss@v1

  - name: Verify
    run: |
      goss --version

```

## About Creator

![CDQ Logo](https://www.cdq.com/themes/custom/gavias_nonid/logo.svg)

This action has been created and is maintained by [CDQ - Data Quality Solutions &amp; Services for Master Data](https://www.cdq.com/).

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.
