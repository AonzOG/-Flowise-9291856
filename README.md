## 📦 Repository Import & Preservation Record — 13 October 2026

### 📌 About This Import

This repository, **[AonzOG/Flowise-9291856](https://github.com/AonzOG/Flowise-9291856)**, was imported from the original **[FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise)** GitHub repository on **Tuesday, 13 October 2026 (Fiji Time)**.

Flowise is an open-source, visual platform for building AI agents, chatbots, and LLM-powered workflows. The original upstream repository has been archived by its maintainers.

This independent import preserves an identifiable snapshot of Flowise's source code and Git history, providing a reference point for future inspection, experimentation, modification, and development.

The repository retains the original project's attribution, documentation, and licensing terms. It is not an official FlowiseAI release or an automatically synchronised upstream mirror.

### 🔖 Original Repository and Import Details

| Property | Details |
|---|---|
| **Original repository** | [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) |
| **Imported repository** | [AonzOG/Flowise-9291856](https://github.com/AonzOG/Flowise-9291856) |
| **Repository owner** | AonzOG |
| **Date imported** | 13 October 2026 |
| **Default branch** | `main` |
| **Upstream status** | Archived |
| **Import type** | Independent GitHub repository |
| **Original commit SHA** | `9291856d1ea4a4ceea9f8fef8ce14f4f6c81e8eb` |

### 🕒 Last Original Upstream Commit at Import

The `main` branch was imported at the following verified upstream commit:

| Commit information | Details |
|---|---|
| **Full commit SHA** | `9291856d1ea4a4ceea9f8fef8ce14f4f6c81e8eb` |
| **Short SHA** | `9291856` |
| **Commit author** | Henry Heng |
| **Commit message** | `Update README.md (#6728)` |
| **Commit date (UTC)** | 13 August 2026, 12:38:19 |
| **Commit date (Fiji)** | 14 August 2026, 00:38:19 |
| **Parent commit** | `abe4a8601a058047b350c260676826e21dd14101` |
| **Git tree SHA** | `ebc9f99171dd855f8127135dfde4adac366425c8` |

**Original upstream commit:**

https://github.com/FlowiseAI/Flowise/commit/9291856d1ea4a4ceea9f8fef8ce14f4f6c81e8eb

**Corresponding commit in this repository:**

https://github.com/AonzOG/Flowise-9291856/commit/9291856d1ea4a4ceea9f8fef8ce14f4f6c81e8eb

The full commit SHA and Git tree SHA were verified to match the original upstream repository.

### 🌿 Preserved Branches and Commit Identification

The imported repository contains branches representing different lines of Flowise development.

| Branch | Last recorded commit | Commit date (UTC) |
|---|---|---|
| `main` | `9291856` | 13 August 2026 |
| `chatflow-data-leak` | `122f4db` | 10 March 2026 |

The `chatflow-data-leak` branch retains the following commit:

`122f4dbadcc5f53abc6eb634e6079973fc81421a`

**Commit message:** `Merge branch 'main' into chatflow-data-leak`

**Commit author:** christopherholland-workday

These branches have distinct development histories. The `chatflow-data-leak` commit is not a replacement for the imported `main` branch commit. Both branch-head identifiers were verified against their corresponding original upstream branches.

### 📜 Original Authors, Licensing and Attribution

Flowise was developed by FlowiseAI and its contributors. Original copyright notices, documentation, contribution history, and applicable licensing conditions remain associated with the imported source code.

The project's `LICENSE.md` specifies Apache License 2.0 for generally available source code, while designated enterprise components and explicitly identified files are subject to commercial licensing conditions. Third-party components remain subject to their respective licences.

See [LICENSE.md](LICENSE.md) for the applicable terms and exceptions.

### 🔄 Repository Continuity

The original upstream commit `9291856d1ea4a4ceea9f8fef8ce14f4f6c81e8eb` remains the permanent reference for the imported `main` baseline.

Subsequent changes, including README updates, maintenance, bug fixes, enhancements, or independent development, will generate new commits without changing the identity of the original imported revision.

**Import recorded: 13 October 2026 — Fiji Time.**

---

*End of Import and Preservation Record.*

<!-- markdownlint-disable MD030 -->

<p align="center">
<img src="https://github.com/FlowiseAI/Flowise/blob/main/images/flowise_white.svg#gh-light-mode-only">
<img src="https://github.com/FlowiseAI/Flowise/blob/main/images/flowise_dark.svg#gh-dark-mode-only">
</p>

<div align="center">

[![Release Notes](https://img.shields.io/github/release/FlowiseAI/Flowise)](https://github.com/FlowiseAI/Flowise/releases)
[![Discord](https://img.shields.io/discord/1087698854775881778?label=Discord&logo=discord)](https://discord.gg/jbaHfsRVBW)
[![Twitter Follow](https://img.shields.io/twitter/follow/FlowiseAI?style=social)](https://twitter.com/FlowiseAI)
[![GitHub star chart](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social)](https://star-history.com/#FlowiseAI/Flowise)
[![GitHub fork](https://img.shields.io/github/forks/FlowiseAI/Flowise?style=social)](https://github.com/FlowiseAI/Flowise/fork)

English | [繁體中文](./i18n/README-TW.md) | [简体中文](./i18n/README-ZH.md) | [日本語](./i18n/README-JA.md) | [한국어](./i18n/README-KR.md)

</div>

<h2>Flowise has been archived. Refer to [Future of Flowise](https://github.com/FlowiseAI/Flowise/discussions/6727)</h2>

<h3>Build AI Agents, Visually</h3>
<a href="https://github.com/FlowiseAI/Flowise">
<img width="100%" src="https://github.com/FlowiseAI/Flowise/blob/main/images/flowise_agentflow.gif?raw=true"></a>

## 📚 Table of Contents

-   [⚡ Quick Start](#-quick-start)
-   [🐳 Docker](#-docker)
-   [👨‍💻 Developers](#-developers)
-   [🌱 Env Variables](#-env-variables)
-   [📖 Documentation](#-documentation)
-   [🌐 Self Host](#-self-host)
-   [☁️ Flowise Cloud](#️-flowise-cloud)
-   [🙋 Support](#-support)
-   [🙌 Contributing](#-contributing)
-   [📄 License](#-license)

## ⚡Quick Start

Download and Install [NodeJS](https://nodejs.org/en/download) >= 20.0.0

1. Install Flowise
    ```bash
    npm install -g flowise
    ```
2. Start Flowise

    ```bash
    npx flowise start
    ```

3. Open [http://localhost:3000](http://localhost:3000)

## 🐳 Docker

### Docker Compose

1. Clone the Flowise project
2. Go to `docker` folder at the root of the project
3. Copy `.env.example` file, paste it into the same location, and rename to `.env` file
4. `docker compose up -d`
5. Open [http://localhost:3000](http://localhost:3000)
6. You can bring the containers down by `docker compose stop`

### Docker Image

1. Build the image locally:

    ```bash
    docker build --no-cache -t flowise .
    ```

2. Run image:

    ```bash
    docker run -d --name flowise -p 3000:3000 flowise
    ```

3. Stop image:

    ```bash
    docker stop flowise
    ```

## 👨‍💻 Developers

Flowise has 3 different modules in a single mono repository.

-   `server`: Node backend to serve API logics
-   `ui`: React frontend
-   `components`: Third-party nodes integrations
-   `api-documentation`: Auto-generated swagger-ui API docs from express

### Prerequisite

-   Install [PNPM](https://pnpm.io/installation)
    ```bash
    npm i -g pnpm
    ```

### Setup

1.  Clone the repository:

    ```bash
    git clone https://github.com/FlowiseAI/Flowise.git
    ```

2.  Go into repository folder:

    ```bash
    cd Flowise
    ```

3.  Install all dependencies of all modules:

    ```bash
    pnpm install
    ```

4.  Build all the code:

    ```bash
    pnpm build
    ```

    <details>
    <summary>Exit code 134 (JavaScript heap out of memory)</summary>  
    If you get this error when running the above `build` script, try increasing the Node.js heap size and run the script again:

    ```bash
    # macOS / Linux / Git Bash
    export NODE_OPTIONS="--max-old-space-size=4096"

    # Windows PowerShell
    $env:NODE_OPTIONS="--max-old-space-size=4096"

    # Windows CMD
    set NODE_OPTIONS=--max-old-space-size=4096
    ```

    Then run:

    ```bash
    pnpm build
    ```

    </details>

5.  Start the app:

    ```bash
    pnpm start
    ```

    You can now access the app on [http://localhost:3000](http://localhost:3000)

6.  For development build:

    -   Create `.env` file and specify the `VITE_PORT` (refer to `.env.example`) in `packages/ui`
    -   Create `.env` file and specify the `PORT` (refer to `.env.example`) in `packages/server`
    -   Run:

        ```bash
        pnpm dev
        ```

    Any code changes will reload the app automatically on [http://localhost:8080](http://localhost:8080)

## 🌱 Env Variables

Flowise supports different environment variables to configure your instance. You can specify the following variables in the `.env` file inside `packages/server` folder. Read [more](https://github.com/FlowiseAI/Flowise/blob/main/CONTRIBUTING.md#-env-variables)

## 📖 Documentation

You can view the Flowise Docs [here](https://docs.flowiseai.com/)

## 🌐 Self Host

Deploy Flowise self-hosted in your existing infrastructure, we support various [deployments](https://docs.flowiseai.com/configuration/deployment)

-   [AWS](https://docs.flowiseai.com/configuration/deployment/aws)
-   [Azure](https://docs.flowiseai.com/configuration/deployment/azure)
-   [Digital Ocean](https://docs.flowiseai.com/configuration/deployment/digital-ocean)
-   [GCP](https://docs.flowiseai.com/configuration/deployment/gcp)
-   [Alibaba Cloud](https://computenest.console.aliyun.com/service/instance/create/default?type=user&ServiceName=Flowise社区版)
-   <details>
      <summary>Others</summary>

    -   [Railway](https://docs.flowiseai.com/configuration/deployment/railway)

        [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/pn4G8S?referralCode=WVNPD9)

    -   [Northflank](https://northflank.com/stacks/deploy-flowiseai)

        [![Deploy to Northflank](https://assets.northflank.com/deploy_to_northflank_smm_36700fb050.svg)](https://northflank.com/stacks/deploy-flowiseai)

    -   [Render](https://docs.flowiseai.com/configuration/deployment/render)

        [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://docs.flowiseai.com/configuration/deployment/render)

    -   [HuggingFace Spaces](https://docs.flowiseai.com/configuration/deployment/hugging-face)

        <a href="https://huggingface.co/spaces/FlowiseAI/Flowise"><img src="https://huggingface.co/datasets/huggingface/badges/raw/main/open-in-hf-spaces-sm.svg" alt="HuggingFace Spaces"></a>

    -   [Elestio](https://elest.io/open-source/flowiseai)

        [![Deploy on Elestio](https://elest.io/images/logos/deploy-to-elestio-btn.png)](https://elest.io/open-source/flowiseai)

    -   [Sealos](https://template.sealos.io/deploy?templateName=flowise)

        [![Deploy on Sealos](https://sealos.io/Deploy-on-Sealos.svg)](https://template.sealos.io/deploy?templateName=flowise)

    -   [RepoCloud](https://repocloud.io/details/?app_id=29)

        [![Deploy on RepoCloud](https://d16t0pc4846x52.cloudfront.net/deploy.png)](https://repocloud.io/details/?app_id=29)

      </details>

## ☁️ Flowise Cloud

Get Started with [Flowise Cloud](https://flowiseai.com/).

## 🙋 Support

Feel free to ask any questions, raise problems, and request new features in [Discussion](https://github.com/FlowiseAI/Flowise/discussions).

## 🙌 Contributing

Thanks go to these awesome contributors

<a href="https://github.com/FlowiseAI/Flowise/graphs/contributors">
<img src="https://contrib.rocks/image?repo=FlowiseAI/Flowise" />
</a><br><br>

See [Contributing Guide](CONTRIBUTING.md). Reach out to us at [Discord](https://discord.gg/jbaHfsRVBW) if you have any questions or issues.

[![Star History Chart](https://api.star-history.com/svg?repos=FlowiseAI/Flowise&type=Timeline)](https://star-history.com/#FlowiseAI/Flowise&Date)

## 📄 License

Source code in this repository is made available under the [Apache License Version 2.0](LICENSE.md).
