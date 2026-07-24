# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Budget RF Lab is a Systemization of Knowledge (SoK) repository for building RF laboratories on a budget for homebrewers. This is a documentation-focused project containing equipment lists, project guides, and resources for RF enthusiasts in different geographical regions.

## Repository Structure

The repository is organized into several key components:

- **Main documentation**: README.md (primary project overview)
- **Equipment lists**: Region-specific markdown files (en_in.md, tr-tr.md) containing detailed equipment recommendations with pricing and vendor information
- **FLOSS Tools**: FLOSS_Tools.md - comprehensive list of free/libre open-source software for RF work
- **Projects**: Projects.md - starter projects with assembly times, costs, and difficulty levels
- **RF Components**: RFParts.md - common hacker-friendly RF integrated circuits and components

## Content Architecture

### Region-Specific Equipment Lists
Equipment lists follow a standardized table format including:
- Item number and name
- Cost information in local currency (INR for India, TRY for Türkiye)
- Vendor recommendations and purchasing links
- Assembly time and difficulty estimates
- Pro-tips and usage notes

### Project Documentation Structure
Projects are documented with:
- Sequential numbering
- Assembly time estimates
- Cost breakdowns
- Vendor/supplier information
- Comments and tips for implementation
- Links to external resources and GitHub repositories

### Software Tools Categorization
FLOSS tools are organized by functionality:
- Circuit simulation (LTspice, Ngspice)
- Filter design (Elsie, AADE Filter Design)
- PCB design (KiCad, LibrePCB)
- 3D modeling (FreeCAD)
- Mathematical computing (GNU Octave, Anaconda)
- Electromagnetic modeling (OpenEMS, Epsilon Forge)

## File Naming Conventions

- Geographic/language specific files use format: `{language_code}_{country_code}.md` (e.g., en_in.md, tr-tr.md)
- Main documentation uses descriptive names: README.md, FLOSS_Tools.md, Projects.md, RFParts.md
- All files use markdown format with .md extension

## Contribution Guidelines

When contributing to this repository:

1. **New Regions**: Create region-specific equipment lists following the established table format
2. **Project Additions**: Add to Projects.md using the existing table structure with complete information
3. **Software Tools**: Contribute to FLOSS_Tools.md with proper categorization
4. **RF Components**: Add new components to RFParts.md with brief descriptions

## Key External References

The project references several important external resources and GitHub repositories, particularly:
- https://github.com/kholia/ (multiple referenced projects)
- Hardware vendors specific to each region
- Educational resources and tutorials

## Documentation Style

- Tables are used extensively for structured information presentation
- Costs are provided in local currencies
- Assembly times are estimated in minutes
- Vendor recommendations include specific supplier names where applicable
- Comments and tips provide practical advice from experienced homebrewers

## License

This repository is released under the Unlicense, dedicating all content to the public domain.