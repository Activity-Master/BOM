# 📦 ActivityMaster BOM (Bill of Materials)

[![JDK](https://img.shields.io/badge/JDK-25%2B-0A7?logo=java)](https://openjdk.org/projects/jdk/25/)
[![Build](https://img.shields.io/badge/Build-Maven-C71A36?logo=apachemaven)](https://maven.apache.org/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Centralizes compatible dependency versions for Activity Master modules. Import this BOM to avoid hardcoding versions for Activity Master artifacts.

## 🔧 Usage (Maven)
```
<dependencyManagement>
  <dependencies>
    <dependency>
      <groupId>com.guicedee.activitymaster</groupId>
      <artifactId>activitymaster-bom</artifactId>
      <version>${activitymaster.version}</version>
      <type>pom</type>
      <scope>import</scope>
    </dependency>
  </dependencies>
</dependencyManagement>
```

Then declare dependencies without versions:
```
<dependency>
  <groupId>com.guicedee.activitymaster</groupId>
  <artifactId>activity-master-client</artifactId>
</dependency>
```

## 📚 Docs & Rules
- Pact: `PACT.md`
- Rules: `RULES.md`
- Guides: `GUIDES.md`
- Architecture index: `docs/architecture/README.md`

## 📝 License & Contributions
- License: Apache 2.0
- Issues/PRs welcome; keep docs aligned with BOM changes.
