---
layout: post
title: "Connect Your AI Assistant to ACCESS-CI"
date: 2026-04-22 10:00:00 -0700
categories: [research-computing, updates]
tags: [access-ci, ai, onboarding]
author: "Joan Zheng"
excerpt: "A quick pointer to the ACCESS-CI announcement on connecting your AI assistant."
---

## Summary

ACCESS-CI now supports connecting your AI assistant to ACCESS-CI services via a Model Context Protocol (MCP)!

This is a useful starting point for students and researchers who want to combine AI workflows with research computing resources.

- Connect Your AI Assistant with ACCESS-CI: [https://support.access-ci.org/announcements/connect-your-ai-assistant-access-ci](https://support.access-ci.org/announcements/connect-your-ai-assistant-access-ci)

## Claude Web with ACCESS MCP

<img src="{{ '/images/access-mcp/claude-mcp.png' | relative_url }}" alt="Add an MCP to Claude" class="img-67-centered" />

ACCESS's MCP service can easily be added in Claude's web version, as shown above. This service is also compatible with CLI, such as Claude Code and Gemini CLI.

## ACCESS MCP Servers

| Server | What It Provides |
| --- | --- |
| Compute Resources | Hardware specs, GPU availability, system capabilities |
| System Status | Current outages, maintenance schedules, incidents |
| Software Discovery | Software packages available across ACCESS resources |
| XDMoD | Usage statistics, visualizations, resource utilization |
| Allocations | Research projects, allocation trends, collaboration discovery |
| NSF Awards | NSF funding data and cross-referencing |
| Events | Workshops, webinars, training sessions |
| Announcements | Community news and updates |
| Affinity Groups | Community groups, events, and knowledge base |

A tenth server, XDMoD Data Analytics, provides per-user job and usage data and requires a personal API token. It works with Claude Code and other CLI MCP clients but is not currently compatible with Claude.ai connectors. See [the setup guide](https://mcp.access-ci.org/docs/getting-started#optional-xdmod-data-analytics) for details.