<!-- Banner / Logo -->
<p align="center">
  <img src="../logo/logo.png" alt="Woodn Company Logo" width="200"/>
</p>

<h1 align="center">Woodn Company</h1>

<p align="center">
  <em>Helping people connect with trusted artisans — simple, fast, reliable.</em>
</p>

---

## 👋 About Us

Woodn Company makes it easy to discover, connect, and book appointments with skilled **artisans**.  
 — a modern, digital way to reach professionals in your area.

---

## 🚀 What We're Building

- 🛠️ A platform to showcase artisans and their work
- 📅 Smart booking & scheduling tools
- 🔍 Search & filter by specialty and availability
- 🌍 Local focus with a clean digital experience

---

## 📫 Contact

- 📧 Email: contact@woodn.fr
- 🌐 Website: https://woodn.fr

---

<p align="center">
  💡 Crafted with care by <b>Woodn Company</b>
</p>
---

## 📂 Projects

- [App Backend](https://github.com/Woodn-Company/woodnCompany/tree/main/apps/api-woodn) _NestJS backend API_
- [Web Frontend](https://github.com/Woodn-Company/woodnCompany/tree/main/apps/woodn) _Next.js customer app_
- [Web Pro Frontend](https://github.com/Woodn-Company/woodnCompany/tree/main/apps/woodn-pro) _Next.js pro app_

---

# Deployment Information

## Current Deployments

### Production (prod)

- **api-woodn**: N/A (PM2)
- **woodn**: N/A (PM2)
- **woodn-pro**: N/A (PM2)

### Demo (demo)

- **api-woodn**: `woodndev/woodn:api-woodn-demo-0.3.1`
- **woodn**: `woodndev/woodn:woodn-demo-0.3.0`
- **woodn-pro**: `woodndev/woodn:api-woodn-demo-0.3.0`

### Development (dev)

- **api-woodn**: `woodndev/woodn:api-woodn-dev-0.3.3`
- **woodn**: `woodndev/woodn:woodn-dev-0.3.3`
- **woodn-pro**: `woodndev/woodn:woodn-pro-dev-0.3.3`

---

## Release Descriptions

### Production (prod) - Latest stable releases

#### api-woodn

- **Version**: N/A
- ## **Release Notes**:
  -
  -
  -

#### woodn

- **Version**: N/A
- **Release Notes**:
  - 
  - 
  - 

#### woodn-pro

- **Version**: N/A
- **Release Notes**:
  - 
  - 
  - 

### Demo (demo) - Demo and new features in pre-release

#### api-woodn

- **Version**: 0.3.1
- **Release Notes**:
  - Need to update pro registration workflow

#### woodn

- **Version**: 0.3.0
- **Release Notes**:
  - Chat implemented

#### woodn-pro

- **Version**: 0.3.0
- **Release Notes**:
  - Chat in progress

### Development (dev) - Latest development builds

#### api-woodn

- **Version**: 0.3.3
- **Development Notes**:
  - WIP

#### woodn

- **Version**: 0.3.3
- **Development Notes**:
  - WIP

#### woodn-pro

- **Version**: 0.3.3
- **Development Notes**:
  - WIP

---

## Quick Release Template

### api-woodn

- **Version**: X.Y.Z
- **Release Notes**:
  - [Feature/Bug Fix/Improvement description]
  - [Another change]
  - [Performance/Security update]

### woodn

- **Version**: X.Y.Z
- **Release Notes**:
  - [UI/UX changes]
  - [New functionality]
  - [Bug fixes]

### woodn-pro

- **Version**: X.Y.Z
- **Release Notes**:
  - [Pro-specific features]
  - [Integration updates]
  - [User experience improvements]

---

## Versioning Tutorial

This project uses **Semantic Versioning (SemVer)** with the format: `MAJOR.MINOR.PATCH`

### Version Format: X.Y.Z

- **X (MAJOR)**: Breaking changes that are not backward compatible
- **Y (MINOR)**: New features that are backward compatible
- **Z (PATCH)**: Bug fixes that are backward compatible

### Examples

| Version | Description                         |
| ------- | ----------------------------------- |
| 1.0.0   | Initial release                     |
| 1.0.1   | Bug fix (backward compatible)       |
| 1.1.0   | New feature (backward compatible)   |
| 1.1.1   | Another bug fix                     |
| 2.0.0   | Major release with breaking changes |
| 2.0.1   | Bug fix in major version            |
| 2.1.0   | New feature in major version        |

### Versioning Rules

#### 1. MAJOR (X): Increment when you make incompatible API changes

- Breaking changes to existing functionality
- Removal of deprecated features
- Major architectural changes

#### 2. MINOR (Y): Increment when you add functionality in a backward compatible manner

- New features
- New API endpoints
- New configuration options
- Deprecation warnings (without removal)

#### 3. PATCH (Z): Increment when you make backward compatible bug fixes

- Bug fixes
- Security patches
- Performance improvements
- Documentation updates

### Deployment Environments

- **prod**: Production releases with stable versions
- **demo**: Demo/staging releases, usually one version before prod and demo version
- **dev**: Development builds for testing the deployment

### Best Practices

1. Always start with 1.0.0 for the first stable release
2. Increment the right number based on the type of change
3. Never skip version numbers
4. Use pre-release versions for testing before major releases
5. Document breaking changes in release notes
6. Tag releases in your version control system
7. Keep version numbers in sync across all services when possible
