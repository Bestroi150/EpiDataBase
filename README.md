# EpiDataBase

XML validation schemas for epigraphic data used in educational contexts.

## Overview

This project provides validation schemas for epigraphic XML files, designed to help students learn XML structure and validation techniques.

## Contents

- **schema.xsd** - XML Schema Definition for validating epigraphic XML documents
- **epiData.dtd** - Document Type Definition for epigraphic data validation

## Purpose

These schemas are designed to validate epigraphic (inscription-related) XML files, allowing students to:
- Learn proper XML structure
- Understand schema and DTD validation
- Work with well-formed epigraphic data

## Usage

### Using XSD Validation
Reference the schema in your XML file:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<root xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="schema.xsd">
    <!-- Your content here -->
</root>
```

### Using DTD Validation
Reference the DTD in your XML file:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE root SYSTEM "epiData.dtd">
<root>
    <!-- Your content here -->
</root>
```

## License

This work is licensed under the Creative Commons Attribution 4.0 International License. See the `LICENSE` file for details.

## Educational Context

Created as course material for teaching XML validation and epigraphic data structures.
