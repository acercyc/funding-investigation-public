# Complete Analysis: University of Helsinki Flamma Research Funding Pages

**Date of Analysis**: December 2024  
**Base URL**: `https://flamma.helsinki.fi/en/group/tutkimuksen-tuki/tutkimusrahoitus`

---

## Table of Contents

1. [Overall Site Architecture](#overall-site-architecture)
2. [Main Landing Page Structure](#main-landing-page-structure)
3. [National Research Funding Page](#national-research-funding-page)
4. [International Research Funding Page](#international-research-funding-page)
5. [Strategic Funding Page](#strategic-funding-page)
6. [Navigation Structure](#navigation-structure)
7. [Information Architecture Patterns](#information-architecture-patterns)
8. [Content Types and Templates](#content-types-and-templates)

---

## Overall Site Architecture

### Layout Structure
The Flamma research funding section uses a **three-column layout**:

1. **Left Sidebar**: Hierarchical navigation tree (persistent across all pages)
2. **Center Column**: Main content area (page-specific information)
3. **Right Sidebar**: Supporting information (contact, resources, newsletter - consistent across most pages)

### Global Navigation Elements
- **Top Header**: University branding, global links (HELSINKIUNI HELP, IT HELPDESK, STUDIES SERVICE, FLAMMA, INSTRUCTIONS FOR TEACHING)
- **Language Switcher**: SUOMI (Finnish) / SVENSKA (Swedish) / English (default)
- **Main Navigation Bar**: Services and Instructions, University, News and Events, My Unit
- **Role-Based Tabs**: Employee, Supervisor, Teacher, **Researcher** (active when viewing funding pages)
- **Search Bar**: "Search on Flamma" prominently displayed
- **User Tools**: CREATE A NEWS ITEM, CREATE A POLL, SECURITY, TAKE PART & INFLUENCE, WORKGROUPS, TOOLS, FAVOURITES

---

## Main Landing Page Structure

**URL**: `/en/group/tutkimuksen-tuki/tutkimusrahoitus`  
**Page Title**: "Research funding services"

### Breadcrumb Navigation
```
Support for research and innovations > Research funding
```

### Main Content Sections

#### 1. Page Title and Introduction
- **Heading**: "Research funding services"
- **Introductory Text**: 
  > "Research Funding Services (RFS), in collaboration with faculties and units, assist researchers looking for research funding. In addition, RFS help researchers with proposal preparation and negotiations, and international funding opportunities."

#### 2. Campus Specific Guidelines (Expandable Accordion)
- **Section Type**: Expandable accordion with sub-sections
- **Main Accordion**: "Campus Specific Guidelines" (expandable)
- **Sub-sections** (each expandable independently):
  
  ##### City Center Campus Specialists
  - **Heading**: "City Center Campus Specialists"
  - **Content Structure**:
    - **Senior advisors**:
      - Mathias Haeggström (clickable link)
      - Vilma Hämäläinen (clickable link)
      - Sanna Villikka (clickable link)
    - **Grant coaches**:
      - Katja Ritari (clickable link)
      - Taina Tuori (clickable link)
  
  ##### Kumpula Campus Specialists
  - **Heading**: "Kumpula Campus Specialists"
  - **Content Structure**:
    - **Senior advisors**:
      - Kirsi Reyes-Anastacio (clickable link)
      - Tobias Tamelander (clickable link)
      - Satu Väisänen (clickable link)
    - **Grant coach**:
      - Jari Laamanen (clickable link)
  
  ##### Meilahti Campus Specialists
  - **Heading**: "Meilahti Campus Specialists"
  - **Content Structure**:
    - **Senior advisors**:
      - Mika Frederiksen (clickable link)
      - Mirkka Herranen (clickable link)
      - Iiro Hämäläinen (clickable link)
      - Eveniina Kettunen (clickable link)
    - **Grant coaches**:
      - Nelli Salminen (clickable link)
      - Leena Karhinen (clickable link)
  
  ##### Viikki Campus Specialists
  - **Heading**: "Viikki Campus Specialists"
  - **Content Structure**: 
    - **Note**: Content structure similar to other campuses (Senior advisors and Grant coaches)
    - **Related Links** (visible on page):
      - "Funding clock 2026" (link)
      - "Viikki Campus" (link)
      - "Faculty of Agriculture and Forestry" (link)
    - **Note**: Specific advisor/coach names require direct page access to verify current listings

**Note**: Each campus section contains contact information for campus-specific funding specialists. The sections can be expanded/collapsed independently.

### Right Sidebar (Consistent Across Pages)

#### Contact Section
- **Heading**: "Contact"
- **Email**: `researchfunding-services@helsinki.fi` (clickable link)

#### Training and Events Section
- **Heading**: "Training and Events"
- **Links**:
  - "Events and materials"
  - "Funding opportunities during different career stages (PDF)"

#### Research Funding Newsletter Section
- **Heading**: "RESEARCH FUNDING NEWSLETTER"
- **Subscription Instructions**:
  - **Subscribe by email**: 
    - To: `majordomo@helsinki.fi`
    - Subject: (leave empty)
    - Body text: `subscribe researchservice-newsletter forename.surname@helsinki.fi`
  - **Unsubscribe by email**:
    - To: `majordomo@helsinki.fi`
    - Subject: (leave empty)
    - Body text: `unsubscribe researchservice-newsletter forename.surname@helsinki.fi`

---

## National Research Funding Page

**URL**: `/en/group/tutkimuksen-tuki/kansallinen-tutkimusrahoitus`  
**Page Title**: "National Research Funding"

### Breadcrumb Navigation
```
Support for research and innovations > Research funding > National Research Funding
```

### Main Content Structure

#### 1. Lead Instructions (Always First)
- **Paragraph 1**: 
  > "If you are applying for funding from national funding sources, contact your own unit, Research Funding Services and Financial Services well in advance."
  
- **Paragraph 2** (Conditional - appears when applicable):
  > "If your application includes international collaboration, please complete the mandatory risk assessment ([instructions here](link))."

#### 2. Funder Descriptions (Structured Paragraphs)

Each major funder receives a dedicated paragraph with consistent structure:

##### Research Council of Finland
- **Who can apply**: Researchers, research groups, and organizations
- **What is funded**: Salary, research costs, researchers' mobility
- **Additional funding types**: Projects, Centres of Excellence, joint international projects, research infrastructures

##### Strategic Research Council (SRC)
- **Target**: Large, multidisciplinary consortia
- **Focus**: Continuous interaction with information users
- **Decision maker**: Strategic Research Council (SRC) decides on funded projects

##### Business Finland
- **Purpose**: Finances cooperation and joint projects of research organizations and companies
- **Funding scope**: Development of research ideas, new knowledge, and innovations

##### Other National Research Funding
- **Examples**: National foundations
- **Funding type**: Personal grants for purposes determined by their rules
- **Additional**: Many also provide funding to research projects

##### State Council and Ministries
- **Source**: State Council grants funding for various investigation and research activities
- **Regulation**: Use of funding granted by Ministries and other entities granting state aid is primarily regulated by the State Aid Act

##### Joint EU-National Funding
- **Note**: Research Council of Finland, Business Finland, and Ministries also provide funding for various projects jointly funded by the EU and national bodies

### Left Sidebar Navigation (Expanded)
Under "National Research Funding", the following sub-items are visible:
- Research Council of Finland
- Business Finland
- Other National Research Funding

---

## International Research Funding Page

**URL**: `/en/group/tutkimuksen-tuki/kansainvalinen-tutkimusrahoitus`  
**Page Title**: "International Research Funding"

### Breadcrumb Navigation
```
Support for research and innovations > Research funding > International Research Funding
```

### Main Content Structure

#### 1. Lead Instructions (Always First)
- **Paragraph 1**: 
  > "When considering applying for international research funding, please contact your own unit, research funding service and financial service on your campus well in advance."
  
- **Paragraph 2** (Mandatory Compliance):
  > "Please note you are required to conduct a mandatory risk assessment when applying for international funding. For more information, please check the [risk assessment guideline](link)."

#### 2. Funder Descriptions

##### European Union Framework Programmes (FP)
- **What they fund**: Research, technological development, and innovation
- **Mechanism**: Provide grants to research and innovation projects through open and competitive calls

##### United States Funding
- **Federal Agencies**:
  - NIH (National Institute of Health)
  - DoE (Department of Energy)
  - DoD (Department of Defense)
- **Additional**: Various other federal agencies

##### Other International Sources
- **Categories**:
  - Multinational research funding organizations
  - Nordic research funding organizations
  - Various national foundations

### Left Sidebar Navigation (Expanded)
Under "International Research Funding", the following sub-items are visible:
- EU Funding
- US Funding
- Other International Funding

---

## Strategic Funding Page

**URL**: `/en/group/tutkimuksen-tuki/strateginen-rahoitus`  
**Page Title**: "Strategic funding"

### Breadcrumb Navigation
```
Support for research and innovations > Research funding > Strategic funding
```

### Main Content Structure

#### 1. Introduction
- **Definition**: Instruments of strategic funding include the Research Council of Finland's Flagship Programme, which supports developing national knowhow networks to promote economic growth, as well as the future-oriented research and innovation activities of the university.

#### 2. Major Strategic Funding Instruments

##### European Institute of Technology (EIT)
- **Focus**: Specific funding opportunities within European research funding
- **Requirement**: Applying for EIT funding often requires membership of the organization in a thematic community (Knowledge and Innovation Community - KIC)

##### Strategic Research Council (SRC)
- **Operating at**: Research Council of Finland
- **Purpose**: Provides funding to search for information on and solutions to societal questions defined by the council
- **Focus**: Societal impact and problem-solving

#### 3. Expandable Sections (Accordions)

##### The Flagship Programme of the Research Council of Finland
- **Heading**: "The Flagship Programme of the Research Council of Finland"
- **Content**:
  - The University of Helsinki is involved in two Flagship Programmes of the Academy of Finland (Research Council of Finland):
    - **Finnish Centre for Artificial Intelligence FCAI**
    - **InFLAMES Research Flagship**
  - The Flagship Programme is a new funding instrument for high-quality research, societal impact, and collaboration
  - Flagships are selected through a competitive process
  - Funding duration: **8 years**
  - Link: "More information on the Flagship Programme" (external link)

##### PROFI
- **Heading**: "PROFI"
- **Full Name**: "Competitive funding to strengthen university research profiles" (profiling funds)
- **Content**:
  - **Purpose**: Fixed-term development funding aimed at strengthening and speeding up the strategic profiling of Finnish universities
  - **Goals**:
    - Improve research quality
    - Clarify roles of actors in the Finnish research field
    - Promote collaboration
  - **Selection Process**:
    - Profiling areas are chosen based on the university's strategy
    - Focus on existing high-quality, emerging, or new areas with top-level potential
    - At the University of Helsinki, areas are chosen from proposals by faculty deans and directors of joint operational units
    - Funding is applied for by universities, with each submitting its own application
  - **Contact Information**:
    - Email: `profi@helsinki.fi`
    - Link: "Flamma workgroup pages for PROFI support"
    - **Contacts**: Javier Arevalo, Johanna Kolhinen

##### EIT Innovation Communities (Knowledge and Innovation Communities - KICs)
- **Heading**: "EIT Innovation Communities (Knowledge and Innovation Communities - KIC)"
- **Full Name**: "European Institute of Innovation and Technology (EIT) Innovation Communities"
- **Content**:
  - **Establishment**: EIT was created in 2008 as an independent EU body
  - **Purpose**: Bring together higher education institutions, research labs, and companies (the "Knowledge Triangle") to boost innovation and entrepreneurship across Europe, turning ideas into products, services, jobs, and growth
  - **Framework Programme Context**: As part of "Pillar 3 'Innovative Europe'" of the Framework Programme, the EIT contributes to four key strategic orientations of the Horizon Europe Strategic Plan:
    1. Strengthening sustainable innovation ecosystems across Europe
    2. Fostering entrepreneurial and innovation skills in lifelong learning and supporting entrepreneurial transformation of EU universities
    3. Bringing new solutions to global societal challenges to the market
    4. Creating synergies and added value within Horizon Europe
  - **Application Requirement**: Applying for EIT funding often requires membership of the organization in a thematic community (Knowledge and Innovation Community - KIC)

---

## Navigation Structure

### Left Sidebar: Complete Hierarchy

```
SUPPORT FOR RESEARCH AND INNOVATIONS
└── RESEARCH FUNDING
    ├── Research Funding Databases (standalone link)
    ├── National Research Funding (expandable)
    │   ├── Research Council of Finland
    │   ├── Business Finland
    │   └── Other National Research Funding
    ├── International Research Funding (expandable)
    │   ├── EU Funding
    │   ├── US Funding
    │   └── Other International Funding
    ├── Strategic funding (standalone link)
    ├── University of Helsinki's own research funding (expandable)
    │   ├── Additional funding for research 2024 - 2028
    │   └── Support for doctoral [researchers]
    └── Funding application app (standalone link)
```

### Navigation Behavior
- **Expandable items**: Show arrow indicators (right-pointing when collapsed, down-pointing when expanded)
- **Active page**: Highlighted in blue when selected
- **Breadcrumbs**: Always visible in center column, showing full path

---

## Information Architecture Patterns

### Standard Page Template Structure

Every category page (National, International, Strategic) follows this pattern:

1. **Breadcrumb Navigation** (top of content area)
2. **Page Title** (H1 heading)
3. **Lead Instructions** (1-2 paragraphs, always first)
   - Contact information requirement
   - Compliance/risk assessment requirements (if applicable)
4. **Funder Descriptions** (structured paragraphs)
   - Each major funder gets 1-2 paragraphs
   - Consistent structure: Who → What → How/Why
5. **Expandable Sections** (if applicable)
   - Accordion-style expandable content
   - Used for detailed sub-information
6. **Right Sidebar** (consistent across pages)
   - Contact information
   - Training and events
   - Newsletter subscription

### Content Organization Principles

1. **Source-Based Categorization**: Primary organization by funding source (National, International, University's own)
2. **Geographic Support**: Campus-specific specialists for personalized assistance
3. **Service-Oriented**: Emphasis on Research Funding Services (RFS) as active support, not just information repository
4. **Compliance-First**: Risk assessment and early contact requirements prominently displayed
5. **Hierarchical Information**: High-level overview first, detailed information in expandable sections

### Information Density

- **Landing Page**: Low density, focus on navigation and service introduction
- **Category Pages**: Medium density, structured funder descriptions
- **Sub-pages**: Higher density, detailed application procedures and requirements

---

## Content Types and Templates

### Type 1: Landing/Overview Page
**Example**: Main Research Funding page

**Structure**:
- Service introduction
- Campus-specific support (accordions)
- Navigation to sub-sections

**Purpose**: Orientation and navigation hub

### Type 2: Category Overview Page
**Examples**: National Research Funding, International Research Funding

**Structure**:
- Lead instructions (contact requirements)
- Compliance reminders (risk assessment)
- Funder descriptions (structured paragraphs)
- Links to sub-pages or external resources

**Purpose**: High-level overview of funding category with links to detailed information

### Type 3: Strategic/Program Page
**Example**: Strategic funding page

**Structure**:
- Program introduction
- Major instruments overview
- Expandable sections for detailed information
- Links to application processes

**Purpose**: Detailed information about specific funding programs or instruments

### Type 4: Support/Resource Page
**Examples**: Campus specialists, Training and Events

**Structure**:
- Contact information
- Resource links
- Event calendars
- PDF guides

**Purpose**: Direct access to support services and resources

---

## Key Findings

### Design Philosophy
1. **Triage System**: Pages provide enough information to identify potential funders, then direct users to human experts (RFS, Campus Specialists)
2. **Compliance Emphasis**: Mandatory requirements (risk assessments, early contact) are prominently displayed
3. **Geographic Personalization**: Campus-based specialists ensure local support
4. **Service Integration**: Funding information is integrated with support services, not isolated

### Information Hierarchy
1. **Critical Actions First**: Contact requirements, compliance reminders
2. **Funder Overviews Second**: High-level descriptions to help researchers identify relevant sources
3. **Detailed Information Third**: Expandable sections, sub-pages, external links
4. **Support Resources Always Available**: Right sidebar with contact and training information

### User Journey
1. **Discovery**: Landing page → Category page → Funder description
2. **Identification**: Funder description helps researcher identify if source is relevant
3. **Action**: Contact RFS/Campus Specialist for detailed guidance
4. **Application**: Use Funding application app or external funder portals

---

## Notes on Content Maintenance

- Pages include "Edit" buttons for coordinators
- "Submit feedback on content" functionality available
- Content appears to be maintained by Research Funding Services team
- Pages support multiple languages (Finnish, Swedish, English)
- Newsletter subscription suggests regular content updates

---

## Recommendations for Understanding the System

To fully understand any specific funding opportunity:

1. **Start at the category page** (National/International/Strategic) for overview
2. **Check lead instructions** for contact and compliance requirements
3. **Review funder descriptions** to identify relevant sources
4. **Contact RFS or Campus Specialist** for detailed guidance
5. **Use Funding application app** for internal applications
6. **Subscribe to newsletter** for updates on new opportunities

---

## Complete Expandable Content Summary

This section provides a complete list of all expandable (accordion) content found across the research funding pages.

### Main Landing Page Expandables

#### Campus Specific Guidelines
Contains four campus-specific specialist sections:

1. **City Center Campus Specialists**
   - Senior advisors: Mathias Haeggström, Vilma Hämäläinen, Sanna Villikka
   - Grant coaches: Katja Ritari, Taina Tuori

2. **Kumpula Campus Specialists**
   - Senior advisors: Kirsi Reyes-Anastacio, Tobias Tamelander, Satu Väisänen
   - Grant coach: Jari Laamanen

3. **Meilahti Campus Specialists**
   - Senior advisors: Mika Frederiksen, Mirkka Herranen, Iiro Hämäläinen, Eveniina Kettunen
   - Grant coaches: Nelli Salminen, Leena Karhinen

4. **Viikki Campus Specialists**
   - Structure: Similar to other campuses (Senior advisors and Grant coaches)
   - Related links: "Funding clock 2026", "Viikki Campus", "Faculty of Agriculture and Forestry"
   - Note: Specific names require direct page access to verify current listings

### Strategic Funding Page Expandables

1. **The Flagship Programme of the Research Council of Finland**
   - University involvement: Finnish Centre for Artificial Intelligence FCAI, InFLAMES Research Flagship
   - Funding instrument: High-quality research, societal impact, collaboration
   - Selection: Competitive process
   - Duration: 8 years
   - Link: "More information on the Flagship Programme"

2. **PROFI**
   - Full name: "Competitive funding to strengthen university research profiles"
   - Purpose: Fixed-term development funding for strategic profiling
   - Goals: Improve research quality, clarify roles, promote collaboration
   - Selection: Based on university strategy, proposals from faculty deans
   - Contact: `profi@helsinki.fi`
   - Contacts: Javier Arevalo, Johanna Kolhinen
   - Link: "Flamma workgroup pages for PROFI support"

3. **EIT Innovation Communities (Knowledge and Innovation Communities - KICs)**
   - Full name: "European Institute of Innovation and Technology (EIT) Innovation Communities"
   - Established: 2008 as independent EU body
   - Purpose: Knowledge Triangle (higher education, research labs, companies) for innovation
   - Framework: Part of "Pillar 3 'Innovative Europe'" of Horizon Europe
   - Strategic orientations: 4 key areas (sustainable ecosystems, entrepreneurial skills, societal solutions, synergies)
   - Requirement: Membership in thematic community (KIC) often required

---

**End of Analysis**

