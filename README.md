# PHP Code Injection Attack Documentation

PHP code injection attack demonstration with bWAPP, Netcat and Commix in Kali Linux Virtual Machine

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Security](https://img.shields.io/badge/security-educational-yellow.svg)](https://github.com/your-username/php-injection-security-demo)
[![Platform](https://img.shields.io/badge/platform-Kali%20Linux-purple.svg)](https://www.kali.org/)

> **WARNING: Educational Purpose Only** - This repository contains security research documentation for educational purposes. All testing was conducted on deliberately vulnerable applications in controlled environments.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Tools](#tools)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)

## Overview

This repository documents a comprehensive PHP code injection attack demonstration project conducted as part of IT Security coursework. The project demonstrates various attack vectors, defensive measures, and provides detailed analysis of web application vulnerabilities.

### Key Objectives
- Demonstrate PHP code injection vulnerabilities
- Compare attack and defense methodologies
- Analyze tool effectiveness
- Provide educational cybersecurity content

## Features

- **Complete Attack Lifecycle**: From reconnaissance to exploitation
- **Multiple Attack Vectors**: Manual injection, automated tools, reverse shells
- **Defense Analysis**: Vulnerability scanning and mitigation strategies
- **Tool Comparison**: Detailed effectiveness evaluation
- **Real-world Scenarios**: Practical examples with bWAPP

## Prerequisites

### System Requirements
- **OS**: Kali Linux (recommended) or any Linux distribution
- **Memory**: 4GB RAM minimum
- **Storage**: 20GB free space
- **Network**: Isolated test environment

### Software Dependencies
````bash
# Core services
apache2
mysql-server
php

# Security tools (pre-installed in Kali)
netcat
commix
owasp-zap
