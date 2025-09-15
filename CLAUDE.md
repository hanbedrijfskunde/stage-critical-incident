# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a complete RevealJS-based interactive presentation for educational use, specifically designed for discussing critical incidents during student internships using the "Incidentmethode Intervisie" methodology.

## Repository Structure

- `docs/` - **MAIN: GitHub Pages deployment folder**
  - `index.html` - Interactive RevealJS presentation with native speaker timer
  - `dist/` - RevealJS core files (CSS, JS, themes)
  - `plugin/` - RevealJS plugins (notes, markdown, highlight)
  - `README.md` - Complete deployment guide for GitHub Pages
- `sources/` - Original methodology documents and materials
  - `methode-beschrijving.md` - Source material from Blankenstein & Partners
- `slide-deck-opzet.md` - Original slide planning document (reference)
- `UX-TEST-REPORT.md` - Complete UX test results (Score: 9.7/10)
- `DESIGN-REVIEW-REPORT.md` - Design analysis and optimization recommendations
- `FINAL-IMPLEMENTATION-REPORT.md` - Complete implementation and testing results
- `POST-FIX-DESIGN-REPORT.md` - Post-optimization analysis and outcomes
- `.claude/` - Claude Code configuration directory
- `.playwright-mcp/` - Test screenshots and browser automation results

## Key Features

### Interactive Presentation
- **Native speaker timer**: Built-in RevealJS timer in speaker view ('s' key)
- **Clean slide design**: Minimalist approach with one focus per slide
- **Timing visibility**: Step duration shown on each timed slide for students
- **Responsive design**: Optimized for desktop, tablet, and mobile devices
- **Educational styling**: Professional theme with beautiful method diagram

### Methodology Implementation
- **6-step Incidentmethode Intervisie** fully implemented across 15 slides
- **Timed phases**: 10, 5, 15, 8, 8, 5, 5 minutes per step (visible on slides)
- **HBO Bedrijfskunde context**: Examples relevant for business students
- **Detailed speaker guidance**: Comprehensive timing and instruction notes
- **Case selection process**: Clear timing for democratic case selection (8-10 min in STAP 1)

### Technical Implementation
- **RevealJS 5.2.1** framework with native plugins only
- **Minimalist CSS design** optimized for content fit and focus
- **CSS Grid method diagram** with gradients and hover effects
- **Mobile-first responsive** design with height-based media queries
- **GitHub Pages ready** deployment with clean, self-contained structure

## Development Workflow

### Working with the Presentation
1. **Primary development** happens in `/docs` folder
2. **Testing**: Use local HTTP server or GitHub Pages
3. **Deployment**: Push to GitHub, enable Pages with "main/docs" setting

### File Organization
- **Never modify** files outside `/docs` for presentation changes
- **Reference materials** stay in `/sources` and root level
- **Test reports** and documentation at root level

## Deployment Status

- ✅ **Production ready**: UX tested and approved
- ✅ **GitHub Pages compatible**: All assets self-contained
- ✅ **Mobile optimized**: Responsive across all device types
- ✅ **Classroom tested**: Timer and navigation functions verified

## Usage Instructions

### For Instructors
1. Navigate to GitHub Pages URL or serve `/docs` locally
2. Press 'f' for fullscreen presentation mode
3. Press 's' for speaker notes with built-in timer and detailed instructions
4. Use arrow keys for slide navigation
5. Follow timing indicators on each slide and in speaker notes

### For Students
- Follow along on personal devices via GitHub Pages URL
- Touch-friendly navigation on mobile/tablet devices
- Step timing visible on each slide for time awareness
- Clean, distraction-free slide design optimized for learning

## Technical Configuration

The repository includes Claude Code permissions for:
- File search and analysis capabilities
- Git operations for version control
- Browser automation for UX testing
- RevealJS framework integration