# Vibe Coding for PMs 🚀

A comprehensive template system designed to help Product Managers transform ideas into working code through structured AI collaboration and systematic development workflows.

## 🎯 What This Is

This template provides Product Managers with a structured approach to:
- **Ideate & Spec**: Transform rough ideas into detailed technical specifications
- **Plan & Architect**: Break down projects into manageable development phases
- **Build & Iterate**: Guide AI developers through systematic implementation
- **Review & Refine**: Ensure quality and maintainability of delivered code

## 🚀 Start Here: Prompt Templates

**The core of this system - everything you need to go from idea to working code.**

### For New Projects (`prompt-templates/new-codebase/`)

#### 1. **Hone the Idea** (`hone-the-idea.md`)
Transform rough concepts into detailed specifications through iterative questioning:
- Guides you through creating a minimum viable specification
- Asks focused questions one at a time to deepen understanding
- Exports final spec to `spec.md`
- Optionally initializes GitHub repository

**When to use:** At the very beginning when you have a concept but need to flesh it out

#### 2. **Plan the Prompt** (`plan-the-prompt.md`)
Convert specifications into actionable development plans:
- Creates detailed technical implementation plans
- Breaks projects into logical development phases
- Generates developer prompts for each technical milestone
- Outputs `plan.md` and `todo.md` for tracking

**When to use:** After you have a spec and need to create a development roadmap

#### 3. **Do the Plan** (`do-the-plan.md`)
Execute your development plan systematically:
- Reviews pending prompts and implements them one by one
- Ensures tests pass and builds succeed
- Commits work with descriptive messages
- Marks prompts as completed
- Pauses for validation after each implementation

**When to use:** When you're ready to start building and have a plan in place

#### 4. **Review** (`review.md`)
Quality assurance and code review:
- Conducts thorough code review of implemented features
- Identifies potential bugs, edge cases, and inconsistencies
- Ensures code quality and maintainability

**When to use:** After each major implementation phase or before final delivery

### For Existing Codebases (`prompt-templates/existing-codebase/`)

#### 1. **Hone the Idea** (`hone-the-idea.md`)
Adapt your concept to work within existing code constraints:
- Analyzes current codebase structure and patterns
- Identifies integration points and dependencies
- Creates specifications that align with existing architecture

#### 2. **Plan the Prompt** (`plan-the-prompt.md`)
Plan implementation considering existing code:
- Maps new features to current codebase structure
- Identifies refactoring needs and technical debt
- Creates development plan that minimizes disruption

#### 3. **Do the Plan** (`do-the-plan.md`)
Implement within existing codebase:
- Follows established patterns and conventions
- Integrates with existing systems and APIs
- Maintains codebase consistency and quality

## 🚀 Getting Started

### 1. **Choose Your Path**
- **New project?** Start with `prompt-templates/new-codebase/hone-the-idea.md`
- **Adding to existing code?** Start with `prompt-templates/existing-codebase/hone-the-idea.md`

### 2. **Follow the Sequence**
```markdown
# Start here with your idea
Here is the idea: [Your concept here]
```

### 3. **Execute Systematically**
Use the templates in order: Hone → Plan → Do → Review

## 🎁 Bonus Features

### Context Architecture (`context-architecture/`)
**Optional but powerful** - The foundation of your project thinking and decision-making process:

#### Project Structure Template
```
your-project/
├── @Core-foundation/
│   ├── product-vision-strategy.md
│   ├── how-i-work.md
│   └── technical-architecture.md
├── Active-hypotheses/
├── Decision-contexts-log/
├── Evidence-repository/
└── README.md
```

**Key Principles:**
- **Use folder structure as thinking structure** - Organize your thoughts through systematic file organization
- **Create templates** for hypotheses, decision logs, and other recurring documentation needs
- **Document AI conversations** to maintain context and track decision rationale

#### Core Foundation Components
- **`product-vision-strategy.md`** - Define your product's north star and strategic direction
- **`how-i-work.md`** - Document your working style, preferences, and collaboration patterns
- **`technical-architecture.md`** - Outline the technical foundation and constraints

#### Active Development Areas
- **`Active-hypotheses/`** - Track current assumptions and testable ideas
- **`Decision-contexts-log/`** - Record key decisions with context and rationale
- **`Evidence-repository/`** - Store research, user feedback, and supporting data

### MCP Configs (`mcp-configs/`)
**Tool integrations** to enhance your development workflow:

- **`filesystem/`** - Enhanced file and directory management capabilities
- **`linear/`** - Integration with Linear for project management and issue tracking
- **`memory/`** - Persistent memory and context management for long-running projects

### Workflows (`workflows/`)
**Specialized development processes** for specific scenarios:

#### Design-to-Code Workflow (`design-to-code.md`)
Seamlessly integrate Figma designs into your development process:
1. Enable MCP in Figma
2. Configure AI IDE with Figma MCP settings
3. Use Figma variables for component transformation
4. Copy Figma selection links directly into your development workflow

#### PM Code Review Workflow (`pm-code-review.md`)
Systematic approach to code reviews from a product perspective:
1. **Structured Checklist** - Cover business logic, UX, data integrity, and quality standards
2. **Guiding Questions** - Specific questions to ask during each review category

## 💡 Best Practices

### For Prompt Templates
- **Follow the sequence** - Use templates in order: Hone → Plan → Do → Review
- **Customize thoughtfully** - Adapt templates to your specific project needs
- **Document decisions** - Use your decision log to track why you chose certain approaches

### For AI Collaboration
- **Be specific** - Provide clear context and constraints
- **Iterate systematically** - Use the review template to catch issues early
- **Maintain context** - Reference your foundation documents in AI conversations

### For Code Reviews
- **Use the structured checklist** - Follow the PM code review workflow systematically
- **Focus on business impact** - Prioritize issues that affect user experience and business logic

### For Context Architecture (Optional)
- **Keep it current** - Update your foundation documents as your understanding evolves
- **Use consistent naming** - Establish clear conventions for files and folders
- **Link related concepts** - Create cross-references between related documents

## 🔧 Customization

This template is designed to be adapted to your specific needs:

- **Start with prompts** - The prompt templates are the core and work independently
- **Add context architecture** - Enhance your workflow with structured thinking when ready
- **Extend workflows** - Add specialized processes for your specific development needs
- **Integrate tools** - Use MCP configs to connect with your existing toolchain

## 📚 Template Philosophy

This system is built on the principle that **structure enables creativity**. By providing systematic approaches to:

- **Idea development** (Hone the Idea)
- **Technical planning** (Plan the Prompt)
- **Systematic execution** (Do the Plan)
- **Quality assurance** (Review)

You can focus on the creative and strategic aspects of product development while ensuring technical implementation follows solid engineering practices.

**Start with the prompts - they're all you need to succeed. The bonus features enhance your experience but aren't required.**

## 🤝 Contributing

This template evolves based on real-world usage. Share your adaptations and improvements to help other PMs succeed with vibe coding.
