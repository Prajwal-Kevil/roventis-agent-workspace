# Roventis Technologies customization

This repository is a Roventis Technologies product workspace built from [CopilotKit/OpenBot](https://github.com/CopilotKit/OpenBot).

## Product identity

- Product: **Roventis Agent Workspace**
- Company: **Roventis Technologies**
- Maintainer: **Prajwal C**
- Focus: agent-powered workflows for websites, apps, SaaS products, and desktop software teams

## Roventis starter features

- A runnable `examples/roventis` tenant package selected through `TENANT_PACKAGE_DIR`.
- Roventis Workmate and Roventis Knowledge as the default coworkers.
- Starter coworkers for website and app planning, SaaS launches, QA release review, and customer-success drafting.
- Business-oriented channels and document roots for Product, Engineering, Customer Success, and Operations.
- Professional product naming and documentation while keeping the upstream OpenBot architecture intact.

The starter coworkers draft and analyze. They do not claim to have deployed software, contacted customers, or published changes without a connected tool confirming the action.

## Upstream and licensing

OpenBot is the upstream project by CopilotKit and is licensed under the MIT license. The upstream license and attribution remain in this repository. Roventis branding does not imply ownership of upstream code.

## Local configuration

Copy `.env.example` to `.env`. It points to `../examples/roventis` by default. For a different tenant package, set `TENANT_PACKAGE_DIR` explicitly. Keep credentials in environment variables or the configured secret store, never in YAML or commits.
