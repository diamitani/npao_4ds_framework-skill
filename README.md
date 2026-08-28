# NPAO Priority Framework + 4Ds Lifecycle

**Category:** 99-uncategorized
**Source:** NPAO_4Ds_FRAMEWORK.md
**Generated:** 2026-08-28

## Overview

This repository contains a generalized AI agent skill ready for use with Claude Code, Hermes Agent, or any PAL-compliant agent framework.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/diamitani/npao_4ds_framework-skill.git
   ```

2. Import the skill into your agent framework:
   ```bash
   # For Claude Code
   @skill SKILL.md
   
   # For Hermes Agent
   skill_view(name='npao_4ds_framework')
   ```

## Configuration

This skill uses placeholder values for company-specific data:
- `{COMPANY_NAME}` — Replace with your company name
- `{COMPANY_SLUG}` — Replace with your company URL slug
- `{USER_HOME}` — Replace with the user's home directory
- `{USER_NAME}` — Replace with user's name

## License

MIT License — See LICENSE file for details.

## Support

Questions? Open an issue on GitHub.
