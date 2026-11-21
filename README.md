<p align="center">
  <img src="assets/logo.png" alt="SmartDrugs logo" width="96">
</p>

<h1 align="center">SmartDrugs Wayback Archive</h1>

<p align="center">Automatic snapshots of <a href="https://smartdrugs.com.br">smartdrugs.com.br</a> on the Internet Archive Wayback Machine, three times a day.</p>

<p align="center">
  <a href="https://web.archive.org/web/*/smartdrugs.com.br*"><img src="https://img.shields.io/badge/Wayback%20Machine-smartdrugs.com.br-fe2e3a?labelColor=1c1c1c&logo=internetarchive&logoColor=white" alt="Wayback Machine: smartdrugs.com.br"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-1c1c1c?labelColor=fe2e3a&color=1c1c1c" alt="License: MIT"></a>
</p>

This repository keeps a public, timestamped history of the SmartDrugs website. A GitHub Actions workflow asks the Wayback Machine to capture the site three times a day, so every change stays on record.

SmartDrugs: Nootrópicos, smartdrugs e stacks pelo que as evidências e relatos dizem. 100% independente. Sem hype, sem venda direta.

Contact: [contato@smartdrugs.com.br](mailto:contato@smartdrugs.com.br)

## Schedule

| Run | UTC | Brasília (UTC-3) |
| --- | --- | --- |
| Morning | 11:00 | 08:00 |
| Afternoon | 17:00 | 14:00 |
| Night | 23:00 | 20:00 |

The workflow can also be started by hand from the Actions tab with **Run workflow**.

## How it works

1. GitHub Actions starts [`.github/workflows/wayback.yml`](.github/workflows/wayback.yml) on schedule.
2. The workflow sends each URL to the Wayback Machine Save Page Now service.
3. The Internet Archive stores a new capture, and the run log shows the snapshot link.

## Links

- Website: [smartdrugs.com.br](https://smartdrugs.com.br)
- History: [Wayback Machine](https://web.archive.org/web/*/smartdrugs.com.br*)
- Contact: [contato@smartdrugs.com.br](mailto:contato@smartdrugs.com.br)

## License

[MIT](LICENSE)
