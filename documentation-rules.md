# User Documentation Rules & Guidelines

Rules for generating documentation for users and for AI.

## Core Principles

### 1. CODE-FIRST DOCUMENTATION (CRITICAL)
- **NEVER document features that don't exist in the codebase**
- **VERIFY EVERY CLAIM against actual implementation**
- **When in doubt, search the code before writing**
- **If you cannot find code evidence, DO NOT document it**
- **Assumption-based documentation is prohibited**
- **Standard WordPress knowledge does not apply to Disciple.Tools**

### 2. Audience
- **Write for non-technical users** who need practical guidance
- **Use clear, everyday language** without jargon or technical terms
- **Focus on what users need to accomplish** their tasks
- **Provide step-by-step instructions** that anyone can follow
- **Explain benefits and outcomes** rather than how things work internally
- **Assume users are new to the platform** and need context

### 3. AI-Optimized Content
- Create markdown documentation that serves both human readers and AI consumption
- Content should be explicit, self-contained, and contextually complete
- Structure content for retrieval augmented generation (RAG) systems
- Use only text-based explanations and instructions

### 4. Self-Contained Sections
- Each section must be understandable in isolation
- Include essential context within every section
- Avoid dependencies on linear reading paths
- Sections are retrieved based on relevance, not document order

### 5. Explicit Information
- If information isn't explicitly documented, it doesn't exist for AI systems
- Include prerequisite steps within procedural content
- Define all acronyms and specialized terms
- Avoid implicit knowledge assumptions
- **Document UI variations**: Provide instructions for both mobile and desktop interfaces if they are different.

### 6. Disciple.Tools vs WordPress Distinctions
- **Disciple.Tools is a custom application** built on WordPress but with completely different user interfaces, workflows, and features
- **Standard WordPress admin features** (like wp-admin language settings, plugin management, user roles) may not be accessible or relevant to Disciple.Tools users
- **WordPress documentation patterns** do not necessarily apply to Disciple.Tools functionality
- **Verify Disciple.Tools-specific implementation** rather than assuming WordPress standard behavior
- **Custom themes and interfaces** mean that typical WordPress user experiences do not translate to Disciple.Tools

### 7. Product Name Standards
- **Always spell as "Disciple.Tools"** with a period between "Disciple" and "Tools"
- **Never use "Disciple Tools"** (without the period) in documentation
- **Acceptable abbreviation is "D.T"** (with period) when shortening is necessary
- **Never abbreviate as "DT"** (without period)
- **Maintain consistent capitalization** - "Disciple.Tools" not "disciple.tools" or "DISCIPLE.TOOLS" in body text

---

## Content Structure Requirements

### Hierarchical Organization
Use clear hierarchy of headings and subheadings to help AI systems understand relationships between sections:

```
Product/Platform Name
├── Feature Category
│   ├── Specific Feature
│   │   ├── Setup/Getting Started
│   │   ├── Configuration
│   │   └── Troubleshooting
│   └── Advanced Usage
└── Reference Materials
```

**Rules**:
- Use descriptive, meaningful headings that indicate function
- Maintain consistent hierarchy levels (H1 → H2 → H3)
- Include product/feature names in headings when relevant
- Ensure each section carries sufficient context to be understood independently

### Document Headers
Keep headers simple and descriptive:
```markdown
# [Clear, Descriptive Title]
```

---

## Content Optimization for AI

### Semantic Discoverability
- Include **product/feature names** in content, not just headings
- Use **consistent terminology** across all documentation
- Establish consistent terminology for your product's unique concepts
- Include specific product or feature names when documenting functionality

### Contextual Completeness
- Keep related information in **close proximity**
- Include **prerequisites within sections** rather than referencing elsewhere
- Provide **complete workflows** within individual sections
- Front-load essential context in each section

### Avoid Contextual Dependencies
**Problem**: Documentation that scatters key details across multiple sections
**Solution**: Keep related information together within close proximity. When introducing a concept with important constraints, include those details in the same paragraph or immediately adjacent paragraphs.

### Address Implicit Knowledge Assumptions
**Problem**: Documentation that assumes user knowledge creates gaps
**Solution**: Include prerequisite steps within procedural content rather than assuming prior setup. When referencing external tools or concepts, provide brief context.

### Text-Only Content Requirements
**Rules**:
- All information must be conveyed through text
- Use numbered lists for step-by-step processes
- Use bullet points for feature lists and options
- Represent workflows as sequential text descriptions
- Include exact UI element names and menu paths in text
- Provide text equivalents for any visual information

---

## Format and Technical Requirements

### Content Organization
- **One topic per document** unless closely related
- **Logical file naming**: use-descriptive-kebab-case.md
- **Clear directory structure** reflecting content hierarchy
- **Consistent cross-references** with meaningful link text

### Markup Standards
```markdown
# Page Title (H1 - only one per document)
## Major Section (H2)
### Subsection (H3)
#### Details (H4)

**Bold** for emphasis and UI elements
*Italic* for introducing new terms
`Code` for technical terms and values
```

---

## Troubleshooting Documentation

### Error Message Format
Include exact error messages to create direct matches between user queries and helpful content:

```markdown
### Error: "Exact error message text here"

**Cause**: Why this error occurs
**Solution**: Step-by-step resolution

**Related Issues**: Links to similar problems
```

### FAQ Structure
Use Q&A format that mirrors questions users often ask:

```markdown
### How do I [specific user goal]?

Clear answer with complete steps.

**Related**: Links to related documentation
```