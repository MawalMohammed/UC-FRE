# UC-FRE Framework Analysis Tool

A web-based tool for assessing the context of Requirements Engineering (RE) based on eight contextual dimensions.

## Live Demo

**[Try the Tool Online](https://MawalMohammed.github.io/UC-FRE/)**

## Overview

The UC-FRE (Universal Context Framework for Requirements Engineering) helps practitioners and researchers assess and compare the context of requirements engineering activities. The tool visualizes assessments using an interactive radar/spider chart across eight key dimensions.

## The Eight Dimensions

| Dimension | Description |
|-----------|-------------|
| **Process Rigor** | The degree of formality and strictness in following defined RE processes, methodologies, and standards |
| **Stakeholder Engagement** | The level and quality of involvement from all relevant stakeholders throughout the RE process |
| **Documentation Formality** | The extent to which requirements and related artifacts are formally documented and maintained |
| **Organizational Maturity** | The organization's capability level in RE practices, typically measured against maturity models |
| **Adaptability** | The ability to respond to changing requirements, market conditions, and stakeholder needs |
| **System Complexity** | The inherent complexity of the system being developed, including technical and domain complexity |
| **Team Distribution** | The geographical and temporal distribution of the development team and stakeholders |
| **Risk Profile** | The overall risk level associated with the project, including technical, business, and compliance risks |

## Features

- **Interactive Radar Chart**: Visualize all eight dimensions simultaneously
- **Dual Assessment**: Compare "Current Situation" vs "Project Situation"
- **Gap Analysis**: Automatically calculates gaps between current and target states
- **Export Options**:
  - Export to JSON for programmatic use
  - Export to CSV for spreadsheet analysis
  - Print-friendly report generation
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **No Installation Required**: Runs entirely in the browser

## Usage

### Online

Visit the [live demo](https://MawalMohammed.github.io/UC-FRE/) to use the tool directly in your browser.

### Local

1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. No build process or server required

```bash
git clone https://github.com/MawalMohammed/UC-FRE.git
cd UC-FRE
# Open index.html in your browser
```

## How to Use the Tool

1. **Enter Project Name**: Give your assessment a name for identification
2. **Assess Current Situation** (Blue): Rate each dimension from 0-10 based on your current RE context
3. **Define Project Requirements** (Green): Rate each dimension from 0-10 based on what your project needs
4. **Analyze Gaps**: Review the gap analysis to identify areas needing attention
5. **Export Results**: Download your assessment as JSON, CSV, or print a report

## Scoring Guide

| Score | Interpretation |
|-------|---------------|
| 0-2 | Very Low / Minimal |
| 3-4 | Low / Basic |
| 5-6 | Moderate / Standard |
| 7-8 | High / Advanced |
| 9-10 | Very High / Comprehensive |

## Technology Stack

- **React 18**: UI framework
- **Recharts**: Chart visualization library
- **Tailwind CSS**: Styling
- **Lucide Icons**: Icon library

All dependencies are loaded via CDN, making the tool completely standalone.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use this tool in your research, please cite:

```
@software{ucfre_tool,
  title = {UC-FRE Framework Analysis Tool},
  author = {YOUR_NAME},
  year = {2025},
  url = {https://github.com/MawalMohammed/UC-FRE}
}
```

## Acknowledgments

- Built for the Requirements Engineering research community
- Inspired by contextual factors research in software engineering
