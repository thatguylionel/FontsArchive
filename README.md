# Font Extension for Jasper Reports

## Overview

The Font Extension library is designed to enhance the application of fonts to Jasper Reports, making it easier to extend
fonts for the original iReport/JasperReport environments. I suspect that newer versions have this functionality built
in, however, for historic purposes, I will keep this project available.

### NOTE: Trueno Font Library Information

This library incorporates the `Trueno Font` by [KineticPlasma Fonts](https://www.fontspace.com/trueno-font-f22345).
While this font is open and free to use, it is licensed under
the [SIL Open Font License (OFL)](https://www.fontspace.com/help#license-17). The inclusion of this font in this library
is solely for educational purposes. We are not responsible for any commercial use of the font. If you plan to use the
Trueno Font commercially, please review the licensing documentation or contact a representative from KineticPlasma Fonts
before proceeding.

## About

This library allows you to include additional fonts in your Jasper Reports, making it easier to create professionally
styled reports.

## Dependency

Before including the dependency, ensure that the project has been compiled in your local working environment. If Maven
is set up on your local terminal, you can compile the project using the following command within the project path:

```bash
mvn clean install -X
```

Alternatively, you can compile the project from your IDE.

Include the following dependency in your `pom.xml`:

```xml

<dependency>
    <groupId>com.tgl</groupId>
    <artifactId>FontsArchive</artifactId>
    <version>1.0</version>
</dependency>
```

## Getting Started

To get started with using the Font Extension library, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/thatguylionel/fontsarchive.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd fontsarchive
   ```
3. **Build the project using Maven:**
   ```bash
   mvn clean install
   ```
