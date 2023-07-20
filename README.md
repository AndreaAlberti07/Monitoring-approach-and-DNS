<h1 align="center">Network Performance and Functionality Investigation</h1>

<p align="center">
  <b>Two Projects Analyzing Network Performance and DNS Functionality</b>
  <br>
  <i>Exploring Latency Analysis and DNS Resolution Time</i>
</p>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#project-1-latency-analysis">Project 1: Latency Analysis</a> •
  <a href="#project-2-dns-functionality-and-performance">Project 2: DNS Functionality and Performance</a> •
  <a href="#how-to-use">How to Use</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

---

## Introduction

Welcome to the Network Performance and Functionality Investigation project repository. This repository contains the code and documentation for two projects that delve into different aspects of network performance and functionality.

## Project 1: Latency Analysis

### Objective

The primary goal of the first project is to analyze the latency of the apple.com website during weekdays and weekends. Additionally, we investigate the impact of different Internet Service Providers (ISPs) and connection technologies (4G and FTTH) on the website's latency.

### Tools Used

The following tools were utilized to collect measurements and analyze the data:

- `ping`: Used for testing network connectivity and latency.
- `traceroute`: Employed to trace the path that packets take from the source to the destination.
- `mtr`: Combines the functionality of `ping` and `traceroute` for more comprehensive network analysis.
- `speedtest-cli`: Utilized to measure network bandwidth and latency.
- `top`: Monitored system resource usage during testing.

### Results

The analysis of latency revealed that it doesn't significantly depend on the day of the week. However, the choice of ISPs and connection technologies had a considerable impact on the website's latency. Further details can be found in the project documentation.

## Project 2: DNS Functionality and Performance

### Objective

The second project focuses on exploring the functionality and performance of the Domain Name System (DNS). It consists of two main parts:

1. Investigation of the DNS resolution process by actively experimenting with DNS queries and responses.
2. Evaluation of the performance of different DNS servers and protocols by measuring the DNS resolution time.

### Tools Used

The following tools were employed for DNS investigation and performance evaluation:

- `dig`: Used for querying DNS servers and obtaining DNS-related information.
- `dnstraceroute`: Traced the path of DNS queries to their resolution.
- `whois`: Provided domain registration information for analysis.
- `dnseval`: Utilized to measure DNS resolution time.

### Results

The results from the second project demonstrated that the DNS resolution time varies depending on the chosen DNS server and protocol. More detailed findings are documented in the project report.

## How to Use

If you wish to replicate the experiments or explore the code and data, follow these steps:

1. Clone the repository to your local machine using `git clone`.
2. Navigate to the respective project folders for detailed instructions on running the experiments.
3. Refer to the project documentation to understand the data collection and analysis process.

## Contributing

Contributions to this project are welcome. If you find any issues or have ideas for improvement, feel free to create a pull request or submit an issue.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and documentation following the terms of the license.

---

We hope this repository helps in understanding network performance and DNS functionality. Should you have any questions or concerns, please don't hesitate to contact us.

Thank you for your interest in this project!

*Project Maintainers: [Your Name](mailto:your@email.com)*
