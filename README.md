# business-intelligence-compendium

People often ask how I know every tool, and I don't. I know the underlying concepts and then figure out how to apply them in a tool.

This set of documentation shows common BI steps at both a conceptual level and how to implement in individual tools. I don't buy in or encourage the tool vs tool battles we see online, and want to bring together the commonalities found in many of the tools that are driven by using data best practices.

## Structure of Content

- Explain concept generally - use visuals and diagrams
- Use same sample data consistently across all examples (if possible)
- Tool how-to
- Show guided example
- Provide link to official documentation if available
- Use consistent steps and terminology - explain where terms are different across tools

## Presentation of Content

- Start w/ Markdown in GitHub repo - Folders by topic
  - Future state: Website
- Use mermaid for diagrams
- Use screenshots saved in static folders organized in a thoughtful way
- State versions of software used in examples
- Videos are good, visuals are good
- We will value readability and understanding before optimization & min/maxing
- When using database connections, we will favor using sqlite since it can be packaged with training materials easily and requires no installation.

## Tools

This list is only brainstorming, and I will select some to start with that I have experience with. I'm hopeful that others will contribute to this repo over time to expand the tool list.

Here is some criteria for tools I want to highlight. This is not a list of requirements, and not every tool will have all these aspects:

- Open source or free to use
- Widely adopted/popular in the industry
- Easy to get started
- Low-code

I will stick to the base tools that are shipped with the product or only use vendor developed extensions. For Python and R, I will only use common and widely adopted packages. I will avoid using code in tools that are marketed as "low code".

### Possible Tools

- Excel
- Power BI Desktop
- KNIME AP
- Tableau Public
- Python
  - Pandas/Polars
  - Matplotlib/Seaborn/Plotly
- R Studio
  - ggplot2
- SQL
  - sqlite
- Metabase

## Collaboration

Build this repo with collaboration in mind. Setup repo to accept PR's from others for new tools or better documentation of existing.

## Sections

### Skills

### Data Concepts

- Problem statements
- Filter first
- Data types
- Dimensions and measures
- Reading documentation
  - Vendor docs & communities
  - Googling
  - 3rd parties like stack overflow

### Data Modelling

- Star Schema
  - Facts vs Dims
  - Relationships vs Joins
- OBT
  - Tall v Wide
- Date Tables/Date logic

### Data Prep

- DAGs

#### In/Out

- Reading files
- Reading databases
- Structuring
- Removing/Adding fields
- Renaming fields
- Re-typing fields

#### Dataset Filtering

- Dimensions
- Numbers
- Rows

#### Combining two datasets

- Joins
  - Inner join
  - Left/Right join
  - Anti-join
  - Cross-join/Cartesian join
  - Joins as filters
- Unions
  - Field structure/naming

#### Calculations

- Add a column (Row-by-row)
- Flexible (ie ratios)
- Multi-Row calculations
- Strings
- Dates
- Math
- Logical

#### Advanced Prep

- Iteration/Looping
- Parameterization/Variables
- Multi-Field
- Conditional operations
- If statements
- Nested If vs Table + Join

### Presenting Data

#### Basic Visualization

- Bar chart
- Line chart
- Scatter plot/Bubble chart
- Tables and Matrices
- Proportional charting - Donut/Pie/Segmented Bar
- BANs

#### Visual Filters

- On visual filtering
- Behind the scenes filtering
- Data source filtering
- Filter types (Dropdown, single/multi-check, etc)
- RLS

#### Advanced Visuals

- Boxplot
- Gantt
- Radar/Polar
- Waterfall
- Sankey
- Combo charts
- Dual Axis

#### Mapping

- GeoSpatial data considerations
- Points
- Shapes
- Buffers/Areas
- Sources of data
- Cloropleth
- Points
- Networks
- Layers

#### Interactivity

- CRUD
- Parameterization / variables
- On-click behaviors
  - Drag to select
  - Links
  - Filtering
  - Highlight
- On Hover
  - Tooltips
  - Viz-in-tooltip
- Buttons, sliders
- Drill-down
- Zooming/panning

#### Accessibility

- Alt text
- Color blindness
- Font sizing

### Sharing & Productionalizing

- Publishing
- Debugging/Performance

### Example Project

- Input
- Prep
- Visualization
- Interaction
- Accessibility
- Host
- Update/Refresh
- Share
