# Helm Charts for My Homelab

This repository contains Helm charts created for my homelab.  
You are welcome to use them in your own homelab or for any other purpose.

---

## Getting Started

Add this repository to Helm:

```bash
helm repo add t7 https://adriant7.github.io/helm-charts/
helm repo update
```

### Install a chart
```bash
helm install my-release t7/<chart-name>
```

Replace **<chart-name>** with the chart you want to install, for example:
```bash
helm install runner t7/gh-runner-chart
```

## Available charts
- **gh-runner-chart** - GitHub Actions self-hosted runner setup

## Resources
- **Source files** ([GitHub](https://github.com/AdrianT7/t7-homelab/tree/main/helm/))

## License

MIT License. See [LICENSE](LICENSE) for details.
