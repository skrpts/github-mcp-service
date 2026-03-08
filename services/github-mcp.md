---
type: service
id: github-mcp
title: GitHub MCP
description: "GitHub MCP server for repository interactions"
tags: [Production]
connections: []
---

## Type

MCP Server

## Package

@modelcontextprotocol/server-github

## Transport

stdio

## Environment Variables

- GITHUB_TOKEN: `{{GITHUB_TOKEN}}`

## Capabilities

- Read repository contents and file trees
- Search code across repositories
- Read and create pull requests
- Read and create issues
