# 🔍 Vuln-Detector

A powerful Node.js CLI tool for detecting vulnerabilities in websites by scanning JavaScript and CSS bundles, analyzing dependencies, and generating detailed security analytics.

## ✨ Features

- **Website Scanning**: Input any URL and automatically scan for vulnerabilities
- **Bundle Detection**: Identify and analyze JavaScript and CSS bundles using Puppeteer
- **Dependency Analysis**: Detect outdated or vulnerable npm packages in loaded resources
- **Vulnerability Database Integration**: Cross-reference findings with known CVE databases
- **Analytics Dashboard**: Generate detailed reports with vulnerability severity levels
- **CLI Interface**: Easy-to-use command-line tool for quick scans
- **JSON Export**: Export scan results in JSON format for integration with other tools
- **Performance Metrics**: Analyze bundle sizes and impact on performance

## 🚀 Quick Start

### Installation

```bash
npm install -g vuln-detector
```

### Usage

```bash
# Scan a website
vuln-detector scan https://example.com

# Scan with detailed output
vuln-detector scan https://example.com --verbose

# Export results to JSON
vuln-detector scan https://example.com --output results.json

# Run with custom timeout
vuln-detector scan https://example.com --timeout 30000
```

## 📋 Requirements

- Node.js 14.x or higher
- npm or yarn
- Chromium/Chrome browser (for Puppeteer)

## 🛠️ Tech Stack

- **Puppeteer** - Browser automation for website scanning
- **Express.js** - API server for web interface
- **Node.js** - Backend CLI tool

## 📊 Scan Output

The tool provides analytics including:
- Detected vulnerabilities with severity levels
- Bundle information (size, type, version)
- Outdated dependencies
- Security recommendations
- Performance impact analysis

## 📝 License

MIT

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
