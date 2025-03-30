# Topic:
Make coding guidelines for the AL language, with detailed description on best practices. There should also be detailed description of the structure of the language, and rules for all object types.


# Business Central Version
Business Central 2024 Wave 2 (version 25)

# Role:
You are a senior AL developer and Microsoft certified Business Central specialist with extensive experience implementing the AL coding standards across enterprise projects.

# Target audience:
* AI Coding agents like Cline and Cursor.
* Junior to mid-level AL developers
* Development teams establishing coding standards
* Solution architects designing Business Central extensions

# Format:
* Create the documentation using Markdown format.
* Create diagrams using mermaid syntax that can be rendered in Markdown
## Diagram Requirements:
* Use simple flowcharts for process flows
* Use entity relationship diagrams for data structures
* Create sequence diagrams for event flows
* Include architecture diagrams showing extension points
* Create state diagrams for complex business processes
* Limit diagram complexity to 15-20 elements per diagram

# Content Length Guidelines:
- Core components (Tables, Pages): 1000-1500 words each
- Secondary components: 500-800 words each
- Best practice sections: 300-500 words per practice
- Each code example: Include 30-50 lines with comments

# Content Progression:
- Begin each major topic with "Fundamentals" (junior level)
- Progress to "Advanced Techniques" (mid-level)
- Conclude with "Expert Considerations" (senior level)

# Application Context:
- For each major component, include at least 2 common business scenarios
- Provide extension examples that solve real business problems
- Include industry-specific considerations for retail, manufacturing, services
- Reference how AppSource apps implement these patterns successfully


# Success Criteria:
- Code examples must be fully functional without modification
- All Microsoft best practices must be cited with sources
- Each component must include common pitfalls and their solutions
- Documentation should be understandable to a junior developer with basic C# knowledge
- Performance recommendations should include measurable metrics


# Research Method:
Follow a 4-step iterative approach:
1. Initial exploration of each component with comprehensive overview
2. Deep technical analysis with code examples and implementation patterns
3. Verification against Microsoft documentation with explicit citations
4. Validation against real-world implementation patterns from Microsoft sample code and successful AppSource apps
* Continue iteration until all specified sections are thoroughly documented

# Handling Uncertainty:
- When official sources conflict, prioritize the most recent Microsoft documentation
- For undocumented features, clearly mark as "Based on observed behavior"
- When multiple approaches exist, present alternatives with pros/cons
- If information is incomplete, acknowledge limitations and provide best available guidance

# Document Structure for AL Development Guidelines

## 1. Introduction
### 1.1 Purpose and Scope
### 1.2 Document Conventions
### 1.3 Version Compatibility
### 1.4 How to Use This Guide

## 2. AL Language Fundamentals
### 2.1 Core Architecture
### 2.2 Syntax Rules
#### 2.2.1 General Syntax
#### 2.2.2 Object Declaration Patterns
#### 2.2.3 Data Types Hierarchy

## 3. Core Components
### 3.1 Tables
#### 3.1.1 Structure and Properties
#### 3.1.2 Extension Patterns
#### 3.1.3 Performance Optimization

### 3.2 Pages
#### 3.2.1 Page Types Comparison
#### 3.2.2 UI Responsiveness Techniques
#### 3.2.3 Extension Best Practices

### 3.3 Codeunits
#### 3.3.1 Single Responsibility Principle
#### 3.3.2 Event Publishing Patterns
#### 3.3.3 State Management

### 3.4 Reports
#### 3.4.1 Dataset Design
#### 3.4.2 Rendering Optimization
#### 3.4.3 Extension Challenges

## 4. Extension Model
### 4.1 Extension Architecture
### 4.2 AppSource Packaging Requirements
### 4.3 Dependency Management Strategies
### 4.4 Upgrade Strategies

## 5. Event-Driven Architecture
### 5.1 Event Types Matrix (Business vs Integration Events)
### 5.2 Publisher-Subscriber Pattern Implementation
### 5.3 Integration Event Scenarios

## 6. Secondary Components (Brief Coverage)
### 6.1 Queries and Optimization Techniques
### 6.2 XMLports for Data Import/Export Scenarios
### 6.3 Permission Sets for Security Management
### 6.4 Profiles for User Role Customization

## 7. Best Practices for AL Development
### 7.1 Code Quality Standards
#### Naming Conventions (Pascal Case, Prefixes)
#### Error Handling Patterns (Try-Catch Alternatives)
### 7.2 Performance Optimization Techniques
#### Query Optimization Strategies (Indexes, Filters)
#### UI Responsiveness Guidelines (Page Load Times)
### 7.3 Security Best Practices
#### Data Validation and Sanitization Techniques
#### Permission Handling Patterns
### 7.4 UI/UX Guidelines
#### Page Design Best Practices
#### Accessibility Considerations

## 8. Development Lifecycle and DevOps Integration
### 8.1 Testing Strategies for AL Codebases
#### Unit Testing Frameworks and Patterns
#### Automated Test Scenarios
### 8.2 CI/CD Pipeline Setup for AL Projects
#### Source Control Strategies (Git, Branching Models)
#### Automated Testing in Pipelines
### Version Control and Release Management

## 9 Version-Specific Features in Business Central Wave Updates
### New Features in Business Central Wave Updates
- Syntax Changes
- Deprecated Features and Migration Paths

## File Organization Best Practices
- Directory Structure Recommendations
- Naming Conventions

# Tasks:
Create extensive documentation of the topic. including, but not limited to:
* Overall architecture including diagrams including a description.
* General syntax rules
* Special syntes for each object
* Make a coding agent an expert al developer
* Best Practice for performance
* UI Guidelines

## AL Components to Cover:
* Extension structure and organization
* Datatypes
* Codeunits
* Controladdin
* dotnet
* entitlement
* enum
* enumextension
* interface
* namespace
* page
* pagecustomization
* pageextension
* permissionset
* permissionsetextension
* profile
* profileextension
* query
* report
* reportextension
* table
* tableextension
* using
* xmlport
* object numbers
* properties
* triggers
* Procedures
* Variables
* Extension model fundamentals
* Event-driven architecture (Publishers and Subscribers)

## Core AL Components (cover in depth):
* Tables, Pages, Codeunits, Reports
* Extensions and customizations
* Event-driven architecture

## Secondary Components:
* Queries, XMLports, Interfaces
* PermissionSets, Profiles

## Specialized Components:
* ControlAddins, DotNet


## Best Practices Categories:
* Naming conventions (Pascal case usage, prefixes)
* Code formatting and structure
* Error handling patterns
* Performance optimization for different object types
* Data access and query optimization
* UI responsiveness techniques
* Extension development patterns
* Application lifecycle management

## Extension Model:
* Detailed documentation on extension architecture
* AppSource packaging requirements
* Extension dependencies management
* Upgradeability considerations
* Side-by-side extensions patterns

## Event-Driven Architecture:
* Event publishers and subscribers patterns
* Business event implementation
* Integration event scenarios
* Event types and their appropriate usage
* Best practices for event handling

## Testing and Debugging:
* Unit testing patterns and frameworks for AL
* Test automation approaches
* AL-specific debugging techniques
* Automated code quality checks
* Logging best practices

## Security Best Practices:
* Data validation and sanitization
* Permission handling patterns
* Secure API implementation
* Safe handling of external data

## DevOps for AL Development:
* Source control strategies
* CI/CD pipeline setup for AL projects
* Environment management
* Automated testing in pipelines
* Versioning strategies


## Version-Specific Coverage:
* New features in Business Central 2024 Wave 2 (version 25)
* Deprecated features and migration paths
* Changes in syntax or best practices from previous versions
* Future roadmap considerations

## AL File Organization:
* File naming conventions
* Project structure best practices
* Object organization within files
* Directory structure recommendations

## Performance Metrics and Benchmarks:
* Expected response times for common operations
* Query optimization targets (records processed per second)
* UI responsiveness guidelines
* Resource consumption guidelines
* Methods to measure and test performance

# Code Examples
## Include code examples that demonstrate:
* Common usage patterns
* Common way to extend business central functionality

## Code Examples Requirements:
* Provide complete, working examples (not just snippets)
* Include before/after examples for extension scenarios
* Add performance comparison metrics where relevant
* Demonstrate both correct and incorrect approaches
* Include comments explaining why certain approaches are preferred

## All code examples should follow Microsoft's AL coding guidelines.
* Format all code examples with:
* 1\. Descriptive comments explaining each significant block
* 2\. Error handling patterns
* 3\. Performance considerations noted where relevant

# Troubleshooting Guide:
* Document common issues and solutions for:
* 1\. Performance bottlenecks with large volumes of tracked items
* 2\. Data integrity issues and recovery procedures
* 3\. Common implementation mistakes and how to avoid them
* 4\. Diagnostic tools and techniques for item tracking problems

# Important documentation:
* Microsoft Source code for business central apps: https://github.com/StefanMaron/MSDyn365BC.Code.History/tree/w1-25
* Official documentation on business central: https://learn.microsoft.com/en-us/dynamics365/business-central/

# Verify all technical information against:
* Official Microsoft documentation.
* Source code examination (citing specific files/line numbers when possible)
* Published Microsoft best practices. Flag any contradictions or gaps in the documentation explicitly.

# Citation Requirements
* For Microsoft documentation references: Include URL, document title, and section
* For source code references: Include GitHub repository path, file name, and line numbers
* For best practices: Cite specific Microsoft guides, blog posts, or official examples
* Flag any conflicting information between sources and explain the recommended approach

# Related information
Add a section of at the bottom of the documentation with suggestion for topics for further research
